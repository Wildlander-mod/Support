# NONE OF THESE PATCHES WILL WORK FOR WILDLANDER. Dont waste your time !!!


# Modding Guides

If you have issues with any of the guides below - you can submit feedback here https://forms.gle/jG4DadrizsRz3bwT9

## Important Terms

1) mod organizer      - The tool which makes everything work - Installed as part of the wabbajack installation in <Ultsky install directory>\Content\Mod Organizer.exe
2) reqtificator       - The requiem patcher - Makes 3rd party mods compatible with the Ultsky install. If you are going to do any modding at all this must be setup first. Instructions for how to do this are [here](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/FAQ.md#reqtificator-questions)
3) reqtificator.ini   - The configuration parameters for the requiem patcher - needed if you are going to make any appearance changes or add any new races. Located in 
<Ultsky install directory>\Content\mods\Ultsky Core Files\SkyProc Patchers\Requiem
4) [Dyndolod](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/Patchers.md#dyndolod)           - The tool which draws items in the distance, generally needed to be ran if adding mods which change the landscape or add new player homes
5) [Automatic Varients](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/Patchers.md#automatic-variants) - The tool which makes creatures in the game have different appearances rather than all having the same appearance.
6) Merging mods       - Advanced modding technique to combine multiple mods Plugin's into one.


