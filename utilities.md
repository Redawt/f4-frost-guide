---
layout: article
titles:
  # @start locale config
  en      : &EN       Utilities
  # @end locale config
key: page-utilities
sidebar:
  nav: docs-en
aside:
  toc: true

---



#### Make sure the **FROST** MO2 profile is active before proceeding!
The titles on this guide are also links that you can click on to get to the mods.
{: .info}


## [Fallout 4 Script Extender](https://f4se.silverlock.org/)

#### Description
* Extends the scripting capabilities of the game

#### Installation Instructions
  1. Click the topmost download link next to **Fallout 4 runtime 1.10.163 - build: 0.6.23**{: .hili}
  2. Extract the contents of the **f4se_0_06_23**{: .hili} folder from the downloaded archive to the game's Root folder
  3. Make sure you are extracting all of the files *inside* of the **f4se_0_06_23**{: .hili} folder, not just the folder itself. 

If you do not know what the Root folder is, read the Key Terminology section from the Initial Setup page.
{: .info}

If you did everything correctly, your **Root Folder**{: .hili} should look like this:

![F4SE in Root folder](./assets/images/root.webp "F4SE in Root folder")


In order for the script extender to work, you need to launch the game using the f4se_loader.exe file. It will automatically be added to Mod Organizer 2 upon restarting it. It should look like this:
{: .info}
![F4SE in MO2](./assets/images/select_f4se.png "F4SE in MO2")


## [xSE PluginPreloader](https://www.nexusmods.com/fallout4/mods/33946)

#### Description
- Allows F4SE plugins to be loaded before the game initializes

#### Installation Instructions
1. Download the **Main File - xSE PluginPreloader**{: .hili} using the **Manual Download**{: .hili} button
2. From the download archive, extract the two files to the game's **Root**{: .hili} folder



## [Address Library for F4SE Plugins](https://www.nexusmods.com/fallout4/mods/47327)

#### Description
- Resource required for other F4SE plugins

#### Installation Instructions
* **Main File - Address Library**

If you do not know what these instructions mean, or how to install mods with MO2, **read the Mod Installation Advice**{: .hili} section from the MO2 page again!
{: .info}


After installing with a mod with MO2, make sure you check the box next to it in the left pane of MO2 to enable it
{: .info}


## [Buffout 4](https://www.nexusmods.com/fallout4/mods/47359?tab=files)

#### Description
- Fixes numerous engine bugs and scripts, and also provides helpful crash logs when you game crashes.

#### Installation Instructions
  * Download and install the **Main File - Buffout**{: .hili} normally through MO2
  * If you encounter problems with Buffout 4, check out this [article](https://www.nexusmods.com/fallout4/articles/3115)

Without the [Microsoft VC++ 2015-2022](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) (x86 and x64 versions) which was mentioned in the requirements section of the guide, Buffout 4 and the xSE Preloader will not work properly. Make sure that you've installed it!
{: .info}


## [High FPS Physics Fix](https://www.nexusmods.com/fallout4/mods/44798)

#### Description
- Allows for playing at framerates over 60, mitigates stutter, and reduces load times

#### Installation Instructions
1. Download and install the **Main File - High FPS Physics Fix**{: .hili} normally through MO2
2. Once the mod has been installed, double-click on it in the left pane of MO2
3. In the **INI-Files**{: .hili} tab, select `F4SE/Plugins/HighFPSPhysicsFix.ini`{: .path}
4. Change the following options:
    - Set **DisableBlackLoadingScreens=**{: .hili} to **true**{: .hili} (line 37)
    - Set **DisableAnimationOnLoadingScreens=**{: .hili} to **true**{: .hili} (line 44)


**REMINDER**{: .hili}: You need to run the game through the F4SE option in Mod Organizer 2 from now on, NOT the Fallout 4 option. You may need to restart MO2 for the option to appear. If that is not the case, you can manually add or select it in MO2. 
{: .info}

![F4SE in MO2](./assets/images/select_f4se.png "F4SE in MO2")