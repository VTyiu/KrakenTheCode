# Kraken the Code
Collaborative with artist Krajna Alcantara (ig: @slice.o.onione), a top down dungeon game created with Unity.  Code is in C++.  Early stages and was only able to make a limited number of levels.
Game is playable on itch.io in-browser: https://vtyiu.itch.io/kraken-the-code-final

Game inspired by Binding of Isaac.

Originally, the game was made to be a 2d platformer which is why the main character's figure does not really fit the game and the style (ex: difficult to dodge the bullets due to the "long" body).  For the second version of the game, we decided to make it a 2d top down dungeon style so we reused the same assets due to time constraints.
The game also has a false sense of choice - there are different exits to the next room but even though the exits are in different places, the room that it exits to is the same.

Successful points:
- Character movement is very responsive to the direction keys that the player uses, including diagonals
- Collectibles disappear and add to the counter once the character makes contact with it
- Obstacles stop the player from moving while keeping the perspective of the game in mind
- Start, Death, and Ending screen - successful game loop
- Successfully implemented sound effects - background music, collecting objects, character getting damaged, cabinets opening
- Player is able to press space to open cabinets
- When all collectibles are collected, the exit doors to the room open
- Very cool enemies: three different types of enemies - ones that are stationary and blink, ones that have their eyes closed, opens when player gets to a certain distance from it, and then the enemy starts chasing the player, and ones that are stationary, blink, and shoot an ink sac at the player
- Name of the game is a pun haha

Aspects that can be improved:
- Change the main character's model to be shorter and more fit for dungeon crawler style games
- Add more stages and make it so that the rooms are randomized
- Add to the efficiency of the game - this was my first couple of months using Unity to create games and in order to get some parts to work, I loaded in assets or coded actions in a very roundabout way with the goal simply of getting it to work
- I wanted to make it so that the hitbox and collision box of the character is different - this could have probably been down by intializing two collision boxes on the character and checking for the respective box when hit by either a damage object or obstacle
- Stylize the itch.io link to be more attractive
- Life should not be reset every time the character walks into a new room
