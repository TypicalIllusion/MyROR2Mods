## BanditReloaded
- The most comprehensive Bandit mod yet!
- 4 alt skills!
- Highly configurable!
- Supports the Ancient Scepter from ClassicItems!

[![](https://i.imgur.com/Ba8ikNP.jpg)]()

[![](https://i.imgur.com/rhjew49.png)]()
[![](https://i.imgur.com/R5zcn4K.png)]()

## IMPORTANT: READ THIS
- The host must have the mod installed for it to work.
- Config options marked with * are server-side.
- The config doesn't auto-update when installing new versions of the mod, so delete your config or manually change the values if you want to receive the newest balance changes.

## Vanilla Compatibility DLL
- I generally recommend against using this.
- To use this, delete BanditReloaded.dll and remove the .disabled extension from BanditReloaded_vanilla.dll.disabled
- The host MUST have the dll installed, otherwise a lot of stuff won't work.
- This will allow unmodded players to see Bandit (but he will not have any attack anims for people without the mod).
- Using this breaks compatibility with the standard dll.

## For Skinmakers
- If you plan to make skins with SkinAPI, the bodyname is BanditReloadedBody. Use BanditBody instead if you plan to use BanditReloaded_vanilla.dll

## Installation
Drop BanditReloaded.dll into \BepInEx\plugins\
Settings can be changed in BepInEx\config\com.Moffein.BanditReloaded_v2.cfg

## Credits
mistername - Ice explosion fix
Kooby521 - Skill icons
Tera - Skill icon concepts
N0TORIOUS_BLT - Bandit figurine used in the mod icon
Rob - SkinAPI support

Ping me in the RoR2 Modding Discord (@Moffein#8244) or DM me if you have any feedback or bug reports!

##Changelog
Full Change History: https://hastebin.com/raw/wugesayeti
`2.2.1`
- Blast damage increased from 230% to 250%. Hoping this will help make Blast feel a bit more rewarding to use when compared to Scatter.
- Dryfiring Bandit's primaries now pauses the reload timer instead of resetting it. The original idea was for dryfiring to mimic firing individual shotgun shots on an empty mag like in TF2, but in practice it felt frustrating to mess up Bandit's skill cycle by accidentally firing a shot too early. This should make Bandit's primaries more lenient to use.
- Thermite Bomb damage increased from 240% to 270% to be higher than Blast.
- Acid Bomb damage increased from 240% to 270% to be higher than Blast.
- Lights Out damage increased from 420% to 450%. Lights Out is incredibly powerful with elemental bands, but feels a bit weak without it. This should help Bandit out a bit when he doesn't have any Bands.
- Rack Em Up damage increased from 70% to 75% to match Lights Out.
- Added option for modifying Blast recoil.
- Added option for modifying Scatter recoil.
`2.2.2`
- Fixed Scatter recoil config option not working.