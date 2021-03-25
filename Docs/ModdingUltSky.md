# Ultimate Skyrim Modding Guides

<!-- TOC -->
- [Ultimate Skyrim Basics](#ultimate-skyrim-modding-basics)
- [Graphics Overhaul Guide](#ultimate-skyrim-Basics)
- [NPC Overhaul Guide](#npc-overhaul-guide)
- [BMX Gameplay Overhaul Guide](#bmx-gameplay-overhaul-guide)
- [Autosave Manager](#autosave-manager)
- [EnaiSiaion mods](#EnaiSiaion-mods)
- [SNBCJ's mods](#SNBCJs-mods)
- [Rain Ash and Snow Shaders](#Rain-Ash-and-Snow-Shaders)
- [None ESP mods](#None-ESP-mods)

<!-- /TOC -->

## Ultimate Skyrim Modding Basics
Installing Mods not covered by guides 

- Download it to your UltSky download folder
- open content\mod organiser.exe select the profile you plan on playing
- select download tab on right side
- find the mod in the list and right click > install
- choose your settings if it has the then once its finished installing turn it on on the left side of the mod organizer.

Sort your (right side) Plugins load order **manually** (LOOT IS THE DEVIL - ERASE its Existence from your memory) .

Firstly There are specific guides in this document for a lot of the more popular mods, along with proper Ultksy patches & install instructions, so check those first!

If there isn't a specific guide, then as a general rule of thumb 
* Anything that adds spells, weapons, followers or other types of NPCs should go ABOVE requiem.esp (right pane of MO2)
* Patches always have to be below the mod they are patching, thus the requiem patches will be below requiem.esp by the other requiem patches while your mod will be above requiem.esp.
* Any mods which are NPC overhauls should follow the same installation process as Bijin (in the Wico/Bijin/EEO guide in pins)
* Any mods which don't Add new NPCS, followers, Spells and weapons, should be installed below the Ultimate Skyrim patches, but above Warburg's Paper world map. (E.g Autosave manager, bathtubs Basins and beyond, tentpalooza)

Setup and run the reqtificator as per the instructions in the FAQ 

close mod organizer - and use the launcher to start the game

---
## Graphics Overhaul Guide

The discord staff have updated the old Rodricktech graphics guide to 4.0.7. 

https://docs.google.com/document/d/1VriFJt2qWrGNuA_gT1NwD7Qr_ewBTG7jnlUNSXE02yU/preview

if you want to suggest mods which you think should be in this guide or broken links you can do so to /u/Mieeka on reddit or Liz#7199 / 𝕽𝖊𝖘𝖎𝖉𝖊𝖓𝖙 𝕿𝖍𝖎𝖊𝖛𝖚𝖑#6745 on discord.

---
## NPC Overhaul Guide
We have an updated WICO, Bijin and EEO guide for 4.0 courtesy of @SuperSurferDave
Please note that this will ONLY work on a NEW game, NO save or template will be compatible with this guide!

https://docs.google.com/document/d/1-YzjWXf749Og-9ieLXyUeWPgqJp0szpoCieIanfZBPM/edit?usp=sharing

---
## BMX Gameplay Overhaul Guide
This guide (updated regularly) is aimed at helping players create an even more immersive playthrough by implementing some quality of life improvements, UI aesthetics along with further gameplay enhancements that allow for a better roleplay experience
https://docs.google.com/document/d/1CVO9m8v72BLvwQAqZlG9z7mYFxJPgUOqhP1SDScIoIA/edit

Issues with this guide should be directed to Bmxfreestyle357#6234 on discord

---
## Autosave Manager
Auto-saves trigger when loading into a Cell - when all the scripts are running that can corrupt a save, and also increase your load times massively.

I use autosave manager because its a mod itself - and therefore triggers the save a few seconds after entering a cell, by which time all of the scripts should have fired. The only drawback is the same freezes for a few seconds while making the save.
https://www.nexusmods.com/skyrim/mods/34842/

Its also highly configurable so you can automate saves at more places than you would be able to in vanilla saves.

To install: 

Follow the guide in the basics, for right side load order, i place mine immidiatly below the Ultimate Skryim Patches (above paper world map)

in the MCM - I use the following settings:-

In save events 
- i have mine set to Manual save on Rest/Wait/Arrive at destination/ discover location/dungeon clear.
- i have it set to do an Incremental every 30 mins.
- i can do a manual save on f4

Save conditions tab
- left as default

General settings tab
- Save delay - 6 seconds
- Script delay - as high as i could set it.
- I also limited the amount of incremental saves to 15

Finally
- I disabled auto-saving via the skyrim settings menu completely.

---
## EnaiSiaion mods

Wintersun - Faiths of Skyrim [Patch updated 2020/01/28]
https://www.reddit.com/r/ultimateskyrim/comments/bt3a1d/us_404_installing_wintersun_faiths_of_skyrim_with/

Sacrosanct - Vampires of Skyrim with Seg's patch [Patch updated 2019/08/21]
https://www.reddit.com/r/ultimateskyrim/comments/by32xk/us_404_installing_sacrosanct_vampires_of_skyrim/

Andromeda - Unique Standing Stones of Skyrim
https://www.reddit.com/r/ultimateskyrim/comments/da780b/us_40x_installing_andromeda_unique_standing/
For 4.0.7  replace Andromeda 1.0.9 - UltSky 4.x MCM Descriptions with this one Andromeda 1.0.9 - UltSky 4.0.7 MCM Descriptions   https://mega.nz/file/aVsl0YJa#6yaVKCFutL85qcqChc668d7udVCu8ASKO5YT9KhTBQU  

---

## SNBCJ's mods

Immersive Divine Blessings, Immersive Abilities, Standing Stone Rebalance, Classic Alchemy Overhaul, Classic Food and Drink. 
https://www.reddit.com/r/ultimateskyrim/comments/br61eo/us_404_installing_snbcjs_mods_immersive_divine/

For 4.0.7  replace UltSky 4.x R-SSR MCM Standing Stone Info with this one Requiem - Standing Stone Rebalance  UltSky 4.0.7 R-SSR MCM Standing Stone Info https://mega.nz/file/vU8TiALY#3Xx6BdDhvI58gEsp8UWNlKXconHaXAJYq3vD2GdRclk

---

## Rain Ash and Snow Shaders 
Rain Ash and Snow Shaders or R.A.S.S. is a shader overhaul all-in-one that aims to add slightly more realistic shaders and particle effects to NPC, Creatures and your Character.

once installed load after WetandCold - Ashes.esp in the right window and after Wet and Cold and Frostfall in the Left(it should be there by default anyway).

In-Game Config(best results): 
Turn off shader effects from Frostfall
In Wet and Cold: For player and NPCs: turn off the drips in wet section, leave soggy feet, snowy and breath in cold, and dusty in Ashes , 
In RASS disable Snowing, Swimming, and set the Raining option in Camera Visual Effects to Off, this will stop disorientating focusing issues if you use the ENB's Anti-Aliasing and Depth of Field effects.
https://www.nexusmods.com/skyrim/mods/103218?tab=files

---

## None ESP mods

Toggle Enchantment lets you turn on/off your weapon's enchantment when you don't want to waste the charge. https://www.nexusmods.com/skyrim/mods/78134
Faster Sleep Wait (SKSE). Decreases the time spent waiting between hours in the Sleep/Wait menu. No esp.  https://www.nexusmods.com/skyrim/mods/95796

----
