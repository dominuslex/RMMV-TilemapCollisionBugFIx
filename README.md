# RMMZ-TilemapCollisionBugFIx
RMMV has a broken collision system. This fixes it. 


In Rpg Maker MZ, there is a strange behavior with tiles. If you have an autotile set as not passable, 
but then you place a tile on top of that tile that is passable, it treats the whole tile as passabe. 

Additionally, if you wanted the player to be able to get on to the auto tile, for instance up a ramp, 
but did not want the player to be able to walk off the back side of the cliff on to the grass,
it was not possible. You had to rely on hand placing tiles for which you can control the movement.

This plugin fixes these issues. The player is not able to step onto an roof autotile that is marked
as impassable except from the bottom. It also prevents fixes the issue of placing a passable tile 
on top of a non passable tile, thereby making the entire tile passable. 
