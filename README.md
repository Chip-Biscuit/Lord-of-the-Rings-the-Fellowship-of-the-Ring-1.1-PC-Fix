# Lord of the Rings the Fellowship of the Ring 1.1 PC Fix

![fellowship](https://github.com/user-attachments/assets/a286ba7b-caef-40bc-97a7-ddc9c3c03731)

# Requirements before using fix
Before using the fix for it to work properly you must have patched the game up to 1.1 release. **This fix WILL NOT WORK on a 1.0 version** of the game and 1.0 is not supported. If you have not updated your Fellowship of the Ring to 1.1 already then you can download the patch from here - https://community.pcgamingwiki.com/files/file/3361-the-lord-of-the-rings-the-fellowship-of-the-ring-v11-us-game-update/

If you have trouble with updating your copy of Fellowship of the Ring to 1.1 with the patch, then join the **Discord** below for help regarding this issue.

**IT IS VERY IMPORTANT YOU READ THE READ ME FILE IN THE DOWNLOADED FILES FOR THIS TO WORK PROPERLY!**

# Official video guide

https://m.youtube.com/watch?v=PTlvVNK5E_s

# Instructions
Go to release, download the latest release zip file and extract it, then put the d3d8.dll, d3d8.ini, fellowship.dll, fellowship.ini, fellowship.rfl, levellist.txt and FellowshipPatcher.exe into your game folder next to the fellowship.exe file.

Before editing the settings in the ini files and starting up the game run FellowshipPatcher.exe once so that it can patch the game to fix the Black Screen issue on startup. Then you are good to go! You can edit the settings you wish to use in the d3d8.ini and fellowship.ini files.

**IMPORTANT:**
if you have your game installed to your C drive or if the patcher throws an error (failed to patch fellowship.exe) then you will have to run the patcher as administrator if it doesn't work or try the following:
or right click your fellowship folder where all the game files are and go to properties and security click the edit button and ensure all the box's have a tick in them for all of the fields.
also in general you will need to uncheck read only for the whole folder after you did all this click apply and then try FellowshipPatcher.exe if it didn't previously work it should say Game and Resources Patched successfully please continue to play the game through Fellowship.exe if successful.

# CONTROLLER SUPPORT (XINPUT) BY CHIP

Fellowship now features custom controller Xinput (xbox) controller support which mimics the layout of the PS2 port of the game in the d3d8.ini you can turn this off with 0 or have controller support on by setting 
[Xinput]
ControllerSupport = 1 
then you will be able to use an xbox controller In the game, if you don't have a xbox controller you can spoof it with the software DS4 windows or you can add the game to steam as a non steam game and make sure steam uses xinput 
then you can enjoy the game with full controller support :) enjoy! the layout is as shown below:


![Lord_of_the_Rings_the_Fellowship_of_the_Ring_Xbox_Controller_Layout](https://github.com/user-attachments/assets/133c3bc4-66cd-4626-9538-0710e6d31d13)

<img width="757" alt="Lord_of_the_Rings_the_Fellowship_of_the_Ring_Controls_Table" src="https://github.com/user-attachments/assets/7e4eb2b1-8eb2-4b47-b027-e3baa3939585" />





# Resolution

It is advised to only go as high as 2560 x 1440 resolution because this game engine on anything above that will have texture popping issues so for example at 4k (3840 x 2160) on the edges of the screen you will have texture popping but this is not present in 2560 x 1440 or under.

# FOV
This fix automatically calculates FOV in the game based on the resolution that you chose in the game.

# FPS
Default for FPS is 60 which you can change in the fellowship.ini file. The game functions on higher fps without too many issues, however, uncapped is not advised.

It is best to leave the option for FPSAnimations alone as this can easily break the game in multiple areas and the option only exists for experimentation in gameplay.

# Changing Level List Names

If you would like to be able to change the level list names to the correct names instead of the developer names given to them then you will need to do the following edits to the levels listed below:
-    Weathertop Mtn
-    Night Weathertop Mtn
-    Troll Shaws
-    House of Elrond
-    IGC_Forest
-    Anduin 1

Inside of the LevelList.txt file edit the levels above lines to the following and save it:
- Levels/Weathertop/Weathertop Mtn/Weathertop.lvl
- Levels/Weathertop/Weathertop Mtn/Night Weathertop.lvl
- Levels/Weathertop/Troll Shaws/Trollshaws.lvl
- Levels/Rivendell/House of Elrond/Rivendell.lvl
- Levels/Lothlorien/IGC_Forest/Lothlorien.lvl
- Levels/River Anduin/Anduin 1/Amon Hen.lvl

Then you will need to go to where Fellowship is installed, Levels and then inside of each of the levels listed above’s folders find and edit the .lvl file to the name of the level. For example, IGC_Forest.lvl you would edit to Lothlorien.lvl. Once you do this for each of the levels above when you go in game you should now see the names have been updated in the menu level list.

# Cheats/Extras
To use the cheats when in gameplay simply press the options listed below:

F5 - fly -> Fly

F6 - drop -> Drop

F7 - tim -> Invincible

F8 - tele -> Teleport

F9 - mrclean -> MrClean

F10 - heal -> Full Health

F11 - bye -> Suicide

F12 - invisowalls -> Show Invisible Statics

On clicking New Game, you shall now have access right away to all the levels within the game. Simply select a level you wish to play or the first level in you wish to start from the beginning of the game like normal.

# Vote to see the game return via GOG Dreamlist
If you are interested in potentially seeing this game easily available to purchase and use today then go and vote on the games GOG Dreamlist to help make this become a reality, you can vote for the game here and write a message about the game if you wish – https://www.gog.com/dreamlist/game/the-lord-of-the-rings-the-fellowship-of-the-ring-2002 

# Issues/Problems
If you have any issues, with the fixes then please go to discord for help linked below.
https://discord.gg/eVJ7sQH7Cc

# Credits
Credit to Elisha Riedlinger for the base wrapper and ThirteenAG.

brought to you by Fix Enhancers

https://fixenhancers.wixsite.com/fix-enhancers

Team:

Chip, JokerAlex21 and (Blankname - fellowship.dll/fellowship.ini (creator)).

Testers:

Osen33, LovelyClaire
