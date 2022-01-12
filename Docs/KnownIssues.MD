# Known Issues

This document will contain all of the Known gameplay related issues. It excludes any graphical issues, EG Clipping textures.

---

When will these be fixed?

There is a hotfix in the works to fix the major issues. Some of the more trivial issues will wait for the next build.

Some cannot be resolved by us and have been reported to the respective mod authors, and will need to wait for a update from them.

---
## Crash to desktop on save when using the BitDefender Antivirus.

1) this is a setting issue with Bitdefender
2) Bit defender cannot work with mod organiser
3) a) Easy solution - Turn off Advance Threat Defence when playing wildlander
   b) proper Solutions Add a ADT exception for Wildlander\game-files\Stock Game\SkyrimSE.exe

If you also have "Ransomware Remediation" on Add Wildlander\game-files\ModOrganizer.exe

---
## Crash to desktop on Entering a building
Generally caused by your Pagefile running out.

Bigger Skyrim modlists need a lot of memory, and when there is not enough available it may fail allocating more. To fix this, you'll want to have a bigger pagefile.

A pagefile is a file on your disk Windows will use when there is not enough RAM available.

Never disable the pagefile - this may lead to various issues on your system, such as this Skyrim crash.

If you've never touched the pagefile, try performing the following steps:
1. Press Windows + R on your keyboard and enter sysdm.cpl ,3
2. Under the Performance section, press 'Settings'
3. Go to the Advanced tab at the top, and at the Virtual memory section press 'Change...'
4. Disable 'Automatically manage paging file size for all drives'
5. a) If you have more than one drive, try enabling it for at least one more drive as a backup (make sure it has a decent bit of free space, like 15GB). Set the size to 'System managed size'.

   b) Otherwise, set a custom size for the drive it's currently on and increase the maximum size to be at least 20GB.

---
## Launcher issues
1) "Launcher locks and unlocks" - This is because you didn't install all the pre-requirements. Please make sure you download and install all 3 requirements from the before you begin section of the install section & are logged into the steam account which owns skyrim Special edition.
2) "Launcher shows a screen which says skyrim is running but its not - so i click the close skyrim button then get a error message". This message shows on the launcher as soon as you click the launcher button. The message says Skyrim is STARTING/running. on slower PC's it can take several minutes before the skyrim process actually starts. you should only hit the close skyrim button if skyrim is visible in your task manager, but not visible in windows.


---
## Character creation issues
1) Several of the presets have options you cannot remove, E.g facepaint, scars.
2) You cannot start as a Werewolf or Vampire
3) Several racemenu options are mislabeled.
4) the Sculpting options do not make any changes.
5) You cannot start as a none-dragonborn

---
## Gameplay Issues
- The Drink/Refill hotkey (;) often unbinds itself. To fix this, go into the SunHelm MCM and rebind the key. (Press T to clear it, then ; to rebind it.)
- All forms of nighteye do not work. With ENB, no changes are made, without ENB whole screen goes blue.
- Some crafting recipes requiring bottled water dont work. (Will be hotfixed)
- Using the crafting "empty bottle" creates a empty bottle object you cannot fill (Will be hotfixed)
- Using a controller on a lock is cauing the camera to fluff up
- Heartwood Mill Door Misplaced after entering (Will be hotfixed)
- Dodge perk is not working as intended when a controller is attached to the PC
- Keybinds may not work on "none-US keyboard" - Specifically drink key. a list of where you can go to rebind the keys is here https://docs.google.com/spreadsheets/d/10Clm3z8O9R0TlVlHdoLYHQ6FeMQiB0MA6iUkazfaxFA/preview
- Faralda doesn't show up to allow you to join ( Workaround #1:  Stand on the bridge where Faralda is supposed to be, and type these two commands in the console: "prid  1C1A5" and "moveto player".  This will teleport her to you, and should initiate the acceptance test.  Workaround #2:  Type the following in the console to get past the acceptance test:  "setstage MG01 30".  You should only use that if you've met the minimum skill requirements for continuity reason)
- Crash to Desktop when using a crossbow for the first time - The crossbow mod needs to initialise and cannot do this while in combat causing the CTD. When you get your crossbow - equip and unsheath it right away. (Will be hotfixed)

