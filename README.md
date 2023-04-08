# Assignment 3.1

- Everything mentioned in the assignment has been implemented.
- **Bonus** :
    - King’s Leviathan Axe has also been implemented.
    - Dragon Character has been added, it can fly over walls.
    - Queen's Eagle Arrow has been added.
    - Movement avoiding walls has also been implemented.

- To run the game : `python3 game.py`
- To view replays : `python3 replay.py`  and select the replay you want to watch according to mentioned date and time.
- For Victory : All buildings apart from walls get destroyed from the map in all three levels.
- For Defeat : If all troops and King die before destroying all buildings apart from walls.

## Controls :

### Hero :

- w : move up
- a : move left
- d : move right
- s : move down
- 1 : Special Attack
- space : Normal Attack

### Barbarian :

- z : spawn at point 1
- x : spawn at point 2
- c : spawn at point 3

### Dragon :

- v : spawn at point 1
- b : spawn at point 2
- n : spawn at point 3

### Archer :

- i : spawn at point 1
- o : spawn at point 2
- p : spawn at point 3

### Balloon :

- j : spawn at point 1
- k : spawn at point 2
- l : spawn at point 3

q : Quit Game

## Assumptions :

- Rage and Heal Spell can be applied multiple times.
- The limit for troops in each level is as follows :
    - Barbarians : 10
    - Archers : 7
    - Balloon : 5
    - Dragon : 3
    - StealthArchers : 5
    - Healers: 2
- You have to choose the type of troop movement at start of the game.
- You have to choose the hero after each level.

## Changes:
- Stealth archers implemented 
- Spawn Keys
  - e : spawn at point 1
  - f : spawn at point 2
  - g : spawn at point 3
- Stealth archer is just a regular archer which is untargetable in the first 10 seconds of the game.

- Healers implemented
- Spawn Keys
  - t : spawn at point 1
  - y : spawn at point 2
  - u : spawn at point 3
- Healers heal troops in a manhattan distance of 7 units, with a area of effect of 1 unit in all directions.

- Levels (Bonus)
- A Building has a level which is hardcoded in the game.
- The Wizard, Cannon and Walls inherit this value from the Building class.
- The wall explodes and deals a damage of 200 to all the surrounding troops