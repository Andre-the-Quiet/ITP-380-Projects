# ITP-380-Projects
This is a collection of projects completed for the course ITP 380: Video Game Programming at USC.  In this course, I have recreated many classic games using C++ and assets provided by the class.  As these projects were created for the course, I cannot have any code publicly available in my repository.  Please contact me directly at pascualgamedesign@gmail.com, so that I can send you my code privately.
----------------------------------------------------------------------------------------------------------------------------------------
Parkour's Edge

A rendition of the game Mirror's Edge (2008) released for Xbox 360, Playtation 3, and PC.  The player must traverse the level and activate all the checkpints without being detected by enemy cameras and lasers.

I created a first-person camera for the player as well as states for wall climbing and wall running.  I utilized both quaternions and object parenting to rotate the lasers and security cameras.  I made a 2D radar that tracks the position of the cameras and the direction they are facing.  I also programmed sound effects relative to the player’s position in 3D space.

----------------------------------------------------------------------------------------------------------------------------------------
Space Tunnel

This 3D game does not emulate any specific game, but it is inspired by games like X-Wing Alliance (1999) where you fly a spaceship into a narrow corridor and must avoid and destroy obstacles in your path.

I implemented a 3D camera that follows the player ship as it moves forward and I recursively programmed chain explosions for certain obstacles.  I also continuously generate more obstacles in front of the ship for endless gameplay.

----------------------------------------------------------------------------------------------------------------------------------------
The Legend of Zelda (1986)

An action-adventure game released for the Nintendo Entertainment System.  For this project I created a dungeon full of monsters and a dragon that Link must overcome in order to collect the triforce.

I used a tile map to create a 2D dungeon and implemented collectibles the player could pick up and use later, such as a key to unlock a door.  I programmed all the enemy behaviors, including the boss who had a normal state and a rage state.

----------------------------------------------------------------------------------------------------------------------------------------
Super Mario Bros. (1985)

A platformer game released for the Nintendo Entertainment System.  For this project I recreated the first level of the game where you play as Mario and traverse across the level to reach the castle the princess is supposedly in.  

I implemented a 2D parallax camera as well as collision boxes for enemies and the player.  I also handled all the sounds, animations, and the win and lose conditions for the player.  
