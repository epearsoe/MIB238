# MIB238

The information within this document is to be used at your own risk. Any loss of data or failure of hardware is the sole responsibility of the end user. If you do not agree to these terms and conditions, do not continue.

The Multipurpose Interface Board (MIB238 board) is a redesign of the Micro Innovations MIB3 board that only requires 5 volts using modern MAX238 transceivers.  The MIB238, like the MIB3, adds a BOOT PROM socket, two RS-232 ports, a parallel port, and a memory expansion board addressor port to your ADAM computer.

The file mib238_v4_routed_2020-11-06.zip contains the Gerber files required for PCB fabrication. This version increases the width of power and ground lines to 16 mil and corrects the capacitor value for the crystal to 22 pF.

The file Multipurpose Interface Board 238.pdf is the documentation for the MIB238. It contains information on using the MIB238 with your ADAM computer, serial and parallel cable construction, Z80 code examples and details on PCB fabrication and Bill of Materials.

The file mib238_v5_routed_2021-01-16.zip contains new Gerber files for the latest version of the MIB238.  The C11 capacitor has been removed and a larger ground plane connection was added.

The file mib238_v7_wifi_routed_2021-07-27.zip contains new Gerber files for a new version of the MIB238 with integrated WiFi.  It uses a Wemos D1 Mini ESP8266 Wifi board programmed with Zimodem firmware (https://github.com/bozimmerman/Zimodem) and one of the MAX238 ICs is replaced with 2 CD74HC4050E ICs for logic level conversion.  NOTE: This design has not been fully tested.  Use at your own risk.
