---
layout: article
titles:
  # @start locale config
  en      : &EN       Initial Setup
  # @end locale config
key: page-initialnarrow
sidebar:
  nav: docs-en
aside:
  toc: true

---

## Introduction
The purpose of this **Basic Guide**{: .hili} is to tell you what mods are absolutely needed to play FROST, how to install them, and what you need to do to make a properly workign load order for FROST.

Installing this setup takes less then 5 minutes (without including Download Time).

This guide doesn't tell you how to install general Fallout 4 bug fixes related to engine problems!

## Some Assumptions and Requirements
* **MO2**{: .hili} or **Vortex**{: .hili} are installed to handle your mods for Fallout 4
* Only **one** mod manager manages Fallout 4 on your PC
* You know what a **load order** is and how to sort it
* Fallout 4 is **not** installed in the `Program Files` directory of Windows
* **Loose Files**{: .hili} are enabled (Vortex automatically does this, MO2 does not)
* You always start the game with **F4SE**{: .hili} through your mod manager
* You've used the **Simple Downgrader** mod tool to downgrade Fallout to **version 1.10.163**{: .hili}
* You've removed the Creation Club mods that are part of the Next-Gen Update
  * They are not patched for FROST, and need to be removed for lore, compatibility and balancing reasons
  * Open the  **Data**{: .hili} folder (`Steam\steamapps\common\Fallout 4\Data`{: .path}) in the Windows Explorer
  * Delete the following files from it:
    * `ccBGSFO4044-HellfirePowerArmor.esl`
    * `ccBGSFO4115-X02.esl`
    * `ccBGSFO4116-HeavyFlamer.esl`
    * `ccBGSFO4110-WS_Enclave.esl`
    * `ccBGSFO4096-AS_Enclave.esl`
    * `ccFSVFO4007-Halloween.esl`
    * `ccBGSFO4046-TesCan.esl`
    * `ccSBJFO4003-Grenade.esl`
    * `ccOTMFO4001-Remnants.esl`
* The following mods and their requirements are installed (mind the version numbers!)
  * **Fallout 4 Script Extender (F4SE) 0.6.23**
  * **xSE PluginPreloader 0.2.5.1**
  * **Buffout 4**
  * **Address Library**
  * **Mod Configuration Menu 1.39**
  * **Backported Archive2 Support System**
  * **PipBoy Tabs 1.10.163.0**
  * **Weapon Debris Crash Fix 1.2** (only if you have an NVIDIA GPU)


**You can not skip a single mod from the Basic Guide! Read everything carefully!**
{:.error}

## Mod Installation Advice

When the guide says to install a mod, it will be formatted as follows: **Main File - FROST (BA2 Version) 0.55**{: .hili}. This is referring to the mod's **category** on Nexus, the **file name**, and the **file version**.  I will leave the file version out in many cases, in that case just download the newest version of the mod. 

![Image of FROST Files Section](./assets/images/download_example_new.png "Image of FROST Files Section")
