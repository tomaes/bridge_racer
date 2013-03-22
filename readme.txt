
BRIDGE RACER (1kb) by tomaes (03/2013)
--------------------------------------


1. Info
-------

Hi. This is my attempt to make a (somewhat) fully featured C64 game in 
less than 20 lines of Commodore Basic v2 code, taking less than 1kb of Basic RAM,
which is about 2.5% of the default space available for Basic code on the machine. 

It's also an entry for the 8bit BASIC competition: http://rsp.retrocomputacion.com


Some of the "highlights" include:

 - Custom graphics (generated charset/modified ROM font, one new character matrix)
 - Highscore saver/loader
 - Animated title screen (by character animation + drawn PETSCII "bridges")
 - Game Over "Music" (by messing with the SID's global volume register and abusing
   the well known "plop" hardware glitch; not enough space for some actual music.)
 - Joystick (port 2) support (controls are a bit sluggish, but the game remains playable)


You might wonder about the self-imposed limits:

 - 20 lines of code: 
   Tribute to German 64'er magazine (1984-1996) and their Basic competitions

 - 1 kilobyte (I'm using the old definition, aka 2^10 bytes): 
   Sounds like a challenge and arbitrary size limits are very demoscene-ish :)


2. How to play
--------------

 - Wait a couple of seconds for the title screen to appear
 - Press space for the game to begin
 - Use Joystick in Port#2 to steer your car to the left/right
 - Avoid holes in the ground ;)
 - Don't miss the bridges, they are only 2 characters wide
 - The numbers beside the track? Car damage! The lower, the better
 - The game ends after 10 hits ("9" damage, you start with Zero)
 - Press space (or any other key) to return to the title screen


3. Misc
-------

Licence: The code is in the Public Domain

Web: http://tomaes.32x.de, e-mail: tomaes{a/t}32x{d\o/t}de

---------------------------------------------------------------------------------------

info[at]rsp.retrocomputacion.com

Name and/or nick/handle of the author(s): 
- tomaes 

Name of the entry: 
- BRIDGE RACER (1kb)

Description:
- A "fully featured" game in Commodore Basic v2, in less than 20 lines of code,
  taking less than 1kb of Basic RAM. (for detailed info, see readme.txt)

Platform: 
- C64

Tools used: 
- CBM Program Studio (coding)
- VICE emulator (testing)
- DirMaster (to edit the disk image)
