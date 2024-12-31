---
layout: article
titles:
  # @start locale config
  en      : &EN       Initial Setup
  # @end locale config
key: page-initialsetup
sidebar:
  nav: docs-en
aside:
  toc: true

---

#### In this step, we will do a clean installation and configuration of the game, which is required for the guide.

If you run into any issues at any point in the guide, feel free to ask for help on our [Discord Server](https://discord.com/invite/BaKsm7Fn4A) in the **#bugs-and-support** channel.
{:.info}

## Enabling File Extensions
By default, Windows Explorer will not show file extensions (such as .exe, .dll, or .esp). These extensions are very important when going through the guide, so it is highly recommended to enable file extensions:

1. Open Windows Explorer
2. Select the **View**{: .hili} tab at the top
3. Check the box next to **File name extensions**{: .hili}

## Making a Clean Install of Fallout 4

### Uninstalling the Game

  1. Open Steam and go to your **Library**{: .hili}
  2. Find **Fallout 4**{: .hili} in the list
  3. Right-click on it and select **Manage -> Uninstall**{: .hili}
  4. Navigate to `Steam\steamapps\common\`{: .path} and, if present, delete the **Fallout 4**{: .hili} folder
  5. Navigate to `Documents\My Games`{: .path} and delete the **Fallout4**{: .hili} folder
  6. Navigate to `AppData\Local`{: .path} and delete the Fallout4 folder

  * **Note for GOG users**: The same steps apply for your, except that your installation folder in step 4 is different.

Do not install your game in the **Program Files** folder. Program Files is a special Windows System folder, and MO2 doesn't load mods correctly if it is in that folder.
{:.error}

### Making a new Steam library
It is strongly recommended to install the games outside of any default Windows folders (such as Program Files (x86)), as the the strict Windows file protections of these folders can break certain mods/tools. Instead, we will use a tool called Steam Library Setup Tool to create a new Steam library folder outside of any default Windows folders.

If you already have Steam installed outside of any default windows folders then go directly to step 1 of the next section and install the games to your custom Steam library. 

1. Completely exit out of Steam using Task Manager or System Tray.
2. Download the **steam_library_setup_tool-3.2.exe**{: .hili} file from [here](https://github.com/LostDragonist/steam-library-setup-tool/releases).
3. Once downloaded, run the file and add a new entry by clicking **Add Row**{: .hili}.
4. Type the chosen path under **Path**{: .hili}, e.g. `C:\Games\Steam`
5. Click **Accept**{: .hili} then **Yes**{: .hili} if prompted to create a new folder.
6. The tool will ask to exit, select **OK**{: .hili}.

![Steam Library Tool Setup](./assets/images/Steam Library Tool Setup.webp)

### Installing the Game
  1. Open Steam and go to your **Library**{: .hili}
  2. Find **Fallout 4**{: .hili} in the list and select **Install**
  3. Under **Install to**{: .hili}:, select the library folder created with the tool, which is the second `C:\` entry if you are installing on the main drive. If you already had another steam library (for example on an external drive), you can chose that one instead.

Make sure to install the English version of Fallout 4 for maximum immersion.
If you do not use the English version, the intro video which is shown when starting a new game might not have audio.

**Note for GOG users**: Do the equivalent steps via GOG. GOG usually installs games outside of the **Program Files** folder by default.

### Disabling Automatic Steam Updates (Steam only)

This will prevent Steam from automatically installing Fallout 4 updates, which will break modding support considerably until they gain wide modding support (and the guide's).

- In your Steam Library, right-click on Fallout 4, and click on Properties in the resulting context menu,
- In the resulting new window, click on the drop-down at the top of the right pane underneath Automatic Updates
- Set it to Only update this game when I launch it.

Since MO2 bypasses Steam's "play" button, Fallout 4 will never automatically update because you will launch the game through MO2.

## Post-Installation
### Key Terminology
Now that the game is installed, there are two folders from it that will be referred to in the guide often:

  - **Root**{: .hili} folder (where the game is installed): `Steam\steamapps\common\Fallout 4`{: .path}

  - **Data**{: .hili} folder (where all of the game's assets are located): `Steam\steamapps\common\Fallout 4\Data`{: .path}




### Generating Fresh .INI Files

1. Run **Fallout4Launcher.exe**{: .hili} from the game's Root folder
    - If you do not know what the game's **Root**{: .hili} folder is, read the [Key Terminology](https://redawt.github.io/f4-frost-guide/initialsetup#key-terminology) section above
3. Click OK to both pop-ups that say **Detecting Video Hardware**{: .hili}
    - If there aren't any pop-ups, navigate to `Documents\My Games\Fallout4`{: .path} and delete all the files ending in **.INI**{: .hili} then retry
5. Select **Options**{: .hili} then select the **High**{: .hili} preset option
    - The high preset is used over the ultra preset because the ultra preset has options that can severely tank FPS without much visual improvement. You can choose a lower preset if you have a lower-end PC, or want to squeeze as much performance out of the game as possible.
7. Click **OK**{: .hili} then **Exit**{: .hili}


### Disabling the [High Resolution Texture Pack/DLC](https://fallout.fandom.com/wiki/High_Resolution_Texture_Pack) from Bethesda
When you installed the game again, it might be possible that you accidently installed the **High Resolution Texture Pack/DLC**{: .hili} from Bethesda. This DLC takes is not very well made. It barely makes the game look better, it decreases performance, it isn't optimised very well, and it causes several bugs. I don't recommend to use it, especially as texture mods from mod authors look a lot better.
If you accidently installed it, here is are instructions on how to use uninstall it:
* Go to your Steam Library by clicking "Library" at the top
* Click on **Fallout 4**{: .hili}
* Click on **Support**{: .hili} to the right of Fallout 4
* Scroll to the bottom, if you have the season pass or a lot of dlc, click **Show all DLC**{: .hili}
* Click on **High Resolution Texture Pack**{: .hili}
* Click on "I want to remove this permanently from my game library"
* **!!! Make sure it says High Resolution Texture Pack at the top, or you'll remove the entire game with no refund !!!**{: .hili}
* Click **OK**

 **Note for GOG users**: Do the equivalent steps via GOG, unless the High Resolution Texture Pack was not downloaded.
