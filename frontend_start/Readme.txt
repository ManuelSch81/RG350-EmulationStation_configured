This scripts expects EmulationStation to be installed on your device!
If you don't want to make use of the functionality this script provides you, just delete it again from the /media/data/local/sbin folder.

Install this script:
1. Connect to your RG350 and copy the "frontend_start" file to /media/data/local/sbin
2. Ensure the file has executeable rights
   2.1 Connect to you RG350 using putty
   2.2 tpye: cd /media/data/local/sbin
   2.3 type: chmod +y ./frontend_start
   or
   2.a Connect to you RG350 using WinSCP
   2.b Navigate to the folder /media/data/local/sbin
   2.c Right-click on the fronend_start script file and choose Properties
   2.d Under "Rights" set executeable rights for this file to yes for all groups (enable the checkboyes for all entries, it's the columns with the 'X')
3. Restart your RG350. Enjoy!