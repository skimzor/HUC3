# HuC-3 Flash Adapter Board

This board is used to convert a DMG-UFDT-01 Cartridge (mainly Robopon) to a Flash Cartridge. One could use this adapter to play Robopon Sun and Star on original Game Boy hardware.

# Disclaimer
Please do not attempt this project if you are inexperienced in soldering; installing the flash adapter will require desoldering the ROM and micro-soldering the adapter and flash chip.  I do not take responsibility or accept blame for any damage to your cartridge or for any failed attempts. 

I have personally tested this adapter and successfully created a working DMG-UFDT-01 flash cart and have been able to play Robopon Star on original Game Boy hardware. All features have been confirmed as working with the cartridge that I have created. ***However, I cannot guarantee a fully working unit if you undertake this project as there are too many factors that can cause issues, so please acknowledge this disclaimer and order/use this PCB at your own risk. Unless it is a PCB design issue, I will be providing limited technical support for any issues you may have.***

If you have suggestions to improve or identify issues with the PCB design, please contact me on discord: *skimzor*.

# Ordering

Download the gerbers and upload them to your PCB fabricator of choice (I have only used JLCPCB) and order as a flex board. OSHPark flex will not work.

# PCB Bill of Materials & Assembly

As mentioned above in the disclaimer, assembly of this PCB requires advance soldering experience and ability to self-troubleshoot any issues.

Items needed:

- DMG-UFDT-01 donor cartridge
- AM29F016 IC Flash Chip
- Pickup Wire
- insideGadgets GBxCart RW (or flasher of your choice)

You will need to remove U1 and C4 from a DMG-UFDT-01 cartridge (keep C4). Line up the flash adapter board and drag solder the pads. Ensure that all pads are making good connections with a continuity check. Solder on the AM29F016 chip, C4, and then solder a wire from the WR pad of the flash adapter to Pin 31 of the DMG-UFDT-01 board. Flash using the flasher of your choice. 

# Credit

All credit goes to Steelfoot for documenting the schematics and wiring of the DMG-UFDT-01. 

# License

 [![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
 
This project/PCB is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. ***Under this license, you are not permitted to profit from or commercialize this project.***
