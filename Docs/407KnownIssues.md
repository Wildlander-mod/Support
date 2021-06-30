# Ultimate Skyrim FAQ - 4.0.7 Known Issues

<!-- TOC -->
[**ENB Questions**]
	-[When I enter a cell everything goes really Bright OR My Nightvision has a blue tint OR i get white-outs on a blizzard]
  -[Instincts is blindingly bright when looking at hanging moss (and other herbs)]
  -[Map is very foggy/unreadable]
  -[Weird Graphical Effect during certain weathers / times of day]
  -[Purple water/lakes at some times of the day]
[**Graphics Questions**]
  -[Twitching Piles of Lumber at lumber Mills]
  -[Crash to desktop near honneybrew meadary near whiterun.]
[**Gameplay Questions**]
  -[Requiem Starting stats not being applied correctly.]
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

##Requiem Starting stats not being applied correctly.
Issue caused by Shipped “requiem for the indifferent.esp” Starting attributes are approx ¼ higher than they should be.
Solution: setup and run the reqtificator. instructions for how to do this in mod organiser are [here](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/FAQ.md#how-do-i-install-the-reqtificator). 
To access mod organiser (open <Ultimate Skyrim Install directory>\Content\Modorganiser.exe)	

---	
##

---	
##

---	
##
  
  
  
  
