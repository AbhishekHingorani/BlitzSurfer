# BlitzSurfer

Web application to simulate a beatpad and create music with beats. User can select diffrent instrument
and record melodies and share them with friends. (Tools and Technologies used : Visual Studio 2012, IIS
Server, SQL Server, C#, HTML, CSS, Javascript, JQuery)

# 1.0. Introduction

**1.1 PURPOSE**

The main purpose of the project is to create an entertaining and a unique game, which runs on the android mobile platform. There are two games in the project and each one will be played with a different mechanism of the device such as virtual joystick or accelerometer. This document&#39;s audience is developers, testers, end users.

**1.2.  SCOPE**

The project&#39;s name is &quot;GameName&quot;. The aim of this project is to create an entertaining and addictive mobile game. This project consists of two basic modes, which are called &quot;single player mode&quot; and &quot;multiplayer mode&quot;, respectively.

In the single player mode, the player will be driving a boat through a narrow stream of river surrounded by mountains dodging different obstacles that come in the way. In the multiplayer mode, players can join a game hosted by a person through there respected devices and play with each other.



**1.3.  REFERENCES**

The resources listed below are the references that has been used during the requirements analysis; IEEE Standard Documents:

[1] IEEE. (1998). IEEE Std 830-1998 IEEE Recommended Practice for Software Requirements Specifications. IEEE Computer Society.

[2] Unity UI. (n.d.). Retrieved November 28, 2014, from http://unity3d.com/

[3] Parse. (n.d.). Retrieved November 28, 2014, from https://www.parse.com/

**1.4.  TARGET USER**

Anyone who has an android device running android 4.4 and higher can download and play this game.



# 2.0.  Overall Description

**2.1.  OVERVIEW:**

GameName is a mobile game which will be made in Unity Game Engine for Android smartphones. The game will have two modes, Single player as well as Multi player.

 When the user enters, the game menu screen will be displayed. From menu screen the user can go to single player scene, multiplayer scene, settings scene and about scene. For the first visit of the user there will be tutorials for each game.

As mentioned before single player mode will be an infinite runner game similar to &#39;Temple run&#39; or &#39;Subway surfer&#39;; In which the user will be driving a boat through a river dodging obstacles. The goal will be to create high score by driving as far as possible.

Multiplayer mode will let players play against each other in an arena by allowing user to join the game hosted by any one player. The game initially supports connection over local area network only.

#3.0.  REQUIREMENTS FOR DEVELOPING SYSTEM**

**3.1.  Software**** Requirements**

User needs an Android device running android 4.4(KitKat) or higher.

**3.2.  Hardware Requirements**

To handle data flow high-end servers are required. The user can use the application using almost any device which has internet access.


# 4.0.  MODULES

**4.1.  Main Menu**

The First screen that user interacts with after the splash screen. This screen contains buttons to traverse to other screens such as &#39;Infinite Runner&#39;, &#39;Multiplayer&#39; etc.



**4.2. Infinite Runner**

This is the single player offline part of the game. User drives a boat through narrow stream of river surrounded by mountains dodging obstacles that come in the way to create high score. The user interacts using a on screen virtual joystick and buttons or using the gyroscopic controls.



**4.3.  Multiplayer**

This is the multiplayer part, where multiple devices connect with each other through WLAN.

The player will be given a choice if he wants to host a new game or join an existing one.

The player can also give name to his game while hosting, so that it is easier for other players to recognize a particular game over number of games on the network. Player will play against each other in an arena and score points.



**4.4.  Settings**

Player can customize some settings. Gameplay settings can also be customized.



# 5.0.  FLOW OF APPLICATION

#

Main menu of the game is the first scene user interacts with when the game starts. From there user can either choose to play the game in multiplayer or single player mode.

If the user selects single player mode, the infinite runner simply starts.

If the player selects multiplayer mode. He will be given a choice to either host a game or join a game. If the player chooses to host a game, he must give his game room a name using which his game will be identified on the network. If the user chooses to join a game, he can choose to join a game from all the available games in the network.

User can also change some gameplay setting by going to &#39;Setting&#39; scene.
