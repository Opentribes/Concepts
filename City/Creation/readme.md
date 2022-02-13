# First City

As a user, i need at least one city in order to build my buildings and play the game.

Before the game starts, we need to check if a user has as least one city. If the use has no cities at all we need to find the next free available space where a new city can be created.

When city is created the user will be redirected to overview.

## Implementation

The process of creating a city will be realitzed in multiple iterations

### Iteration 1

Just create a City with random unused locations within a grid boundary

### Iteration 2
Use directions indicator for the random values boundaries

### Iteration 3
Build cities from Centerpoint to the outside boundaries of the map based on date and density 

## UseCaes
CheckPlayerHasCity
CreateNewCity