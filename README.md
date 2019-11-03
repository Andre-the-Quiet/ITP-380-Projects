# ITP-380-Projects
This is a collection of projects completed for the course ITP 380: Video Game Programming at USC.  In this course, I have re-created many classic games using C++ and assets provided by the class.

Pong For One

This project recreates the classic arcade tennis game Pong(1972), but as single player gaem instead.  The player controls a rectangular paddle and bounces the ball against the wall.  The goal is to keep the ball from moving past your paddle.

I calculated delte time to limit the game to 60 frames-per-second (FPS) and I implemented the movement of both the paddle and the ball.  I included an additional feature where the player can "rewind time" and have the ball travel backwards along its trajectory by holding down the "R" key.

Super Mario Bros. (1985)

A platformer game released for the Nintendo Entertainment System (NES).  You play as Mario and traverse across eight worlds to save Princess Peach from Bowser, the Koopa King.  For this project I recreated the first level of the game.

I implemented a scrolling camera that follows Mario only when traveling towards the right side of the screen.  I also handled all the collisions between Mario, Goombas, and the platforms.  

The Legend of Zelda (1986)

An action-adventure game released for the NES.  You play as Link, seeking eight fragments of the Triforce so you can save Princess Zelda from the evil Ganondorf.  For this project I created a dungeon where a dragon protects the triforce.

I used a tile map csv file to create the dungeon and implemented collectibles the player could pick up and use later, such as a key to open a locked door.  I programmed secret blocks the player had to push in a specific direction to unlock certain doors as well as coded all the enemy behaviors.
