Download link :https://programming.engineering/product/jr-game-developer/


# JR.-GAME-DEVELOPER
JR. GAME DEVELOPER
There are few common rules that apply to all tasks:

Your game should be played in portrait mode and should support different aspect ratios.

You are expected to use Unity 2020 LTS.

A playable windows build should be included in submission.

You can use third party assets for any requirement.

Use provided assets where applicable.

It is expected that you will create materials with given textures and apply wherever needed.

Main camera perspective is third person. Feel free to change it whenever needed.

Core mechanics cannot be changed. But you can improve other aspects of the game as you like.

You should be able to answer all project related questions.

If you can’t understand the tasks perfectly, feel free to ask.

TASK 1:PLATFORM RUNNER SCORE: 35 STAGE 1

In this task, you are responsible for making a third person runner game. The goal is to reach the end of the platform without being hit by any obstacle. If our character hits any obstacle, the game will start from the beginning.

You can find the platform that will be used in game in “Platform” folder.

Camera will follow the character from behind during the game. An example camera angle is included in the “Screenshots” folder.

A character will run on the platform trying to avoid obstacles. You can find the necessary assets in the “PlayerCharacter” folder. You are expected to find animations from third-party sites, preferably Mixamo.

There will be no lanes in the platform so the player will be able to move their character freely using swerve mechanics.

Gameplay will be around 25 – 30 seconds. So use your time wisely and design your level accordingly.

Mandatory Obstacles:

There are 2 types of mandatory obstacles. One of them will move horizontally and the other one will be static. The moving obstacles can move in other directions too, depending on your level design. You are expected to use the models provided by us. You can find them in the “MandatoryObstacles” folder.

Bonus Mechanics:

There are 3 types of bonus mechanics. You can find them in the “BonusMechanics” folder. If you implement all of them, you will get 10 bonus points.

Rotating Platform:

This obstacle is designed to rotate around the z-axis with fixed speed. All characters should be affected by it’s rotating speed when they are moving on the platform. For example, if the platform rotates left, characters should try to move right in order to stay in the middle. You can find an example of usage in “Screenshots”.

Half-Donut:

This obstacle can be placed on the sides of the platform. It’s stick can be moved in the x-axis in time intervals to trick the players. Characters can both interact with donuts and stick.

Rotator:

This obstacle contains two different meshes(Rotator and Stick). Stick should be combined with a rotator and rotated around the y-axis. When characters get hit by the stick, they should be pushed with a force. Characters can both interact with rotators and sticks. But only sticks should apply force.

TASK 2: PAINTING THE WALL SCORE: 25 STAGE 2

In this task, you are responsible for painting an object with a desired color.

After finishing the platform at Task 1, a wall will be shown after the finish line. Character will stop in front of the wall and the player won’t be able to control the character any more. Instead, the player will be able to paint the wall with Red color using swerve mechanics.

If you can show the percentage of painted wall in real time, you will get 10 bonus points.


TASK 3: PLAYING AGAINST OPPONENTS SCORE: 40 STAGE 3

In this task player won’t play alone anymore. He/she will play against opponents which are controlled by your code(shouldn’t be multiplayer)

There will be 10 opponents.

Every opponent will use the same model. You can find it in the “OpponentCharacter” folder.

All players should be able to collide with each other.

Objective for opponents is to finish the game by avoiding obstacles.

Opponents should move and avoid as perfect as possible.

If opponents hit any obstacle, they will start from the beginning.

At the top left corner of the screen, the player’s current ranking should be shown in real time.

SAVE & SEND! STAGE 4

You are expected to share your project via BitBucket or Github (send us an email that contains the link to the project – hr@panteon.games).

GOOD LUCK AND HAVE FUN!
