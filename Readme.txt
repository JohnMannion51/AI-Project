A.I. Project 4th Year Software Development GMIT


A.I. Maze Game:
The objective of the game is to escape from a maze and either 
avoid or fight off the enemy characters (spiders) that move around 
in the game environment. The player navigates through the maze using 
the arrow keys trying to find an exit which triggers the end of 
the game. If at any point the player gets lost in the maze you can
press the z button to zoom out and view the entire maze and the player 
is represented by a yellow square on the map. The player must avoid 
enemy spiders that are actively seeking out the player, using traversal 
algorithms, in an attempt to destroy him. When the spiders find the
player fuzzy logic and a neural network are employed to decide on what 
action they should take. The player can however increase his durability 
by collecting swords that are placed throughout the maze. This can also 
determine if the spiders attack or flee the player. The player can also
collect and drop bombs that can hurt enemies and destroy hedges on a time 
delay but if the player stands to close to the blast it will inflict damage
upon them. 


Enemy Spiders:
This game makes use of traversal algorithms, neural networks 
and fuzzy logic that decide how the spiders behave. Each spider has 
their own thread which means when one dies another is created. There 
are 8 different types of spiders, each has its own traversal algorithm, 
making use of A*, Steepest Ascent Hillclimb, Best First, Random Walk 
and Brute Force. Once the game starts the spiders are created and the 
traversal algorithm begins looking for the player. If the player is 
found it then checks whether to fight or run using fuzzy logic or neural net.

Player:
The player starts with a health of 100 to allow him to actually take 
a few hits while he wanders around. The player can also interact with 
swords and bombs. The swords provide added durability and the bombs 
are used to hurt enemies and destroy hedges in the maze.

Running the Project:
Open a command prompt window and cd to the folder then run

java –cp ./game.jar ie.gmit.sw.ai.GameRunner


