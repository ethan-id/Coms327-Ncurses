
# ComS327-Trainers
### Author:
Ethan Hancock, ehancock@iastate.edu
### TA Notes: 
> Some functionality is missing, Hikers and Rivals aren't moving (I think my distance map output from 1.03 isn't completely correct) and Swimmers don't path to the player when it is cardinally adjacent, I believe everything else required is implemented though.

### Description:
#### Changes:
 - Program usage is now:
      `./trainers --numtrainers [number of trainers, default is 8]`
      To quit press Ctrl+C
 - Removed ability to move around the world, instead the game is now 'turn-based' with each trainer on the map as well as the player getting a turn.
 - The map is redisplayed every time it is the player's turn.
 - Currently the player's turn is 'ignored' and just used to refresh the map
	 - Later the turn will sort of 'pause' the game awaiting input from the user for how they would like to move

#### Methods Added
 - generateTrainers()
 - findPosition()
 - positionNotOccupied()
 - getMoveCost()

