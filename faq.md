---
layout: article
titles:
  # @start locale config
  en      : &EN       FAQ
  # @end locale config
key: page-faq
sidebar:
  nav: docs-en
aside:
  toc: true

---
## Guide FAQ


## FROST FAQ


## Technical FAQ
#### Why are there only instructions for MO2 but not Vortex?
1. I can't install two mod managers on the same system to modify a single game. Using two mod managers messes things up badly.
2. MO2 is the better mod manager from a technical perspective, as it uses an advanced software approach.
Down below I describe in detail why MO2 is a better mod manager.

#### MO2 is better then Vortex? Why?
Many people will tell you: *Oh, mod managers are a matter of taste, just like Pepsi and Cola*.
This is true to a degree, but from a technical point of view MO2 is better then Vortex.

Unlike Vortex or NMM, MO2 has a "Virtual File System (VFS)". The VFS does not install mods directly into the game files, but rather puts every mod into their own folder on your computer, far away from the game files. When you start your game with MO2, the mods are automatically and virtually linked with your game. Your original game files stay clean, unpoluted from the thousands of files that your mods might add. 

The VFS allows for deactivating mods with one click. Unlike Vortex, it doesn't has to move dozens or even hundreds of files to deactivate one mod. The VFS also makes it easier to resolve file conflicts, or debug your game if it crashes or has some other problems.
Furthermore, the VFS allows MO2 to make "profiles", so you can have several different profiles for the game that are completely different.
You can have a FROST setup, and a Horizon or vanilla F4 setup with no problems. Vortex on the other side can't do it as well, and you will encounter problems.

I also think that MO2 gives its user a lot of direct control, because its UI is well structured. In Vortex you have to click through countless different screens to use certain features, which often takes a lot of time. In MO2 everything is neatly packaged in 2 panels, you don't have to click through several things to get anywhere. 

Vortex is also known for having a slow UI, and it also tries to take away control from the user and instead is trying to use flawed tools and functions to compensate this. Vortex tries to make things easier by automating everything and taking away control from you. It does this in order to "help" you, but instead it often just stands in your way. 

Vortex is also advertised a lot more then MO2, that is why many people use it. They don't use it because its the better mod manager, they use it because they are the "victim" of a marketing strategy.


#### What is/was the "Nexodus"?
Back in 2021, Nexusmods silently tried to add huge changes to its Terms of Services, but tried to push the changes as silent and fast as possible. What were those changes? Nexus basically changed their ToS so that Mod Authors can not delete their mods anymore. Once they are on the Nexus, they are there forever, and Nexus can do with them what they want. 
It happened a few times that staff from Nexusmods treated its users and mod creators unfairly. In such cases, Mod Authors could delete their mods and move them elsewhere. This isn't possible anymore, Nexus basically owns almost all rightsy to the files of mod creators, and they can keep them forever. 
Some mod authors left Nexus in 2021 because of this, mainly because they don't give away the rights to their own files, and because the fact that Nexus tried to change this as silently and fast as possible pissed many people of. 
Nexus is a company. They want to control the video game modification market, and they want to make a lot of money.
There are some further reasons, but I think this is beyond the scope of this FAQ.



#### Why does a pirated version of Fallout 4 not work properly with FROST?
I don't know, but I have hypothesis. Pirated versions of Fallout 4 are often hacked together or outdated, and that conflicts with the .esps of certain mods, often resulting in a version mismatch problem between the mod and the pirated version.
Its like trying to use a mod from 2022 with the original unpatched version of Fallout 4 from 2015. It doesn't work, stuff will break or the game will crash.


#### Why do you have to install at least 8 mods to properly play FROST?
FROST needs the 8 core mods (Frost Cell Fixes, Frost Plus, ...) because different developers are working on FROST, and its easier for each one of them to develop their stuff in their own seperate mod. The Creation Kit and xEdit were never made with the concept in mind that multiple people can work on a single mod at once properly. Additionally, it makes development and bug fixing easier if stuff stays seperate.
You also have to keep in mind that FROST is basically a complete conversion of the game. You can't put everything into one mod to achieve that.
If one thing goes horribly wrong, it will not affect the other stuff as bad.


**So what is that technical advantage that MO2 has over Vortex?**
MO2 uses a virtual file system. That means that all mods you install with it will not be added into the game files. Instead, they will be put into their own folders in MO2. When you start Fallout through MO2, these folders will be virtually linked to the game.
What is the advantage of that? You can easily disable complete mods, including their .esp and all files from that mod. They are just unlinked. Easy as that. The Virtual File System als can handle file conflicts between mods much better.
It is also helpful for developing mods better. You can copy and create different versions of your mods, you can switch them on and off with one click, and the entire time, not a single files pollutes the original game files. 

This virtual file systems also allows to make big load orders and mod setups with no problems, because nothing polultes the game files and if something doesn't work you can deactivate it with one click.
Because all files are virtually installed, MO2 allows for creating true modding profiles. You can make two completely different profiles in MO2, and don't have to worry that any files from one profile mess with files from another profile. Vortex can't do that. Vortex tries to work around it, but it doesn't work well, especially if lose files are enabled. If one thing does wrong in Vortex, you might have to start over completely because of this.

**User Interface and User Control**
I also think that MO2 gives its user a lot of direct control, because its UI is well structured. In Vortex you have to click through countless different screens to use certain features, in MO2 everything is neatly packaged in 2 panels. Vortex is also known for being a bit with its UI, and trying to take away control from the user and instead uis trying to use flawed functions to compensate this. Vortex tries to make things easier by automating everything and taking away control from you. It does this in order to "help" you, but instead it often just stands in your way. 

**TL;DR:** MO2 has better code and makes modding easier by using a virtual file system to manage mods.


#### Why is this website so ugly!!!!!11
I'm not a web developer, and I made this guide in my free time. Sure it could be better from a visual point of view, but it does its job pretty well I think. And you can always fork/copy the source code from this website from GitHub and make try to make it better yourself. 


#### Why isn't there a patch for mod XYZ for FROST?
Probably because no one made one yet, or because the mod is impossible/hard to patch