# Where do I put these files?
**Please make sure to rename the files before putting them in your game folder and only have one of the files in the game folder at any time in order to prevent things breaking.**

The UserAssembly files are enormous and therefore they are compressed into 7z files so git stops complaining (too lazy to set up large file storage, sorry. and no, I don't know what releases are). **To extract these files, you must use [7-Zip](https://7-zip.org/).**

## 2.8 and 3.0
* `global-metadata.dat` files go in `GenshinImpact_Data\Managed\Metadata\global-metadata.dat`

## 3.1 and 3.2
* `UserAssembly.dll` files go in `GenshinImpact_Data\Native\UserAssembly.dll`

## 3.3
* `RSAPatch.dll` files go in the base directory. Make sure to rename it to `version.dll` or `mhypbase.dll`
* **This is not needed if you only plan to use the patch with Grasscutter.** If you want to change the public key used, put a file called `PublicKey.txt` in the same folder containing your public key.
* For any reason, if you need to replace the private key, create a file named PrivateKey.txt under the same folder and put your private key in there.
* A console window should open up if it works.
* The patch also comes with the source code if you want to compile it yourself.