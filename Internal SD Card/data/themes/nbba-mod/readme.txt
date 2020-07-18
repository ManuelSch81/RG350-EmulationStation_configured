nbba theme

Changes:
Version 1.2
- Added theme for 3DO Interactive Multiplayer, Atari Jaguar, Famicom Disk System, Kodi, Magnavox Odyssey 2, Nintendo DS, Nintendo Virtual Boy, Sega Saturn, Sega SG-1000, SNK Neo Geo Pocket
- Added partial theme for Commodore Amiga, Sinclair ZX Spectrum
- Changed background for Atari 7800 ProSystem, Sega CD
- Changed logo for Atari 2600, Atari 5200 SuperSystem, Atari 7800 ProSystem, Sony PlayStation
- Changed gamelists style to have a light color selector bar with black text. All other text is a light color
Version 1.1
- Added theme for Atari 5200, Atari 7800, Mattel Intellivision, Sega CD
- Split up the zip files to make the main zip just the theme
Version 1.0 Initial Release
- Fixed the filter so it does not overlap for 4:3 displays.
- Centered the bg.png so that it appears centered on 4:3 displays.
- Lightened the Sega 32X text more so that is more visible.
- Fixed the es theme so that the text will cut off rather than overlap each other.
- Added theme for Sega Dreamcast, Atari Lynx, GCE Vetrex and Commodore 64.
- Changed the font used in the theme to a better fitting font.
- Adjusted various parts of the theme.
- Included alternate logos if you want a more accurate system logo.
- Changed the bg.png files to bg.jpg to save a lot of space. This may help reduce memory usage.
- Included the game console image in the system select screen.
- Included alternate themes that do not include the game console image.
Version 0.1 Beta
- Very first release

---------------------------------------

This theme was inspired by Florian Hurtaut's theme which was released for EmulationStation 1.x. I have built the theme using EmulationStation for Windows and have tested with a Raspberry Pi 2 B with a 320 MB memory split at 1920x1080 resolution. I have yet to test this theme with older Raspberry Pi models. I have a Raspberry Pi B+ that I will test with in the future.

This theme is mostly complete. There are changes that I have planned to make.
- Adding additional systems that are supported by the Raspberry Pi.
- Adding one additional layout choice.

For any question and updates you can reply to the topic below. I am also willing to add additional systems and system logo localization upon request.
http://blog.petrockblock.com/forums/topic/nothing-but-box-art-wip/

I fully plan on releasing all the materials I used to make this theme but now I think it maybe upon request. I never realized going into this that the materials would be so large. I may end up optimizing some of the materials as it would save much space. this will come at a later day once I figure out how to get it from 370 MB to under 100 MB.

---------------------------------------

There are 38 systems themed if you count the RetroPie settings. The systems themed are

RetroPie
Sega Dreamcast
Nintendo 64
Sony PlayStation
Sega Saturn
Sega Genesis 32X
Atari Jaguar
3DO Interactive Multiplayer
Sega CD
Super Nintendo Entertainment System
NEC TurboGrafx-16
Sega Genesis
Sega Master System
Atari 7800 ProSystem
Famicom Disk System
Nintendo Entertainment System
Sega SG-1000
Atari 5200 SuperSystem
GCE Vectrex
Mattel Intellivision
Magnavox Odyssey 2
Atari 2600
Nintendo DS
Nintendo Game Boy Advance
Nintendo Game Boy Color
SNK Neo Geo Pocket
Nintendo Virtual Boy
Sega Game Gear
Atari Lynx
Nintendo Game Boy
Commodore Amiga
Commodore 64
Sinclair ZX Spectrum
Ports
SNK Neo Geo System
Final Burn Alpha
Multiple Arcade Machine Emulator (MAME)
Kodi | Open Source Home Theatre Software

---------------------------------------

Installation

Copy the contents of the 'themes' folder to the 'themes' folder of EmulationStation
Example: '/etc/emulationstation/themes' for the Raspberry Pi

You must at minimum copy the 'nbba theme' folder to themes. The two alternate layouts reference all of its resources from the main theme to cut down on disk usage and files.

Before the next step make sure to make a backup copy of the RetroPie 'gamelist.xml' file if you wish to revert the changes back. I have provided the default 'gamelist.xml' file my Raspberry Pi generated. Copy the contents of the 'gamelists' folder to the 'gamelists' folder of emulationstation.
Example: '/home/pi/.emulationstation/gamelists'

Copy the contents of the 'downloaded_images' folder to the 'downloaded_images' folder of EmulationStation.
Example: '/home/pi/.emulationstation/downloaded_images'

Copy the contents of the 'retropiemenu' folder to the 'retropiemenu' folder of RetroPie.
Example: '/home/pi/RetroPie/retropiemenu'

nbba theme - This theme layout will display the image referenced in the gamelist.xml as large as possible to take up the left half of the screen. A list of games is on the right with a few details listed about the game below the image.

nbba theme es - This theme layout keeps the default layout which is provided with EmulationStation.

nbba theme ns - This theme layout is similar to the nbba theme but gets rid of the list of games on the right for a single selection at the top. The image that is referenced in the gamelist.xml then expands to the maximum size of the space left.

---------------------------------------

Alternate nbba Filters

The filters are no longer provided within this zip file. You can get a download link from the topic link above.

I have provided 3 additional filter choices for the theme. In order to use one of these filters you must open the chosen folder and copy the contents into the 'themes' folder of EmulationStation.
Example: '/etc/emulationstation/themes' for the Raspberry Pi

---------------------------------------

Alternate nbba Logos

The logos are no longer provided within this zip file. You can get a download link from the topic link above.

I have provided additional logos for each of the systems. These logos were extras that were a result of creating the logo that I chose to use. For the most part the colors of the alternate logos match what the actual logo is. Ports has several different logo choices. Most were a result of not knowing what I wanted. To use the alternate logo just place it in the appropriate system folder in the 'nbba theme' and make sure it is named 'logo.svg'.

---------------------------------------

Alternate nbba Themes

The alternate nbba themes are no longer provided within this zip file. You can get a download link from the topic link above.

I have provided an alternate version of the themes that do not include the game console above the logo in the system select screen. In order to use these themes you can either rename the folder and place it in the themes folder or you can copy the folders replacing the default themes.

---------------------------------------

EmulationStation es_systems.cfg

I have provided a copy of my 'es_systems.cfg'. I have listed out the game systems newest to oldest first. Next listed is portables newest to oldest. Last is arcade systems. I cannot guarentee it will work 100% as I have not used every emulator on the RetroPie.

---------------------------------------

Remove Scroll Sound

If you do not want or like the scroll sound for the game lists I have provided a blank wave file that can replace the click sound. To do this open the nbba theme folder then the main folder. Inside of the folder delete the 'sound.wav' file and rename the 'nosound.wav' file to 'sound.wav'

---------------------------------------

Hope you enjoy
sekazi
