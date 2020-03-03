These scripts expects EmulationStation to be installed on your device!
If you don't want to make use of the functionality this script provides you, just delete it again from the /media/data/local/sbin folder.

There are two versions of the start-up script:
* frontend_start_menu    : Automatically starts EmulationStation on boot-up. If you quit EmulationStation it returns to your device menu.
* frontend_start_poweroff: Automatically starts EmulationStation on boot-up. If you quit EmulationStation it turns off your device.

Install this script:
1. Choose your desired frontend_start_xxx script and rename it to frontend_start
2. Connect to your RG350 and copy the "frontend_start" file to /media/data/local/sbin
3. Ensure the file has executeable rights:
   3.1 Connect to you RG350 using putty
   3.2 tpye: cd /media/data/local/sbin
   3.3 type: chmod +x ./frontend_start

   or (alternative)

   3.a Connect to you RG350 using WinSCP
   3.b Navigate to the folder /media/data/local/sbin
   3.c Right-click on the fronend_start script file and choose Properties
   3.d Under "Rights" set executeable rights for this file to yes for all groups (enable the checkboxes for all entries, it's the columns with the 'X')
4. Restart your RG350. Enjoy!