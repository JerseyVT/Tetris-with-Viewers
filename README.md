# Tetris-with-Viewers
Allow twitch chat to interface and play the game tetris on stream

Modify the game.game_speed to modify the speed. I have found 0.25 with chat latency is ideal. 

The program will look for !right !left !rotate !r !l !rt !r [Insert numbers here] !l [Insert numbers here] and !rt [Insert numbers here] ; it will look for deviation of right, left, rotate with various capitilizations like !RiGhT etc. make sure there is a space between the symbol and the numbers else the bot will error. 

Twitch has a 3 second delay as well so keep that inmind. 

24 leves, level 24 is the "Kill level"

1000 points == new level

Each line cleared is 100. 

Game will automatically start over after gameover screen.

Game speeds up each level by adding 0.25 to the speed. so level 2 would be 1, level 3 is 1.25 etc. 
