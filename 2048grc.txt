2048 for Sega Master System, v1.0

by Julien Verneuil aka Grz-

=======================================================================
A puzzle game based on : http://gabrielecirulli.github.io/2048/

Design inspired by the C64 release : http://csdb.dk/release/?id=129788
=======================================================================

Controls:
============

D-Pad: move the tiles 
Button 1: start or restart the game
Button 2: if you win you can press it to continue to play

How To Play:
============

When two tiles with the same number touch, they merge into one, the goal is to get a tile with the number 2048, then you win but you can continue and try to go to 8192 if you want.

ChangeLog:
============

v1.02
    - a simple makefile was added
    - the border color is now black
    - the background color of the board is now back to grey instead of blue, this was modified by error in the 1.01 version

v1.01
    - "4" can also appear randomly as a new tile instead of only the tile "2"
    - new tiles location are chosen truly randomly now, in the previous version if the first randomly chosen location was not empty, the tile was placed to the first empty location found on the board
    - sometimes (but not always) the tiles would be merged continually until there was no merging possible in a single "turn"
    - bugfix related to continuing the game after getting 2048
    - help at the start of the game
    - gfx are now compressed, the game could easily fit in a 16kb rom now so there is room for a music, the background tilemap is not compressed because it seem the v0.40 of the bmp2tile tool does not take into account the tile index when it save compressed tilemap
    - source code cleaned up and optimized
 
============

The first release of the game was made in four days (24/03/2014 to 27/03/2014).

website: http://garzul.tonsite.biz
mail: grz.zrg@gmail.com