## Guides list
<!-- TOC -->
- [Ultimate Skyrim Basics - READ ME!!!!](#ultimate-skyrim-modding-basics)
- [Known Mod Issues or Incompatibilities](#known-mod-issuesincompatibilities)
- [How do I Re-run Automatic variants, FNiS or Dyndolod?](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/Patchers.md)
- [Graphics Overhaul Guide](#ultimate-skyrim-Basics)
- [NPC Overhaul Guide](#npc-overhaul-guide)
- [BMX Gameplay Overhaul Guide](#bmx-gameplay-overhaul-guide)
- [Anna Gameplay Overhaul Guide](#Anna-gameplay-overhaul-guide)   
- [Autosave Manager](#autosave-manager)
- [EnaiSiaion mods](#EnaiSiaion-mods)
- [SNBCJ's mods](#SNBCJs-mods)
- [Rain Ash and Snow Shaders](#Rain-Ash-and-Snow-Shaders)
- [Discord Community Patches](#Discord-Community-Patches)
- [None ESP mods](#None-ESP-mods)
- [Other mods & Tweaks](#other-mods)
- [What About legacy of the Dragonborn](#What-About-legacy-of-the-Dragonborn)

<!-- /TOC -->


---

## Ultimate Skyrim Modding Basics

Installing Mods not covered by guides. 

- Download it to your UltSky download folder (this will be the directory you entered on the wabbajack installer when you first installed the list)
- open < Ultimate Skyrim install directory >\content\mod organiser.exe. Once open - top left dropdown - select the profile you plan on playing.
- select download tab on right side 
- find the mod in the list and right click > install (you may need to click the refresh button to make it appear)
- choose your settings (if it has installation options) then once its finished installing turn it on, on the left side of the mod organizer (should be at bottom of the list). 
- **Important** if patching from "Requiem patch central" Untick any ticked patches for mods in the base Ultsky install, and only tick ones for mods you are adding yourself.

If you mod doesn’t have any ESP/ESM's then that’s it - otherwise continue!

Sort your (right side) Plugins load order **manually** (LOOT IS THE DEVIL - ERASE its Existence from your memory).

Firstly, There are specific guides in this document for a lot of the more popular mods, along with proper Ultsky patches & install instructions, so check those first!

If there isn't a specific guide, then as a general rule of thumb 
* Anything that adds spells, weapons, followers or other types of NPCs should go ABOVE Requiem.esp (right pane of MO2)
* Patches always have to be below the mod they are patching, thus the requiem patches will be below Requiem.esp by the other requiem patches while your mod will be above Requiem.esp.
* Any mods which are NPC overhauls should follow the same installation process as Bijin (in the [NPC Overhaul Guide](#npc-overhaul-guide))
* Any mods which don't Add new NPCS, followers, Spells and weapons, should be installed below the Ultimate Skyrim patches, but above Warburg's Paper world map. (E.g. Autosave manager, bathtubs Basins and beyond, tentpalooza)

![Modding Rules](https://cdn.discordapp.com/attachments/790534021380964382/834791598964604948/unknown.png)

Setup and run the reqtificator as per the instructions in the [FAQ](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/FAQ.md#reqtificator-questions)

Close mod organizer - and use the launcher to start the game.

---

## Known Mod Issues/Incompatibilities

The following Types of mods are NOT Compatible. (cause game breaking bugs)
> * Any Alternate start mod. (Ultimate Skyrim reborn is included in the list, which acts as a alternate start mod. It cannot be removed and replaced with somthing else)
> * Any Mod which affects the perk trees E.g. Ordinator 
> * Truly Absorb Dragon Souls, DSAMG - Dragon Soul Absorb More Glorious and Dragon Remains (prevents the main quest from firing upon killing a dragon)
> * UltSky Starting items for 4.0.6hf2 (Breaks Ultimate Skyrim reborn, character wont teleport after creating and doesn’t have the promised items anyway!)
> * New Races                          (unless requiem patch available) Requiem won’t start and will return you to the main menu.
> * Skyrim Together (Just doesnt work)  

The following Mods are extremely script heavy, Will possibly break your game.
> *  Enhanced Blood Textures (known to cause fps degradation/script bloat)
> *  Open Cities (also requires a tonne of manual patching)
> *  Sexlab Seperate Orgasms (known to cause fps degradation/script bloat)

The following types of mods have Issues 
> *  New creatures/enemies/NPC's/followers   (unless requiem patch available) - Note: for enemies - they are generally added as unleveled, and in requiem this means they are always level 1. for NPC's and Followers - they will be missing the requiem perks and may also be unleveled (ergo level 1)
> *  Dead NPC Body Cleaner Remover (caused Immortal Vampires when you attempt to burn them, also causes civil war patrols to scream like banshee's)  
> *  Important Information Overhaul (Just doesn’t work with our ENB)
> *  New Quest area mods   (unless requiem patch available) - Note: This is because new area's generally add new creatures/enemies/NPC's and followers
> *  3Tweaks (We use Requiem 3.0.2, 3tweaks requires 3.4. It also changes so much stuff, that it won't be compatible with anything without 3tweaks dedicated patch - which just dont exist for the bulk of the mods in the list - Including Ultimateskyrim.esp itself).     

---

## Graphics Overhaul Guide

The discord staff have updated the old Rodricktech graphics guide to 4.0.7 and beyond. 

https://docs.google.com/document/d/1VriFJt2qWrGNuA_gT1NwD7Qr_ewBTG7jnlUNSXE02yU/preview

if you want to suggest mods which you think should be in this guide or broken links you can do so to /u/Mieeka on reddit, Liz#7199 / Resident Thievul
#6745 on discord Or by filling in the feedback form here https://forms.gle/jG4DadrizsRz3bwT9

---
## NPC Overhaul Guide
We have an updated WICO, Bijin and EEO guide.
Please note that this will ONLY work on a NEW game, NO save or template will be compatible with this guide!

https://docs.google.com/document/d/1V0W74f-WdmsFP2PwYDRgs9zVtPoJ3wjNPBvBRUeRiss/preview

---
## BMX Gameplay Overhaul Guide
This guide (updated regularly) is aimed at helping players create an even more immersive playthrough by implementing some quality-of-life improvements, UI aesthetics along with further gameplay enhancements that allow for a better roleplay experience
https://docs.google.com/document/d/1CVO9m8v72BLvwQAqZlG9z7mYFxJPgUOqhP1SDScIoIA/preview

Issues with this guide should be directed to Bmxfreestyle357#6234 on discord or by filling in the feedback form here https://forms.gle/jG4DadrizsRz3bwT9
    
---
## Anna Gameplay Overhaul Guide

If you enjoy the following playstyles and themes, these MCM settings and extra mods might be perfect for you:

> - Deadly, realistic combat with longer-term consequences.
> - Immersive world experience with minimally intrusive HUD/mechanical elements.
> - Enhanced NPC interactions with more in-world characters.
> - Warrior, thief, and lower magic playstyles.
> - Civil War and military playthroughs.
> - Slower, grindier pace of play. 
> - *EXTREMELY HARDCORE*    

You can get a lot of this experience from the default UltSky list, but the added mods and plugins in this guide really turn it up to 11 for me.   
    
Please note: 
This guide was designed using the 4.0.7 modpack, and some of the mods featured in the MCM setup area and no longer included (Nether’s Follower Framework), BURVARP now requires wintersun, and Phintweaks is included in the base build so installation is no longer nessisary. You can see Anna's modwatch here https://modwat.ch/u/cascadianna/plugins . 

https://unearthedarcanna.wordpress.com/ultimate-skyrim-annas-mcm-mod-roleplay-setup/
 
    
    
---
 
    
## Autosave Manager
Auto-saves trigger when loading into a Cell - when all the scripts are running that can corrupt a save and increase your load times massively.

I use autosave manager because it is a mod itself - and therefore triggers the save a few seconds after entering a cell, by which time all of the scripts should have fired. The only drawback is the game freezes for a few seconds while making the save.
https://www.nexusmods.com/skyrim/mods/34842/

It is also highly configurable so you can automate saves at more places than you would be able to in vanilla saves.

Installation Instructions:

On the RIGHT side:
> - Load patch BELOW Ultimate Skyrim's patches, ABOVE Automatic Variants (and paper world map if you have this in your load order).

In the MCM - I use the following settings: -

In save events 
> * I have mine set to Manual save on Rest/Wait/Arrive at destination/ discover location/dungeon clear.
> * I have it set to do an Incremental every 30 mins.
> * I can do a manual save on f4.

Save conditions tab.
> * Left as default.

General settings tab
> * Save delay - 6 seconds.
> * Script delay - as high as I could set it.
> * I also limited the number of incremental saves to 15

Finally
> * I disabled auto-saving via the Skyrim settings menu completely.


---
## EnaiSiaion mods

### Wintersun - Faiths of Skyrim* [Guide updated 2021/04/02]

https://github.com/UltimateSkyrim/UltimateSkyrim/blob/master/Docs/HazGuides.md#installing-wintersun---faiths-of-skyrim-with-segs-patch
```
Changelog:
Enabled the scripts from the mod Alternate House of Horrors. Without the scripts activated the mod would not work.
```
### Sacrosanct - Vampires of Skyrim with Seg's patch* [Patch updated 2019/08/21]

https://github.com/UltimateSkyrim/UltimateSkyrim/blob/master/Docs/HazGuides.md#installing-sacrosanct---vampires-of-skyrim-with-segs-patch

### Andromeda - Unique Standing Stones of Skyrim* [Guide updated 2020/09/15]
    
https://github.com/UltimateSkyrim/UltimateSkyrim/blob/master/Docs/HazGuides.md#installing-andromeda---unique-standing-stones-of-skyrim
```
Changelog:
- Bugfix - Removes conflict with Skyrim unbound reborn so that MCM options are not messed up.
```

---

## SNBCJ's mods

Immersive Divine Blessings, Immersive Abilities, Standing Stone Rebalance, Classic Alchemy Overhaul, Classic Food and Drink. 
    https://github.com/UltimateSkyrim/UltimateSkyrim/blob/master/Docs/HazGuides.md#installing-snbcjs-mods-immersive-divine-blessings-immersive-abilities-standing-stone-rebalance
```
Changelog:
- Bugfix - Removes conflict with Skyrim unbound reborn so that MCM options are not messed up.

- Updated Khajit and Argonian races (including vampire) to keep their Ultimate Skyrim perks.
    - Claw attack for argonian
    - Perkless lockpicking for Khajiit
```
---

## Rain Ash and Snow Shaders 
Rain Ash and Snow Shaders or R.A.S.S. is a shader overhaul all-in-one that aims to add slightly more realistic shaders and particle effects to NPC, Creatures and your Character. https://www.nexusmods.com/skyrim/mods/103218?tab=files

Installation Instructions:
Load after WetandCold - Ashes.esp in the right window and after Wet and Cold and Frostfall in the Left (it should be there by default anyway).

In-Game Config (best results): 
> * Turn off shader effects from Frostfall.
> * In Wet and Cold: For player and NPCs: turn off the drips in wet section, leave soggy feet, 
  snowy and breath in cold, and dusty in Ashes. 
> * In RASS disable Snowing, Swimming, and set the Raining option in Camera Visual Effects to Off, 
  this will stop disorientating focusing issues if you use the ENB's Anti-Aliasing and Depth of Field effects.



---
## Discord Community Patches

The following are custom patches developed by the discord community. Unless otherwise specified, all will require a new save and the Reqtificator running after installation.

### from kilted Frog#6208

#### Interesting NPCs https://www.nexusmods.com/skyrim/mods/8429/ (Download & install, Main file, Update file, both Optional Files (hearthfire & Vampires)

Patch location: https://cdn.discordapp.com/attachments/566109104360390657/820459848423571486/kFs_3DNPC_-_Requiem_Patch.esp

Install Instructions:
> - Open RealisticRoomRental-Enhanced-25029-1-8-3.7z in your downloads folder and extract RRR_3Dnpc-patch.ESP to content\Mods\Perseid's Inns and Taverns - Enhanced.
> - Create a folder in Mods directory called "Interesting NPCs Requiem patch" and save the patch into that folder. 
> - Re-open or refresh Mod organizer.
> - Install Interesting NPCs Main file, Install Update file the same folder as "Interesting NPCs" main file - when asked what to do about overwrites - select "Merge". 
> - Install both optional files into their own unique names. 

 
Left Side
> - Inconsequential NPCs 
> - Interesting NPCs
> - Interesting NPCs - Hearthfire Patch
> - Interesting NPCs - Dawnguard Meshes for Vampires
> - Interesting NPCs Requiem patch can be left at the end - It doesn’t matter.


Right side

For *3DNPC.esp*:- Install below Inconsequential NPCs. Load order should be: - 
> - Immersive Patrols II.esp 
> - Inconsequential NPCs.esp 
> - 3DNPC.esp 

For *RRR_3Dnpc-patch.esp* 
> - RealisticRoomRental.esp 
> - RRR_3DNPC-Patch.esp 

For *kFs_3DNPC_-_Requiem_Patch.esp* 
> - between Requiem.esp and Ultimate Skyrim.esp

Finally, in ETAC's MCM menu (below) check Morthal Blacksmith fix
![Blacksmith Fix](https://i.imgur.com/cepn8aX.png)

If you would like to add some beauty/customization

Download Both. 
Cuyima Interesting NPCs LE https://www.nexusmods.com/skyrim/mods/92893
Interesting NPCs Visual Overhaul https://www.nexusmods.com/skyrim/mods/104506

Install Instructions:

Left Side
> - Inconsequential NPCs 
> - Interesting NPCs
> - Interesting NPCs - Hearthfire Patch
> - Interesting NPCs - Dawnguard Meshes for Vampires
> - Interesting NPCs Requiem patch can be left at the end - It doesn’t matter.
> - Cuyima Interesting NPCs LE 
> - Interesting NPCs Visual Overhaul 

**If you know how to merge mods and have a merge mod tool installed**

> - Make sure the .esp files in the right pane are in the same order. Cuyima’s first, then Visual Overhaul second. Leave them at the bottom of the load order.
> - Use your favorite merging program to merge these 2 mods together. 
> - Call the merge “iNPCs Visual.esp”. Make sure that load order has VO overwriting Cuyima (Interesting NPCs Visual Overhaul on the bottom).
> - Take your new merged mod and place it directly under Interesting NPCs Visual Overhaul in the left pane.
> - Open “Information” for both Cuyima and VO and hide their respective .esp files.
> - Take your new iNPCs Visual.esp in the right pane and place it directly below 3dNPC.esp.
> - Open your Reqtificator.ini file.
> - Add iNPCs Visual.esp under the [NPC Visuals] section.
> - Rerun Reqtificator.

**If you don't know how to merge mods**

Right Side

> - 3dNPC.esp
> - Cuyima 3DNPC - Redone.esp
> - 3DNPC Visual Overhaul.esp 
> - Open your Reqtificator.ini file.
> - Add both Cuyima 3DNPC - Redone.esp & 3DNPC Visual Overhaul.esp under the [NPC Visuals] section.
> - Rerun Reqtificator.

*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_
### from Liz#7199
    
Beta releases. Please give [feedback](https://forms.gle/jG4DadrizsRz3bwT9) if something is very wrong.
    
#### Revert Notification Speed changes back to default.

Quick patch to revert the notification scroll speed back to vanilla defaults, can be added mid-playthrough. No need to run Reqtuificator.

Patch location: https://www.nexusmods.com/skyrim/mods/107926/?tab=files

Install Instructions:

> - Download Revert Notification Speed changes back to default. & Install Via Mod Organiser
> - Make sure left side it is located after "Ultimate Skyrim core files".
> - enable, no need to run reqtificator.
    
#### Wounds Crafting patch.
Patch to move the crafting recipes for wounds to the crafting table and crafting ledger where appropriate. Also replaced Firewood with Wood.   
I have also merged in the file "Requiem - Wounds" https://www.nexusmods.com/skyrim/mods/94958 (all credits to Atardecer), and added compatibility to leveled lists between the requiem patch & Ultimateskyrim.esp
    
Patch location:  https://www.nexusmods.com/skyrim/mods/107926/?tab=files
    
Install Instructions:    
> - Download UltSky Wounds Patch. & Install Via Mod Organiser    
> - Wounds.esp above requiem.esp     
> - Ultsky - Wounds.Esp After Ultimate Skyrim patches.   

#### Liz's Campfire Placeables
    
Updates: 
> - 05/19/21 12:30 PST - Added Spinning wheel, Added craftman perk required to make crafting stations, corrections to mismatched carry weights between Standalone & all-in-one versions. 

Choose 1 only (except standalones)
* Tentapalooza UltSky patch containing Craftable & Placeable Wooden Bathtub, Spinning Wheel & Crafting table https://www.nexusmods.com/skyrim/mods/107926/?tab=files
* Combined   Craftable & Placeable Crafting table, Spinning Wheel & Wooden Bathtub https://www.nexusmods.com/skyrim/mods/107926/?tab=files
* StandAlone Craftable & Placeable Wooden Bathtub https://drive.google.com/file/d/1hgd9ExLKyNDb95XWwtkQm9CNVfehDaUR/view?usp=sharing
* StandAlone Craftable & Placeable Crafting table https://drive.google.com/file/d/1A6DFEWl0MApe5iWwlmIhlxPDpmpRSYRy/view?usp=sharing
* StandAlone Craftable & placeable Spinning Wheel https://drive.google.com/file/d/1buwKj2yzb_GH7dP5iU_0OcTTN5eSS11j/view?usp=sharing    

TentaPalooza patch makes the following changes
>- Disables the chest items which grant you infinite storage which you can pick up and fit in your backpack.
>- Adds all items to a suitable crafting station (mostly the crafting table).
>- Adds all items to the crafting ledger.
>- Replaces deactivated materials with UltSky equivalents
>- Adjusted materiel requirements for the more powerful tents in line with existing recipes in Ultsky.
>- Integrates Bathing in skyrim functionality to tentpalooza bathtubs.
>- Adds a User craftable crafting table which you can move with your camp. (requires Wood, Nails, Iron hammer)
>- Adds 4 new placeable beds, Linen Hammock, Coffin, White & red linen bedrolls. 
>- Adds a Simple Wooden bathtub (like you see in inn's) which you can move with you camp.  (requires Wood, Iron ingots, Beehive husks)
>- Adds a Spinning Wheel which you can move with you camp.  (requires Wood, Iron Fittings)


Install Instructions:

Download your choice of mod and install via mod organiser. right side Placement after Tentapalooza (if installed)

Right side
> - After Ultimate Skyrim patches. 
> - If installing TentaPalooza Patch - then this needs to go after Tentpalooza.esp as well.

*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_

### from Plotinuz#5876 
https://www.nexusmods.com/skyrim/users/655458 

Beta releases. Please give [feedback](https://forms.gle/jG4DadrizsRz3bwT9) if something is very wrong.

#### Barely Used Vanilla Actors Recycle Project https://www.nexusmods.com/skyrim/mods/85540 

Patch location: https://www.nexusmods.com/skyrim/mods/107219/
    
Requires : Wintersun & Patch from here [EnaiSiaion mods](#EnaiSiaion-mods)

Install Instructions:

There are two files - you want the main file. 
> - Buvarp Ultsky patch with ETAC and Wintersun Ultsky patch compability.7z 

On the RIGHT SIDE (plugins tab) in MO2:
> - Put Buvarp.esp below relationship Dialogue Overhaul, and above Ultsky.
> - Patch below: Wintersun 3.1.5 - Seg 1.4 - Ultsky patch

#### Dragon Combat Overhaul (DCO) - https://www.nexusmods.com/skyrim/mods/32597

What the patch does:
- forwards Dragon Combat Overhaul (DCO) specific flying, acceleration and other DCO effects into a Ultsky/Requiem optimized environment.
- DCO changes to Alduin
- Conflict resolving with Requiem/Ultsky stats and perks in favor of vanilla, but DCO for specific traits.

Why you DON'T want DCO with patch in your load order.
This will hurt. Badly. Only the most masochistic player will want this in their load order.

I heartily recommend limiting the Assault MCM option to only 1 dragon until you are at VERY high levels and are comfortable fighting these dragons.

For those who are concerned about power-creep in the higher levels.... Don't worry. The Dragons are now.... bad.
just the DCO Soulfire curse that you can get from fighting these dragons will make you feel under leveled in a MOST immersive way.

You have been warned.

This will **HURT**.

Patch Location: https://drive.google.com/file/d/1PBwAA7FTwnxmDy3dGZbPvnycDHbgUd_I/view?usp=sharing

Install Instructions:

On the RIGHT side:
> - DCO above Requiem.
> - Load patch BELOW Ultimate Skyrim, ABOVE Automatic Variants (and paper world map if you have this in your load order).

On the LEFT side:
> - Doesn't matter unless you have a mod that overwrites scripts from DCO main file.
    

#### Realistic Armor https://www.nexusmods.com/skyrim/mods/102963

Patch location: https://drive.google.com/file/d/1qOZmcoCWNs4pUbzWdbdk4cj_HRdMHei6/view?usp=sharing
    
What it does: Forwarded UltSky records, flags and stats where applicaple.

Be aware. Several armortypes that previously were flagged as light/evasion, are now classified as Heavy Armor.

Recipes of existing armors (that are already in UltSky and are overwritten by this mod) have for the most part crafting recipes as in UltSky.

New armors have been left untouched for now.

To be done.

Crafting recipes. Will be done when I have too much time on my hands (and I get annoyed enough).

Install Instructions:

On the RIGHT SIDE (plugins tab) in MO2:

Load Mod & patch BELOW Ultimate Skyrim, ABOVE Automatic Variants (and paper world map if you have this in your load order).
    

#### Helgen Reborn https://www.nexusmods.com/skyrim/mods/35841 

Patch location: https://drive.google.com/file/d/16bVZFpcB1oCPhj1W5iJHzJm3DWBP4h3N/view?usp=sharing

Install Instructions:

> - Install Helgen Reborn very high up in load order on both left and right side in MO2. (above Requiem at least. Further up to avoid chance of texture assets overriding other mods)
> - Install patch between Requiem and Ultsky on the right side in MO2. Left side should not matter.
> - Nothing ELSE with Helgen Reborn has been done. Consider this very beta. (There are some weapons that are not fixed yet that had insane damage. 10000 from vanilla mod, turned 40000 in requiem for the indifferent. What the heck those weapons are for, I do not know, but holy sh*te!)

#### Requiem - Unarmed Combat Enhancer WITH integrated Cosmetic UCE addons https://www.nexusmods.com/skyrim/mods/75779?tab=files (Download version 2.4.2 from OLD FILES)

I have merged in the file "Requiem - UCE Addon" that add "Adds cosmetic Cestus and Claws that can be worn over gloves/gauntlets."

Important note: This patch for Ultsky with additional SNBCJ mods Immersive Abilities and Immersive Divine Blessings. It will not work without those mods installed please see [SNBCJ's mods](#SNBCJs-mods) for install instructions.

All credits to Noxcrab#2521

Patch location: https://drive.google.com/file/d/1utXH1-YniYzFq4TNN3O5HosCQcPhmurc/view?usp=sharing

Install Instructions:

Right side
> - Load Requiem - Unarmed Combat Enhancer Below Requiem.esp and ABOVE UltimateSkyrim.esp. 
> - Load patch on Right side below Ultimate Skyrim.esp and BELOW R-IA 1.6 Ultsky 407 patch.

#### Sofia - The Funny Fully Voiced Follower - https://www.nexusmods.com/skyrim/mods/54527?tab=description

This file is an attempt at an update of the "Requiem 1.9.x - Sofia Follower Patch" (created by LosGrak) to Ultsky Requiem.

I have merely updated the perks in Tes5Edit, added some that seemed missing, and reinstated some of the vanilla stats that seemed appropriate. 
with regards to the perks. 

In LosGrak's words:
"This file is a patch to bring the Sofia follower, created by John Jarvis and Christine Slagman? more in line with the changes made by version 1.9.2 of the Requiem Roleplaying Overhaul. This means that her stats have been changed as well as her perks. A brief list of changes can be seen below:

Base HP, Magicka and Stamina have been set to levels fitting a Nord character. However, because she is a spell sword, she has a slight Magicka offset of 15. She has no Health or Stamina offsets.

Sofia's base combat stats have been reduced to bring her in line with a level 1 Nord character.

Several perks have been added that are both appropriate and thematic to a spell sword.

This patch does have its limitations. I am neither a true modder nor a coder. I am unable to remove control of Sofia's Health, Magicka and Stamina from her MCM, nor am I able to remove access to her infinite storage. It is up to you to not use these features.

Patch location: https://drive.google.com/file/d/1xQ-PPfb1rK79TyrVbGlxK77KECLFtCyd/view?usp=sharing

Install Instructions:

Right Side: 
> SofiaFollower.esp before Requiem.esp
> Requiem - Sofia.esp after Requiem.esp

#### Guards Armor Replacer https://www.nexusmods.com/skyrim/mods/95719?tab=files

Patch notes:

Forwarded UltSky values for a consistent gameworld.
Except where the mod author intended that guards are also expert marksmen with full suite of requiem perks to back that up.

Set up tempering recipes to be consistent with material and crafting perks.
You will need advanced smithing to temper guard armor. Ebony for ebony armor and dwarven for Markath. 

(It was a mix of basic crafting for some cuirasses, but advanced for helmets and such. Also advanced for ebony armor, and for Markaths dwarven based armor. Made little sense).

Changed armortype to steel for Solitude and Whiterun (Dwarven for Markath, Iron for the other holds) to reflect their intended status as rich holds and to ensure the reqtificator add in proper armor resistances.

Are considering to set Solitude to Steel Plate....."

Patch location: https://drive.google.com/file/d/1haUrgT2wGr_oFi97napiadaMk_MfM0d6/view?usp=sharing

Install Instructions:

You will need to install Main file through MO2.

It is **strongly** recommended a completely new play-through. Template save might work. But I do not know.

In Content\mods folder
> - Create Folder called "Guards armour Patch"
> - Save patch to folder.

On the left side in MO2
> - place Guards armour replacer (Main mod) below UltSky.
> - Place Guards armour Patch below Guards armour replacer

On the Right side 
> - place Guards_Armor_Replacer.esp between Ultsky and Paper World Map.

As always - You have to run Reqtificator.

*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_*_

### from Phinocio#6969 

#### Buffed nightingale armor 

Patch location: https://cdn.discordapp.com/attachments/566109104360390657/711400642190508082/BuffedNightingaleArmor.zip

Changes Nightingale armor values to
```
* Hood: 20 Illusion, 25 Ranged, +30 Magicka
* Chest: 30% Magic Resist, 25% Sneak, 100% Poison Resist
* Gloves: +18 Lock Picking, +20 Lockpick expertise, 20% One handed, 35% Pickpocket
* Shoes: +100 Stamina, 100% Stamina Regen, Muffle 1

Also changes Ancient Shrouded Cowl and Ancient Shrouded Boots to match the hood and boots respectively. 
because Requiem is lazy and uses the same effect for both.
```

Install Instructions:
> Load anywhere after Requiem ESP. Left side doesn't matter.
> 
#### Dwemer Hacker https://www.nexusmods.com/skyrim/mods/80660

Patch Location: https://github.com/phinocio/Dwemer-Hacker-US-Patch/releases/tag/1.0.0

Install Instructions:
> - Place the Dwemer Hacker ESP before Requiem.esp, left pane doesn't matter.
> - Install Dwemer Hacker - US Patch from Github
> - Place the ESP just anywhere after the Ultimate Skyrim.esp file.

---

## No ESP mods

Toggle Enchantment lets you turn on/off your weapon's enchantment when you don't want to waste the charge. https://www.nexusmods.com/skyrim/mods/78134

Faster Sleep Wait (SKSE). Decreases the time spent waiting between hours in the Sleep/Wait menu.  https://www.nexusmods.com/skyrim/mods/95796

Disable Quick Save: This mod makes the Quick-Save hot-key make a Full save instead. Use Main File - https://www.nexusmods.com/skyrim/mods/82951

Smaller Cursor: Very small but great mod. Simply makes the in-game cursor smaller instead of the GIANT default one. Use Main File - https://www.nexusmods.com/skyrim/mods/2317/

Rudy HQ - More Lights for ENB - Bthardamz: highly recommended, no ESP required. In the left window, load after Ultimate Skyrim core files.
https://www.nexusmods.com/skyrim/mods/95614?tab=files 


**The following were suggested by u/PeonTheGrate on Reddit **

EZ2C DIALOGUE MENU: Makes the Dialogue menu look much nicer with a high amount of customization. I used the preset found below (Yes, I know this says Skyrim Special Edition - the author of the preset does have a habit of hiding his mod frequently so you can try asking on his discord).
- Use Main File - https://www.nexusmods.com/skyrim/mods/18466
- YASHed/Northern Experience Preset: - https://www.nexusmods.com/skyrimspecialedition/mods/23894?tab=files

Sleep Tight SE Fixes: Use 3rd Main File (Without Yundao Hair) - https://www.nexusmods.com/skyrimspecialedition/mods/31620
Same as above, this mod says Skyrim Special Edition, however it’s just a script file. It works 100% fine in LE. What it does it fixes the script to where NPCs will take off their boots, gauntlets, helmet, and cape if they wear them while going to sleep. This allows you to keep the MCM option friendly sleepwear to robed like US had in the past before the bug was discovered. This makes more sense logically, and also looks much better than taking off all their clothes in the cold land of Skyrim.

Slower Lockpick: Use Main File - https://www.nexusmods.com/skyrim/mods/82373?tab=files&file_id=1000237877
SKSE plugin that slows down (or speeds up) the lockpick on the lockpicking screen to allow more accurate control. AMAZING! I prefer changing its ini file to 0.12 instead of the 0.5 default. This makes the lockpicking screen slower but not too slow.

Cobb Bug Fixes: Use Main File - https://www.nexusmods.com/skyrim/mods/96734
Little Plugin that fixes some bugs in the vanilla game.

Load Game CTD Fixes: Use Main File - https://www.nexusmods.com/skyrim/mods/85443
CTD Fix that will lessen even more crashes that US already fixes.

Dog Bark Quiet: Use Main File - https://www.nexusmods.com/skyrim/mods/188/
Small mod that makes the Dog bark a bit quieter. Muh immersion.

Animated Clutter: Use Main File - https://www.nexusmods.com/skyrim/mods/48287
Fantastic mod that animates Clutter. Choose what you want animated in the FO-MOD. I recommend almost all of them.

Full Screen MCM Menu for SkyUI (Option 4): - https://www.nexusmods.com/skyrim/mods/95924?tab=description
Very nice organizational/UI mod. Makes the MCM menu larger. Looks very nice, I prefer Option 4.

Skeletons don't breathe: Use Main File - https://www.nexusmods.com/skyrim/mods/64312/
Muh Immersion! Why should Skeletons make breathing noises if they don't have lungs?

Hircine Restoration Project: Use Main File - https://www.nexusmods.com/skyrim/mods/90594/
Make Hircine's voice sound more like the original games, very small and welcome change.

Wash that Blood Off: Use Main File - https://www.nexusmods.com/skyrim/mods/98546
Small Immersion mod that makes blood come off you while in water.

To Your Face - Sensible NPC Commenting: Use Main File - https://www.nexusmods.com/skyrim/mods/87635
Great mod that prevents NPC's telling you random comments just by walking behind you.

Immersive Horses v2.5 Talking Fixes: Use Main File - https://www.nexusmods.com/skyrim/mods/100521
Bug fix for Immersive Horses that makes you talk function choose the closest NPC instead of a random one.

Srt Crash Fixes: Use Main File - https://www.nexusmods.com/skyrim/mods/100672
Another crash fix mod that works with everything, helps prevent even more crashes.

Quieter Thieves Guild Door: Use Main File - https://www.nexusmods.com/skyrim/mods/1826
GREAT mod that lowers the volume of the ridiculously loud Thieves Guild secret entrance in Riften.

Simple Lock Picking Menu: - https://www.nexusmods.com/skyrim/mods/26490?tab=files
This mod removed unnecessary clutter from the Lock picking menu. I Recommend the Normal Version.

Simple Reading UI (Take and Steal): - https://www.nexusmods.com/skyrim/mods/74434/
Same as above however this mod is for the reading UI. I recommend the Take and Steal version.

Markarth Waterfall fix for dark nights: Use Main File - https://www.nexusmods.com/skyrim/mods/97903
I call this a bug fix for ENB. Fixes the meshes for the waterfalls in Markarth to not be bright white with a ENB at night.

No Screenshot Pop up: Use Main File - https://www.nexusmods.com/skyrim/mods/95802
Simple Plugin that makes the screenshot Pop Up go to the console instead of on the UI.

No Poison dialogues: Use Main File - https://www.nexusmods.com/skyrim/mods/33916
Removes the dialogue submission for putting on poisons.

----

## Other Mods

Requiem - Less Double-Vision (R-LDV) - Reduces the Blur/double vision you get when you get a debuff. https://www.nexusmods.com/skyrim/mods/73666/

Requiem - Blessings Ignore Crime - This patch removes crime gold, bounty, murder, and Thieves Guild/Dark Brotherhood membership, as conditions preventing blessings from the nine divines. https://www.nexusmods.com/skyrim/mods/50251?tab=description

Bathtubs Basins and Beyond - Wash up! Adds usable bathtubs, basins, towels and more, using the Campfire framework and optionally Bathing in Skyrim. https://www.nexusmods.com/skyrim/mods/102654 (grab both Bathing in Skyrim version & Ultimate Skyrim Patch) Should be loaded after UltimateSkyrim.esp on the right pane

Requiem - Noxcrab's Tweaks https://www.nexusmods.com/skyrim/mods/78134
> Should all be loaded after UltimateSkyrim.esp on the right pane.
> * Toggle Enchantment - lets you turn on/off your weapon's enchantment when you don't want to waste the charge.
> * Enemy Regeneration Tweak - Regeneration of mid-level enemies (Trolls and Spriggans) are simply reduced, and boss enemies (Dragonpriests and Enchanted Spheres) are rebalanced in a way that they are more interesting challenges instead of dps/powergame limiter. (Make sure you grab V3.1 from the old files)
> * Requiem - Faster Crossbows - Makes Crossbows faster, but instead increase the stamina cost a bit.
> * Requiem - Enchantment Tweaks - Fortify Magicka Regen magnitude changed: 25 -> 35 Fortify Health Regen and Magic Resist placeable on head equips.
> * Automaton Resistance Tweak - Automatons (including the Forgemaster) will be weaker to Frost as much as they are to Shock.


PhinTweaks - Requiem and Ultimate Skyrim Tweaks. https://www.nexusmods.com/skyrim/mods/102978?tab=files
> Should all be loaded after UltimateSkyrim.esp on the right pane.
> * Toggleable Aetherium Helmet Night Vision - Changes the Aetherium Helmet's constant Night Vision into a toggleable power. Power is added on equip and removed on unequip.
> * UltSky - Armor Resistances Fix - Known issue patch for 4.0.7 
> * UltSky - Inn Prices Fix - Known issue patch for 4.0.7
> * Wet and Cold - Non Enchantable Cloaks - Made with Ultimate Skyrim in mind. Can be used with Requiem no problem (technically only requires `Wet and Cold`). Simply adds keyword to the cloaks making them unenchantable. Requires W&C.
    
Better Dead Thralls & Patch https://www.nexusmods.com/skyrim/mods/58069 & https://www.nexusmods.com/skyrim/mods/95859?tab=files

    Makes Undead summons less braindead 😉
> Better Dead Thralls.esp before Requiem.esp
> Requiem - BDT Patch.esp  after Requiem.esp    
As always - You have to run Reqtificator.    


Ultimate Skyrim - Music mods patch https://www.nexusmods.com/skyrim/mods/99822 a ultimate Skyrim patch to add a whole bunch of music mods to the game.

## What About legacy of the Dragonborn?

This mod is **NOT** recommended for install and only experienced modders who are capable of writing their own patches should even make an attempt.  

It is only being included in this document because Support are fed up about people asking what is required. 

Please don’t ask for step-by-step instructions on what to do to write a custom patch, and before you ask - no you cannot just ignore the custom patch and no we won't write one for you.

As a rough guide
1) LoTD should be installed as the last mod you are going to add to your list, so that it's FOMOD detects what mods are active and enables the appropriate content. The ESP for this should go as high in your load order as you can get it.
2) Install patches for the base install, any additional mods you have added and Requiem (https://www.nexusmods.com/skyrim/mods/72921/, you need Legacy of the Dragonborn Patch Collection and Optional Mod Patches for Legacy at bare minimum for base install. https://www.nexusmods.com/skyrim/mods/57376/? also need this for if you want your followers to sandbox in the safehouse.)
3) Clean added mods
4) Create merges for patches using your merge tool of choice - As you will have over 10 of them - Suggest loading this ESP just before Ultimate Skyrim.esp
5) Check for texture conflicts on the new mods/patches (E.G ETAC/LOTD conflict in Falkreath where ETAC places a tree in the Kadjit camp for the moonpath of Elswyr quest)
6) Create conflict resolution patch using Editing tool of choice - this ESP should be loaded just before paper world map in your load order. This should at minimum:-
    1) Deal with any conflicts which aren’t taken care of by the patches.  
    2) To drastically reduce the complete OP-ness of the items lotd adds
    3) LoTD conflicts with Book Covers of Skyrim (gives duplicates that you can't store at your museum), so you have to edit all those to replace with the LoTD item id, as well as levelled lists where the books drop.
    4) Deal with Texture conflicts.
7)  Rerun Dyndolod
8)  Rerun Reqtificator

