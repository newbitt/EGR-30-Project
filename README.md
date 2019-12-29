# EGR-30-Project
Scanning Game Simulation

Project Summary
Inputs:
- Pushbutton

Outputs:
- LED
- LCD Screen
- Piezo Buzzer

     The goal of this project was to make a mini scouting game for the user to interact with, in an attempt to simulate an RNG (random number generator) game setting.
     Every few seconds, the game will go through a list of variables and check their individual randomized values. An event in the game is triggered when the randomized value matches accordingly with a condition which I had intended.
     A sizeable portion of the randomization occurs during "enemy hunting", whereupon encountering a unique enemy, the player is then placed into turn-based combat against it (push button is used to attack). There is also a leveling system where after successfully beating a certain amount of enemies, the player and enemies get stronger and more difficult.

Long Term/Potential:
    This scope of this project can be expanded and improved upon easily, with each randomized value potentially storing its own event for the player to experience throughout the game. Some of the events I wanted to implement but couldn't due to time constraints were:
- Shield Robot Actions
     Mounting the Arduino on a Shield Robot, where certain levels will allow it to perform actions (moving in a square at level 3 or moving to a tune played). 
- Unlockable Content/Enemies
     Upon defeating enemies, the player will unlock MORE enemies to encounter and defeat.
- Changing LCD resolution
     Quality of life - adjustment.
- File Storage/Memory Save 
     Creation of a file to tag all hunted monsters and player statistics.
-  Ping Sensor (turn off and on)
     Used to turn the game off or on depending on the distance from one's hand.
- Small hidden improvements
     More melodies for certain actions. 

