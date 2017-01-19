# Ark-Script-Gen
This program will generate the level and exp scripts to override default and can generate the engram scripts as well.

Ark Script Gen 1.jpg and Ark Script Gen 2.jpg show the 2 tabs of this application.

Tab 1 shows Starting level, Max level, Starting Exp and Exp Increase as well as 2 checkboxes labeled Adding Extra Levels and Exp % Increase.

Starting level is the level you would like to start with in Ark, aka Level 1, if your continuing to add levels to a preset game.ini config
then you would want to set it to for example 501 if you already have levels 1-500. Max Level is just that, what do you want the max level to be.
Starting exp is how much exp will it take to complete level 1? Exp Increase is how much exp do you want to add to the next level? do you want it
to be a solid gain by say 1000 or do you want 10%? if you want a percentage check the exp % increase box. Otherwise each level will gain
by a solid number exe 1000 if you put 1000 in the exp increase box.

Tab 2 shows Level Start, Level End and Engrams each with 5 boxes and 4 check boxes. The first 4 boxes on top must be filled. The way this
works is it will take the starting level and the ending level ex:1 - 10 and loop 10x to gen the code for however many engrams you want
for that level segment. Engrams are how many engrams you want to give during that segment so lvls 1-8 by default would be 8.

If you have several segments to do, say lvls 1-8, 8-16 and so on you put the start of the segment, end of the segment and the engrams to earn
each time in that segment. If you use the second row, you must check the box telling the program you are using the first and second row.
From the checkboxes you must use the row starting at 2 down and in order so no using rows 1,2,4 it wont gen the 4th row code.

The big text fields at the bottom of both tabs are the output for the scripts, all you have to do is copy paste them into your game.ini
file, save and boot up and wala it will take effect. On the first tab there is a small bar under the output, it will gen the single line for
the max exp override to also be posted in the game.ini file.


Ark Script Gen 3-6 show the program in use. 3 is basic levels 1-10 starting with 100 exp to get to level 2 and an increase of 10 exp per level. 4 shows the same levels 1-10 but with using the Exp Increase as a 10% increase for the next level. Using pic 4 you get the info for level 10, then in pic 5 I show you how to use it to extend the levels from 10 up to 20. Lastly pic 6 shows the engrams, however only the first 2 sections ran, the reason is row 3 checkbox is not checked so neither row 3 or 4 ran even though they were filled. So make sure you use the correct boxes in order and to enable those you use.
