# **C Stew’s Skyrim SE Modlist v1.0 [WIP]**
## Foreword
This mod list uses the **now outdated 1.5.97 version** of Skyrim SE. If you have updated to or are using the Anniversary Edition, use [this mod](https://www.nexusmods.com/skyrimspecialedition/mods/57618) to downgrade to the compatible SE version. It is also incompatible with Skyrim: Legendary Edition, the original game with all DLC Add-ons, and Skyrim VR, the Virtual Reality version of Skyrim SE, due to many mods not supporting those versions of the game.

This mod list uses ESO & UI’s [SKYRIM SE MICRO MOD LIST – V1.2](https://eso-ui.com/skyrim-se-micro-list/) as a base. It is recommended to use my list as it contains updated instructions since the release of Anniversary Edition, but you can skip the *ESO & UI’s List* section if you choose to install them according to their website. Either way, you should get the same result.

**System Requirements*** **(and AMD equivalent):**
- NVIDIA GTX 1050 \| AMD HD 7870
- Intel i3 \| Ryzen 3
- 8GB DDR3

**My System Specifications (and AMD equivalent):**
- NVIDIA GTX 1660-Ti \| AMD RX 5600-XT
- Intel i5-10300H \| Ryzen 5 4600H
- 16GB DDR4-2933MHz

**Storage:**
- 1140 MB Available + Skyrim SE File Size (Approx. 14GB)

**According to ESO & UI’s [SKYRIM SE MOD LISTS](https://eso-ui.com/skyrim-se/) page*

*I have yet to test the full pack, so I am currently unable to vouch for the performance at this time.*

This guide is designed to be as user-friendly as possible and accessible to those with zero previous modding experience!

## Pre-Installation
I use [Vortex](https://www.nexusmods.com/about/vortex/) to install and manage mods. For a comprehensive usage and setup guide, Ultimate Immersion has an intuitive video [here](https://www.youtube.com/watch?v=EyDtcYuDd9w) on setting up your Skyrim installation and Vortex to be mod-ready. **It also covers installing SKSE64, a crucial plugin that requires manual installation. Make sure you download *Legacy SE build 2.0.20 (runtime 1.5.97)*, NOT the *Latest AE Build!***

When downloading mods, use the **MOD MANAGER DOWNLOAD** button unless otherwise specified. Do note that Nexus limits Non-premium users to one 2MB/s download at a time, so patience is a must. If you get a pop-up in your browser asking to open a link with Vortex, **select Open Vortex**. It will automatically begin downloading the mod within Vortex.

If Vortex shows any mod conflicts in the upper right corner, **always load the mods in the order of this list**. Mods downloaded first should be loaded **before** mods downloaded after them. This way features won’t be unintentionally overridden by other mods.

## ESO & UI's List
**When downloading mods, use the specified version unless replaced by a newer build!**

**If a mod is no longer available, proceed without it as it will likely work anyway.**
- [SSE Engine Fixes](https://github.com/aers/EngineFixesSkyrim64/releases/)
  - Not sure why, but their Nexus Mods page is set to hidden, so it must be acquired from their GitHub instead.
  - Download **Part.1.SSE.Engine.Fixes.for.1.5.39-1.5.97.7z** and **Part.2.skse64.Preloader.TBB.Lib.7z** from their latest release.
  - Open Vortex, activate SSE, and select the **Mods** tab on the left side.
  - Click the plus icon on the orange bar and select **Part.1.SSE.Engine.Fixes.for.1.5.39-1.5.97.7z** to automatically import the mod.
  - Using File Explorer, cut or copy **Part.2.skse64.Preloader.TBB.Lib.7z** to your Skyrim SE installation (it should contain SkyrimSE.exe and SkyrimSELauncher.exe)
  - Using [7-zip](https://www.7-zip.org/), right click **Part.2.skse64.Preloader.TBB.Lib.7z**, hover over `7-Zip >`, and select `Extract Here`.
- [Address Library for SKSE Plugins](https://www.nexusmods.com/skyrimspecialedition/mods/32444?tab=files)
  - Download **All in one (Special Edition)**, NOT Anniversary Edition!
- [Unofficial Skyrim Special Edition Patch](https://www.nexusmods.com/skyrimspecialedition/mods/266?tab=files)
- [SkyUI](https://www.nexusmods.com/skyrimspecialedition/mods/12604?tab=files)
- [Static Mesh Improvement Mod - SMIM](https://www.nexusmods.com/skyrimspecialedition/mods/659?tab=files)

## My Additions
**When downloading mods, use the specified version unless replaced by a newer build!**

**If a mod is no longer available, proceed without it as it will likely work anyway.**

**All of the following mods should be loaded AFTER mods from ESO & UI’s List!**
- [9.0.1 A Quality World Map - Vivid with Stone Roads](https://www.nexusmods.com/skyrimspecialedition/mods/5804?tab=files)
  - Also download [A Quality World Map - Clear Map Skies](https://www.nexusmods.com/skyrimspecialedition/mods/5804?tab=files) under the Optional Files section.
