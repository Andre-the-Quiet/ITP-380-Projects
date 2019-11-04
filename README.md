# ITP-380-Projects
This is a collection of projects completed for the course ITP 380: Video Game Programming at USC.  In this course, I have recreated many classic games using C++ and assets provided by the class.
------------------------------------------------------------------------------------------------------------------------------------------
Super Mario Bros. (1985)

A platformer game released for the Nintendo Entertainment System (NES).  You play as Mario and traverse across eight worlds to save Princess Peach from Bowser, the Koopa King.  For this project I recreated the first level of the game.

I implemented a scrolling camera that follows Mario only when traveling towards the right side of the screen.  I also handled all the collisions between Mario, Goombas, and the platforms.  
------------------------------------------------------------------------------------------------------------------------------------------
The Legend of Zelda (1986)

An action-adventure game released for the NES.  You play as Link, seeking eight fragments of the Triforce so you can save Princess Zelda from the evil Ganondorf.  For this project I created a dungeon where a dragon protects the triforce.

I used a tile map csv file to create the dungeon and implemented collectibles the player could pick up and use later, such as a key to open a locked door.  I programmed secret blocks the player had to push in a specific direction to unlock certain doors as well as coded all the enemy behaviors.
------------------------------------------------------------------------------------------------------------------------------------------
Space Tunnel

This 3D game does not emulate any specific game, but it is inspired by games like X-Wing Alliance (1999) where you fly a spaceship into a narrow corridor and must avoid obstacles in your path.

I implemented a camera that follows the ship as it moves forward through the corridor using matrix transformations.  I also generate more obstacles and game objects in front of the ship as it continues forward to create an endless mode.  
