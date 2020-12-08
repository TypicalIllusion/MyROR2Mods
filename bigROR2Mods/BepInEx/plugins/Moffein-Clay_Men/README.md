Adds the unfinished Clay Man into the game as a fast melee trash mob that can deal high damage to unwary players.
They can chase and keep up with sprinting players, but can be outmaneuvered by jumping and strafing.
Spawns on Abandoned Aqueduct and Rallypoint Delta, and replaces beetles on Scorched Acres.

All players need the mod. This is because Clay Men do not have a hitbox by default, so people without the mod will be unable to damage them.
Partially based on rob's unfinished Clay Man code.

## Installation
Place ClayMen.dll in /Risk of Rain 2/BepInEx/plugins/

## Changelog
'1.0.0'
- Release
'1.0.1'
- Readme update.
'1.1.0'
- Fixed issues with Huntress targeting and melee in multiplayer.
'1.1.1'
- Increased spawn cost from 15 to 18 to be on par with the Cost:HP ratio of other enemies.
'1.1.2'
- Reverted spawn cost back from 18 to 15. The original intent of increasing the spawn cost was to make Clay Men spawn a bit less frequently earlygame, but it instead caused them to rarely spawn at all. Even increasing the spawn cost just to 16 seemed to reduce their spawnrate significantly, so I'll be leaving it at 15.
- Reduced HP from 180 to 170. This is a minor change that should make it a bit easier to deal with Clay Men on stage 2 when you still have few damage items.
- Added spawn cost config option. This is server-side.
'1.1.3'
- Clay Men now use BodyClones for better compatibility with PlayableTemplar. Clay Men are now internally labeled as MoffeinClayManMaster when spawning them via DebugToolkit.