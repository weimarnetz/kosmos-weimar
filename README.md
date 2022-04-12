# Kosmos Weimar

Workadventure Map for Maschinenraum, M18 and more

A collection of connected workadventure maps of Weimar.

These maps will be automatically deployed to [https://play.world.maschinenraum.tk](https://play.world.maschinenraum.tk/_/global/maps.world.maschinenraum.tk/campus.json). A script will automatically optimize tiles and maps. For this to work properly, all maps have to follow some conventions.

`campus` will contain the central map with exits to all locations and an exit to [2D World Thüringen](https://github.com/die3ungleichen/2D-Welt-thueringen).

## How to add a new location

1. create a new directory for your location. Here you can create one or more maps.
2. Within your directory, create another directory called `tiles`. All tilesets go here. Don't use tiles from other locations directly, please copy them if needed. This applies also if you're going to use
3. Set exit links to the campus to `../campus/campus.json#<yourlocation>`.
4. Create entries and exits for your location in `campus.json`.
5. Add the property `tilesetCopyright` for every tileset you use. This can be done on 
