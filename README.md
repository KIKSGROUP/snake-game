<h1>SNAKE GAME<h1>

<h1>The sheet is made of 25rows and 25columns
The snake atn (5,5) , each cube has 10pixels on the X and Y axis
Random - it is used to place the food randomly at different spots in the game 
Resizable - this done so that nobody can alter the change the size on the playing screen
The window feature is used to centre the playable screen on your home screen
The CLASS_Tile is used to store the position of thr snake and the food

(Keep in mind the 5 is the pixel size and we want it to be 5 tiles, so we that's why we add TILE_Size function)

When you use the global function with the snake it references it references to the one outside the function
Velocity is the change of the position over time
KeyRelease - when u press and release a key, we want a change to occur
e - stands for event
(keysym) - key symbol
When defining the snakes movement you multiply by 1 Tile_Size and not 1 pixel
Delete all - deletes all the frames the snakes passes so as to make it looking too continuous
Adding velocity != 1 (is not equal to one) is to prevent the snake moving backwards since it is already moving upwards (up button)
Adding velocity != 1 (is not equal to one) is to prevent the snake moving upwards since it is already moving downwards (down button)
Adding velocity != 1 (is not equal to one) is to prevent the snake moving to the left since it is already moving right (right arrow button)
Adding velocity != 1 (is not equal to one) is to prevent the snake moving to the right since it is already moving left (left arrow button)<h1>

