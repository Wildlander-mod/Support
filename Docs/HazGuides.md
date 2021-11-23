## **Installing Wintersun - Faiths of Skyrim with Seg's patch**

Even if you are familiar with[ Wintersun](https://www.nexusmods.com/skyrim/mods/95545?tab=description), do check out the changes in[ Seg's Requiem patch](https://www.nexusmods.com/skyrim/mods/95859?tab=description) used here. Some of the tweaks are significant.

About the Ult Sky patch:

* _Forwarded all relevant scripts from "Book Covers Skyrim" book records. Retained book models and inventory art from "Book Covers Skyrim" mod._
* _Fixed a minor error in Stendarr's Fortify Block effect._
* _Arkay's Chalice of Life restoration effect now works as intended. Requiem's "No Natural Regen" permanent spell was blocking it._
* _Forwarded the appropriate quest activators that unlock the various daedric blessings._
* _Applied quest journal logs from "Even Better Quest Objectives" mod._
* _Resolved a script conflict with "House of Horrors Alternate Ending" mod._
* _Fixed a few invalid references in Seg's patch (it was made for an older version of Wintersun)._
* _Resolved a few magic effect conflicts related to blessings, and a couple of quest conflicts with "The Choice is Yours" mod._

To install:

1. Download and install[ Wintersun 3.1.5](https://www.nexusmods.com/skyrim/mods/95545?tab=files) with MO2. Load the esp plugin anywhere between _Book Covers Skyrim.esp_ and _Requiem.esp._ On the screenshot below it is right before _Requiem.esp_. Mod position on the left side of MO does not matter (end of the mod list is fine).
2. Download and install[ Wintersun - Requiem patch (v1.4)](https://www.nexusmods.com/skyrim/mods/95859?tab=files) from Segolia94's patch collection. Load the esp between _Ultimate Skyrim.esp_ and _Requiem for the Indifferent.esp_.
3. Install [Wintersun 3.1.5 - Seg 1.4 - Ultsky 407](https://drive.google.com/file/d/1hP53c8KQQz4plQGNl-qlLSpMnYFRVy0d/view?usp=sharing) On the left side of MO2 keep this patch **after** Wintersun mod and Seg's patch. On the right side of MO load the esp **after** Seg's patch and also **after** _Ultimate Skyrim - Book Covers Skyrim.esp_ **_._** You can place both patches there, as shown on the screenshot below.
4. Run the [Reqtificator](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/FAQ.md#reqtificator-questions). Done.

_Note: If you are a Sanguine worshipper, and you are also using SNBCJ's "Requiem - Classic Food and Drink (R-CFD)" mod, make sure to load the Wintersun patches after the R-CFD patch, so that you'll get the correct effect from alcohol which boosts favor with Sanguine the more you drink._

*_Installing over an existing save:_

_Starting a new game is always the safest option when installing scripted mods. From my limited testing it seems to work fine when installed mid-game. Just make sure to let any active blessings expire before installing._


Left side

![Left Side](https://cdn.discordapp.com/attachments/852619952845750302/912837141875294258/unknown.png)

Right side

![Right Side Requiem](https://cdn.discordapp.com/attachments/852619952845750302/912837731317596170/unknown.png)

![Right Side Bottom](https://cdn.discordapp.com/attachments/852619952845750302/912837845205520464/unknown.png)

----


## **Installing Andromeda - Unique Standing Stones of Skyrim**

This[ standing stone overhaul](https://www.nexusmods.com/skyrim/mods/89219?tab=description) allows for some very interesting play styles. It is pretty much compatible out of the box, with one minor exception pertaining to the Undeath mod (optional patch posted). I haven't changed anything in terms of balance because nothing strikes me as balance-breaking at first glance (_EDIT: see comments below_), but I've only just started using the mod. Do leave some feedback if you think something needs tweaking.

As in base Requiem, once you choose a standing stone, you can only switch to other stones within the[ same group](https://www.reddit.com/r/skyrimrequiem/wiki/standing_stones#wiki_standing_stones_of_requiem_.28v_3.0.29).

To install:

1. Download and install[ Andromeda 1.0.9](https://www.nexusmods.com/skyrim/mods/89219?tab=files) with MO2. Load the esp **after** _Ultimate Skyrim.esp_ on the right side of MO.
2. Download and install[ Andromeda 1.0.9 - Ultsky 4.0.7 MCM Descriptions](https://mega.nz/file/aVsl0YJa#6yaVKCFutL85qcqChc668d7udVCu8ASKO5YT9KhTBQU) to update the descriptions in the Ult Sky MCM. No plugin here, just a text file. On the left side of MO keep this patch **after** _Ultimate Skyrim_ mod.
3. [Optional] Install the patch[ Andromeda - Undeath Ritual Stone patch](https://drive.google.com/open?id=141SgIO7hjle7Y2j-YHv2-edYak74AROS) if you intend to play the Undeath quest line. Load the plugin **after** _Andromeda - Unique Standing Stones of Skyrim.esp_ on the right side.
4. Run the [Reqtificator](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/FAQ.md#reqtificator-questions). Done.



![alt_text](https://cdn.discordapp.com/attachments/852619952845750302/912840754131517450/unknown.png "image_tooltip")


_Installing_ _on an existing save:_

If you install this mod mid-game, the standing stones in Skyrim will be updated, but your currently active abilities may not be updated automatically. To reset your active powers after installing the mod, travel to a different standing stone in the[ same group](https://www.reddit.com/r/skyrimrequiem/wiki/standing_stones#wiki_standing_stones_of_requiem_.28v_3.0.29) and activate it. Then travel back to your original standing stone and re-activate it. See the stone locations[ here](https://en.uesp.net/wiki/Skyrim:Standing_Stone). (To speed up the process you can use 'coc' in the console to teleport to each standing stone. The "Console Location Code" is listed on the individual standing stone pages).

-----

## **Installing Sacrosanct - Vampires of Skyrim with Seg's patch**

Refer to the[ Sacrosanct](https://www.nexusmods.com/skyrim/mods/80159?tab=description) page for mod features, and also see the change log for[ Segolia94's Sacrosanct-Requiem Patch v1.2](https://www.nexusmods.com/skyrim/mods/95859?tab=description) which tweaks a few minor aspects of the mod for better synergy with Requiem.

This is a tweaked version of Seg's patch, uploaded with permission.

**Changes**:

- Fixed a bug in **Vampiric Drain** spell (Seg's patch) where the spell magnitude did not scale properly with hunger stages, i.e. it stayed at a constant 5 HP/sec at every stage. Now the drain spell has correct magnitude of **5/10/15/20 HP/sec** (stages 1-4). This is half as strong as the Requiem spell, with reversed progression. If you want the spell to be strongest at stage 1 and weakest at stage 4 as it is in Requiem, enable "Reverse Progression" in the Sacrosanct MCM.

- Fixed a condition error in Vampiric Drain stage 3 (Seg's patch).

- Tweak: **Weakness to Fire** is brought back to Sacrosanct levels: -**20%/-30%/-40%/-50%** (stages 1-4), instead of Requiem levels (-75%/-85%/-100%/-150%). This seems appropriate since the vampire character no longer receives the insanely strong +300 HP/SP buff from Requiem, but instead only **+50 HP/SP** buff.

- **Frost Resistance** remains unchanged: **+50%/+40%/+30%/+20%** (stages 1-4)

To install:


1. Download and install[ Sacrosanct v5.15](https://www.nexusmods.com/skyrim/mods/80159?tab=files) using MO2. On the left side keep the mod after Ultimate Skyrim mod (end of the mod list is fine). On the right side load _Sacrosanct - Vampires of Skyrim.esp_ anywhere **between** _Ultimate Skyrim.esp_ and _Warburg's 3D Paper World Map_.
2. Download and install[ Requiem 3.x - SCS 5.15 - RaceCompat 1.107 Patch](https://drive.google.com/file/d/1eSqCffbxL2BKPc7auVkS8bsPhcQwwLsS/view?usp=sharing) and place it after Sacrosanct mod on the left side of MO. Load the esp plugin **after** _Sacrosanct - Vampires of Skyrim.esp_ on the right. _[Note: Load both esp's_ **_after_** _SNBCJ's mods and patches if you have any of them installed (e.g. Classic Food and Drink or Immersive Divine Blessings).]_
3. Run the [Reqtificator](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/FAQ.md#reqtificator-questions). Done.

Load Order: Left and right side of MO2 shown below.

MO2 Left side

![alt_text](https://cdn.discordapp.com/attachments/852619952845750302/912845242577879090/unknown.png "image_tooltip")


MO2 Right side

![image](https://user-images.githubusercontent.com/26418143/143144446-16e0bc5a-4ece-411a-90dc-fb47f47b41a6.png) 


MCM settings:



* **Allow regeneration in Shadows:** I always enable this option because it allows for some interesting RP and combat strategies when engaging enemies outside during the day, when my stats are debuffed due to sunlight. Hide behind any object that blocks direct sunlight to regain stat regeneration. Cloudy weather works too.
* **Trespassing Curse: Disable -** The 'curse', which is active by default, drains your magicka and stamina as soon as you enter someone's property illegally. I disable it because that never made sense to me.
* **Fortitude: Disable** - The Fortitude ability is a bit OP so I disable it. It auto-resurrects you when you die in Sated state, and then makes you Thirsty. It has no cooldown and can be easily exploited for infinite lives, if you harvest enough blood potions and keep yourself Sated at all times. It's also a bit redundant since you also have the Blood Cauldron active power, which fully restores all 3 stats and is much more fun to use.
* **Vampiric Drain: Enable Reverse Progression** - by default, the Vampiric Drain spell grows in magnitude the hungrier you become, i.e. it is the weakest when you are Sated (5 HP/sec), and strongest when you are Blood Starved (20 HP/sec). If you prefer Requiem's reverse progression (strongest when sated, weakest when starved), enable this setting.



![image](https://user-images.githubusercontent.com/26418143/143144487-6a9bd99a-4fac-41ca-b852-c0ffc177adc2.png)


*_Installing on an existing save:_

_A_ _new game_ _is always recommended with any scripted mod. Having said that, I have not encountered any issues after installing and loading my old template save. I was able to use the vampiric powers right away, including feeding, draining, Vampire's Command / Seduction / Sight / Will._


-----


## **Installing SNBCJ's mods: Immersive Divine Blessings, Immersive Abilities, Standing Stone Rebalance**

_A big Thank You to SNBCJ for his great work!_

**_List of tested mods. (Make sure to download the exact version)_**



* _Requiem - Immersive Divine Blessings (R-IDB) 1.31 .........**[updated for US 406 HF2]**_
* _Requiem - Immersive Abilities (R-IA) 8.0 ............................**[old patch works with US 406 HF2]**_
* _Requiem - Standing Stone Rebalance (R-SSR) 3.6 .............**[mod works with US 406 HF2]**_
* _Requiem - Classic Alchemy Overhaul (R-CAO) 6.2 .............**[updated for US 406 HF2]**_
* _Requiem - Classic Food and Drink (R-CFD) 3.3 ...................**[updated for US 406 HF2]**_


### Requiem - Immersive Divine Blessings (R-IDB) v1.31

**_Note: Aside from blessings, the mod also tweaks certain items and gear, so I recommend taking some time to read through the[ Nexus page](https://www.nexusmods.com/skyrim/mods/90691) to learn about the changes. A notable example is the Necromancer's Amulet - the mod raises the minimum magicka requirement to equip it from 150 to 300 base magicka._**

_Also , the mod comes with[ Requiem - Werewolf and Vampire Rebalance (W&VR)](https://www.nexusmods.com/skyrim/mods/87420) fully integrated, which changes vampire / werewolf stats. If you are going to play as one of those races, you may want to read that mod page._

_If you want to use R-IDB with **Sacrosanct**, load the Sacrosanct mod and patch plugins after IDB patch plugin._

_About the 4.0.6 HF2 patch._

_All the blessings from the mod description remain intact. IDB also tweaks some gear and items that are meant to synergize with the various blessings. Those are also intact, except I mostly kept Ult Sky's item names, value and weight stats, in order to preserve the balance of the economy. The Akatosh blessing was tweaked to account for the fact that Skyrim Unbound skips the first few quests in the Main Quest sequence. It should apply the appropriate effects as though those quests were properly completed._

_To install:_



1. _Download and install the main file[ Requiem - Immersive Divine Blessings 1.31](https://www.nexusmods.com/skyrim/mods/90691?tab=files) using MO2. On the right side of MO the plugin should be loaded **between** Requiem.esp and Ultimate Skyrim.esp (screenshot below). On the left side of MO, R-IDB should override Requiem 3.0.x to win any file conflicts. It's fine to leave it at the end of the mod list._
2. _Download the patch archive ([R-IDB 1.31 UltSky 406HF2 patch](https://drive.google.com/open?id=1vZRbFBXgjlJ-2GvkUcNiqhf3y0guDmM8)) and install in MO2. On the right side move the plugin **between** Ultimate Skyrim.esp and Automatic Variants.esp. If you don't have AV installed, the plugin can be loaded anywhere between Ultimate Skyrim.esp and Requiem for the Indifferent.esp. Mod order on the left side is not important._
3. _Run the [Automatic Variants](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/Patchers.md#automatic-variants)  patcher.
4. _Run the [Reqtificator](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/FAQ.md#reqtificator-questions). Done. (**Note: Remember to re-run both patchers if you remove IDB from your load order later on.**)_


_*Installing **R-IDB** on an existing save: All shrines and amulets should work right off the bat, but make sure to clear any active effects from old blessings._


### Requiem - Immersive Abilities (R-IA) v8.0

**_[The patch for R-IA v1.6 works with R-IA v8.0 and US 4.0.6 HF2]_**

_[Requiem - Immersive Abilities](https://www.nexusmods.com/skyrim/mods/96880) fixes a few balance issues with the races in base Requiem. For example, the Altmer's extreme 40% weakness to Magic is replaced with 25% weakness to Fire, Frost, and Shock, which makes it a more viable option. Read about all the changed on the mod page._

_About the patch: The one significant change in the patch is the addition of the "IsAdultRace" keyword from the Immersive Children mod, which is required in all race records. Also, the patch contains the changes from "Requiem - IA Chasing the Dragon Plus patch 1.2"[ provided by SNBCJ](https://www.nexusmods.com/skyrim/mods/96880?tab=files) for Requiem 3.X compatibility, so there is no need to install that file._

_To install:_



1. _Download and install[ Requiem - Immersive Abilities 8.0](https://www.nexusmods.com/skyrim/mods/96880?tab=files) (**main file only!**). Mod placement on the left side of MO2 doesn't matter. On the right side place Requiem - Immersive Abilities.esp **between** Ultimate Skyrim.esp and Requiem for the Indifferent.esp._
2. _Install[ R-IA 1.6 UltSky 406 HF2 patch](https://drive.google.com/file/d/1G6MP_qGJnUUKoLrzR3_BizkcelddyWWx/view?usp=sharing) (works with R-IA v8.0) and load the esp anywhere **between** Requiem - Immersive Abilities.esp and Requiem for the Indifferent.esp. (Note: this patch contains the file "Requiem - IA Chasing the Dragon Plus patch 1.2" needed for Requiem 3.X compatibility on the Nexus downloads page, so there is no need to install that file.)_
3. _Run the [Reqtificator](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/FAQ.md#reqtificator-questions)._

_*Installing **R-IA** mid-game is not recommended._

### Requiem - Standing Stone Rebalance (R-SSR) v3.6

**_[Mod works with US 4.0.6 HF2 out of the box]_**

_[Requiem - Standing Stone Rebalance](https://www.nexusmods.com/skyrim/mods/88988) works out of the box (no patching needed), since no other mods in Ult Sky change the standing stone abilities._

_To install:_



1. _Download the main file[ Requiem - Standing Stone Rebalance 3.6](https://www.nexusmods.com/skyrim/mods/88988?tab=files) using MO2, and install. Mod order (left side of MO) doesn't matter. On the right side, place the esp plugin **between** Ultimate Skyrim.esp and Requiem for the Indifferent.esp._
2. _[Optional] Download and install[ UltSky 4.x R-SSR MCM Standing Stone Info](https://mega.nz/file/vU8TiALY#3Xx6BdDhvI58gEsp8UWNlKXconHaXAJYq3vD2GdRclk) to update the stone descriptions in the Ult Sky MCM. This is only useful at the start of a new game. No esp plugin here, just a text file. Place it **after** Ultimate Skyrim mod on the left side of MO2._
3. _Run the [Reqtificator](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/FAQ.md#reqtificator-questions)._

_*Installing **R-SSR** on an existing save:_

_If you install R-SSR mid-game, the standing stones will be updated, but the player's active stone abilities will not be updated automatically and they need to be reset. To reset your character's active powers, travel to a different standing stone in the[ same group](https://www.reddit.com/r/skyrimrequiem/wiki/standing_stones#wiki_standing_stones_of_requiem_.28v_3.0.29) and activate it. Then travel back to your original standing stone and re-activate it. See the stone locations[ here](https://en.uesp.net/wiki/Skyrim:Standing_Stone). (To speed up the process you can use 'coc' in the console to teleport to each standing stone. The "Console Location Code" is listed on the individual standing stone pages)._


### Requiem - Classic Alchemy Overhaul (R-CAO) v6.2

**_[updated for US 4.0.6 HF2]_**

_Refer to this[ README](https://drive.google.com/open?id=1mlSyUApSt5DqrgsTh_1VWJicr55u_MZR) to find out what my patch does exactly._

_To install:_



1. _Download[ Requiem - Classic Alchemy Overhaul 6.2](https://www.nexusmods.com/skyrim/mods/86504?tab=files) and install with MO2. On the right side of MO move the esp plugin anywhere **between** Ultimate Skyrim.esp and Requiem for the Indifferent.esp. Left side of MO doesn't matter (end of the mod list is fine)._
2. _Download the patch[ R-CAO 6.2 UltSky 4.0.6 HF2 patch v2](https://drive.google.com/open?id=15ZPY7eBkEPNt_PbNaoJTpaMFuoI03tLA) and install. Move the the patch esp **between** Requiem - Classic Alchemy Overhaul.esp and Requiem for the Indifferent.esp. Left side of MO doesn't matter._
3. _Run the [Reqtificator](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/FAQ.md#reqtificator-questions). Done._

_*Installing **R-AR** on an existing save:_

_It seems to work fine when installed mid-game. Note that the mod tweaks the Alchemy tree, so if you've already acquired some of the base Requiem Alchemy perks, you may need to remove and reapply them using[ console commands](https://elderscrolls.fandom.com/wiki/Console_Commands_(Skyrim)/Perks), to get the new stats. Users have confirmed this worked for them._


### Requiem - Classic Food and Drink (R-CFD) v3.3

**_[Updated for US 4.0.6 HF2]_**

_See[ here](https://drive.google.com/open?id=1Z7YnyFrsed8YTw_aD0EwKWfURPdpp6t4) what the patch does._

_To install:_



1. _Download and install[ Requiem - Classic Food and Drink (R-CFD) 3.3](https://www.nexusmods.com/skyrim/mods/90714?tab=files). On the right side of MO load the plugin **after** Ultimate Skyrim - Expanded Towns and Cities.esp. Mod order on the left side of MO does not matter._
2. _Install the patch[ R-CFD 3.3 UltSky 406 HF2 patch](https://drive.google.com/open?id=1EvaHyIVUaKqkZE_HqC3_u9t3AKfX1hoa) and load the esp **after** Requiem - Classic Food and Drink.esp. If you are also using Wintersun or Sacrosanct mods, make sure to load their patches after the R-CFD patch._
3. _Run the [Reqtificator](https://github.com/phinocio/UltimateSkyrim/blob/master/Docs/FAQ.md#reqtificator-questions)._

_*Installing mid-playthrough should be safe._

