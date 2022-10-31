## A warning before proceeding

Adding mods is generally considered a bad idea unless you know what you are doing. Any form of customisation "support" will be in the Dedicated Customisation channels. Should you ask in general or either of the support channels, your posts will be deleted and you will be directed to ask in the appropriate locations.

Helping you will basically be a waste of volunteer time that should go to those who have NOT customized the modlist. 

Should you customise your list - You will be ON YOUR OWN unless another member of the community takes pity on you.

If you accept this, then Grab yourself a custom build role on discord and continue!


## Modding Basics

NEVER EVER uninstall mods unless you are starting a new playthrough.

Be careful updating mods. Check for update instructions. Some updates require you to start a new playthrough.

When you load your savefile, wait at least thirty seconds before saving again. Some scripts will break if you save too soon after loading.
    
At least try to avoid saving during combat or other conditions of heavy script load.

Vortex / Wyrebash / Loot have their place, that place is 2 billion miles away from wildlander and should not be used.
    
Make sure when downloading mods - they work with skyrim 1.5.97. Downloading SKSE for aniversary editions WILL NOT WORK.

You Cannot Disable Essential mods required by wildlander.ESP.

## Known Mod Issues/Incompatibilities

The following Types of mods are NOT Compatible. (cause game breaking bugs)
> * Any Alternate start mod. (Skyrim unbound reborn is included in the list, which acts as a alternate start mod. It cannot be removed and replaced with something else)
> * Any Mod which affects the perk trees E.g. Ordinator 
> * Truly Absorb Dragon Souls, DSAMG - Dragon Soul Absorb More Glorious and Dragon Remains (prevents the main quest from firing upon killing a dragon)
> * Cold & Wet SE - causes Various CTD
> * Populated Cities Towns Village SE - Can cause the game to bug out into an endless loading scene when entering cities. COC'ing into one of the cities shops and leaving into the city from there circumvents and fixes it for some time
> * New Races (unless requiem patch available) Requiem won’t start and will return you to the main menu.
> * Skyrim Together (Just doesnt work)  
> * Enhanced character edit - Not compatible with racemenu, which cannot be disabled.
> * Any SKSE mods for Skyrim version 1.6 onwards.

The following Mods are extremely script heavy, Will possibly break your game.
> *  Open Cities (also requires a tonne of manual patching)
> *  Sexlab Separate Orgasms (known to cause fps degradation/script bloat)

