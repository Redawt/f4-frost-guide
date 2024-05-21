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


## Making a Clean Install of Fallout 4

### Uninstalling the Game

  1. Open Steam and go to your **Library**{: .hili}
  2. Find **Fallout 4**{: .hili} in the list
  3. Right-click on it and select **Manage -> Uninstall**{: .hili}
  4. Navigate to `Steam\steamapps\common\`{: .path} and, if present, delete the **Fallout 4**{: .hili} folder
  5. Navigate to `Documents\My Games`{: .path} and delete the **Fallout4**{: .hili} folder
  6. Navigate to `AppData\Local`{: .path} and delete the Fallout4 folder

Do not install your game in the **Program Files** folder. Program Files is a special Windows System folder, and MO2 doesn't load mods correctly if it is in that folder.
{:.error}

### Installing the Game
  1. Open Steam and go to your **Library**{: .hili}
  2. Find **Fallout 4**{: .hili} in the list and select **Install**
  3. Select **Next**{: .hili} then wait for the install to finish

Make sure to install the English version of Fallout 4 for maximum immersion.
If you do not use the English version, the intro video which is shown when starting a new game might not have audio.

### Disabling Automatic Steam Updates

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


### Enabling File Extensions
By default, Windows Explorer will not show file extensions (such as .exe, .dll, or .esp). These extensions are very important when going through the guide, so it is highly recommended to enable file extensions:

1. Open Windows Explorer
2. Select the **View**{: .hili} tab at the top
3. Check the box next to **File name extensions**{: .hili}


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
