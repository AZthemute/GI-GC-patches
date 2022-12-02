# GI-GC-patches
Archived versions of *Anime Game* patches required to play on [Grasscutter servers](https://github.com/Grasscutters/Grasscutter). These include global-metadata files (2.8 and 3.0) and UserAssembly files (3.1 and 3.2). Lots of these were taken from the [Grasscutters Discord server](https://discord.gg/grasscutter), this repository is just here to easily archive and compile them if you want to play an old version of the game, or even the live version of the game.

## Where do I put these files?
**Please make sure to rename the files before putting them in your game folder and only have one of the files in the game folder at any time in order to prevent things breaking.**
* `global-metadata.dat` files go in `GenshinImpact_Data\Managed\Metadata\global-metadata.dat`
* `UserAssembly.dll` files go in `GenshinImpact_Data\Native\UserAssembly.dll`

## Sources
These are my exact sources for the files in this repository. The unpatched files for every version aside from Global 3.0 were taken from my own copy of the game, and are therefore the same ones official server uses. Although to be fair it's kind of pointless on old versions of the game but whatever, it doesn't hurt to have anyway.

* Global 2.8: [Patched](https://discord.com/channels/965284035985305680/969297345240006736/996728837838741514)
* Global 3.0: [Patched and unpatched](https://discord.com/channels/965284035985305680/969297345240006736/1014278094204436561)
* Global 3.1: [Patched](https://discord.com/channels/965284035985305680/969297345240006736/1024342034716295269)
* Global 3.2: [Patched](https://discord.com/channels/965284035985305680/969297345240006736/1037131564833837091)

The UserAssembly files are enormous and therefore they are compressed into 7z files so git stops complaining (too lazy to set up large file storage, sorry. and no, I don't know what releases are).

**To extract these files, you must use [7-Zip](https://7-zip.org/).**

## To-do
* Add MD5 hashes for each file.
* Get CN files.
* Hopefully someone can help verify the legitimacy of these files as I have not tested the 2.8-3.1 ones myself.
* Maybe include betas? Not sure if betas use a different patch to their live counterparts, but if they do it would be nice to have here.

Please make a pull request if you have any contributions to make!