The following types of mods have Issues 
> *  New creatures/enemies/NPC's/followers   (unless requiem patch available) - Note: for enemies - they are generally added as unleveled, and in requiem this means they are always level 1. for NPC's and Followers - they will be missing the requiem perks and may also be unleveled (ergo level 1)
> *  Dead NPC Body Cleaner Remover (caused Immortal Vampires when you attempt to burn them, also causes civil war patrols to scream like banshee's)  
> *  New Quest area mods   (unless requiem patch available) - Note: This is because new area's generally add new creatures/enemies/NPC's and followers
> *  3Tweaks/BTweaks (Wont be compatible OUT OF THE BOX - It changes so much stuff, that it won't be compatible with anything without 3tweaks dedicated patch - which just doesn't exist for the bulk of the mods in the list - Including Wildlander.esp itself).     

---

### Installing Mods not covered by guides.

All most should be added to Mod organiser, not to your Skyrim directory. 

- Download it to your Wildlander download folder (this will be the directory you entered on the wabbajack installer when you first installed the list)
open < Wildlander install directory >\Game-files\mod organiser.exe. Once open - top left dropdown - select the profile you plan on playing.
- select download tab on right side
- find the mod in the list and right click > install (you may need to click the refresh button to make it appear)
- choose your settings (if it has installation options) then once its finished installing turn it on, on the left side of the mod organizer (should be at bottom of the list).
- **Important** if patching from "Requiem patch central" Untick any ticked patches for mods in the base wildlander install, and only tick ones for mods you are adding yourself.
- If you mod doesn’t have any ESP/ESM/ESL's then that’s it - otherwise continue!

Sort your (right side) Plugins load order manually (LOOT IS THE DEVIL - ERASE its Existence from your memory).

If there isn't a specific guide, then as a general rule of thumb

- Anything that adds spells, weapons, followers or other types of NPCs should go ABOVE Requiem.esp (right pane of MO2)
- Patches always have to be below the mod they are patching, thus the requiem patches will be below Requiem.esp by the other requiem patches while your mod will be above Requiem.esp.
- Any mods which don't Add new NPCS, followers, Spells and weapons, should be installed below the wildlander Full mod(E.g. Autosave manager, bathtubs Basins and beyond, tentpalooza)
- Run the reqtificator whenever you change the load order.

Close mod organizer - and use the launcher to start the game.

---

## General guidance

If you start modding make a copy of Wildlander profile and name it something like "$Original Wildlander Profile name+ Modified".
You will always be able to switch back to the original profile and load it that way in case you screw up badly. or run loot or otherwise fubar your load order.

Quick Links to a variety of Helpful Topics:

### The Distinction between List/Loose Files Load Order and Plugins Load Order: 

![image](https://user-images.githubusercontent.com/26418143/173229360-cc431243-c5fb-4f1b-babd-74efc9cb80db.png)

### Building New Animations with Nemesis/FNIS alternative: 

https://youtu.be/gc8Ai7jYDXc?t=1077

The video covers most of it and I already linked to the timestamp that is really important, but there are a few edge cases still left.

Q: I have followed the tutorial but my animations don't show up/Nemesis just throws up something like: Initializing Engine update, engine update complete 15 seconds. But none of my extra animation mods are referenced.

A: Click Launch Nemesis Engine and not Update.

Q: I clicked Launch Nemesis engine and now I am getting an access error or some other sort of crash.

A: You have to add Nemesis Engine to the windows defender exception list, or whatever Anti Virus you are running. For Windows defender, go to its system  and add "Nemesis Unlimited Behavior Engine.exe" Process to the exclusion list. It should look something like this. 

![image](https://user-images.githubusercontent.com/26418143/173229406-08b78e3a-6ec5-4eaf-9647-5d618559c6e0.png)


### A quick guide to NetScriptFramework Error Codes

https://www.nexusmods.com/skyrimspecialedition/articles/3031/

More crash help here

https://github.com/Fikthenig/Crash-Bonanza

and finally - if all else fails

https://www.nexusmods.com/skyrimspecialedition/mods/49130?tab=posts

### Resaver - Save cleaner and script remover.

This tool is useful for removing Bugged/crashed scripts from your save and correct scriptlag. 

I strongly recommend reading the modpage And/or watching tutorial videos before using.

ReSaver from FallrimTools: https://www.nexusmods.com/skyrimspecialedition/mods/5031?tab=files
-----
# Tool Setup

## Creation Kit

1) Download and install into steam Folder : https://store.steampowered.com/app/1946180/Skyrim_Special_Edition_Creation_Kit/
2) Download and install into steam Folde  https://www.nexusmods.com/skyrimspecialedition/mods/67096/

* Copy Papyrus Compiler folder from Steam skryim into Game-files\Stock game
* Copy Creation kit.exe from Steam skryim into Game-files\Stock game  
* Unzip <steam fold>\data\Scripts.zip into Game-files\Stock game\Data
	
Download https://www.nexusmods.com/skyrimspecialedition/mods/20061 and unzip contents into Game-files\Stock game

## Papyrus Compiler SE
	
1) Download and install creation kit as per above instructions
2) Open program from mod organiser
![image](https://user-images.githubusercontent.com/26418143/180988545-9a2f1b18-553e-455c-ba28-73c67f225e5a.png)
3) from above screen click cog icon
4) Set  Skyrim SE folder to Game-files\Stock game 
5) Set  papyrus compiler to Game-files\Stock game\Papyrus Compiler


-----

# Guides

## Inn's can be closed

**Original Mod name. and link**

Inns Can be Closed - https://www.nexusmods.com/skyrimspecialedition/mods/57407?tab=description

**What does your patch do?**

This is only a patch to keep the possibility of inns having no free beds, while also keeping the changes from Relationship Dialogue Overhaul and Wildlander for the different NPC answers.

**Patch URL**

https://www.nexusmods.com/skyrimspecialedition/mods/62112?tab=description


**Load order**

On the RIGHT side:

	Wildlander.esp
	-
	-
	Inns Can Be Closed
	Inns Can Be Closed Wildlander Patch.esp
	-
	-
	Requiem for the indifferent.esp

On the LEFT side:

	Doesn't matter
  
---
### Requiem - Static Skill Leveling (Experience Mod Add-on)

**Original Mod name. and link**

Requiem - Static Skill Leveling - https://www.nexusmods.com/skyrimspecialedition/mods/43185

**Guide URL**

https://docs.google.com/document/d/1ybW3_zI60rtaCIDrKZIz_vNDzu-cXECO5sx6oMisS7U/edit

**Additional Notes*

Added a final note to the guide to state that the patcher needs to be run every time new mods are added that change perks, quests, or books. Synthesis.esp should remain last in the load order. (Unless the Synthesis changes are manually forwarded into another patch)
  
---

