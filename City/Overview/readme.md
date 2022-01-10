# City overview

## General information

As a user, i can build buildings in a city. So i need the city overview to see all the buildings within the city.

A city have building slots on which you can place a building. You can build multiple buildings in Order to modify the production output of the city. Since there is a limitation, you need to plan what kind of buildings youre going to build in every city. So you can create specialisations.

Some Buildings can be build once on a special slot. For example the city wall has only one slot and can be build only there.

Each Building will have his own overview with actions. On empty slots a list of availiable Buildings will be opened in order to place the building on this slot.

It is possible to create multiple buildings of same kind in a city.

## User Story

as a player, i can navigate to a URL with a coordianates. for example

/city/123/456

if the city belongs to another player, you will see some general information about the owner and this city. More about this topic [here](other_cities).

if the city blongs to the user, you will see the city overview.

### Overview
as a player, i will see 10 empty slots to place a building. by clicking on an empty slot, a popup will open and show all avaliable buildings. 

i can choose to build one building to build and will return to the city overview afterwards. 
the slot where the building will be placed is no longer free and shows a progressbar with end date when the building will be build. 

in the slot i also can see the building name.

When the progressbar reaches 100% the building is build and i can only upgrade this building or downgrade this building.

Next to the empty slots i can see special slots. in this slots i can only build specific buildings made for this slot. For example a wall or maybe in the future a harbor. 

When i click on existing building, a popup of this building will open with three buttons, upgrade, downgrade and destroy. each of the buttons will closes the popup and create a progressbar at this slot to indicate the progress.

If the Building reaches Max level, upgrade button is not shown anymore. 

If the Building reaches Min level, the slot is marked as empty and i can build another buildings on this slot.

Destroy destroys the builduing completely

## Implementation

This Feature will be developed in Multiple Iterations. 

### Iteration 1

First Iteration will display a simple list as slots indicators. Each slots opens a popup whic display all buildings and a build button next to building name.

Build button closes the popup and shows the progressbar at this slot.

### Iteration 2

Slots are now split in multiple types, fixed and variable and only buildings for that slot can be displayed in the popup.

Buildings increase the building time per level based on fixed value

### Iteration 3

Slots are displayed on a background image. For this Iteration it is required to have city background image and building images.

### Iteration 4

Only Buildings which can be build, based on techtree are displayed in the popup. For this Iteration it is required to have a [Techtree](../../Techtree)

### Iteration 5

Buildings have costs