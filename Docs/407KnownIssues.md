# Ultimate Skyrim FAQ - 4.0.7 Known Issues

<!-- TOC -->
[**ENB Questions**](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/407KnownIssues.md#enb-questions)
  - [When I enter a cell everything goes really Bright OR My Nightvision has a blue tint OR i get white-outs on a blizzard](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/407KnownIssues.md#when-i-enter-a-cell-everything-goes-really-bright-or-my-nightvision-has-a-blue-tint-or-i-get-white-outs-on-a-blizzard)  
  - [Instincts is blindingly bright when looking at hanging moss (and other herbs)](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/407KnownIssues.md#instincts-is-blindingly-bright-when-looking-at-hanging-moss-and-other-herbs)  
  - [Map is very foggy/unreadable](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/407KnownIssues.md#map-is-very-foggyunreadable)  
  - [Weird Graphical Effect during certain weathers / times of day](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/407KnownIssues.md#weird-graphical-effect-during-certain-weathers--times-of-day)  
  - [Purple water/lakes at some times of the day](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/407KnownIssues.md#purple-waterlakes-at-some-times-of-the-day)  
  - 
[**Graphics Questions**](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/407KnownIssues.md#graphics-questions)
  - [Twitching Piles of Lumber at lumber Mills](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/407KnownIssues.md#twitching-piles-of-lumber-at-lumber-mills)  
  - [Crash to desktop near honneybrew meadary near whiterun.](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/407KnownIssues.md#crash-to-desktop-near-honneybrew-meadary-near-whiterun)  
[**Gameplay Questions**](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/407KnownIssues.md#gameplay-questions)
  - [Requiem Starting stats not being applied correctly.]()
  - [ Inn’s are charging the incorrect price(50g) Vs. what is listed in the MCM]()
  - [Entering waist keep water unequips your weapons & other Misc Fixes]()
  - [Several armours missing requiem resistances (Wolf Armor & Stahlrim Light/Heavy & Nordic Carved)]()


  
<!-- /TOC -->  

#**ENB Questions**
---
## When I enter a cell everything goes really Bright OR My Nightvision has a blue tint OR i get white-outs on a blizzard

Issue caused by incorrect Night vision, lighting, effects settings in ENB
Solution: replace Skyrim\Enbseries\EnbEffect.fx.ini with this [one](https://cdn.discordapp.com/attachments/348579495537803274/757900105427976252/enbeffect.fx.ini)
	
---
	
## Instincts is blindingly bright when looking at hanging moss (and other herbs)
Issue caused by ComplexParticleLights Settings in the ENB
Solution: replace the Skyrim\enbseries.ini with the [attached](https://cdn.discordapp.com/attachments/648152435197607938/819659629112983633/enbseries.ini)	
	
---

## Map is very foggy/unreadable
Issue caused by the ENB missing the map weathers.
Solution: Download the following [file](https://cdn.discordapp.com/attachments/348579495537803274/769587154623791214/enbseries.rar) unzip the contents into Skyrim\Enbseries Overwriting as needed.	

---
	
## Weird Graphical Effect during certain weathers / times of day 
![image](https://user-images.githubusercontent.com/26418143/123943939-884bfa80-d994-11eb-9707-2fa23e372aae.png)

Issue caused by : Sunglare disabler not enabled on Low/Medium profiles
Solution Open content Folder, double click Mod organiser.exe - Select the profile that you play from drop down, at bottom of left side of screen, tick box next to Sunglare disabler. Then close mod organiser.

---

## Purple water/lakes at some times of the day
Firstly - look up - if the sky is purple - thats why. if its not then

Issue caused by BreflectSky being set to 0 in the [Water] section of _content\profiles\<profile you play>\Skyrim.ini.
Solution: Change it to a 1.


---	
# Graphics Questions

## Twitching Piles of Lumber at lumber Mills
Issue caused by : it's caused by mesh file milllogpile_lod_0.nif which is located in the folder: <ultimate Skyrim install>\content\mods\UltSky 4.0.7 DynDOLOD\Meshes\lod\clutter\milllogpile_lod_0.nif 
Solution: Delete the file.

---	
## Crash to desktop near honneybrew meadary near whiterun.
Issue Caused by: Bad texture mesh in Skyrim flora overhaul.
Solution: Delete Content\Mods\Skyrim Flora Overhaul\Meshes\Landscape\Grass\vurt_greenyelplant.nif

---	
# Gameplay Questions

## Requiem Starting stats not being applied correctly.
Issue caused by Shipped “requiem for the indifferent.esp” Starting attributes are approx ¼ higher than they should be.
Solution: setup and run the reqtificator. instructions for how to do this in mod organiser are [here](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/FAQ.md#how-do-i-install-the-reqtificator). 
To access mod organiser (open <Ultimate Skyrim Install directory>\Content\Modorganiser.exe)	

---	
## Inn’s are charging the incorrect price(50g) Vs. what is listed in the MCM
Issue caused by: Patch not applied to the room rental cost
Solution
- Download UltSky - inn prices Fix from https://www.nexusmods.com/skyrim/mods/102978?tab=files to your download folder
- Open content\mod organiser.exe select the profile you plan on playing
- Select download tab on right side
- Find the mod in the list and right click > install
- Turn it on on the left side of the mod organizer.
- Select plugin tab on right side.
- Drag UltSky - inn prices Fix.esp  up from bottom of the list to position immediately below UltimateSkyrim.esp on the right pane
- Setup and run the reqtificator as per https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/FAQ.md#How-do-i-Install-the-Reqtificator
- In the Inns and Taverns MCM, change the default room cost to 10
 
A load order with this mod installed is located here for easy comparison https://loadorderlibrary.com/lists/ultsky-default-407-w-known-issues-fixes
---	
## Entering waist keep water unequips your weapons & other Misc Fixes

Issue Caused by Bathing in skyrim script not allowing user to disable removing weapons in the MCM. Patch has been made to remove the “unequip weapons” lines from the script.
 
Mod also fixes 
* Corrects Signy in Morthal being killed by Guards
* Prevents missives for carriage drivers and ferrymen which cannot be completed
* Corrects corundum ingot Breakdown recipes to give correct fragments
 
1) Download Ultsky Misc known issue fixes from https://www.nexusmods.com/skyrim/mods/107926?tab=files to your download folder
2) Open content\mod organiser.exe select the profile you plan on playing
3) Select download tab on right side
4) Find the mod in the list and right click > install
5) Turn it on from the left side of mod organizer.
6) Drag  Ultimate Skyrim - misc fixes.esp up from bottom of the list to position immediately below Ultimate Skyrim - Expanded cities and towns.esp on the right pane
7) Setup and run the reqtificator as per https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/FAQ.md#How-do-i-Install-the-Reqtificator
	
---	
## Several armours missing requiem resistances (Wolf Armor & Stahlrim Light/Heavy & Nordic Carved)
Issue caused by: Keywords for the DLC armors have to be manually added.
Solution
- Download US - Armor Resistances Fix from https://www.nexusmods.com/skyrim/mods/102978?tab=files to your download folder
- open content\mod organiser.exe select the profile you plan on playing
- select download tab on right side
- find the mod in the list and right click > install
- turn it on on the left side of the mod organizer.
- select plugin tab on right side.
- Drag US - Armor Resistances Fix.esp  up from bottom of the list to position immediately below UltimateSkyrim.esp on the right pane
- Setup and run the reqtificator as per https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/FAQ.md#How-do-i-Install-the-Reqtificator
	
A load order with this mod installed is located here for easy comparison https://loadorderlibrary.com/lists/ultsky-default-407-w-known-issues-fixes	
  
  
  
  
