Instructions:
This guide runs on:
- Windows
- Linux
- MacOS

For this guide, you require a sd-card to use in the external sd-card slot of your RG350.

For CFW V1.5 or 1.7:
--------------------
1. You need a sd-card that is formatted as FAT32 (If your sd-card is not formatted FAT32 use this program here to format it:
   http://www.ridgecrop.demon.co.uk/index.htm?guiformat.htm
   Note: All data of your sd-card will be erased when you format it!
2. Name your sd-card "sdcard" and insert it to your PC.
2. Drag the content of folder "External SD Card" to your sd.card (not the folder it's self).
3. Copy the emulators from the "emulators" folder to /media/data/apps/ on your RG350.
4. Drag the folder "Internal SD Card" to your SD card.
5. Eject your SD card from your PC, push it into the RG350, and turn it on.
6. Use the "DinguxCmdr" to transfer "emulationstion.opk" into the /media/data/apps folder.
7. Then transfer the "data" contents (not the folder) into /media/data/local/home/.emulationstation/ folder.
8. You're done! launch the EmulationStation app from the "emulators" section on your RG350.

For Rogue Firmware:
--------------------
1. Open the file "Internal SD Card\data\es_systems.cfg" and replace "/RG-350" occurences with "/sdcard"
2. Drag the "External SD Card" contents to your SD Card (not the folder it's self).
3. Place your emulators in the "emulator" folder. (Use the READ ME.TXT file to correctly rename the opks!)
4. Drag the folder "Internal SD Card" to your SD card.
5. Eject your SD card from your PC, push it into the RG-350, and turn it on!.
6. Use the "DinguxCmdr" to transfer "emulationstion.opk" into the apps folder.
7. Then transfer the "data" contents (not the folder) into ".emulationstation".
8. You're done! Just launch and you're good to go!