---
## Quest issues
- Several missives send you to characters who have scripted quests and cannot be completed unless you do their quests first.
- Missives send you to Cedric in Rorikstead (who is inaccessable) and the courior
- Hired muscle can send you to Cedric in Rorikstead (who is inaccessable) 
- I have "requiem for a better times" is stuck installing. This will not affect your gameplay - ignore it. (Will be hotfixed)
- Cannot progress Companions/Thieves guild despite meeting the requirements (Under investigation)

      - For ESF The requirements shown in the MCM do not reflect the requirements imported by dylan.
         1) Level 30 for 1 weapon skill
         2) Level 30 for 1 Armor Skill
         3) Minimum player level 10
         4) 10 radients
         5) 1 Radient for each circle member. Note: If you are not getting a radient from either Skjor or Vilkas. Turn the requirement on in the MCM, then turn it back off and do 1 more radient.

---
## Mod Issues.

### Outlaw Refuges. 
- Fences dont spawn as intended unless you create and load a save while inside the refuge
- The stores contain static items which cant be stolen
- Several beds have owned markers
- Several objects (e.g training dummies) are not interactable and should be

### Heljarchen Farm
- was removed at last minute as we were unable to correct the bugs within.

### Properties Without Pestering
- Hjerim is not available for purchase after completing "blood on the ice" until you are Thane.
- You need to be carrying the full price of the house(before 'thane' deductions), even after completing the 'thane' quest (E.G if a hourse costs 35,000 before deductions, this is how much gold you need to be carrying, even though the house now only costs 20,000)

### Wearable lanterns
This mod is "touchy" in SE and breaks easily. 

1) You cannot turn on and off the light using the "L" hotkey

Workaround: use the MCM to change its slot to 46(cloak slot), equip the lantern, requip your cloak, then change the lanterns slot back to 56.

2) You spawn a Carpet/Cookpot/Backpack instead of a light when using the "L" hotkey.

Workaround:  Drop the lantern and console yourself a new one then Follow the procedure for issue 1.

### Bathing
If bathing in very cold water, it can kill you before the animation finishes. 

Work around: dont take a bath in cold water ;)

---

## Immersion issues

### NPC's
1) Several NPC's are sleeping in unrealistic places. (e.g Orphans are found sleeping on the ground, in windhelm in the middle of a snowstorm not near a fire)
2) Gerda has incorrect voice for appearance.
3) Guards dont always use torches at night - and yet have perfect eyesight.
4) Companion NPC's have missing voice dialog.
5) Some vendors don't show a inventory/show limited inventory when you open them for the first time.
6) Wylandriah doesn't train Enchanting until after her quest
7) Some NPC's like idling inside of bushes or sitting on invisible chairs.
8) Milking a cow doesnt require a empty bottle and should.
9) There is a stubborn pig in windhelm which likes being in the way
   
### Objects / Buildings
1) Several wells are missing bucket activators
2) Imperial Alehouse in solitude is locked
3) Several Barrels, chests, woodpiles and herbs dont have ownership and should
4) Wooden chopping blocks - Wood doesnt align correctly on the block.
5) Training dummies outside of whiterun (on the battlements) cannot be interacted with
6) Rain effects on trees gives a off blue glow.
7) Aela's shield can be purchased before joining the companions and Vilkas's sword can be sold.
8) Breezehome upon purchase has loot in the safe's. In addition the fire is located in the wrong place.
9) the woodcutters axe in is invisible when equipped (Male Character)

### Sounds
1) Insect noise is overly loud.
2) Some interiors have ghost children playing sound effect.
3) Female Hungry/thirsty/sleep sounds play occasionally on male characters who have been gender switched

----

## Civil war
- It exists. 
- Its full of vanilla bugs.
- Several immersion breaking issues during battle for whiterun (vendors in market are trying to make a living, The carriage driver be vibing as explosions happen all around him)
- Lights within Korvanjund Hall beyond the sealed door are lit (should be dark)
