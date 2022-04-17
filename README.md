# Baofeng Programming Adapter

This board adapts the 5 volt USB port from a computer to 3V3 UART for use with programming Baofeng or similar chinese HTs. Most of these radios use a "Kenwood style" connector for programming; I have chosen to use separate 3.5mm and 2.5mm jacks as, annoyingly, several of the brands use non-standard spacing so as to make most cable incompatible. I have also elected to use a Silicon Labs chip to avoid the driver fiasco with the other common supplier of cheap UART bridge ICs.

## 3d

Within the folder labled '3d', you will find a .step file of the complete board and all its components, as well as models for the non-standard parts I used. I made a casing for this board to be 3D printed, but I currently do not have that file on hand. If I get a copy of it again sometime in the future, I will add it.

## gerber.zip

This is an archive of all the gerber files needed for manufacturing. I did not bother having this assembled in the factory so there is no BOM or pick-and-place file.

## main_board

I originally made this board in Kicad 5, and have since updated it to Kicad 6. I do not see anything obviously wrong with the project after converting, but I have not looked that close. If I notice any problems, I will fix them and push the change.