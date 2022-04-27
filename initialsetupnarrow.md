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

## Some Assumption
I will assume that you know the following things:
* What a load order is
* How to sort your load order
* Why sorting your load order is important
* How to set up a mod manager
* How to properly use a mod manager
* Just because your game doesn't crash doesn't mean that there are no problems with it
* That you always start the game with F4SE through your mod manager
* That you can read
* That you know that using NMM, Kortex or Fallout Mod Manager are all outdated mod managers and should not be used anymore


This guide here doesn't carefully walk you through everything to make a modern all-inclusive setup. 
It only tells you which mods you absolutely need to play FROST.
**You can not skip a single mod in this list!**{: .hili}


## Enable loose files
In your **Fallout4Custom.ini**{: .hili}, make sure that loose files are enabled.
To enable lose files, the following three lines need to be present in your your **Fallout4Custom.ini**.
Adding those lines to the Fallout4.ini or the Fallout4Custom.ini will cause problems. 
Make sure that these three lines are only in your **Fallout4Custom.ini**!
```
[Archive]
bInvalidateOlderFiles=1
sResourceDataDirsFinal=
```

These settings allow for files from mods to be loaded in-game. It is intentional that the bottom setting does not have anything after the =
{:.info}


## Mod Installation Advice

When the guide says to install a mod, it will be formatted as follows: **Main File - Unofficial Fallout 4 Patch 2.1.2b**{: .hili}. This is referring to the mod's category on Nexus, the file name, and the file version. Sometimes I will leave the file version out though, in that case just download the newest version of the mod. 

![Image of UFOP4 Files Section](https://themidnightride.github.io/img/download%20example.png "Image of UFOP4 Files Section")
