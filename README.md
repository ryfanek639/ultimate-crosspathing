<a href="https://github.com/doombubbles/ultimate-crosspathing/raw/main/UltimateCrosspathing.dll"><img align="right" alt="Download" height="75" src="https://github.com/doombubbles/BTD6-Mods/blob/main/download.png?raw=true"></a>

# Ultimate Crosspathing

As always, requires [BTD Mod Helper](https://github.com/gurrenm3/BTD-Mod-Helper/releases/latest).

![Screenshot](https://github.com/doombubbles/ultimate-crosspathing/blob/main/screenshot.png?raw=true)

This is a prototype I've been working on for algorithmically generating more crosspathing combinations. 

With this mod, instead of your Towers being restricted to 5 Upgrades in one path and 2 in another, you can take your upgrades in any path.

The default mode is keep the restriction of just 7 total upgrades so you can do 430s, 331s, 322s, 511s, etc, but if you're really adventurous, there's a setting at the bottom of the options list you can enable to allow for all 15 Upgrades.
You can also individually toggle which Towers get Ultimate Crosspathing, and changing any settings no longer requires a restart.

I'm releasing this now because the majority of the combinations work okay, so there's a lot of fun to be had trying them all out. I do intend to eventually make this much more polished and balanced.

## Community Crosspathing Patches

Since the algorithm is only ever going to get so smart, there's going to need to be manual fixes to certain Crosspathing combinations one way or another.
So, I thought it would be nice if people didn't have to necessarily wait on me for those to happen.

I've implemented an easy system for members of the Community to create "Crosspathing Patch" mods that can be used alongside Ultimate Crosspathing to alter the behavior of generated towers.
Patches can be "published" as Github Issues on this repository using the appropriate tag.

[View All Published Patches](https://github.com/doombubbles/ultimate-crosspathing/labels/crosspathing%20patch)

The very first one is an example / template patch by me that has more information for those interested.

**Changelog**

v1.2.0 Fixed for Bloons TD 6 v28.0. Now supports Alchemist crosspathing

v1.1.0 Crosspath Data is now bundled into the .dll. It's now a bigger download, but instead of taking minutes to load on startup it's ~15s. Also some misc algorithm improvements

v1.0.0 Execute order 66

v0.1.2 Fix Monkey Knowledge inconsistencies, allow Community Crosspathing Patches

v0.1.1 Fixed Buccaneer and Dartling crashes

v0.1.0 Prototype
