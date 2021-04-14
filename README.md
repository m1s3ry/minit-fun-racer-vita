# minit-fun-racer.vita
A patch to make Minit Fun Racer playable on the PS Vita

###

## Disclaimer
This patch does not contain any game files from Minit Fun Racer. **You need the game files from your legally owned copy**.
If you don't have a copy of the game, you can buy it [HERE](https://store.steampowered.com/app/1503530/Minit_Fun_Racer/)

## Instructions 
1. Download the VPK and install it on your hacked PS Vita
2. Download the patch and extract it anywhere. Open your newly created patch folder
3. If you have the Steam version of Minit Fun Racer, right click on it -> Manage -> Browse local files. Otherwise, find the folder in which Minit Fun Racer is installed
4. Copy `data.win` to your patch folder, and execute `apply_patch.bat`
5. Launch VitaShell on your Vita and connect to PC via FTP or USB. (***NOTE:*** *If you connect through USB, you will need to enable Windows to show hidden files and folders*)
6. Copy the resulting `game.win` to `ux0:app/MINITRACE/games`
7. Copy all of the other game files (except options.ini and data.win) to `ux0:app/MINITRACE/games`
8. Launch the game on your Vita and enjoy
9. Optional but highly recommended: Install PSVShell and overclock ES4 to 166 or 222 mhz. You can also overclock CPU to 444mhz to mitigate micro stutters

**IMPORTANT:** This patch is not confirmed to work with any other version that it's not the current latest build of Steam (6471361). It _should_ support other versions but it's very likely it won't properly.

## Known Bugs
* Fullscreen, contrast and brightness sliders don't do anything
* Palette swap shader has been disabled
* There are micro stutters

## Credits
Credits for the original game go to Kitty Calis, Jan Willem Nijman, Jukio Kallio & Dominik Johann.
Additional credit for the port goes to @Grossleymoo for UTMT and helping/teaching me to port Vita games.

## Donations
If you want to support my work, you can [buy me a coffee here!](https://www.buymeacoffee.com/m1s3ry)

Also you can [follow me on twitter](https://www.twitter.com/m1s3ry_)
