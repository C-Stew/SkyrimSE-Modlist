# **C Stew’s Skyrim SE Modlist v1.0 [WIP]**
## Foreword
This mod list uses the **now outdated 1.5.97 version** of Skyrim SE. If you have updated to or are using the Anniversary Edition, use [this mod](https://www.nexusmods.com/skyrimspecialedition/mods/57618) to downgrade to the compatible SE version. It is also incompatible with Skyrim: Legendary Edition, the original game with all DLC Add-ons, and Skyrim VR, the Virtual Reality version of Skyrim SE, due to many mods not supporting those versions of the game.

This mod list uses ESO & UI’s [SKYRIM SE MICRO MOD LIST – V1.2](https://eso-ui.com/skyrim-se-micro-list/) as a base. However, my list includes several changes to exclude certain mod features and incorporate compatibility patches. I also include some personal favorites to replace a few excluded features, annoyances, and to improve aspects their list doesn't cover. Their install instructions are also lacking, that is to say non-exsistent, making it impossibly difficult to match their settings.
This mod list also incorporates ENB, a post-processing program that enhances visuals drastically. If you experience performance issues or are running on a low-end system, test with ENB off. **Certain mods rely on ENB being present, and they will need to be removed if ENB is not in use.**

LOOT will be used periodically to optimize load order and solve override issues, as Vortex doesn't do the best job of this. *If your deploy/load order is shuffled while installing mods, don't worry.* LOOT can pretty easily resolve many load order issues.

*Any mods containing NSFW content/additions will not be included.*

**System Requirements*** **(and AMD equivalent):**
- NVIDIA GTX 1050 \| AMD HD 7870
- Intel i3 \| Ryzen 3
- 8GB DDR3

**My System Specifications (and AMD equivalent):**
- NVIDIA GTX 1660-Ti \| AMD RX 5600-XT
- Intel i5-10300H \| Ryzen 5 4600H
- 16GB DDR4-2933MHz

**Storage Requirements:**
- 10.3GB for Archives + 15GB for Mod Files + Skyrim SE (Approx. 13GB Base, 27.6GB after Mods)
  - Total Space Requirements comes out to be **53GB for Skyrim SE and all mod files**. While this is a hefty number, it's fairly standard for mod lists that replace the majority of the game's textures and sounds. *Note: These numbers are subject to change as the list is further developed.*

**According to ESO & UI’s [SKYRIM SE MOD LISTS](https://eso-ui.com/skyrim-se/) page*

*I have yet to test the full pack, so I am currently unable to vouch for the performance at this time.*

This guide is designed to be as user-friendly as possible and accessible to those with zero previous modding experience!

## Pre-Installation
I use [Vortex](https://www.nexusmods.com/about/vortex/) to install and manage mods. For a comprehensive usage and setup guide, Ultimate Immersion has an intuitive video [here](https://www.youtube.com/watch?v=EyDtcYuDd9w) on setting up your Skyrim installation and Vortex to be mod-ready. **It also covers installing SKSE64, a crucial plugin that requires manual installation. Make sure you download `Legacy SE build 2.0.20 (runtime 1.5.97)`, NOT `Latest AE Build!`**

When downloading mods, use the `MOD MANAGER DOWNLOAD` button unless otherwise specified. Do note that Nexus limits Non-premium users to one 1-2MB/s download at a time, so patience is a must. If you get a pop-up in your browser asking to open a link with Vortex, select `Open Vortex`. It will automatically begin downloading the mod within Vortex.

If Vortex shows any mod conflicts in the upper right corner, **always load the mods in the order of this list**. Mods downloaded first should be loaded **before** mods downloaded after them. This way features won’t be unintentionally overridden by other mods.

## ESO & UI's List (including patches)
**When downloading mods, use the specified version unless replaced by a newer build! If no version is specified, download the latest Main File!**

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
  - When prompted, select `Skyrim 2016 Special Edition: Everything`
- [Water for ENB](https://www.nexusmods.com/skyrimspecialedition/mods/37061?tab=files)
  - *If you don't plan to use ENB, **do not** install this mod.*
  - When prompted, select `Shades of Skyrim` and `No iNeed Support`, then Select LOD Brightness
  - Here, select `Default LOD Water`, then select Water Texture Resolution
  - This is up to preference, but I use `2K`. Select Waterfalls And Effects Add-On next.
  - Pick the same resolution as the previous selection, or None, then select Patches.
  - Leave all boxes unchecked and select Finish.
  - **Vortex will now show a file conflict. Load SMIM *BEFORE* Water for ENB!**
  - Hit `Deploy` in the pop-up.
- [Water for ENB USSEP and Location Patches](https://www.nexusmods.com/skyrimspecialedition/mods/50394?tab=files)
  - *If you don't plan to use ENB, **do not** install this mod.*
  - Download **WENB Shades USSEP Patch**
- [Noble Skyrim Mod HD-2K](https://www.nexusmods.com/skyrimspecialedition/mods/21423?tab=files)
  - Download **A. Noble Skyrim - FULL PACK_2K** (recommended) or **B. Noble Skyrim - FULL PACK_Performance Edition** (recommended for low-end systems), and **NSM - SMIM Patch**
  - This download will take a while, but **do not skip it for later**!
- [Enhanced textures detail (UV-tweaks)](https://www.nexusmods.com/skyrimspecialedition/mods/992?tab=files)
  - Check `Install SMIM Conflicting Files` when prompted!
  - On the next page, select `I want it all!` and 
 the above boxes unchecked.
  - On the next page, only check `Farmhouses with 3D Ropes`.
  - The next option is up to preference, but I use `None`.
  - On the next page, leave all boxes unchecked, and select Finish.
  - Now we have *many* file conflicts!
    - Load Noble Skyrim AFTER UV-tweaks
    - Load Noble Skyrim BEFORE its SMIM Patch
    - Load Noble Skyrim AFTER SMIM
    - Load UV-tweaks BEFORE SMIM
    - Load UV-tweaks BEFORE Water for ENB
    - Load NSM SMIM Patch AFTER SMIM
  - Hit `Deploy`
- [Fluffy Snow](https://www.nexusmods.com/skyrimspecialedition/mods/8955?tab=files)
  - Download **Fluffy Snow - 2K** (recommended) or **Fluffy Snow - 1K** (slight performance boost), **Fluffy Snow - Blended Roads Patch**, **Fluffy Snow for Majestic Mountains - 2K (MM1.8 and newer)**, and **Fluffy Snow Windhelm Bridge and Street Fix**.
  - Load Noble Skyrim BEFORE Fluffy Snow
  - Hit `Deploy`
- [Majestic Mountains](https://www.nexusmods.com/skyrimspecialedition/mods/11052?tab=files)
  - When prompted, select `Snow Mountain New version ESL` and `Moss Rocks ESL version`
  - Choose Sun Direction **None if using ENB**, and **North or South without ENB**.
  - Finish the installation for this mod.
  - Now even *more* unresolved file conflicts!
    - Load Majestic Mountains AFTER SMIM
    - Load Majestic Mountains AFTER UV-tweaks
    - Load Majestic Mountains BEFORE Fluffy Snow
    - Load Majestic Mountains AFTER Noble Skyrim
  - Vortex will say **Fluffy Snow for Majestic Mountains - 2K (MM1.8 and newer)** is redundant. Ignore this warning, as it shouldn't be the case.
  - Hit `Deploy`
- [FNIS SE](https://www.nexusmods.com/skyrimspecialedition/mods/3038?tab=files)
  - After installing, watch the **Vortex Users** section of [this video](https://www.youtube.com/watch?v=sYEAnTdZb-s) to properly set up FNIS
    - Note that only the Behavior pack is needed, not creatures or spells!
    - Also, ignore the MO2 portion of the chapter.
  - When configuring FNIS, check `Skeleton Arm Fix` and `HKX File Compatibility Check`.
    - Only use Vortex's menu, as using it and the executable causes conflicts!
- [Immersive Citizens](https://www.nexusmods.com/skyrimspecialedition/mods/173?tab=files)
  - Options selected should be `Core` and `None`.
  - If it shows External Changes from using FNIS Generator, choose **Use newer file**.
- [DDCse](https://www.nexusmods.com/skyrimspecialedition/mods/695?tab=files)
- [Blended Roads](https://www.nexusmods.com/skyrimspecialedition/mods/8834?tab=files)
  - When prompted, set both selections to `Blended Roads`.
- [RS Children Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/2650?tab=files)
  - When selecting patches, choose `USSEP`
  - In Extra Options, select `Bigger Heads` and `Facial Animations` to prevent potential bugs.
  - For whatever reason, Blended Roads conflicts didn't appear until now for me, so lets fix them!
    - Load Noble Skyrim BEFORE Blended Roads
    - Load Blended Roads AFTER SMIM
    - Load Blended Roads AFTER UV-tweaks
    - Load Blended Roads BEFORE Fluffy Snow
  - Hit `Deploy`
- [RS Children Patch Compendium](https://www.nexusmods.com/skyrimspecialedition/mods/13409?tab=files)
  - Download **RSC FOMOD Beta** and **RS Children and USSEP Aventus fix**
  - ONLY SELECT `Cutting Room Floor` and hit Finish
    - It will now display a `Missing Masters` warning, which will be resolved later
- [JK's Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/6289?tab=files)
  - Download **JK's Skyrim all in one**
- [RUGNAROK - Special Edition](https://www.nexusmods.com/skyrimspecialedition/mods/5436?tab=files)
  - Download **RUGNAROK - Special Edition - 2K** (recommended) or **RUGNAROK - Special Edition - 1K** (recommended for low-end systems)
    - Load Noble Skyrim BEFORE RUGNAROK
  - Hit `Deploy`
- [RUSTIC CLOTHING - Special Edition](https://www.nexusmods.com/skyrimspecialedition/mods/4703?tab=files)
  - Download **RUSTIC CLOTHING - Special Edition - 2K**
  - Load RUSIC CLOTHING AFTER SMIM
  - Hit `Deploy`
- [Happy Little Trees](https://www.nexusmods.com/skyrimspecialedition/mods/50961?tab=files)
  - When prompted, select `All Trees` and `Tree Size`
  - Load Happy Little Trees AFTER SMIM, UV-tweaks, and Noble Skyrim
  - Hit `Deploy`
- [Folkvangr - Grass and Landscape Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/44899?tab=files)
  - Load Folkvangr AFTER Noble Skyrim
  - Hit `Deploy`
- [Aspens Ablaze](https://www.nexusmods.com/skyrimspecialedition/mods/39998?tab=files)
  - Choose `Autumnal` or `Autumnal Variety` (recommended)
  - Leave `Install` unchecked for LOD Assets
  - Load Aspens Ablaze AFTER Happy Little Trees
  - Hit `Deploy`
- [Enhanced Lights and FX](https://www.nexusmods.com/skyrimspecialedition/mods/2424?tab=files)
  - Set Ambience to `None` and leave Exterior alone
  - Select both SMIM patches
  - Check `Torches` in Optionals
  - Load ELFX AFTER SMIM
  - Load ELFX AFTER RUGNAROK
  - Load ELFX AFTER UV-tweaks
  - Hit `Deploy`
- [SFCO](https://www.nexusmods.com/skyrimspecialedition/mods/2414?tab=files)
  - Download **Snazzy Furniture and Clutter Overhaul SE** and **Snazzy Furniture and Clutter Overhaul SE - Patches**
  - Select Mix-n-Match Plugin - USSEP Version
  - Choose `Standard` if **not using ENB**, choose `De-saturated` if you **are using ENB**
  - For patches, select `Cutting Room Floor`, `Enhanced Lights and FX`, `Immersive Citizens`, and both `JK's` options.
  - Load SFCO AFTER SMIM
  - Hit `Deploy`
  - The **Missing Masters** warning for SFCO and JK's Skyrim should be ignoreable.
- [PELTAPALOOZA](https://www.nexusmods.com/skyrimspecialedition/mods/5442?tab=files)
  - Download **PELTAPALOOZA Special Edition - FULL**
  - Load PELTAPALOOZA AFTER Noble Skyrim
  - Hit `Deploy`
- [Enhanced Blood Textures](https://www.nexusmods.com/skyrimspecialedition/mods/2357?tab=files)
  - **Don't** download the LITE version!
  - Leave settings on default, but use `Medium Distance` (recommended) for better performance or lower resolutions.
  - I use `High Res / Darker Color` but color can be left up to preference.
  - For Alt. Textures, leave as `None` (recommended) or make this setting match your last.
- [Gemling Queen Jewelry SE](https://www.nexusmods.com/skyrimspecialedition/mods/4294?tab=files)
  - Select all options except `Unobtainable`
  - Select `Gamwich - 512` (recommended) or `Gamwich - 1024`
  - Leave Optional Mesh Packs as `None`
  - Ring Texture is completely up to preference, I use `Combined - 1k`
  - Load Gemling Queen Jewelry SE AFTER SMIM
  - Hit `Deploy`
- [Immersive Sounds - Compendium](https://www.nexusmods.com/skyrimspecialedition/mods/523?tab=files)
  - Options are entirely up to preference. I use default settings with all Creature Options selected.
- [Sounds of Skyrim Complete SE](https://www.nexusmods.com/skyrimspecialedition/mods/8286?tab=files)
  - Choose `Light` for a lore-friendly experience (recommended).
  - The  `Immersive Citizens` patch should already be selected, but also select `Natural Atmospheric Tamriel`, but **not the ENB patch!**
  - Make sure ELFX is set to **only `ELFX`**.
  - Check `I Understand` on the next page. It discusses potential conflicts with multiple weather/lighting mods.
- [Bellyaches Animal and Creature Pack SSE](https://www.nexusmods.com/skyrimspecialedition/mods/6839?tab=files)
  - Choose `Default Replacement`
  - Load Bellyaches AFTER SMIM
  - Hit `Deploy`
- [Landscape Fixes For Grass Mods](https://www.nexusmods.com/skyrimspecialedition/mods/9005?tab=files)
  - Download (*there's a lot*) **Landscape Fixes For Grass Mods**, **Immersive Citizens v0.4 Patch**, **JK's Skyrim - Towns**, **Patches for Arthmoor's Town add-ons**, and **Generic Grass Limiter** (under Misc. Files)
  - In **Patches for Arthmoor's Towns**, select `Cutting Room Floor`
  - We'll use LOOT later to make sure these load in the proper order (Folkvangr -> Base Mod -> Patches)
- [Cutting Room Floor - SSE](https://www.nexusmods.com/skyrimspecialedition/mods/276?tab=files)
- [Smoking Torches and Candles](https://www.nexusmods.com/skyrimspecialedition/mods/8607?tab=files)
  - Choose `Subtle` (recommended) or `Classic` (not recommended)
  - Choose `Optimized` (recommended) or `Max Quality` (not recommended for low-end systems)
  - Choose `ESPFE`
  - Load Smoking Torches BEFORE ELFX
  - Load Smoking Torches AFTER SMIM
  - Hit `Deploy`
- [NAT - Natural and Atmospheric Tamriel](https://www.nexusmods.com/skyrimspecialedition/mods/12842?tab=files)
  - Only download **NAT Stand Alone**
  - NAT should be loaded **after other lighting mods**!
    - We will fix this with LOOT later, as Vortex doesn't notice lighting mod conflicts.
- [Embers HD](https://www.nexusmods.com/skyrimspecialedition/mods/14368?tab=files)
  - Choose `1K` (recommended) or `1K Orange Cast`
  - Select `Fireplaces Add-On + Custom Fire Effect`
  - Select **both** Add-Ons
  - Select the `Smoking Torches Patch`
  - Now for several file conflicts!
    - Load EMBERS HD BEFORE ELFX
    - Load EMBERS HD AFTER Smoking Torches
    - Load EMBERS HD AFTER SMIM
  - Hit `Deploy`
- [Immersive Fallen Trees SSE](https://www.nexusmods.com/skyrimspecialedition/mods/8767?tab=files)
- [aMidianBorn Book of Silence SE](https://www.nexusmods.com/skyrimspecialedition/mods/35382?tab=files)
  - Download **1) aMidianBorn Book of Silence SE -- COMPLETE**
  - This download will take a while, but **do not skip it for later**!
- [RaceMenu](https://www.nexusmods.com/skyrimspecialedition/mods/19080?tab=files)
  - Enable both RaceMenu plugins if they show as Disabled.
- [Ruins Clutter Improved](https://www.nexusmods.com/skyrimspecialedition/mods/5870?tab=files)
  - Download **Ruins Clutter Improved SE Mod Manager**
  - Select `Install Everything` and hit Finish.
  - Once again, it conflicts with the other texture mods.
    - Load Ruins Clutter Improved AFTER Noble Skyrim
    - Load Ruins Clutter Improved AFTER SMIM
    - Load Ruins Clutter Improved AFTER NSM SMIM Patch
    - Load Ruins Clutter Improved AFTER UV-tweaks
    - Load Ruins Clutter Improved BEFORE Smoking Torches
    - Load Ruins Clutter Improved BEFORE ELFX
    - Load Ruins Clutter Improved BEFORE Enhanced Blood Textures
    - Load Ruins Clutter Improved BEFORE RUGNAROK
  - Hit `Deploy`

Congrats! The easy part of the modding process is finished! Next, the load order needs to be optimized so the game doesn't instantly crash or have severe glitches.

## LOOT Part 1
As useful as Vortex's sorting rules are, **they are far from perfect**.

## Setting up ENB

## My Additions
**When downloading mods, use the specified version unless replaced by a newer build! If no version is specified, download the latest Main File!**

**If a mod is no longer available, proceed without it as it will likely work anyway.**

**All of the following mods should be loaded AFTER mods from ESO & UI’s List unless specified otherwise!**
- [9.0.1 A Quality World Map - Vivid with Stone Roads](https://www.nexusmods.com/skyrimspecialedition/mods/5804?tab=files)
  - Also download [A Quality World Map - Clear Map Skies](https://www.nexusmods.com/skyrimspecialedition/mods/5804?tab=files) under the Optional Files section.
- More to come!

## LOOT Part 2
