---
title: My Personal Path with Retroarch
layout: post
permalink: /blog/:year/:title/
tags: [games, resources]
---

# MY PERSONAL PAHT WITH RETROARCH

As a video game lover, I have spent a lot of time playing videogames. With time, I sold all my GameBoy cartridges and console videogames (such as Xbox 360 and Nintendo 3DS games) to earn some money. I realized that physically owning the games doesn't make any sense. In fact, I would rather play those games in my computer rather than in the original console.

All these thoughts lend me to a situation where playing a videogame only depends on my computer, and that's how I discovered **Retroarch**. Retroarch is a global emulator that allow you to play with multiple systems within a single software. You can download all the emulators you want (called _cores_), download some ROMs and play them. Then, you can switch between a different system, load the appropriate core and play another game.

It sounds amazing but this system has some disadvantages. Retroarch can recognize **only** specific ROMs, so you can't download all ROMs on the internet and put them inside Retroarch, you need the right ones.

## ROMS

There are many retro websites that host such a wide range of ROMS, but you can only download those that have _no-intro_ in their description. I use [Emuparadise](https://www.emuparadise.me/) because it has the full romset of popular systems (NES, SNES, etc.). Unfortunately, few years ago Nintendo disabled this website to provide download links, but there are a few methods (search on the internet!) to download the files.

Once you get the ROMS, the next step is to load them in Retroarch. I recommend you to create a folder inside Retroarch directory and put there all the ROMS separated by folders, one folder for each system. The next step is to load the core into Retroarch and load the appropriate ROM.

In many cases, those steps are always the same: load the core and then load the ROM. But there are some systems where loading the ROM requires the system BIOS files, such as PlayStation or Dreamcast. The solution is to download the BIOS from the internet and create a folder called _bios_ whitin the **system** directory in Retroarch.

Once you have all these things, you need to do a full scan to tell Retroarch where all these ROMs are. You need to click in _Import Content > Scan Directory > Parent Directory_ assuming you are located in the ROM folder. After that, some systems will appear in the left panel.

## CORES

There are many cores whitin Retroarch. You can test them and choose the one that works best on your machine. In my personal experience, these are the ones I recommend:

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

Retroarch gives you the ability to apply some graphic changes like scan lines. By default, Retroarch have very good shaders and overlays, but I recommend **Analog Shader Pack V3** and some overlays you can download if you search on GitHub.

## MAME

Unlike another systems, MAME ROMs (Arcade games) have given me a lot of toubles. First of all, you need to download the specific ROMS (as I said before). You can download the correct ROMS from the repositories at Archive.org. Then you need to download the _dats_ files from [this repository](https://github.com/libretro/FBNeo/tree/master/dats/).

Once you have all those things, you need to go to Retroarch, click in _Import Content > Manual Scan_ and select the directory, core and the dat directory you download earlier. You can check the [official documentation](https://docs.libretro.com/library/fbneo/).

## TO SUM UP

After a few years testing Retroarch, I can say that it's my favourite solution because I can play a wide variety of retro games. It's true that there are some previous steps to configure it correctly, but once the hard work is done the magic just appears.
