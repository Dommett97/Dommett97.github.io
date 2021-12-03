---
layout: project
type: project
image: images/GameBoard.jpg
title: The Sun Temple
permalink: projects/the_sun_temple
labels:
  - Python
summary: A text based board game I developed for my Introduction to Programming module.
---

**Project description:** The Sun Temple is a competitive board game between two players.
The temple is represented by a linear path of 40 spaces. A single marker representing the players’ expedition is placed on the first space of the board (the entrance to the Sun Temple). The remaining 39 spaces contain precious gems and glass beads. 

### 1. Aim of the Game
Players alternate turns moving the expedition marker.  For each space traversed, the active player collects the gem or glass bead on that space. After the expedition marker exits the Temple (i.e. moves past space 40), the game is over and players calculate their scores based on the gems and glass beads they have collected. The player with the most points is the winner.

### 2. Game Setup
The game begins by asking the players to enter in their names and once done the game board is displayed and one of the two players is chosen at random to start the game, the board is populated with a variety of different gems and also glass beads. The players are presented with  set of movement cards that they can choose between, there are up to 13 different cards to choose from and the correct validation has been implemented to only allow selection of the present cards.

The following image represents the game board with a randomly generated array of gems and glass beads:<br>
<img src = "https://Dommett97.github.io/images/GameBoard.jpg"/>

The following image represents the movement cards and a validation check:
<img src = "https://Dommett97.github.io/images/MovementChits.jpg"/>

### 3. Playing the Game
The active player chooses a movement chit from those available and advances the expedition marker by the chosen number. For each space traversed, including the final resting space, the active player collects the associated gem or glass bead. The movement chit is then discarded (and no longer available to the players).

<img src = "https://Dommett97.github.io/images/MovementMade.jpg"/>

### 4. End of the Game
Once the expedition marker exits the board, the game is over. 
<br>
<br>
The player who did not exit the board with the marker receives a bonus gem or bead, determined at random, in addition to those already collected.

## Scoring
When the game is finished, players calculate their scores as follows:<br> 
<br>
Firstly, count the number of gems each player has collected of each type. Players gain points for collections of gems as follows.
<br>
•	1 gem of one type = 1 point<br>
•	2 gems of a type = 3 points [1 + 2]<br>
•	3 gems of a type = 6 points [3 + 3]<br>
•	4 gems of a type = 10 points [6 + 4]<br>
•	etc.<br>
<img src = "https://Dommett97.github.io/images/ScoreOutput.jpg"/>
