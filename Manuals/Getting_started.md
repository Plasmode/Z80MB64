# Getting Started with a new Z80MB64
### Introduction
The Getting Started guide is written for two audiences. One audience are buyers who have purchased the assembled/tested Z80MB64 which is ready to be power up and use. The instruction for powering up the fully assembled/tested board is located at the end of this manual. The other audience are hobbyists who have downloaded the design information to build their own Z80MB64 from scratch. Please read the entire guide if you are building Z80MB64 from scratch.

Once a Z80MB64 is assembled (see the pictorial assembly guide), the first component to populate is Altera EPM7064SLC44. Connect the USB Blaster cable to the 2×5 header such that the pin 1 (or red wire) is on the same side of silkscreen '2'. The programming file is “top.pof” in the Z80SBC64_EPM7064.ZIP design file.

Once the EPM7064S is programmed and verified, populate the rest of the components. If you have a CP2102 6-pin USB-serial adapter, it can plug directly in the 6-pin serial header. Only 3 signals are needed, transmit, receive and ground. Set the terminal program to 115200, no parity, 8 data bit, 1 stop bit, and no handshake. The bootstrap mode jumper should set to “serial bootstrap” which is on the side closest to the '+' terminal of the battery holder. Refer to connector picture for the bootstrap mode setting.
