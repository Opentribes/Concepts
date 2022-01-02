# Map

The Map is a tiled based map with different tiles on it.

It is also the Entrypoint to the game. When a player joins the game he will see the city which he selected or visited last time.

Around the cities the player will see his own troups, enemies and other cities which are near by.

Different Tiles on the map can have an effect of movement speed and visibility. Also the tiles define the amount of resources a city can get nearby.

## Generation
For the start the map can be just generated randomly.
The map will be generated with Perlin Noise algorithm.
In the Future a map generator tool is required.

## Storage
After generating the values, the values will be stored in a file. The filename will contain meta informations for the map. Those are the maximum widht and bytesize for values. 

map_10000_10000_4.txt = map width is 10000, height is 10000 and each value in the file is 4 character long. with those values you can read very performant the specific section of a map.

## Display

The map will be display in Isometric fashion
![[isogrid.png]]