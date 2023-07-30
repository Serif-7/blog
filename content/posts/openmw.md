+++
title = "The Modern Gamer's Guide to Running Morrowind"
date = 2022-05-17T22:51:10-04:00
draft = false

+++
Ah, Morrowind. Widely regarded as one of the best RPGs of all time. It was my first PC game at around four or five years old, though I don't think I ever got out of Seyda Neen. It's a great game and an important landmark in gaming history. Personally, I would argue it is Bethesda's 'purest' RPG.

Sadly, it has not aged well. Playing it today, when we're all spoiled with modern conveniences, is kind of like reading a classic novel. You know it's good for you, but it's a slow and annoying kind of fun. Thankfully, though, some kind souls have resurrected it for today's audience in the form of OpenMW.

# What is OpenMW?

OpenMW is a from-scratch reimplementation of Morrowind's engine. Before you ask, no that isn't illegal. But it doesn't mean Morrowind is suddenly free either. They've remade the engine, but not the game assets, like textures and voice lines, so you still need to buy a copy of Morrowind and point OpenMW to where the assets are located on your computer.

OpenMW comes with a lot of extra benefits over the original, such as:
* 2147483646 mod limit, up from 255 for vanilla Morrowind
* Multiple quicksaves
* Quality of life improvements, such as being able to search for spells
* Native support for macOS, Linux, and Windows. 
* Improved physics and AI
* Greatly improved graphics and draw distance
![Seyda Neen. No mods](/images/seyda_neen.png)
* You can cancel a nocked arrow now.
* Much more. The full feature list is [here](https://wiki.openmw.org/index.php?title=Features)


But there are some cons as well. Any mods requiring Morrowind Script Extender (MWSE), Morrowind Code Patch (MCP), Morrowind Graphics Extender (MGE) will not work, because they all relied on modifying the original game engine. OpenMW was written from scratch, so none of those extenders are compatible. Any other mods may still work fine, though there are many exceptions.

Another point is that, if you're a particularly nostalgic fan, then OpenMW may not look *exactly* as you remember. However, almost all of the graphical and gameplay enhancements I listed above can be turned off to make the game very closely resemble vanilla Morrowind in terms of look and feel.

The full docs of the game are [here.](https://openmw.readthedocs.io/en/latest/index.html) Click on 'Installation Guide' to get started. For more info, I recommend joining the discord. You can find the link on the official site [here.](https://openmw.org/en/) 

# Tweaking Launcher Options

The 'Advanced' menu in the launcher has a lot of little configuration options that are worth looking at. If you don't want to think about it right now, I personally recommend turning these ones on:

*If you want to know what each of these do in detail, hover over each option in the launcher with the mouse and a tooltip will pop up.*

**Game Mechanics**
* Toggle sneak
* Build nav mesh for world geometry
* NPCs avoid collisions
* Permanent barter disposition change
* Can loot during death animation

**Visuals**
* Smooth movement
* Turn to movement direction
* Radial fog
* Bump/reflect local map lighting
* Distant land

**Interface**

I personally turn all of these on. They just provide more exact information on weapons, effect durations, enchantment chances, etc.

**Bug fixes**
* Merchant equipping fix
* Trainers choose their training skills based on their base skill points

**Miscellaneous**
* Add "Time Played" to saves
* Raise max quicksaves to 5


# That's cool and all but what about ***Mods?***

Of course, what's a Bethesda game without mods? [^1] OpenMW has made huge strides with regards to modding support. The devs have added native Lua scripting, something that MWSE provided for the base game. No more weird proprietary Bethesda scripting language, just use Lua. They've added a hundred other features as well, most of which can found in the modding reference [here.](https://openmw.readthedocs.io/en/latest/reference/modding/index.html) 


For mod users, the site to look at is [modding-openmw.com](https://modding-openmw.com/). The community has collected modlists and resources for modding. It should contain all the information you need to get started. The essential reference for installing mods is this [docs page](https://openmw.readthedocs.io/en/latest/reference/modding/mod-install.html#install).

There is also a mod manager made for the game; it's called [Portmod](https://portmod.gitlab.io/portmod/index.html). If you're on Windows, then Vortex or Mod Organizer will work fine, but on Linux they can be a little janky. Portmod may be the best solution. While the docs are decent, I may edit this page to include a guide on basic usage in the future.

Alright, that should be it. Hopefully I've prepared you well enough to enjoy this gem of a game in our modern times. Enjoy yourself, N'wah.


***Note: This is a reference post, which means it's for informational purposes only. I may edit it at any time if I realize things need to be added, changed, or removed.***


# Footnotes

[^1]: Very little.




