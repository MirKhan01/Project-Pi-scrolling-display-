# Project-Pi-scrolling-display-
mirsaad@udel.edu
Mir Sa'ad Ali Khan 
702588948

When the program is started, it should show a letter on the display (one partner's first initial) in a similar fashion to the Monogramming project. If the joystick is pushed (like a button: straight into the board), the letter changes to the next initial. All teammates initials must be represented (in any order). If Xia Han and Amy Carpenter are working together, then the Pi should display an 'X' on program start, an 'H' when the button is pressed once, then an 'A', then a 'C', then the program should clear the screen and exit. Note that if all letters would be the same, you should substitute the number 3 for the second one shown (to highlight that it actually changes).

When the joystick is moved in a direction, the letter shown should start scrolling in that direction, starting at (about) one pixel/second. Each extra push will speed it up (to 2/second, 3/second, then a max required speed of 10/second: continuing to move faster is okay). The scroll must not "skip" pixels, the delay should just drop between moving to the next position. Pushing the joystick in the opposite direction will slow and eventually reverse the scrolling. You must permit both vertical and horizontal scrolling at the same time with independent speeds!
