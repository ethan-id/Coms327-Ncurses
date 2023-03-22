
# ComS327-Ncurses
### Author:
Ethan Hancock, ehancock@iastate.edu
### TA Notes: 
> 

### Description:
#### Changes:
 - generateTrainers() contains main game loop, which loops through queue of trainers, including the player
   - Player's 'turn' is a nested switch case statement, beginning at line 770.
     - This handles all user actions
 - generateTrainers() updated to handle player movements and other user actions.

#### Methods Added
 - notGate(): Method for player movement verification, returns true if a position is not a gate.

