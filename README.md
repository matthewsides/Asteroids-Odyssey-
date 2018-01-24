
![Alt text](https://github.com/matthewsides/Asteroids-Odyssey-/blob/master/asteroids-odyssey-poster.png?raw=true "Optional Title")

| Version 1.00    |
|-----------------|
| 04 December 2017|
 


## Revision List

| Version     | Author          | Date                 | Comments                       |
|-------------|-----------------|----------------------|--------------------------------|
| 1.00        |  Matthew Sides  | 4th December 2017    | Initial Version                |
|             |                 |                      |                                | 
|             |                 |                      |                                | 
|             |                 |                      |                                |
|             |                 |                      |                                |
                   

## Asteroids Odyssey Documentation
This Repository pertains information relating to the conceptual and developed own rendition, reboot of the 1979 video game Asteroids that was first hosted on Arcade Machines.


## Table Of Contents

[1] Introduction 

[2] Scope

[3] Type Conventions

[4] Game Mechanics 

### [1] Introduction

This document specifies a design for the conceptual features and mechanics (gameplay) of a game with the provisional title “Asteroids Odyssey”. It is based on the 1979 arcade game "Asteroids". Asteroids Odyssey a redition of "Asteroids" will hone the elements used in Asteroids and its style, merging the ideology and methodology of Astroids with newer ideologys, methodologies and technology, being re-built from the ground up and not ported (ported Asteroids version edited), Asteroids Odyssey will be compatible and be able to function on newer systems.

### [2] Scope

This documentation is intended to be read by programmers, artists and producers involved in the design implementation and testing of the the Desktop-game and Asteroids recreation  "Asteroids Odyssey".

### [3] Type Conventions

Things that have been discussed in a meeting are presented in this document with no asterisks.

Things that have not been offically agreed on but which are suggested by the author are presented with asterisks, like this (*),being marked as omitted until it has been agreed upon that it may be of use or implemented.


### [4] Game Mechanics

#### Player States

Move-


#### Interactable Entitys 

Big Space Ship

Small Space Ship

Big Asteroid 

Small Asteroid

#### Points system

| ID          | Value           | Destroyed            | Points                         |
|-------------|-----------------|----------------------|--------------------------------|
| Small Asteroid|  50  | 0   |                                                          |
| Big Asteroid|    100 | 0   |                                                          | 
| Small Saucer|    150 | 0   |                                                          | 
| Big Saucer  |    200 | 0   |                                                          |
|             |        |     |                                                          |
                   
#### Health|Damage system

| ID          | Damage          | Hit                  | System Health                  |
|-------------|-----------------|----------------------|--------------------------------|
| Small Asteroid| -1 | 0  | 100%                                                        |
| Big Asteroid|   -5 | 0  |                                                             | 
| Small Saucer|   -4 | 0  |                                                             | 
|  Big Saucer |   -7 | 0  |                                                             |
|             |      |    |                                                             |
                   

#### Player Camera View
The Camera will be a fixed aerial view, tracking the 2D ship graphic model continously (realtime), positioned in the middle of the screen. The system applied, similiar to the online game Diep.io which boasts a fixed camera that disables scrolling out to view the surrounding enviroment (area), thereafter adding another element to the game as players are forced to be more cautious.

![Alt text](https://github.com/matthewsides/Asteroids-Odyssey-/blob/master/Diep.io.png?raw=true "Optional Title")

procedural/randomly generated enviroment

Decided that the game will be hosted on PC despite the rise in the mobile market since the majority of user's and reason for the sudden rise in mobile gaming stems from the east in particular china, whilst the game will only run (be using) on one lingistutic language english. 


Therefore it would be useless to cater to a demographic whom are unlikely to buy the game due to its demenor and exclusion of national language a barrier that though passable is still a problem in regards to the user's ease of use. 

Furthermore nationals with whom speak the english language (americans,english, australia, etc) though have a huge following on mobile, the computing  gamer market still largely outweighs the mobile market by ______, hence the reason the game will be run on PC.

With regards to download, despite the heavy critiscm steam has been garnering recently due to the scrap of steam greenlight and in flux of shoddy and poorly made games, the game will be aviliable and hosted (put up) via the steam store as although the massive flow traffic will make it harder for a game to be distinguishable the abolishment of steam green light does not come without any advantages, since now only a fee is required to be procured by valve or steam rather than a fee and user recognition.

Whilst the ability to stand out in a ever so saturating and cluttered market place would prove capablity and thereafter boost influence and recognition (brand status).

Steam is also still a widely regarded and respected market platform and although may not herald the same status as it used to still has the ability to make or break a game.

In addition to market said applications onto the apple store place an ID is required meriting or allowing the application to be sold through the apple store. Furthermore  apple also includes its own terms of  service  that have to be met and abided by with the application being checked based on said regulations before it is even released even after paying for the right to host on the apple store since apple have their own standards. 

### [5] Inspiration 
Following the decision to recreate the 1979 arcade game Asteroids, collective research into similiar classics and there remakes 
has given fruit to the ideology behind this rendition, Asteroids Odyssey, using the original asthetic outlook and updated vectors,  along with tweaked game mechanics, updated game sounds and a multitude of game variations thus giving the game more flavour, tweaking any faults found in the original due to developer mistakes and allowing the user to have access to more content. Thus enhancing playablity, Mimicking the orignal with a twist, allowing gamers to experience the journey that is asteroids with another, overall following suit to the originals legacy but altering certain aspects of the game to build upon the flaws that stemmed from the 1979 release, essentially modernising the game.

As seen below games that helped formulate this rendition-

Pacman Championship

Mario 

Halo Anniversary (switch between graphics)

call of duty black ops (Zombie mode, Team work, Leaderboard)

Crash bandicoot (DDA System)

Diep.io (Camera view)

http://soundbible.com/1795-Electrical-Sweep.html

add adaptive music 
button to switch between retro graphics and sounds to updated versions
neon updated graphics
faced paced intro before the menu 
2D with 3D aspects or illusion of 3D
