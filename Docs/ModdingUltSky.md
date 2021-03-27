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
- [Other mods & Tweaks](#other-mods)

<!-- /TOC -->

## Ultimate Skyrim Modding Basics
Installing Mods not covered by guides 

- Download it to your UltSky download folder (this will be the directory you entered on the wabbajack installer when you first installed the list)
- open <Ultimate Skyrim install directory>\content\mod organiser.exe. Once open - top left dropdown - select the profile you plan on playing.
- select download tab on right side 
- find the mod in the list and right click > install (you may need to click the refresh button to make it appear)
- choose your settings (if it has install options) then once its finished installing turn it on on the left side of the mod organizer (should be at bottom of the list).

If you mod doesnt have any ESP/ESM's then thats it - otherwise continue!

Sort your (right side) Plugins load order **manually** (LOOT IS THE DEVIL - ERASE its Existence from your memory) .

Firstly There are specific guides in this document for a lot of the more popular mods, along with proper Ultksy patches & install instructions, so check those first!

If there isn't a specific guide, then as a general rule of thumb 
* Anything that adds spells, weapons, followers or other types of NPCs should go ABOVE requiem.esp (right pane of MO2)
* Patches always have to be below the mod they are patching, thus the requiem patches will be below requiem.esp by the other requiem patches while your mod will be above requiem.esp.
* Any mods which are NPC overhauls should follow the same installation process as Bijin (in the Wico/Bijin/EEO guide in pins)
* Any mods which don't Add new NPCS, followers, Spells and weapons, should be installed below the Ultimate Skyrim patches, but above Warburg's Paper world map. (E.g Autosave manager, bathtubs Basins and beyond, tentpalooza)

Setup and run the reqtificator as per the instructions in the [FAQ](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/FAQ.md#reqtificator-questions)

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

Faster Sleep Wait (SKSE). Decreases the time spent waiting between hours in the Sleep/Wait menu.  https://www.nexusmods.com/skyrim/mods/95796

Disable Quick Save: This mod make the Quick-Save hot-key make a Full save instead. Use Main File - https://www.nexusmods.com/skyrim/mods/82951

Smaller Cursor: Very small but great mod. Simply makes the in-game cursor smaller instead of the GIANT default one. Use Main File - https://www.nexusmods.com/skyrim/mods/2317/

Rudy HQ - More Lights for ENB - Bthardamz: highly recommended, no ESP required. In the left window, load after ENB particle patch if you have it installed 
https://www.nexusmods.com/skyrim/mods/95614?tab=files 


**The following were suggested by u/PeonTheGrate on Reddit **

EZ2C DIALOGUE MENU: Makes the Dialogue menu look much nicer with a high amount of customization. I used the preset found below (Yes I know this says Skyrim Special Edition).
- Use Main File - https://www.nexusmods.com/skyrim/mods/18466
- YASHed Preset: - https://www.nexusmods.com/skyrimspecialedition/mods/23894?tab=files

Sleep Tight SE Fixes: Use 3rd Main File (Without Yundao Hair) - https://www.nexusmods.com/skyrimspecialedition/mods/31620
Same as above, this mod says Skyrim Special Edition, however its just a script file. It works 100% fine in LE. What it does it fixes the script to where NPCs will take off their boots, gauntlets, helmet, and cape if they wear them while going to sleep. This allows you to keep the MCM option friendly sleepwear to robed like US had in the past before the bug was discovered. This makes more sense logically, and also looks much better than taking off all their clothes in the cold land of Skyrim.

Slower Lockpick : Use Main File - https://www.nexusmods.com/skyrim/mods/82373?tab=files&file_id=1000237877
SKSE plugin that slows down (or speeds up) the lockpick on the lockpicking screen to allow more accurate control. AMAZING! I prefer changing it's ini file to 0.12 instead of the 0.5 default. This makes the lockpicking screen slower but not too slow.

Cobb Bug Fixes: Use Main File - https://www.nexusmods.com/skyrim/mods/96734
Little Plugin that fixes some bugs in the vanilla game.

Load Game CTD Fixes: Use Main File - https://www.nexusmods.com/skyrim/mods/85443
CTD Fix that will lessen even more crashes that US already fixes.

Dog Bark Quiet : Use Main File - https://www.nexusmods.com/skyrim/mods/188/
Small mod that makes the Dog bark a bit more quiet. Muh immersion.

Animated Clutter: Use Main File - https://www.nexusmods.com/skyrim/mods/48287
Fantastic mod that animates Clutter. Choose what you want animated in the FO-MOD. I recommend almost all of them.

Full Screen MCM Menu for SkyUI (Option 4): - https://www.nexusmods.com/skyrim/mods/95924?tab=description
Very nice organizational/UI mod. Makes the MCM menu larger. Looks very nice, I prefer Option 4

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

Bathtubs Basins and Beyond - Wash up! Adds usable bathtubs, basins, towels and more, using the Campfire framework and optionally Bathing in Skyrim. https://www.nexusmods.com/skyrim/mods/102654 (grab both Bathing in Skyrim version & Ultimate Skyrim Patch ) Should be loaded after UltimateSkyrim.esp on the right pane

Requiem - Noxcrab's Tweaks  https://www.nexusmods.com/skyrim/mods/78134
- Should all be loaded after UltimateSkyrim.esp on the right pane
- Toggle Enchantment - lets you turn on/off your weapon's enchantment when you don't want to waste the charge.
- Enemy Regeneration Tweak - Regeneration of mid-level enemies (Trolls and Spriggans) are simply reduced, and boss enemies (Dragonpriests and Enchanted Spheres) are rebalanced in a way that they are more interesting challenges instead of dps/powergame limiter. (Make sure you grab V3.1 from the old files)
- Requiem - Faster Crossbows - Makes Crossbows faster, but instead increase the stamina cost a bit.
- Requiem - Enchantment Tweaks - Fortify Magicka Regen magnitude changed : 25 -> 35 Fortify Health Regen and Magic Resist placable on head equips.
- Automaton Resistance Tweak - Automatons (including the Forgemaster) will be weaker to Frost as much as they are to Shock.

PhinTweaks - Requiem and Ultimate Skyrim Tweaks. https://www.nexusmods.com/skyrim/mods/102978?tab=files
- Should all be loaded after UltimateSkyrim.esp on the right pane
- Toggleable Aetherium Helmet Night Vision - Changes the Aetherium Helmet's constant Night Vision into a toggleable power. Power is added on equip, and removed on unequip.
- UltSky - Armor Resistances Fix - Known issue patch for 4.0.7 
- UltSky - Inn Prices Fix  - Known issue patch for 4.0.7
- Wet and Cold - Non Enchantable Cloaks - Made with Ultimate Skyrim in mind. Can be used with Requiem no problem (technically only requires `Wet and Cold`). Simply adds keyword to the cloaks making them unenchantable. Requires W&C.

Ultimate Skyrim - Music mods patch https://www.nexusmods.com/skyrim/mods/99822 a ultimate skyrim patch to add a whole bunch of music mods to the game
