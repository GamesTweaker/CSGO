# CSGO

#####-console
This option will open the console automatically when opening the game.

#####-novid
This option removes starting intro.

#####-tickrate 128
This option allow you to play local at tickrate 128.

-refresh <rate> / -refreshrate <rate> / -freq <rate>
This option allows you to force monitor refresh rate. 
This only makes sense if your monitors maximum refreshrate is higher than 60. 

-high
This option will start the game in high-priority mode.

-threads <number of cores/threads>
So far, I was not able to find a definitive information about the maximum number of threads that CS:GO uses and if this launchoption makes any sense. If you have a CPU with 4 or more cores, you can try to set -threads to the number of cores (or number of threads if you own a CPU with 2 threads/core) you have, but right now I can not guarantee that your performance will improve. Test it, if you don’t notice any difference or your performance is actually worse, remove the launchoption again.

-full / -fullscreen
This option forces the game to run in fullscreen mode.

-windowed / -window / -sw / -startwindowed
This option will force the game to run in windowed mode.

-w <width> / -width <width>
-h <height> / -height <height>
This forces the game to start with the resolution you specified, e.g. -w 1920 -h 1080.

-noborder
Using this launch option will remove the border that Windows puts around the window when the game is run in windowed mode.

-x <position> – horizontal
-y <position> – vertical
When the game is run with no border, you can’t move the window around and it is stuck to the center of your screen. You can define the position of the window with these 2 launch options. <position> is the space in pixels, that you want the game to be “away” from the left and top side of the screen.

-lv
This option turns the game into a low violence version. There’s no blood and models lie down with their hands behind their heads.

-language <language>
This option will start the game in specified language.



+exec <exec>
This option allows you to load the specified config file.

+clientport 27055 (Suggested by him) 
Very useful command especially when playing on a LAN with friends. By default CS:GO uses port 27005 so if you're on a LAN with someone else who is also playing CS:GO then there would be port conflictions and you guys would not be able to play CS:GO at the same time on the same network so by setting it to a different port you can both play together. Normally when this problem is occurring if you're both in a party trying to start a competitive match then the ACCEPT button will never show up for either of you.

+cl_forcepreload 1 (Suggested by him) 
This command will load all textures, etc. before joining the game.

-nod3d9ex1
Disables a DirectX extension that makes alt tab faster.

-nojoy (Suggested by him) 
removes joystick support



-heapsize
-noforcemaccel
-noforcemparms
-noforcemspd
These launch options have absolutely no effect in CS:GO. Use m_rawinput 1 and m_customaccel 0 instead. Or don’t, since it’s creating input lag for some people. Test a bit and use the settings you’re most comfortable with.
