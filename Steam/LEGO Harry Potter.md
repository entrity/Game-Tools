# Notes for LEGO Harry Potter Years 1-4

## Crash (Freeze) in Dark Tower

https://steamcommunity.com/app/21130/discussions/0/618458030678089713/
>  Year 3, The Dark Tower crash.
> Hi, guys. Please, help me. On the mission The Dark Tower when I try to light a statue holding a torch, the sound is loaded and the game freezes. 

> *Go to C:\Documents and Settings\your username\Application Data\WB Games\LEGO Harry Potter\ (on XP)
or C:\Users\your username\Appdata\Roaming\WB Games\Lego Harry Potter\ (on Win8)

> *Find a file called pcconfig.txt, back it up (I just saved a copy on the desktop, to use whenever needed), and then change DesiredDynamicLightQuality to 0 (near the bottom of the file). That is basically what is causing the problems. Although I read in some forum post or another, that Tt answered someone who contacted them, to change everything below MouseSensitivity to 0, so if you want to be extra sure...

> That will cause all the lights to look weird, but at least the game doesn't crash anymore.

> *After finishing the level, follow the same path again and replace pcconfig with the one you backed up earlier (you did back it up, right?), to get your original settings back. You do have to quit the game and restart it for it to work of course. Just sayin'. "
