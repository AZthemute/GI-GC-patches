# Where do I put these files?
**Please make sure to rename the files before putting them in your game folder and only have one of the files in the game folder at any time in order to prevent things breaking.**

The UserAssembly files are enormous and therefore they are compressed into 7z files so git stops complaining (too lazy to set up large file storage, sorry. and no, I don't know what releases are). **To extract these files, you must use [7-Zip](https://7-zip.org/).**

## 3.3 to 3.6
* `RSAPatch.dll` files go in the base directory, the one with your `GenshinImpact.exe` file. Make sure to rename it to `version.dll` or `mhypbase.dll` (Replace the `mhypbase.dll` file if needed. A backup is provided in this repository. Replacing or removing it also results in memory protection being disabled, so you can use mess around with the game, for example using Cheat Engine).
* A console window should open up if it works.
* **This is not needed if you only plan to use the patch with Grasscutter.** If you want to change the public key used, put a file called `PublicKey.txt` in the same folder containing your public key.
* For any reason, if you need to replace the private key, create a file named `PrivateKey.txt` under the same folder and put your private key in there.
* This repository also includes the source code if you want to compile it yourself.

## 2.7 or earlier
* No patches needed!

## 2.8 and 3.0
* `global-metadata.dat` files go in `GenshinImpact_Data\Managed\Metadata\global-metadata.dat`. Feel free to overwite the file when asked.

## 3.1 and 3.2
* `UserAssembly.dll` files go in `GenshinImpact_Data\Native\UserAssembly.dll`. Feel free to overwite the file when asked.