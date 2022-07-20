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
#### Your question is not answered here? Ask your question on our [FROST Discord Server](https://discord.com/invite/BaKsm7Fn4A)!

### I need help. Where can I get help?
Don't worry buddy, the [FROST Discord Server](https://discord.com/invite/BaKsm7Fn4A) will always help you out!
You can also check out the [troubleshooting](troubleshooting.html) segment of the guide.

### Why are there only instructions for MO2 but not Vortex?
1. I can't install two mod managers on the same system to modify a single game. Using two mod managers messes things up badly.
2. MO2 is the better mod manager from a technical perspective, as it uses an advanced software approach.

### MO2 is better then Vortex? Why?
I recommend to read [this](https://github.com/sower-j/modding-guides/blob/main/mo2-v-vortex-faq.md) for a proper summary about Vortex vs. MO2. 
Here is my opinion to this topic:
- MO2 uses a Virtual File System (VFS), Vortex doesn't. VFS are very good at managing mods, all other solutions are inferior from a technical point of view
- Vortex takes control away from its users, MO2 gives its user proper control over installed mods
- With MO2 you will learn how to properly mod Bethesda Games, that won't happen if you use Vortex
- Vortex UI is slow and has many annoying layers
- Manually adjusting a load order in Vortex is complicated, unlike in MO2 where its very easy
- MO2 is better for making mods as it helps kleeping files seperate from others through the VFS

### What is/was the "Nexodus"?
Back in 2021, Nexusmods silently tried to add huge changes to its Terms of Services, but tried to push the changes as silent and fast as possible. 
Mod authors can not delete their mods from Nexusmods as a result of these changes. Don't like what Nexusmods is doing? Nexusmods treats you unfairly? To bad, you can't delete your mods anymore. That's why many people left. 

### Which mods are compatible/incompatible with FROST?
Check out this [section](./compatability.html) please. If you want to know if a specific mod is compatible, ask on the [Frost Discord Server](https://discord.com/invite/BaKsm7Fn4A)

### Why does a pirated version of Fallout 4 not work properly with Fallout 4/FROST?
I don't know, but I have hypothesis. Pirated versions of Fallout 4 are often hacked together or outdated, and that conflicts with the .esps of certain mods, often resulting in a version mismatch problem between the mod and the pirated version.
Its like trying to use a mod from 2022 with the original unpatched version of Fallout 4 from 2015. It doesn't work, stuff will break or the game will crash. Not all pirated versions have this problem, but if you use a pirated version, you won't get any support from me. 

**I don't condone piracy in any way!**{: .hili}
Fallout 4 costs $15-$20 on websites like MMOGA or during Steam Sale. Just buy the game, it's cheap, it will be worth it.
Also keep in mind that many pirated version of Fallout 4 install malware like viruses on your PC, and the damage dealt through this malware will cost you more then buying Fallout 4.


### Why do you have to install at least 10 mods to properly play FROST?
FROST needs the ~10 core mods (Frost Cell Fixes, Frost Plus, ...) because different developers are working on FROST, and its easier for each one of them to develop their stuff in their own seperate mod. The Creation Kit and xEdit were never made with the concept in mind that multiple people can work on a single mod at once properly. Additionally, it makes development and bug fixing easier if stuff stays seperate.
There are also technical reasons for certain decisions, like Frost Cell Fixes who need to be loaded last to ensure that Bethesda's performance boosting preculling system works properly. This is nothing FROST specific, this applies to every Fallout 4 mod setup.
You also have to keep in mind that FROST is basically a complete conversion of the game. You can't put everything into one mod to achieve that.
If one thing goes horribly wrong, it will not affect the other stuff as bad.


### "Why is this website so ugly and bad!!!!!11"
I'm not a web developer, and I made this guide in my free time. Sure it could be better from a visual point of view, but it does its job pretty good. You can always fork/copy the source code from this website from GitHub and make try to make it better yourself, I won't stop you.

### I don't like this or that from the guide. Can you change it?
Sure, constructive feedback is always welcome. Just post your criticism on the [FROST Discord Server](https://discord.com/invite/BaKsm7Fn4A), you can ping me there too if you want (@Redawt#1999).

### Why isn't there a patch for mod XYZ for FROST?
Probably because no one made one yet, or because the mod is impossible/hard to patch.

### Is this guide perfect? 
No. There is no such thing as a perfect guide, and this guide definitely has some flaws. I am more then happy to admit that.
There are currently some very minor conflicts between some of the mods that are featured in this guide. They are not really problematic, but a "perfect" guide would provide some .esp to fix those smaller conflicts. And example for this is currently a small conflict between SCM and FROST. 
I appreciate and welcome well defined criticism, especially from other mod authors and guide makers. 
Feel free to contact me anytime on Discord, my discord ID is *Redawt#1999*.

Keep in mind that I basically "revived" the FROST community after years of FROST not getting any proper development and patches. I provided new content and bug-fixes, rebuilt the FROST wiki together with Arbitrary4711, set new standard about properly patching mods for FROST, took over managing the Frost Discord, and a lot more. It was a lot of work, I put thousands of hours into making FROST and its community better. 
Some of the things I did are not perfect, like this website here, but I am proud of my work. 
I also would never been able to do this all alone, I got a LOT of help from the FROST community.