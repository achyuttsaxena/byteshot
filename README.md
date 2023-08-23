# byteshot

An 8 bit FPS game for uxn written in uxntal

To play the game,

1. clone the repo
2. cd into byteshot/uxn
3. ./uxnemu.exe ../byteshot.rom

Controls of the game -

(up arrow) - To move forward
(down arrow) - To move backward
(left arrow) - To turn left
(right arrow) - To turn right

(left ctrl ) - To shoot/fire
(left alt) - To open Door

Objective of the game -

The objective is to unlock the door of the level which can be done using the door code for that level. The enemies are to be killed in a specific order to form the binary representation of the door code

for example if the code is 3 then its binary represntation becomes 0011 so in order to unlock the door the enemies of the corresponding type need to be killed in that order which will become to be

1 -> 1 -> 0 -> 0

Once the correct code is achived the door will unlock and turn from red color to green.

In order to pass through to the next level, the player should stand in front of it and press ( left alt) to open it.

Note -
The walls are represented by white color.
The door initially in its locked state is represented by red color.
After unlocking the door with the correct code the color changes from red to green.
