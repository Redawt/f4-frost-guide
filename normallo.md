---
layout: article
titles:
  # @start locale config
  en      : &EN       Load Order
  # @end locale config
key: page-normallo
sidebar:
  nav: docs-en
aside:
  toc: true
nonext: true
---

#### This section tells you how to sort your load order. It contains rules for sorting your load order, an example load order, and an automatic load order checker at the bottom of the page! 

## Load Order

**Sorting your load order correctly is very important!**
**Do not skip this step, and read the sorting rules below carefully.**
**Please sort your modlist (the left panel of MO2) similar to the load order (right panel, "plugins" section) in MO2**
{: .warning}

You can sort your load order on the **right** panel of MO2 in the **plugins**{: .hili} section by moving the files with your mouse there. If you need further information, please read the [MO2 Sorting Crashcourse](https://github.com/sower-j/modding-guides/blob/main/mo2-sorting-crashcourse.md)!




## About LOOT
**LOOT**{: .hili} is a tool which automatically sorts load orders.
Its sorting rules are often outdated or do not exist at all when it comes to Fallout 4 mods, especially to FROST. I do not recommend to use it, as it often destroys FROST load orders based on outdated information. **It is not a reliable tool for sorting Fallout 4 load orders!**{: .hili}
LOOT is also not reliable as it doesn't know every plugin, so even if you want to use it, you will still have to sort stuff manually.

Before you start adding additional mods that are not mentioned in the guide, make sure to read the [compatability section](./compatability.html) of the guide! It lists which mods and mod types are problematic, and which are okay to use!
{: .warning}


## Check for Missing Masters
While you sort your load order in the plugins section of MO2, check if there are any Red Warning Triangles after the plugin names.
If that is the case, you didn't follow the guide correctly! The red triangle indicates that you forgot to install a requirement.
You can than hover over the plugin name with your mouse, and MO2 will display a small pop-up which tells you what master plugin is missing.

## How to structure your Load Order
The following rules show you how to structure your load order. 
Please use these rules to sort your load order. 
An example load order can be found below if you need an example on how it should look like in the end.
The rules indicate where to place your mods starting from the top of your load order down to the end of your load order.
Example: Rule 1 is about which mods need to be at the top of your load order, rule 2 is about which mods need to come after the mods of rule 1 etc.

There is also an **Automated Load Order Checker**{: .hili} below which can check if your load order has problems.

*Not all mods appear in the load order, as some don't have an esp/esl/esm plugin file.* 

*Mods like Buffout 4 won't appear in your load order for this reason.*

##### \[This is the start of the load order\]
{: .hili}

#### 1. Bethesda Files
{: .hili}
All Bethesda main files. Make sure that you don't have DLCUltraHighResolution.esm here.
- Fallout4.esm
- DLCRobot.esm
- DLCworkshop01.esm
- DLCCoast.esm
- DLCworkshop02.esm
- DLCworkshop03.esm
- DLCNukaWorld.esm


#### 2. Master files
{: .hili}
Put all .esm files and .esm flagged .esp files here 
- PANPC.esm
- HUDFramework.esm
- Unofficial Fallout 4 Patch.esp
- ...


#### 3. Frost Unrelated Mods I
{: .hili}

Put all mods that are unrelated to FROST and don't need a frost patch here.
Weather should not be placed here though, they need to be loaded later if possible.
* GCM_DLC_Automatron.esl
* GCM_DLC_Far_Harbor.esl
* GCM.esp
* SCM.esp
* Immersive HUD.esp
* M8rDisablePipboyEffects.esp (this is an optional plugin from FallUI Inventory)
* ...


#### 4. Frost Unrelated Mods II
{: .hili}

Put all mods here that need a patch for Frost. Load their frost patches at the section marked down below!. Mods that belong here are Lighting Mods, Weapon Mods, Armor Mods, Creature Mods, Mods that edit leveled lists, ...
* UltraInteriorLighting.esp
* UltraExteriorLighting.esp
* ...


#### 5. Frost Main Files
{: .hili}

The following four plugins must be in this exact order! 
- FROST.esp
- RedsFrostFixes.esp
- aFrostMod.esp
- FROST - UFO4P Patch.esp


#### 6. Other Frost Mods
{: .hili}
Put all other FROST standalone mods here
* RedsFrostBlurRemoval.esp (Optional File)
* RedsFrostExplosionEffects.esp (Optional File)
* FROST - It Snowed.esp
* Frost-Snowy-Weathers.esp
* FROST - LootableCars.esp
  * FROST_LLCars_Intermediate.esp (Optional File)
  * FROST_LLCars_Realistic.esp (Optional File)
  * FROST_LLCars_Scarcity.esp (Optional File)
* FROST - AccessibleMedTekResearch.esp
* FROST - AccessibleFortStrong.esp
* FROST - AccessibleArcJet.esp
* FROST - AccessibleFortHagen.esp
* FROST - SuperMutantLocations.esp
* FROST - Hunkered Down.esp
* FROST - Hunkered Down-Settlements.esp
* ...


#### 7. Frost Patches
{: .hili}
Put all mods here that patch a certain mod for FROST
* PANPC FROST Patch.esp
* RedsFrostCampsitePatch.esp
* RedsFrostSCM.esp
* ...

#### 8. Weather Mods
{: .hili}
Weather mods need to be loaded here.
Notes: 
- The Automatic Load Order checker below does not know which mods are weather mods, and therefore might complain. You can ignore the load order checker in such cases. Certain Weather mods are esm files and can't be loaded here. In that case they need to be loaded at the top of the load order (see rule 1), and require a patch for FROST that needs to be loaded here.
- NACX does not need a patch for FROST anymore and needs to be loaded at the top of the load order

#### 9. Frost Cell Fixes (FCF)
{: .hili}

No other files should come after the FCF .esp files, except very special mods.
Two exception to this rule are the Satellite Worldmap mod (SatelliteWorldMap.esp), and Item Sorter patches like Complex Sorter patches from xEdit. The two exceptions must be loaded after the FCF files.
If you don't follow these rules, bad things will happen!
The FCF_Main.esp and FCF_Previsibines.esp must come first, and in the same order as below. After those two plugins all other FCF plugins must be loaded.

- FCF_Main.esp
- FCF_Previsibines.esp
- (Additional FCF files for patching certain mods)
- ...

##### \[This is the end of the load order\]
{: .hili}



## Example Load Order
This load order contains all mods from the Recommended Guide.
Ultra Interior and Ultra Exterior Lighting were used as lighting mods in this example load order.
```
# This file was automatically generated by Mod Organizer.
Fallout4.esm
DLCRobot.esm
DLCworkshop01.esm
DLCCoast.esm
DLCworkshop02.esm
DLCworkshop03.esm
DLCNukaWorld.esm
PANPC.esm
HUDFramework.esm
Unofficial Fallout 4 Patch.esp
GCM_DLC_Automatron.esl
GCM_DLC_Far_Harbor.esl
GCM.esp
SCM.esp
Immersive HUD.esp
M8rDisablePipboyEffects.esp
UltraInteriorLighting.esp
UltraExteriorLighting.esp
Campsite.esp
FROST.esp
RedsFrostFixes.esp
aFrostMod.esp
FROST - UFO4P Patch.esp
FROST - It Snowed.esp
RedsFrostBlurRemoval.esp
RedsFrostExplosionEffects.esp
FROST - LootableCars.esp
FROST_LLCars_Scarcity.esp
FROST - AccessibleMedTekResearch.esp
FROST - AccessibleFortStrong.esp
FROST - AccessibleArcJet.esp
FROST - AccessibleFortHagen.esp
FROST - SuperMutantLocations.esp
FROST - Hunkered Down.esp
FROST - Hunkered Down-Settlements.esp
PANPC FROST Patch.esp
RedsFrostCampsitePatch.esp
RedsFrostSCM.esp
FCF_Main.esp
FCF_Previsibines.esp
```

## The Ending Of Things
That was the Recommended Guide. If you followed everything in this guide, you are ready to play FROST! 
Or you can add other mods to your setup, just make sure to use this Load Order page to put new mods into the right spot.
You can check out the next sections of this website for information about which mods are compatible with FROST, or which mods work well with FROST.
Consider joining the [FROST Community on Discord](https://discord.com/invite/BaKsm7Fn4A)!

You can now start Fallout 4 through F4SE, click "New Game" in the Main Menu, and play FROST. Note that currently the Fallout 4 Intro was not replaced yet by the FROST Development team, so don't be confused if you see it. Make sure to read this [starting](./starting.html) section which mentions how the start/intro from frost is supposed to happen, and which MCM options should be adjusted.
{: .info}

Before you start adding additional mods that are not mentioned in the guide, make sure to read the [compatability section](./compatability.html) of the guide! It lists which mods and mod types are problematic, and which are okay to use!
{: .warning}


{% include_relative lochecker.md %}
