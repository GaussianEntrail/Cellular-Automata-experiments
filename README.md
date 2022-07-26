# Cellular-Automata-experiments
various experiments with cellular automata

## Mazectricblobs.html
This one has a large neighborhood and rules akin to Maze/Mazectric. 

## TwoRulesBlobbymaze.html
Alternates between the standard Game of Life and a rule involving a large diamond shaped neighborhood. Has four states. Creates a bunch of mazes

## Jellyfish.html
Alternates between two rules with four states- Empty, Alive, Old, Dying. Instead of immediately going Empty when it doesn't pass the Survive rule, a cell instead becomes Old, which still counts as Alive for it's neighbors, but it'll immediately go to Dying (which does not count as Alive)

* B3/S34 with a Moore neighborhood 
* B56/S56789 with a diamond shaped neighborhood of radius 2. 

Creates interesting jellyfish shaped gliders.

