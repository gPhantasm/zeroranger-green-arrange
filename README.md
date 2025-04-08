# ZeroRanger Arranged Soundtrack Mod - GREEN ARRANGE

## Description

This mod adds the arranged versions of most tracks to [ZeroRanger](https://store.steampowered.com/app/809020/ZeroRanger/). Not all tracks received arranges, so they are either replaced by another track (System Endless -> The Orange Cafe), retrofitted with a section of some other track (Final Box act 2 -> Final Box (later segment)) or left alone (Void, Apprivorange, etc.).

You can watch this [video showcase](https://youtu.be/PsD7ZGAG230) to get the gist of it.

This is available as a musicpack for [JuliaScythe](https://github.com/juliaScythe/)'s [ResourceManager](https://juliascythe.net/2024/10/04/resource-manager.html), which allows for easy switching between packs.

Alternatively, you can just copy the music files and overwrite the originals if you do not feel like modding the game. Be warned that many tracks will be excluded this way as the vanilla game cannot randomize track selection.

It should also be noted that many of the .ogg files present in this mod are heavily edited compared to their album counterparts to fit the context of this game. Please support Resonant Union and System Erasure by [buying the album yourself](https://resonantunion.bandcamp.com/album/zeroranger-arranged-album-green-arrange), if you enjoy this mod.

## Installation

Since this is just a repo of the edited music files and the patch, making releases would be clunkier. Thus, **please download the mod by clicking the green "Code" button up top and "Download ZIP".** This will give you a ZIP file of everything. 

### ResourceManager (RECOMMENDED)

Ensure you have the [ResourceManager mod](https://juliascythe.net/2024/10/04/resource-manager.html) installed correctly, then place the entire contents of the repository in your ZeroRanger folder (you can find this easily by right-clicking on ZeroRanger and selecting "Browse local files"). If you've done this correctly, the musicpack will be written into the `musicpacks` folder. Select 'GREEN ARRANGE' from the in-game musicpack setting. Palettes will be added to the "Visuals" menu alongside the existing palettes. Feel free to delete the `mod.toml` file as it is for NirvanaMM.

### NirvanaMM

If you are using [NirvanaMM](https://github.com/Jamesthe1/nirvanamm), this pack is supported with ResourceManager as a dependency. Download the newest [release](https://github.com/gPhantasm/zeroranger-green-arrange/releases) and place the `.zip` file in your `mods` folder, so that it has its own folder in there. Ensure you also have a compatible version of ResourceManager installed in a similar fashion. If done correctly, the musicpack will appear in the in-game sound settings, and palettes will be appended to the list in the visual settings.

### Itch to Steam

Since it is kind of cumbersome to ship and update an Itch and Steam version of the patches, there is instead a separate `.xdelta` patch included that will convert an Itch version of `data.win` into the Steam version, which you can then use ResourceManager or the DeltaPatch with.

## How does it pick the tracks?

Tracks with multiple versions are chosen randomly every time a run is started (must go back to the title screen to reroll). This includes but is not limited to

- It May Be Greenish
- For Your Security
- UNSTOPPING
- The Sea Has Returned
- Sky XXXX Days

and a few others. The functionality of this can be adjusted by editing the `pack.json` file. Any track that randomizes has `choices` and `choices_sync` variables to select the tracks.

## Other changes

- The male voice's "MAXIMUM" soundbite has been replaced with eebrozgi yelling "ZERORANGER!".
    - If you want to disable this, simply set `"custom_zeroranger_male_shout"` at the top of `pack.json` to `false`.
- Some extra palettes have been included if you've beaten the TLB.
- While I've tested most of the game out, I don't know if some edge cases will crash or behave weirdly. Please let me know on Discord (`gooeyphantasm`) or make an issue here and I'll maybe fix it if I know how.
