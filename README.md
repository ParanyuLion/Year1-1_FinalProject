# Defender's Last Stand
This project is a shooting game where you need to shoot enemies and avoid theirs bullets.

How to install and run the project:
1. Click green 'Code' button on the top
2. Click Download ZIP
3. Extract the ZIP file
4. Open it in your IDE
5. Run program on run_ball.py file

or you can clone this repository to your IDE and run run_ball.py file

Usage

Demo video link: https://youtu.be/u1avE_1D32M

How to interact:

-Press W,A,S,D to move

-Click left mouse to shoot

-Hold "space bar" to block

You need to run a code and start a game by press 'R' button on your
keyboard. In this game you need to shoot enemies and prevent them to move
close to you and avoid enemies bullet because it will decrease your hp.
If your hp is 0 it will game over. Additionally, you can buy a better gun in a shop
or buy more hp to make you survive.

Project design and implementation
![UML.png](UML.png)

There are 8 classes in this game. Event class is for checking collision of a bullet(ball) and pallet.
 Paddle class is used to be a shield that can block a bullet(ball) and bounce it. Player class
is used for draw a player when it moves. Ball class is used to draw a bullet that have shot from player
and make it collision. Enemies class is used to draw a green enemies. Boss class is used to draw a boss(purple enemy) 
and check when boss get hit or dead. Shop class is used to draw a shop. Run_Program class is used to run a program which
called every function to work and draw on this class and make a system that run a game.

Code that modified: I modify a paddle that will appear when hold 'Space bar' and location is depends on location of 
Player and object that move by user input is Player object.
Next, I modify a wall and delete horizontal wall. Additionally, I modify ball to be shot as a bullet that direction of 
it is depends on user's left click.

Bugs that are still to be resolved:

- When a game is run for a long time it will lag.
- When a game is lagged, speed of enemies and ball will be slower.

Project sophistication level: 98/100 I think this is sophistic for me because this game has many features. For examples:
 Buy a better gun, Buy HP, and boss fight.