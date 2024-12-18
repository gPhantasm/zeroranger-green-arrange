# ZeroRanger Arranged Soundtrack Mod - GREEN ARRANGE

## Description

This mod adds the arranged versions of most tracks to [ZeroRanger](https://store.steampowered.com/app/809020/ZeroRanger/). Not all tracks received arranges, so they are either replaced by another track (System Endless -> The Orange Cafe), retrofitted with a section of some other track (Final Box act 2 -> Final Box (later segment)) or left alone (Void, Apprivorange, etc.).

You can watch this [video showcase](https://youtu.be/PsD7ZGAG230) to get the gist of it.

This is available as either a standard deltapatch based mod, or a musicpack for the [ResourceManager mod](https://juliascythe.net/2024/10/04/resource-manager.html) which allows for easy switching between packs.

I would recommend using ResourceManager. It allows for easy customization of the mod via its `.json` file, and now supports palettes as well. The only advantage of the included deltapatch is the included flavour text.

It should also be noted that many of the .ogg files present in this mod are heavily edited compared to their album counterparts to fit the context of this game. Please support Resonant Union and System Erasure by [buying the album yourself](https://resonantunion.bandcamp.com/album/zeroranger-arranged-album-green-arrange), if you enjoy this mod. A hell of a lot more work went into these tracks actually being made than what little work I did to fit them into the game.

## Installation

Since this is just a repo of the edited music files and the patch, making releases would be clunkier. Thus, **please download the mod by clicking the green "Code" button up top and "Download ZIP".** This will give you a ZIP file of everything. 

### ResourceManager (RECOMMENDED)

Ensure you have the [ResourceManager mod](https://juliascythe.net/2024/10/04/resource-manager.html) installed correctly, then place the entire contents of the repository in `<ZERORANGER FOLDER>/musicpacks/green-arrange`. Select 'GREEN ARRANGE' from the in-game Music Pack setting. Palettes will be added to the "Visuals" menu alongside the existing palettes.

### DeltaPatch

Use [DeltaPatcher](https://github.com/marco-calautti/DeltaPatcher) to apply the included `.xdelta` to the `data.win` of a **2022 Steam version** of [ZeroRanger](https://store.steampowered.com/app/809020/ZeroRanger/). Then copy all the `.ogg` files from the archive to your ZeroRanger folder. Allow overwriting, and do not touch the new files. Then just launch. Feel free to delete `zrpal` files as they are for ResourceManager.

### Itch to Steam

Since it is kind of cumbersome to ship and update an Itch and Steam version of the patches, there is instead a separate `.xdelta` patch included that will convert an Itch version of `data.win` into the Steam version, which you can then use ResourceManager or the DeltaPatch with.

## How does it pick the tracks?

Tracks with multiple versions are chosen randomly every time a run is started (must go back to the title screen to reroll). This includes but is not limited to

- It May Be Greenish
- For Your Security
- UNSTOPPING
- The Sea Has Returned
- Sky XXXX Days

and a few others. Special thanks to Kirvoid for showing me how to add new tracks to the game and how to let them be chosen randomly.

## Other changes

- The male voice's "MAXIMUM" soundbite has been replaced with eebrozgi yelling "ZERORANGER!".
    - *[ResourceManager exclusive]* If you want to disable this, simply set `"custom_zeroranger_male_shout"` at the top of `pack.json` to `false`.
- *[DeltaPatch exclusive]* Some flavour text has been modified to match some tracks.
- Some extra palettes have been included if you've beaten the TLB.
    - If you use these palettes in the DeltaPatch, it will reset to COOL DAY every time you close the game. This is because the save file has clamping on the palettes that can be set. I don't want to touch how save files work! Palettes function properly in ResourceManager.
- While I've tested most of the game out, I don't know if some edge cases will crash or behave weirdly. Please let me know on Discord (`gooeyphantasm`) or make an issue here and I'll maybe fix it if I know how.
