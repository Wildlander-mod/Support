# Backing up UltSky: 
1)  Backup the main UltSky folder - the one with ModOrganizer.exe from which you start up the mod pack.
2)  [Optional]  Back up the Downloads folder which contains all the mod archives downloaded from Nexus.  _While this is not required to play UltSky, it will prove useful to have handy in case you need to re-install the mod pack from scratch using Wabbajack.  Point the installer to this folder as the "Download location", and it should detect the available mods, in which case it will only download the ones that need to be updated.  This will reduce the installation time considerably._
3)  [Recommended]  Backup the ENB binaries and configuration files from the Skyrim game folder (the folder with TESV.exe)
     *  **d3d9.dll** 
     *  **enbhost.exe** 
     *  **enblocal.ini**
     *  **enbseries.ini**
     *  **enbseries folder**
     
Note: I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143/?tab=description) or a similar tool to do this.  This is an app that can backup or restore your complete ENB setup with just a few mouse clicks, and can store multiple ENB configuration profiles.

# Restoring UltSky from a backup:
1)  Start with a fresh installation of Skyrim Legendary Edition from Steam, or from a Steam backup.
2)  Refer to the [Wabbajack install guide](https://docs.google.com/document/d/1JxbNnYpLp2seYQxfFfyUKWkXoVDpjGgUdk_HjA8-kDE/edit), and make sure that you have all additional requirements installed, such as the latest **64-bit Java** and **.NET framework**.
3)  Copy the main UltSky folder (the one with ModOrganizer.exe) from your backup to a location of  your choice, preferably on your OS drive.   Use a short path, close to the root directory, e.g. **C:\US** .
4)  Start ModOrganizer.exe from the Ult Sky folder, go into **Settings > Paths**, and update the paths for **Base Directory** and **Downloads**.  Base Directory is the path to ModOrganizer.exe itself, and Downloads should point to the folder with all the mod archives from Nexus.
5)  Complete the Post-installation steps from the Wabbajack guide.

If you wish to restore your ENB configuration from a backup, copy those files to the game folder.
