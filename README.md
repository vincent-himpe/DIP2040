# DIP2040
## An RP2040 in DIP40 PACKAGE with bare minimum on-board circuitry

### Features
- on-board Flash
- on-board 3V reference (LM4040-3.0). Can be disabled by opening a solder bridge.
- ESD protected USB-C connector
- Reset and BOObuttones. Boot button also available under the USB-C connector so you can poke it with a paperclip
- Heartbeat LED. can be disabled using a solder bridge
- USB powered 3V3 regulator. Can be strapped to the 3V3 bus using a solder bridge.
- External 3V3 input for self-powered operation
- All GPIO brought out on the pins.  (except the QSPI for the flash). Nothing is hidden.
- Fits standard 40 pin DIP socket
- USB connector extends past the board so you can mount it close to an enclosure wall and have the USB connector stick out.
- 4-layer PCB with ground plane and impedance control.
- 3D STEP model avaiabale
- Design released under Creative Commons Zero Universal.
- Source files available (Altium V25 format)
- Production data available for DKred ( Digikey's PCB service ) and others ( Standard Gerber-X format )

  ![3D view](/IMAGES/DIP2040.png)
