# ArenaGame4

Game Versions:

The branch "Old Version" contains the version that was playtested with the participants. 
The version on the main branch contains the submission.

Tools:

The prototype is implemented in Unreal Engine 5.1.1 and was tested with an Oculus Quest 2 VR Headset.
To test it, you have to connect your VR Headset (for the Oulus Quest 2 it was necessary to install Oculus first).
Also you have to install Unreal Engine (via the Epic Games Launcher) and clone this GIT repository containing the prototype.
When having the VR Headset connected to the computer, open the game and start the VR Preview Mode.
To start the VR Preview Mode in UE5, click on the settings symbol (three vertical points) next to the play button (green triangle) in the toolbar at the top.
Then select "VR Preview". If you cannot select it, make sure your headset is properly connected and restart the Unreal Engine editor.
The headset will start the application automatically if it is properly connected.

![Screenshot 2023-07-31 015153](https://github.com/MilosDenck/ArenaGame4/assets/132711859/3801427f-4221-4aee-8a19-94ac3ec7359b)

Controller:

The game is only meant to be played  with the right controller. The left controller currently has a small bug when picking up weapons for the first time, 
but we did not consider that important because the game is playable with only one controller.

Game:

Controller functions are grabbing, shooting (and teleporting). 
There are four waves of enemies that have to be defeated to win the game. 
There are melee enemies, ranged enemies and drones that will attack you.
When losing all health in a game, enemies will despawn and the current wave will end.

Advanced:

The waiting time in the beginning can be set in the level blueprint of the game map (the main level is called "Map").
To open the level blueprint click on the tree symbol in the toolbar at the top and slect "Open Level Blueprint".
Select the variable TimeBeforeBegin (time before the first wave starts) and set the value in the Details panel under Default Value.
Dont forget to compile the blueprint (under "Compile" left in the toolbar at the top).
However, setting other variables might lead to unpredicted behaviour.

![Screenshot 2023-07-31 022200](https://github.com/MilosDenck/ArenaGame4/assets/132711859/e45a4080-5362-46d9-baac-2c44427a1fb3)
![Screenshot 2023-07-31 022024](https://github.com/MilosDenck/ArenaGame4/assets/132711859/ad2f39fa-6742-4ea1-b251-ca820e6e27c3)
