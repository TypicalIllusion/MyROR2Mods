- Code, UI, and other stuff by me
- Model, Textures and Animations by Drag
- Sounds by Violet Chaolan
- Skill icons by Leaf_It

**Note: Everyone in multiplayer must have the exact same version of this mod or you will be unable to join the lobby. This will change starting with version 1.1.0, where the first 2 digits will be the important ones outside of specific issues**

Feedback and bug reports are welcome, feel free to join my [discord server](https://discord.gg/jXGFN4k), I also do beta testing for new features and content there.

Fully compatible with multiplayer with no errors or desync as long as everyone has the mod installed. If you happen to find an issue, please let me know (preferably with the console logs from all players involved)


## Showcase

[![Showcase video](https://img.youtube.com/vi/UWSz8fImjqQ/0.jpg)](https://youtu.be/UWSz8fImjqQ)

## Overview
### Recent Changes:
```
    New:
- Blink knife (Alternate Special)
- Classic skin

    Adjustments:
- Mag now follows same reload delays and timing as Snipe. (This is roughly a 25% dps increase)
- All skin materials improved
- Added sound and vfx for backflip
- A lot of assorted qol and cleanup across the board.

    Bugfixes:
- Your eclipse level now persists between installs (it gets saved to the config file)
    This isn't a perfect solution, but it is better than nothing until we have a more robust way to add things to save file.
```

### Installation
- Unzip the Sniper folder to `[RoR2InstallFolder]/BepInEx/Plugins/Sniper`
- (Create the sniper folder if it isn't there)
- If you run into issues, try using [r2modman](https://thunderstore.io/package/ebkr/r2modman/) by ebkr
- To uninstall, simply delete the Sniper folder from `[RoR2InstallFolder]/BepInEx/Plugins/`

### General info
Sniper is a long ranged, single-target dps that incorperates some elements of an assassin to stay alive.

They excel at taking down bosses and high priority targets but struggle against larger groups of weak enemies.

### Skills
See the in game descriptions, maintaining two copies of all the information tends to just result in a mess of conflicting information.

## FAQ
### This model doesn't fit the game's art style.
Have you tried clicking on the classic skin? (It is the last one on the row)

### Why isn't classic the default?
...

### Where is the Spotter Drone?
Stay tuned. It is planned as an equipment item rather than a skill.

### Where are the item displays?
I add them a few at a time because they take quite a bit of trial and error, so not all items are displayed yet.

### The sounds are really loud
This particular issue should be resolved now, but if the volume is still not quite right for you there are two options in the config file to adjust. One is for just the fire sounds, the other is for all sounds from this mod.

### Sniper feels really overpowered
You mean fire/ice rings right? Unfortunately the rings are such powerful items for characters like sniper that the experience can feel extremely binary between runs where you have them and runs where you don't. This is also noticeable in vanilla with characters like Loader.

### Sniper feels really underpowered
Please keep in mind that my balance target is, and will always be, default loadout Commando at the start of early access. With that said, if you still feel the character is too weak relative to that standard please let me know.

### What does '1.0x' mean?
Any skill with that type of notation in its description means that a multiplier is being layered on top of another skill, usually your primary. So, for example, say an attack from your primary would deal 500% damage. If your ammo type has a 2.0x multiplier, that attack would be multiplied by 2.0, and deal 1000% damage. 

### How do I use this in multiplayer?
As with all custom characters, everyone must have the mod installed. If you still run into issues, verify that everyone has the exact same installed mods, including versions. 

### Can I use this on console?
Unfortunately no, there currently is no modding for console RoR2. This would require complete official mod support from Hopoo for both PC and consoles, which is no small task.

### How do I zoom in on controller?
Unfortunately, you can't do it just yet. I'm working on a fix for this. You can still use secondary, you just can't scroll to increase zoom and enter scope.

### Can you add integration for [ModNameHere]?
My priority is content for this mod. Once I am satisfied with that I will consider adding functionality for use with other mods.

### Do you have a Patreon or something?
Yes, [link](https://www.patreon.com/ReinRoR2Mods). Note that all my mods are 100% free, there are no incentives tied to Patreon. It is only there for people who really want to.


## Changelog
### 1.3.0
```
    New:
- Blink knife (Alternate Special)
- Classic skin

    Adjustments:
- Mag now follows same reload delays and timing as Snipe. (This is roughly a 25% dps increase)
- All skin materials improved
- Added sound and vfx for backflip
- A lot of assorted qol and cleanup across the board.


    Bugfixes:
- Your eclipse level now persists between installs (it gets saved to the config file)
    This isn't a perfect solution, but it is better than nothing until we have a more robust way to add things to save file.
```

### 1.2.4
```
    Bugfixes:
- OOPS
- See below...
```

### 1.2.3
```
    Bugfixes:
- Fixed networking for plasma ammo
```

### 1.2.2
```
    New:
- Plasma now has effects for the burn.
- Explosive ammo reworked
    - Explosion damage falloff: Linear -> None
    - Explosion damage: 0.4x -> 0.7x
    - Explosion damage per boost: 0.32x -> 0.56x
    - Bullet damage: 0.4x -> 0.2x
    - Bullet damage per boost: 0.32x -> 0.16x
    - Base radius: 7.5m -> 8m
    - Radius per boost: 7.5m -> 8m

    Adjustments:
- Mag damage per shot: 230% -> 250%
- Plasma duration: 5s -> 10s
    Number of ticks per second: Unchanged
    Number of total ticks: Doubled
    Damage per tick: halved
- Plasma ammo now uses the correct sound
- Tuned base stats
    - Base health: 100 -> 130
    - Level health: 30 -> 39
    - Base regen: 1.0 -> 2.0
    - Level regen: 0.2 -> 0.4
    Sniper overall struggles a bit more in the early game than other characters, and also has less inherent synergy with some healing items. This should help deal with that.
- Burst recoil adjusted
- Burst fire rate adjusted
- Steady Aim renamed to Charged Shot (Steady Aim will be reworked and added as a skill variant in the future)
- Charged Shot no longer slows you
- Charged Shot charges at the same speed while moving
- Charged Shot charge speed slightly reduced
- You can now sprint while reloading
 
    Bugfix:
- Fixed bug preventing the aiming portion of secondary skills from being used without stock.
- (FINALLY) fixed the physics with backflip that caused you to be launched to orbit. This isn't a perfect fix, so it may be possible to launch yourself under very odd conditions still, but it should be incredibly rare.
```

### 1.2.1
```
    Adjustments:
- Added option to disable zoom resetting when you enter scope
- Steady Aim and Quickscope now both allow you to enter scope while they are on cooldown.
- Steady aim now resets its charge on fire
```

### 1.2.0
```
    New:
Plasma Ammo
- Unlocked by default (This will change!)
- Deals all its damage through a Dot effect.
- Each tick of the dot has a 0.5 proc coef

Mag Snipe
- Unlocked by defauly (This will change!)
- Deals 230% - 345% damage.
- Can fire 4 times before reloading.
- Delay between shots is fairly low.
- 1.0 proc coef
```

### 1.1.0
```
    New:
Burst Ammo
- Currently is unlocked by default (this will change!)
- Fires 3 shots that deal reduced damage
- Boosting only increases the number of shots.
- Yes each shot has a 1.0 proc coef.

    Adjustments:
- Explosive ammo proc coef: 0.6 -> 1.0
- Explosive ammo explosion proc coef: 0.3 -> 0.5
- Scope charge indicator size reduced substantially
- Added additional config option for just the shot volume

    Bugfix:
- Fixed compatibility with BanditReloaded
- Fixed sounds not properly responding to SFX volume setting
- Texture quality settings are no longer applied to skill icons
- Fixed crosshair allocating memory occasionally when not needed.

    Misc:
- Major progress on other skills. 2 more of these will be coming very soon.
```
### 1.0.12
```
    Bugfix:
- Now works with RoR2 v1.0.1.1
```
### 1.0.11
```
    Adjustments:
- Added config for sound effects volume. 100 is default, 0 is totally muted.
```

### 1.0.10
```
    Adjustments:
- Returned some momentum inheritance to backflip
- Reload attack speed smoothing now runs at all times, not just while reloading
    With the longer smoothing time, and since attack speed starts at zero, it was very annoying getting the bar up to default speed at the start of a run
```

### 1.0.9
```
    New:
Reworked Boosting mechanic for ammo
- Steady aim and Quickscope now solely apply a boost effect
- The effect of boost varies with ammo type
- FMJ scales in:    
    Damage                  +1.0x per 1 boost
    Crit damage multiplier  +0.1x per 1 boost
- Explosive scales in:
    Damage                  +0.32x per 1 boost
    Radius                  +7.5m per 1 boost

- Steady aim modifier: 0.0 - 3.0 boost
- Quickscope modifier: 0.75 boost

Decoy now inherits items
- ONLY purely defensive items
- Base stats of decoy reduced to match sniper

    Adjustments:
- All skill descriptions improved and use the keyword system. Some could still use more work though.
- Explosive Ammo explosion radius: 6.0m -> 7.5m
- Steady aim now counts vertical speed as movement for charge rate
- Steady aim charge speed: 0.2 -> 0.4
- You now automatically reload during spawn animation
- Improved overall feel of primary and reload
- Attack speed reload smoothing bar factor: 0.5s -> 2.0s
- Second passive: Removed
- New icons border slimmed down
- Sprint animation speed adjusted
- Strafe animation speed adjusted
- Aim animation sync improved
- Cleaned up backflip movement
- Totally rewrote the backend code of primary to allow for more interesting ammo types in the future (soon tm)

    Bugfixes:
- Gorags Opus now works properly on sniper
- Now runs spp_disable_survivor Sniper on startup in order to prevent skills++ from breaking the character.
```

### 1.0.8
```
    New:
- Entirely new skill icons (courtesy of Leaf_It)

    Adjustments:
- Corrected a few skill descrpitions (Currently working on getting keywords set up to make things read more nicely)
    
    Bugfix:
- Updated to use standard r2api format for networkmodlist entry
```

### 1.0.7
```
    Bugfix:
- Deleted an in-progress ammo type that was conflicting with r2api
```

### 1.0.6
```
    Adjustments:
-Backflip distance increased
-Backflip is now more stable while firing
-Updated default crosshair
-Added configuration options for crosshair, there are quite a few to work with
-Added configuration option for scope zoom sensitivity
-3 new item displays

    Bugfixes:
-Fixed bug that prevented eclipse progress from saving
-Networking is now stable
```
### 1.0.5
```
    Adjustments:
-Backflip cooldown: 8s -> 5s
-Backflip backflip duration now decreases with movespeed.
-Backflip distance and height reduced.
    This makes backflip much more usable to do quick reloads and then fire.

    Bugfix:
-Now works properly on eclipse
-Decoy now has the same item display setup as Sniper
-Decoy cooldown no longer resets when decoy dies
```
### 1.0.4
```
-Now compatible with 1.0 update.
    Adjustments:
-Decoy reactivation delay: 2s -> 0.75s
-Decoy cloak duration: 2.5s -> 3s
-Decoy cloak now gives 40% movespeed
-Decoy cooldown is now not visible until reactivation (it already didn't start until then)

-Backflip now stuns and knocks back enemies
-Backflip now automatically grants a perfect reload on use

-Explosive ammo bullet radius: 0.1 -> 0.5
-Explosive ammo damage: 0.45x -> 0.4x
-Explosive ammo description now more clearly indicates that it will deal damage two times to the main target.
    Explosive ammo is generally a more forgiving option compared to FMJ. Overall it was a bit overtuned.

-Ricochet shots more reliably hit enemies

-Reloading before too early now incurrs a small delay before able to fire (equal to waiting for bar to reach the start of good region)
    This elimates potential abuse cases at higher attack speeds where mashing primary would yield more dps than perfect reloads.
-Bad reload multiplier: 0.8x -> 1.0x
-Good reload multiplier: 1.4x -> 1.2x
-Perfect reload multiplier: 2.0x -> 1.5x
-Snipe base damage: 450% -> 600%
    The resulting %s on reloads:
    Bad reload: 360% -> 600%
    Good reload: 630% -> 720%
    Perfect reload: 900% -> 900%
        Due to fixing that abuse case, the penalties for missing a perfect reload can be made much less severe (more in line with ror1 values)
        This also should help with making attack speed feel less risky to take.

-Added 14 item displays
-Adjusted crosshair UI
-Added icon for decoy reactivation
-Added quickscope icon
-Updated steady aim icon
```

### 1.0.3
```
    Bugfixes:
- Fixed reload UI not working on artifact hidden stage.
```

### 1.0.2
```
    Adjustments:
- The impact of attack speed on the reload bar is now smoother
    Essentially, when your attack speed changes, the bar move speed gradually shifts over half a second to that new speed.
    This should make items like berserkers, predatory, war horn, and tonic less jarring upon activation.
    While this does mean that you don't get the full benefits of conditional attack speed items immediately, you do get to keep them a bit longer because of the falloff time.

    Bugfixes:
- Fixed various UI issues for clients in multiplayer
```

### 1.0.1:
```    
    Adjustments:
-Quickscope cooldown: 4s -> 5s
    Quickscope was allowing too many successive shots without items.

-Steady aim max damage: 6.5x -> 6x
-Steady aim min damage: 1.5x -> 1.25x
-Steady aim delay: 0.35s -> 0.5s
    Steady aim was a bit too strong with backup mags

-Decoy cooldown: 18s -> 12s
-Decoy stealth duration: 2s -> 2.5s
    Decoy was not up enough to do its job of keeping you safe

-Precise aim now also gives +1% crit chance per character level
    Precise aim relied on items too much.

-Remade scope UI and added a new shader for it
-Greatly reduced size of reload bar
-Moved reload bar to upwards
-Reload bar now has some transparency
-Charge indicator outline thickness reduced
-Improved perfect reload sound
-Improved some ability descriptions
-Slimmed down crosshair

    Bugfixes:
-Steady aim properly restarts delay between shots 
-Fixed issues with ricochet sounds on fmj
-Fixed ricochet being limited to 2 bounces
-Fixed reload bar hiding on death
-Fixed reload bar being visible on other characters
-Corrected version number
-Fixed reload bar not being visible after revive
-Fixed issue with quickscope not starting aim animations
```

### 1.0.0:
```
-First release
```