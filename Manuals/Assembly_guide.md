# Pictorial Assembly Guide of Z80MB64
The order of assembly is based on the height of the components, the lowest components are soldered down first and the tallest last.

Bare PC board, component side
![baretop](Z80MB64_rev0_bare_topview.jpg)

Bare PC board, solder side
![baresolder](Z80MB64_rev0_bare_solder.jpg)

1. Solder down all resistors (4.7K), bypass capacitor (0.1uF), and SIP resistor (4.7K BUS). The orientation of SIP resistor is important, pin 1 is marked with a black bar on the SIP package and should be positioned where the red arrow is pointed.
![res_cap](z80mb64_rev0_res_cap.jpg)

2. Install the IC sockets as well as the 1×6 serial port header.
![socket](z80mb64_rev0_socket.jpg)

3. Install the PLCC socket. The orientation of the socket is important, the beveled corner should be placed where the red arrow is pointed. Also install 1×3 jumper block (T34), 2×5 programming header (P3), push button (S1), 2.1mm x 5.5mm power jack (J1), and CR1220 battery holder are also installed. Observe the orientation of the battery holder as indicated on the picture below.
![PLCC](z80mb64_rev0_plcc_battery.jpg)

4. Install the CF adapter. The connector is keyed so it can only be installed in one orientation. Solder one pin, make sure the adapter is perpendicular to the mother board before soldering the rest.
![complete](z80mb64_rev0_complete.jpg)

5. Populate just the CPLD and power up the board to program it. Observe the orientation of the CPLD and programming cable as indicated on the picture below.
![programCPLD](z80mb64_rev0_cpld_prog.jpg)

6. Populate all components
![populated](z80mb64_rev0_complete.jpg)
