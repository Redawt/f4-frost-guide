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


## About the Guide(s)
I have two guides for you. The recommended guide will carefully walk you through how to make a modern and stable Fallout 4 setup with a focus around FROST. The basic guide is a basic setup that only lists mods that you need to have to play FROST, but it won't walk you carefully through everything and it will not be a complete and modern setup, and it will have mor ebugs as non-FROST related bugs (= bugs from vanilla Fallout 4 etc.) will not be fixed. Both guides will give you a setup that can be enhanced by adding more mods.


### Recommended Guide
### Basic Guide
The Midnight Ride is a modding guide for Fallout 4 that will carefully walk you through how to install all the mods you will need for a perfectly stable, smooth, and most importantly, enjoyable experience. Unlike other modding guides, it is built with customization in mind. Mods are subjective, so every mod listed in the guide is 100% optional. Hand-made conflict resolution and load order will be provided at the end of the guide. The conflict resolution will be supplied in a fully-modular FOMOD installer, meaning that you can still use it even if you skip any mods.

The guide is highly accessible for everyone, no matter your modding experience. It is still incredibly important that you read all the instructions very carefully, even if you believe you are experienced enough to skip them. There are many small instructions that are vital for your game to function, and could be easily missed if you aren't careful. Although you don't need any modding experience to use this guide, it is expected for you to be relatively experienced with operating a computer in general.


### Additional Mods
A list of other recommended mods will also be provided, as well as suggestions on where to put them in your load order.


### Requirements

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
- CPU: Modern quad-core processor (2.75GHz or more)
- RAM: More then 8 GB of RAM (I recommend at least 16 GB)
- GPU: NVIDIA 900 series card or an AMD RX 400 series card


## Credits
- [The Midnight Ride Guide](https://themidnightride.github.io/index.html) which heavily inspired this guide. A lot of sections from my guide are identical to the Midnight Ride Guide. If you are planning to make a non-FROST Fallout 4 setup, you should use their guide.
- [u/Kanonking](https://www.reddit.com/user/Kanonking) for making the first proper FROST guide back in 2019 which inspired me and others to make our own guides
- [Argonn](https://www.nexusmods.com/fallout4/users/37574150?tab=user+files) for putting together a FROST Guide which was more comprehensible then previous guides
- [krrptd](https://www.nexusmods.com/fallout4/users/35409570) for providing his load order which inspired other FROST guides, and for making the FROST Cell Fixes
- [BSJ Prophet](https://www.nexusmods.com/fallout4/users/103241948) for making Frost Plus and for always helping me out
- [Naugrim04](https://www.nexusmods.com/fallout4/users/6324000) for creating FROST
- All of our users over at the FROST Discord