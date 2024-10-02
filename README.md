# ZeroRanger Arranged Soundtrack Mod - GREEN ARRANGE

### Description

This mod adds the arranged versions of most tracks to [ZeroRanger](https://store.steampowered.com/app/809020/ZeroRanger/). Not all tracks received arranges, so they are either replaced by another track (System Endless -> The Orange Cafe), retrofitted with a section of some other track (Final Box act 2 -> Final Box (later segment)) or left alone (Void, Apprivorange, etc.).

It should also be noted that many of the .ogg files present in this mod are heavily edited compared to their album counterparts to fit the context of this game. Please support Resonant Union and System Erasure by [buying the album yourself](https://resonantunion.bandcamp.com/album/zeroranger-arranged-album-green-arrange), if you enjoy this mod. A hell of a lot more work went into these tracks actually being made than what little work I did to fit them into the game.

### Installation

Use [DeltaPatcher](https://github.com/marco-calautti/DeltaPatcher) to apply the .xdelta to the `data.win` of a **2022 Steam version** of [ZeroRanger](https://store.steampowered.com/app/809020/ZeroRanger/). Then copy all the `.ogg` files from the archive to your ZeroRanger folder. Allow overwriting, and do not touch the new files. Then just launch.

### How does it pick the tracks?

Tracks with multiple versions are chosen randomly every time a run is started (must go back to the title screen to reroll). This includes but is not limited to

- It May Be Greenish
- For Your Security
- UNSTOPPING
- The Sea Has Returned
- Final Box (in White Vanilla)

and a few others. Special thanks to Kirvoid for showing me how to add new tracks to the game and how to let them be chosen randomly.

### Excluded tracks

~~Some tracks~~ ONE TRACK was omitted because I was simply too lazy to figure out how to fit it in. The Earth Has Returned is very transformed from the original track, and it didn't really fit the vibe of 2-3 anyway. I could have just included it unchanged, but if you got it randomly and felt it didn't fit that would've been sad... If you want to fit it and add it yourself, just overwrite one of the `bgm_level_three_ex` files with your creation.

Also... There is no Orangardimus. I initially had it play a segment of That Future of Ours, but it's kind of annoying when it cuts off the Greenish remixes (imo). So Greenish will just play through that miniboss always. There is currently an issue where the music will not kick in again upon using a continue at this segment. It's probably easy to fix, but it's currently broken.

### Other changes

- The male voice's "MAXIMUM" soundbite has been replaced with eebrozgi yelling "ZERORANGER!".
- Some extra palettes have been included if you've beaten the TLB.
    - If you use these palettes, it will reset to COOL DAY every time you close the game. This is because the save file has clamping on the palettes that can be set. I don't want to touch how save files work!
- While I've tested most of the game out, I don't know if some edge cases will crash or behave weirdly. Please let me know on Discord (`gooeyphantasm`) or make an issue here and I'll maybe fix it if I know how.
