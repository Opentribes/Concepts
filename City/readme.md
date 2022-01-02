# Cities

Cities are used to produce resources, create troups and build buildings.

Each player will get automatically one city when he enter the game first time. The location for the city will be picted based on an algorithmus see [creation](#creation)  

In the city view the player can see different spots where he can create buildings. 

He can only select buildings which a suited for the place and if he has the requirements to build the bilding. Requirements in terms of Techtree.

Each Building is clickable so you can enter the building view to manage the building.

## Creation

Cities will be created surrounding the center of the map. When a new Player starts the game he will see a selection for EAST,SOUTH,NORTH, WEST and RANDOM. Here he can define which position he prefer to have a new city.

The complete Map will be devided into 4 Sections and the city will be created in one of those section based on selection of the player.

How far away fom the center will be calculated based on game server start. At the start everyone will gather in the center of the map and with the time the player will be placed further outside. 

The time should not be used as a linear measurement, otherwise players which are joined latly will be placed far away from everyone. The amount of player should be a factor as well, if a new server is crated many players might join and since in the center there is not that much space the player has to be placed further away.

Next to the new Player Village some random NPC Villages and Hideouts will be placed so we can provide first battle experience

## Deletion

If a player deletes his account due to inactivity or manually all his cities become NPC VIllages

## Overview

Once a city is created the player can see the city overview with a specific URL.
More details [here](City/Overview/readme.md)



