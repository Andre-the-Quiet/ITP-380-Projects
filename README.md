# ITP-380-Projects
作品名　　：Super Mario Bros.
 Work Name
 作成期間　：1 week
 Time Frame

-----------------------------------------------------------------------------
 プログラム作品の開発環境についてご記入ください
 What was the development environment used for your program?
-----------------------------------------------------------------------------
・動作確認したOS名とそのバージョン
Windows 10


・開発に使用したライブラリ、ミドルウェアとそのバージョン
 Simple DirectMedia Layer (SDL 2.0) Library


・開発に使用したエンジンのバージョン
  No engine used


・開発に使用した開発環境のバージョン
  Visual Studio 2019


-----------------------------------------------------------------------------
 どうしてそのプログラムを作ろうと思いましたか？
 Why did you create this program?
-----------------------------------------------------------------------------
I created this program for a video game programming course at the University of Southern California

-----------------------------------------------------------------------------
 プログラムを作成する上で注意した事は？
 What were you careful about?
-----------------------------------------------------------------------------
I was careful about implementing object collisions so that the player (Mario) could stand on platforms and stomp on Goombas.  I also made sure that when the Goombas collide with each other they start moving in the opposite direction.

-----------------------------------------------------------------------------
 プログラムを作成する上で大変だった所は？
 What did you find difficult?
-----------------------------------------------------------------------------
Implementing the camera was difficult because it had to follow Mario when he traveled towards the right of the screen, but it couldn't go left.  Also, Mario is not allowed to move past the camera.

-----------------------------------------------------------------------------
 力をいれて作った部分で、「プログラム上」で特に注意してみてもらいたい所は？
 What points do you want us particulary focus on your work?
-----------------------------------------------------------------------------
I'm pleased I was able to successfully check collisions between Mario, the platforms, and the Goombas because it was my first time having to check for collisions between game objects and then implement specific behaviors upon colliding.

-----------------------------------------------------------------------------
 参考にしたソースファイルがあるのなら、 どの様なところを参考にしましたか？
 またその部分のファイル名を書いてください。
 If you took some source codes as reference, what part of them did you use? 
 Please also tell us the filename of that part.
-----------------------------------------------------------------------------
Because this project was for a class I cannot publicly display my code.  If you would like to see the code I wrote, please contact me and let me know so that I can send my code directly and privately.


作品名　　：The Legend of Zelda
 Work Name
 作成期間　：1 week
 Time Frame

-----------------------------------------------------------------------------
 プログラム作品の開発環境についてご記入ください
 What was the development environment used for your program?
-----------------------------------------------------------------------------
・動作確認したOS名とそのバージョン
Windows 10


・開発に使用したライブラリ、ミドルウェアとそのバージョン
 Simple DirectMedia Layer (SDL 2.0) Library


・開発に使用したエンジンのバージョン
  No engine used


・開発に使用した開発環境のバージョン
  Visual Studio 2019


-----------------------------------------------------------------------------
 どうしてそのプログラムを作ろうと思いましたか？
 Why did you create this program?
-----------------------------------------------------------------------------
I created this program for a video game programming course at the University of Southern California

-----------------------------------------------------------------------------
 プログラムを作成する上で注意した事は？
 What were you careful about?
-----------------------------------------------------------------------------
I had to make sure that when the player (Link) goes through a door to another room, the game knows what room Link is entering and what game objects are in that room that may need to be spawned/set active.

-----------------------------------------------------------------------------
 プログラムを作成する上で大変だった所は？
 What did you find difficult?
-----------------------------------------------------------------------------
Using a tile map to create the dungeon was challenging because I had to make sure the correct tile was being put in the correct space in the game.  Also, creating a secret block that needs to be pushed in a specific way by the player in order to open a closed door was challenging as well.

-----------------------------------------------------------------------------
 力をいれて作った部分で、「プログラム上」で特に注意してみてもらいたい所は？
 What points do you want us particulary focus on your work?
-----------------------------------------------------------------------------
I'm glad I was able to use callback functions to implement specific object behaviors in the game such as collectibles and enemies taking dameage.  Additionally, I was able to create and implement a rage mode for the dungeon boss when its health was low.

-----------------------------------------------------------------------------
 参考にしたソースファイルがあるのなら、 どの様なところを参考にしましたか？
 またその部分のファイル名を書いてください。
 If you took some source codes as reference, what part of them did you use? 
 Please also tell us the filename of that part.
-----------------------------------------------------------------------------
Because this project was for a class I cannot publicly display my code.  If you would like to see the code I wrote, please contact me and let me know so that I can send my code directly and privately.


作品名　　：Supace Tunnel
 Work Name
 作成期間　：1 week
 Time Frame

-----------------------------------------------------------------------------
 プログラム作品の開発環境についてご記入ください
 What was the development environment used for your program?
-----------------------------------------------------------------------------
・動作確認したOS名とそのバージョン
Windows 10


・開発に使用したライブラリ、ミドルウェアとそのバージョン
 Simple DirectMedia Layer (SDL 2.0) Library


・開発に使用したエンジンのバージョン
  No engine used


・開発に使用した開発環境のバージョン
  Visual Studio 2019


-----------------------------------------------------------------------------
 どうしてそのプログラムを作ろうと思いましたか？
 Why did you create this program?
-----------------------------------------------------------------------------
I created this program for a video game programming course at the University of Southern California

-----------------------------------------------------------------------------
 プログラムを作成する上で注意した事は？
 What were you careful about?
-----------------------------------------------------------------------------
I needed to delete the walls and obstacles I was creating once they went past the screen so as to make sure the memory wouldn't fill up and the game wouldn't slow down as a result.

-----------------------------------------------------------------------------
 プログラムを作成する上で大変だった所は？
 What did you find difficult?
-----------------------------------------------------------------------------
I had trouble initially figuring out how to load in more blocks and obstacles as the ship continued to fly forward.  They had to be loaded in a certain amount of units ahead of the ship's position current position.

-----------------------------------------------------------------------------
 力をいれて作った部分で、「プログラム上」で特に注意してみてもらいたい所は？
 What points do you want us particulary focus on your work?
-----------------------------------------------------------------------------
I'm happy I was able to correctly use matrices of the camera space and the world space to have the camera follow the ship as it moves down the corridor.  I'm also pleased with how I programmed the red exploding blocks to destroy blocks in a radius around it which can cause other red blocks to explode as well in a chain reaction.

-----------------------------------------------------------------------------
 参考にしたソースファイルがあるのなら、 どの様なところを参考にしましたか？
 またその部分のファイル名を書いてください。
 If you took some source codes as reference, what part of them did you use? 
 Please also tell us the filename of that part.
-----------------------------------------------------------------------------
Because this project was for a class I cannot publicly display my code.  If you would like to see the code I wrote, please contact me and let me know so that I can send my code directly and privately.
