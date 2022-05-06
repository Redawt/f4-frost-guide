---
layout: article
titles:
  # @start locale config
  en      : &EN       Introduction
  en-GB   : *EN
  en-US   : *EN
  en-CA   : *EN
  en-AU   : *EN
  zh-Hans : &ZH_HANS  
  zh      : *ZH_HANS
  zh-CN   : *ZH_HANS
  zh-SG   : *ZH_HANS
  zh-Hant : &ZH_HANT  
  zh-TW   : *ZH_HANT
  zh-HK   : *ZH_HANT
  ko      : &KO       
  ko-KR   : *KO
  fr      : &FR       
  fr-BE   : *FR
  fr-CA   : *FR
  fr-CH   : *FR
  fr-FR   : *FR
  fr-LU   : *FR
  # @end locale config
key: page-intro
sidebar:
  nav: docs-en
aside:
  toc: true

---


## Overview
Welcome to {{ site.title }}, a fully modular Fallout 4 FROST modding guide!

**IMPORTANT**: Everything in this guide is written down for a reason! It is vital to read everything! You can NOT skip any paragraphs/instructions and expect your game to function as it should. 
{:.warning}

This guide is still WIP, but it ios functional. It contains some TODOs, some spelling erros, the usual. This will be fixed soon, don't worry :D
{:.info}


## About the Guide(s)
I have two guides for you, the Recommended Guide and the Narrow Guide. Choose one!
Both are centered around MO2. Why not Vortex? You can find an answer to that question in the FAQ section.


### 1. Recommended Guide
The Recommended Guide will carefully walk you through how to install all the mods you will need for a perfectly stable and content-rich, and most importanly, enjoyable experience. Unlike other modding guides, it is built with customization in mind, and will detail were you can add additional mod that you found and downloaded. Certain mods in the guide are optional, but most of them can not be skipped!
The guide is highly accessible for everyone, no matter your modding experience. It is still incredibly important that you read all the instructions very carefully, even if you believe you are experienced enough to skip them. There are many small instructions that are vital for your game to function, and could be easily missed if you aren't careful. Although you don't need any modding experience to use this guide, it is expected for you to be relatively experienced with operating a computer in general.

**Important Notes:**
* Optional mods are flagged with **\*O** in their title.
* Mods that can only be found on a Discord Server are flagged with a **\*D** in their title.
* Mods that need a patch for frost are marked with **\*F**
* All Discord mods mentioned in the guide are entirely optional
* The end of the guide will give you an example load order and instructions for where you should mods that are not mentioned in the guide.


### 2. Basic Guide
This guide shows you the most basic and bare-bones setup that you can have for FROST. It doesn't get any smaller then that.
It only focuses on the must-use/must-have mods for FROST in order to get all of the main content of the current official Frost Development team, including the most important bug fixes and performance improvements.
I recommend this guide for people who are either too lazy to make a proper mod setup, or who only want to try out FROST.
If you have not much modding knowledge, please use the recommended guide!
Unlike the Recommended Guide, it will not mention ANY mods that fix engine bugs or vanilla Fallout 4 bugs. 
It will also give you an example load order and tell you how to structure your load order.
And overview on where mods that you want to use should be placed in the load order is also given. 


### Additional Mods
A lst of other recommended mods will also be provided, as well as suggestions on where to put them in your load order.
It will also mention which mods you should NEVER use with FROST at all.
Certain mods are either incompatible with FROST by default (liek Horizon), or are outdated, or are simply badly made and will cause more harm then good.


## Requirements

- An English copy of the game with all DLCs from Steam (instructions for properly installing it are in the next step)
  - Only the English version of the game is supported for maximum compatibility.
  - The Bethesda.net and Xbox Game Pass versions of the game are also unsupported, as they do not work with F4SE which is essential for many mods.
- At least 37.5 GB of free drive space
- Windows 7 or higher (64bit)
- [Microsoft VC++ 2015-2022](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) (x86 and x64 versions)
- A text editor (I recommend Notepad++ or Visual Studio Code, but the default Windows notepad will work)
- An archiving tool (I recommend [7-Zip](https://www.7-zip.org/))
- The latest GPU drivers (Either NVIDIA or AMD)
- A [Nexus Mods](https://users.nexusmods.com/register) account
- A [Discord](https://discord.com/) Account (*optional*)
  - During the "Nexodus", many mod authors removed their mods from Nexusmods and are now hosting them on a Discord Server
  - All mods from Discord will be optional in this guide


## Recommended Specs
The guide will make the game run better than vanilla. The game is pretty un-optimized, especially in downtown Boston, so FPS will never be extraordinary. However, the guide will ensure that your FPS is as high as possible in these areas. The game is much more CPU-intensive than GPU-intensive. Installing the game on an SSD can drastically improve load times and decrease stuttering. Here are the (minimal) recommended specs for being able to run the guide at 60FPS in 1080p:
- **CPU:** Modern quad-core processor (2.75GHz or more)
- **RAM:** 16 GB of RAM
- **GPU:** NVIDIA 900 series card or an AMD RX 400 series card


## Choose your guide!
\
[![Basic Guide](./assets/images/basic_guide.png)](./initialsetupnarrow){: .center-image}
\
\
[![Recommended Guide](./assets/images/recommended_guide.png)](./initialsetup){: .center-image}



## Credits
- [The Midnight Ride Guide](https://themidnightride.github.io/index.html) which heavily inspired this guide. A lot of sections from my guide are identical to the Midnight Ride Guide. If you are planning to make a non-FROST Fallout 4 setup, you should use their guide.
- [u/Kanonking](https://www.reddit.com/user/Kanonking) for making the first proper FROST guide back in 2019 which inspired me and others to make our own guides
- [Argonn](https://www.nexusmods.com/fallout4/users/37574150?tab=user+files) for putting together a FROST Guide which was more comprehensible then previous guides
- [krrptd](https://www.nexusmods.com/fallout4/users/35409570) for providing his load order which inspired other FROST guides, and for making the FROST Cell Fixes
- [BSJ Prophet](https://www.nexusmods.com/fallout4/users/103241948) for making Frost Plus and for always helping me out
- [Naugrim04](https://www.nexusmods.com/fallout4/users/6324000) for creating FROST
- All of our users over at the FROST Discord