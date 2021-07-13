---
title: My Personal Path with Retroarch
layout: post
permalink: /blog/:year/:title/
tags: [games, resources]
---

# MY PERSONAL PAHT WITH RETROARCH

As a videogames lover I spend a lot of time playing videogames. With time, I sold all my GameBoy cartridges and my console videogames (such as Xbox 360 and Nintendo 3DS games) to earn some money. I realized that own physically the games doesn't make any sense, in fact, I would rather play those games in my computer rather than in the original console.

All these thoughts took me to a situation that play a videogame only depends on my computer, and that's how I discovered **Retroarch**. Retroarch is a global emulator that allow to play with multiple systems within an only software. You can download every emulator you want (called _core_), download some ROMs and play the game. Then, you can switch between another different system, load the appropriate core and play other game.

That sounds amazing but there are some disadvantages with this system. Retroarch can recognize **only** specific ROMs, so you cannot download every ROM on internet an put inside Retroarch, you need the appropiate ones.

## ROMS

There are a lot of retro websites that host such a wide range of ROMS, but you only can download those that have the _no-intro_ in your description. I use [Emuparadise](https://www.emuparadise.me/) because it has the complete romset of the popular systems (NES, SNES, etc.). Unfortunately, few years ago Nintendo disabled this website to provide download links, but there are some methods (search on the internet!) to download the files.

Once you get the ROMS, the next step is to load inside Retroarch. I recommend you to create a folder inside Retroarch directory and put there all the ROMS separated by folders, one folder for every system. The next step is to load the core inside Retroarch and load the appropriate ROM.

In many cases, those steps are always the same: load the core and then load the ROM. But there are some systems in which the ROM load required the BIOS files of the system, such as PlayStation or Dreamcast. The solution is to download the BIOS from internet and create a folder called _bios_ inside the **system** directory in Retroarch.

Once you have all these things, you need to do a full scan to tell Retroarch where are all these ROMs. You need to click in _Import Content > Scan Directory > Parent Directory_ by asuming you are in the ROM folder. After that, in the left pannel some systems will appear.

## CORES

There are a lot of cores inside Retroarch. You can try them and choose the one that works better in your machine. In mt personal experience, these are the ones I recommend:

- FinalBurn Neo. MAME
- Snes9x - Current. Super Nintendo and Super Game Boy
- Dolphin. GameCube
- Nestopia UE. NES
- Nintendo 64. Mupen64Plus-Next
- Flycast. Dreamcast
- BlastEm. Genesis.
- VBA-M. Game Boy Advance
- Gambatte. Game Boy / Color
- Beetle PCE. PC Engine

## SHADERS AND OVERLAYS

Retroarch brings you the possibilitie to apply some graphical changes such as scanlines. By default, Retroarch have quite good shaders and overlays, but I recommend **Analog Shader Pack V3** and some overlays you can download if you search on Github.

## MAME

In contrast with other systems, MAME (Arcade games) ROMS have given me a lot of problems. First of all, you need to download the specific ROMS (as I said before). You can download the correct ROMS in Archive.org repositories. Then you need to download the _dats_ files from [this repository](https://github.com/libretro/FBNeo/tree/master/dats/).

Once you have all those things, you need to go to Retroarch, click in _Import Content > Manual Scan_ and select the directory, core and the dat directory you download before. You can check the [official documentation](https://docs.libretro.com/library/fbneo/).

## TO SUM UP
