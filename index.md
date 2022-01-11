# **C Stew’s Skyrim SE Modlist v1.0**
## Foreword
This page serves as a complete guide to use the same mods I do, beginning from a vanilla (un-modded) Skyrim SE Installation. It covers everything from downloading mods to optimizing load order to increasing stability, and is designed to be followed by those with zero previous modding experience.

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
- 11.8GB for Archives + 16.2GB for Mod Files + Skyrim SE (Approx. 13GB Base, 29.4GB after Mods)
  - Total Space Requirements comes out to be **57.4GB for Skyrim SE and all mod files**. While this is a hefty number, it's fairly standard for mod lists that replace the majority of the game's textures and sounds.

**According to ESO & UI’s [SKYRIM SE MOD LISTS](https://eso-ui.com/skyrim-se/) page*

**At 1080p with Graphics set to High and ENB enabled, I generally get 50-60fps indoors and 45-55fps outdoors.**

## Pre-Installation
I use [Vortex](https://www.nexusmods.com/about/vortex/) to install and manage mods. For a comprehensive usage and setup guide, Ultimate Immersion has an intuitive video [here](https://www.youtube.com/watch?v=EyDtcYuDd9w) on setting up your Skyrim installation and Vortex to be mod-ready. **It also covers installing SKSE64, a crucial plugin that requires manual installation. Make sure you download `Legacy SE build 2.0.20 (runtime 1.5.97)`, NOT `Latest AE Build!`**

When downloading mods, use the `MOD MANAGER DOWNLOAD` button unless otherwise specified. Do note that Nexus limits Non-premium users to one 1-2MB/s download at a time, so patience is a must. If you get a pop-up in your browser asking to open a link with Vortex, select `Open Vortex`. It will automatically begin downloading the mod within Vortex.

If Vortex shows any mod conflicts in the upper right corner, **always load the mods in the order of this list**. Mods downloaded first should be loaded **before** mods downloaded after them. This way features won’t be unintentionally overridden by other mods.

## ESO & UI's List (including patches)
**When downloading mods, use the specified version unless replaced by a newer build! If no version is specified, download the latest Main File!**

**If a mod is no longer available, proceed without it as it will likely work anyway.**
- [SSE Engine Fixes](https://github.com/aers/EngineFixesSkyrim64/releases/)
  - Due to recent controversy, Aers's Nexus Mods page is set to hidden, so it must be acquired from their GitHub instead.
  - Download **Part.1.SSE.Engine.Fixes.for.1.5.39-1.5.97.7z** and **Part.2.skse64.Preloader.TBB.Lib.7z** from their latest release.
  - Open Vortex, activate SSE, and select the **Mods** tab on the left side.
  - Click the plus icon on the orange bar and select **Part.1.SSE.Engine.Fixes.for.1.5.39-1.5.97.7z** to automatically import the mod.
  - Using File Explorer, cut or copy **Part.2.skse64.Preloader.TBB.Lib.7z** to your Skyrim SE installation (it should contain SkyrimSE.exe and SkyrimSELauncher.exe)
  - Using [7-zip](https://www.7-zip.org/), right click **Part.2.skse64.Preloader.TBB.Lib.7z**, hover over `7-Zip >`, and select `Extract Here`.
- [Address Library for SKSE Plugins](https://www.nexusmods.com/skyrimspecialedition/mods/32444?tab=files)
  - Download **All in one (Special Edition)**, NOT Anniversary Edition!
- [Unofficial Skyrim Special Edition Patch](https://www.nexusmods.com/Core/Libs/Common/Widgets/DownloadPopUp?id=209150&game_id=1704)
  - Arthmoor removed USSEP for 1.5.97 from Nexus, but it can still be acquired from the above link and installed manually.
  - Once downloaded, install it the same way as **Part.1.SSE.Engine.Fixes.for.1.5.39-1.5.97.7z**.
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
- [Immersive Citizens](https://www.nexusmods.com/skyrimspecialedition/mods/173?tab=files)
  - Options selected should be `Core` and `None`.
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
  - Download **JK's Skyrim all in one** and **JK's Skyrim - Arthmoor's Patch Pack**
  - For Arthmoor's Patch Pack, select `Individual Patches`, then `Cutting Room Floor Patch`.
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
  - Enable RaceMenu.esp if it shows as Disabled. The plugin is optional and can be disabled.
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

## LOOT/SSEEdit Part 1
As useful as Vortex's sorting rules are, **they are far from perfect**. To remedy this, we can use **LOOT: The Load Order Optimisation Tool**. Below are full, in-depth instructions from downloading and installing LOOT to fixing Vortex's shortcomings.
- Go to [LOOT's official website](https://loot.github.io/) and click the blue `DOWNLOAD LOOT` button. This takes you to their GitHub releases page.
- Download **LOOT.Installer.exe** from the latest release. Save it to a temporary location, such as your Downloads folder.
- After it downloads, run it by clicking it at the bottom of your browser or locating it in File Explorer and double-clicking it.
- Click `Yes` in the User Account Control Pop-up
- Follow the installer instructions to install LOOT.
- Launch LOOT when you finish installing.
- Hit OK in the First Time window.
- SFCO - JK's Whiterun Interiors Patch.esp will show the same warnings Vortex did, and they can be ignored.
- At the top of the window, hit the Sort Plugins (three lines) button.
- LOOT has now optimized the load order, and found several issues. Unlike Vortex, LOOT provides recommendations for fixing these, so let's go through them!
  - Locate **NAT.esp**, click the three dots on its card, and select **Edit Metadata**.
    - Select the **Load After** tab, and select **ADD NEW ROW**
    - For the Filename, enter `EnhancedLightsandFX.esp`
    - Select the Save Icon at the top of the **NAT.esp** tab.
  - Next, navigate to **Unofficial Skyrim Special Edition Patch.esp**
    - It will have a notice about a compatibility patch that is not in use. Click [Circlet USSEP Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/35576?tab=files) here or in LOOT, and download **Gemling Queen Jewelry SE USSEP Circlet Fix** the same way as every other mod.
    - In LOOT, click the three dots in the top right, and select **Refresh Content**.
  - Now, navigate to **GQJ_DG_vampireamuletfix.esp**.
    - LOOT recommends deleting this plugin. To do so, use File Explorer to open your Skyrim SE installation, and open the `Data` folder within it.
    - Find the plugin and delete it. Go back to Vortex's Plugins menu
    - Click `Deploy Now` at the top, and it will open and **External Changes** menu. Make sure it says **Save change (delete file) and click `Confirm` in the bottom right.
    - Refresh Content in LOOT as before.
- Next, it's time for more compatibility patches LOOT picked up on.
  - Download these fixes are for ELFX: [Here](https://www.nexusmods.com/skyrimspecialedition/mods/25498/?tab=files) and [Here](https://www.nexusmods.com/skyrimspecialedition/mods/53957?tab=files)
  - Download the [Flashing Savegames Fix](https://www.nexusmods.com/skyrimspecialedition/mods/20406/?tab=files) and [Immersive Fallen Trees Patch](https://www.nexusmods.com/skyrimspecialedition/mods/27834/?tab=files)
    - For ELFX Fixes, select `Sounds of Skyrim - Tonycubed version` and **only if you plan to use ENB** select `ENB ELFX Meshes`.
    - Load ELFX Fixes AFTER all conflicting mods and hit `Deploy`.
    - For Flickering Meshes Fix, set all options to `No parallax version`, `Farmhouses Without Parallax`, and enable patches for SMIM, Majestic Mountains, and, **only if using ENB**, Water for ENB.
    - Load Flickering Meshes Fix AFTER all conflicting mods **EXCEPT WATER FOR ENB** and hit `Deploy`.
    - Go back to Vortex and make sure **fallenbridgesSSE-Patch.esp** is enabled. If not, enable it using the down arrow next to `Disabled` and select `Enabled`.
  - At this time, Refresh Content in LOOT as before.
  - If for some reason you see **JKs Skyrim_Arthmoor All_Patch.esp**, disable it within Vortex as it shouldn't be there.
  - Now, in LOOT, find **JKs Skyrim.esp** and enter its **Edit Metadata** menu.
    - In the **Load After** tab, add a new row with `Cutting Room Floor.esp` and save it.
    - Do the same with **JKs Skyrim_Cutting Room Floor_Patch.esp**, but instead enter **JKs Skyrim.esp** in the rule and save it.
  - In LOOT, navigate to **fallenbridgesSSE-Patch.esp** and add a **Load After** rule for **fallentreebridgesSSE.esp** and save it.
- Now, refresh content and sort your load order again.

Leave LOOT open, as the next step is fixing all of those yellow warnings it showed using **SSEEdit**. While SSEEdit can be run through Vortex, it is easier not to.

*Quick note before this step: **Never clean Master Files, especially Base Game Files!** These are marked with a Crown icon within LOOT, and cleaning them with SSEEdit can have irreversible, game-breaking consequences. **Best practice is to only clean files with a yellow warning in LOOT that ARE NOT Master Files.***

- Download the latest [SSEEdit](https://www.nexusmods.com/skyrimspecialedition/mods/164?tab=files) to somewhere memorable, such as your Desktop.
- Right-click the .7z file, then click `7-Zip >`, `Extract Here`.
- Open the folder and double-click `SSEEditQuickAutoClean.exe`.
- Click `OK` and `Close` in the next two windows that appear.
- Now, keep a few things in mind:
  - SSEEdit can only clean **one file at a time**. Selecting multiple will give an error, meaning the files must be cleaned one by one.
  - We only want to clean the following files: **EnhancedLightsandFX.esp**, **NAT.esp**, **RSChildren.esp**, and **Immersive Citizens - AI Overhaul.esp**.
- Select an afrementioned plugin and click `OK` in the bottom right.
  - You may notice that some of the Base Game Files have a square in their checkbox when selecting a mod. This simply denotes what ESMs the selected file has data referencing, and is only cleaning the file with a checkmark.
- If a large `Cancel` button appears on-screen, **do not click it!** You can also ignore any other pop-up during the cleaning process.
- Once it's done, close SSEEdit, reopen the QuickAutoClean executable, and repeat for the other plugins.

Now, return to LOOT and Refresh Content. You should no longer see yellow boxes on anything except DLC and Update Master Files. If this is the case, close LOOT and Vortex for now.

## Setting up ENB
*If you don't plan to use ENB, skip to the next section.*

This process has two major steps: Installing the files for ENB, and installing the ENB Preset. First, install ENB for Skyrim SE:
- Go [here](http://enbdev.com/mod_tesskyrimse_v0466.htm) and download the latest ENB for Skyrim SE.
  - Ignore any links, scroll down to the bottom of the page and click the icon to the left of `download`.
  - For ease of access, save the .zip to your Skyrim SE installation (the folder with SkyrimSE.exe and SkyrimSELauncher.exe).
- Open the .zip, and within it open the **Wrapper Version**.
- In this folder, select the **enbseries folder**, **both DLLs**, **enblocal.ini**, and **enbseries.ini**. Copy these to the same folder as the Skyrim executables.

Next, download the ENB preset itself:
- Download [Ultimate Immersion SE ENB](https://eso-ui.com/ultimate-immersion-se-enb/) by hitting the blue `Download Ultimate Immersion SE ENB v1.5` buttom halfway down the page.
  - Save this .zip to your Skyrim SE installation.
- Right-click **Ultimate-Immersion-SE-ENB-v1.5.zip**, then click `7-Zip >`, `Extract Here`.
  - When it asks about conflicting files, select `Yes to All`.

ENB is now set up and ready to go! *There are some settings that need changing once in-game for the intended result, but those come later.*

## My Additions
The following mods are some of my picks that cover aspects of the game the previous mods don't by updating visuals and removing annoying occurrences. **If you get an External Changes pop-up from Vortex, choose `Use newer file`.**

**When downloading mods, use the specified version unless replaced by a newer build! If no version is specified, download the latest Main File!**

**If a mod is no longer available, proceed without it as it will likely work anyway.**
- [A Quality World Map](https://www.nexusmods.com/skyrimspecialedition/mods/5804?tab=files)
  - Download **9.0.1 A Quality World Map - Vivid with Stone Roads** and **A Quality World Map - Clear Map Skies**.
    - Load A Quality World Map BEFORE Majestic Mountains
  - Hit `Deploy`
- [Total Character Makeover](https://www.nexusmods.com/skyrimspecialedition/mods/1037?tab=files)
  - **Use `Manual Download`! DO NOT install with Vortex!**
    - Download the .zip to the `Data` folder within your Skyrim SE installation
    - Right-click **Total Character Makeover 1.2-1037-1-2.zip**, then click `7-Zip >`, `Extract Here`.
    - When it asks about conflicting files, select `Yes to All`.
  - *When using this mod, verifying files through Steam will revert its changes.*
- [LeanWolf's Better-Shaped Weapons SE](https://www.nexusmods.com/skyrimspecialedition/mods/2017?tab=files)
  - Download **LeanWolfs Better-Shaped Weapons Installer v2.1.03 SE** and **LWs BSW Orcish Greatsword inventory fix - sheath**.
  - Select `Install Everything`
  - Check both Sheaths options
  - Check `Scimitar Bling`
  - Select `Refractive Glass Weapons`
  - Select `Stalhrim with Refraction`
  - Select `Dawnbreaker Sheath Elf`
  - **If using ENB**, select `Dawnbreaker for ENB`, otherwise select `Dawnbreaker No ENB`
  - Select `DragonBling Red` (or Green or Blue, if you prefer)
  - Select No Dual Sheath
  - Load LeanWolf's BEFORE its patch and Majestic Mountains
  - Hit `Deploy`
- [Deadly Spell Impacts](https://www.nexusmods.com/skyrimspecialedition/mods/12939?tab=files)
  - Select `Default`
- [Move it Dammit](https://www.nexusmods.com/skyrimspecialedition/mods/752?tab=files)
  - Select the first option
- [Visual Animated Enchants](https://www.nexusmods.com/skyrimspecialedition/mods/7037?tab=files)
- [Lanterns Of Skyrim II](https://www.nexusmods.com/skyrimspecialedition/mods/30817?tab=files)
  - Download **Lanterns Of Skyrim II - FOMOD** and **LoS II - JK's Skyrim patch**.
  - Don't select any addons, only the `SMIM patch`.
  - Only select `JK's Skyrim patch`.
  - Select patches for `Cutting Room Floor`, `ELFX`, and `Sound of Skyrim`.
  - Leave the next patches page unchecked.
  - **Load LoS II BEFORE the standalone JK's Skyrim patch**.
  - Hit `Deploy`
- [Point The Way](https://www.nexusmods.com/skyrimspecialedition/mods/352?tab=files)
- [CC's HQ Roadsigns SSE](https://www.nexusmods.com/skyrimspecialedition/mods/2778?tab=files)
  - Download the **(2048x1024)** version (*the only one with a green checkmark*).
  - Select the `Cutting Room Floor` and `Point the Way` patches.
  - Load CC's HQ Roadsigns AFTER Noble Skyrim
  - Hit `Deploy`
- [ELFX - Exteriors Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/26327?tab=files)
  - **If using ENB**, download **ELFX - Exteriors Fixes for ENB users**, otherwise download **ELFX - Exteriors Fixes**.
  - Load Exteriors Fixes BEFORE Flickering Meshes Fix
  - Load Exteriors Fixes AFTER SMIM
  - Hit `Deploy`
- [Run For Your Lives](https://www.nexusmods.com/skyrimspecialedition/mods/2272?tab=files)
- [Hold Border Banners](https://www.nexusmods.com/skyrimspecialedition/mods/1737?tab=files)
  - Download **Hold Border Banners - No Text Version** (recommended for immersion) or **Hold Border Banners**
- [Improved Roads](https://www.nexusmods.com/skyrimspecialedition/mods/12082?tab=files)
- [No Spinning Death Animation SE](https://www.nexusmods.com/skyrimspecialedition/mods/1432?tab=files)
  - Download **No Spinning Death Animation MERGED**.
- [Classic Sprinting Redone (SKSE64)](https://www.nexusmods.com/skyrimspecialedition/mods/20166?tab=files)
  - Download **Classic Sprinting Redone (Legacy SE)**.
- [Better Jumping SE](https://www.nexusmods.com/skyrimspecialedition/mods/18967?tab=files)
  - Download **Better Jumping SE** under Old Files.
- [Dynamic Animation Replacer](https://www.nexusmods.com/skyrimspecialedition/mods/33746?tab=files)
  - Download **DynamicAnimationReplacer v1.1.0 for SkyrimSE** under Old Files.
- [Mfg Fix](https://www.nexusmods.com/skyrimspecialedition/mods/11669?tab=files)
  - Download **MfgFix SE**.
- [EVG Conditional Idles](https://www.nexusmods.com/skyrimspecialedition/mods/34006?tab=files)
  - Select `Recommended`
- [EVG Animation Variance](https://www.nexusmods.com/skyrimspecialedition/mods/38534?tab=files)
  - Select `Full Install`
- [Conditional Expressions](https://www.nexusmods.com/skyrimspecialedition/mods/45148?tab=files)
  - **DO NOT USE MOD MANAGER DOWNLOAD!**
    - Use **MANUAL DOWNLOAD** and install the same way as **Total Character Makeover**.
  - In Vortex's Plugins Menu, enable the plugin.
- [First Person Combat Animations Overhaul 2.0](https://www.nexusmods.com/skyrimspecialedition/mods/45177?tab=files)
  - Download **FPCAO2 - SIZE MATTERS SE ALL-IN-ONE 2.01**
- [Enhanced 1stperson Parry Animation for SSE](https://www.nexusmods.com/skyrimspecialedition/mods/20374?tab=files)
  - Select all **except** `Dual wield`
- [Finally First Person Magic Animation for SSE](https://www.nexusmods.com/skyrimspecialedition/mods/20375?tab=files)
  - Download **First Person Magic Animation for SSE** under Old Files.
  - Select `Variant 3`
- [360 Movement Behavior SE](https://www.nexusmods.com/skyrimspecialedition/mods/33139?tab=files)
- [Skyrim Is Windy](https://www.nexusmods.com/skyrimspecialedition/mods/5836?tab=files)
- [Actor Limit Fix](https://www.nexusmods.com/skyrimspecialedition/mods/32349?tab=files)
  - *The requirement for .NET Framework is already met by the current Windows 10 builds.*
- [Clean Menu](https://www.nexusmods.com/skyrimspecialedition/mods/3223?tab=files)
  - Download **Clean Menu -- All in One (30 FPS)** as 60FPS menus can cause conflicts.
- [Main Menu Spinning Skyrim Emblem](https://www.nexusmods.com/skyrimspecialedition/mods/725/?tab=files)
  - Download the main file, despite its nomenclature.
  - Select `Special Edition Steel - Average Speed` (recommended, but any works).

Whew! *Now* we're done downloading mods! Next, we'll optimize these mods as we did before.

## LOOT/SSEdit Part 2
As before, start by opening **LOOT**.
- Sort Plugins using the three lines icon at the top right.
- **The following patches are only intended for those using ENB!**
  - Surprisingly, we missed only one compatibility patch available [here](https://www.nexusmods.com/skyrimspecialedition/mods/41284/?tab=files), but that site lists an ENB fix for [Word Walls](https://www.nexusmods.com/skyrimspecialedition/mods/41463?tab=files) as well. Download both through Vortex as normal.
  - *There may still be graphical issues for ENB users. Please report them to my [issues page](https://github.com/C-Stew/SkyrimSE-Modlist/issues).*
  - Now, go back to **LOOT** and Refresh Content.
  - Sort Plugins again as before.
- Thankfully, no new warnings appeared, so **SSEEdit** is not necessary this time.
- SFCO - JK's Whiterun Interiors Patch.esp still shows missing masters, but it should not need them since the all-in-one version of JK's Skyrim is in use.

That wasn't too difficult! Now, close LOOT and **restart Vortex**. This will force Vortex to update its load order to match LOOT's.
- Open Steam
- Run SKSE64 through Vortex
  - **If you get a Steam Pop-up about updating the game, IMMEDIATELY do the following:**
    - Click `View Updates`
    - On the far right, click the light blue Pause Icon, then click the `X` Icon of the same color.
    - Steam has now cancelled the update. It should not try again until Steam restarts, in which case you'll have to cancel the update again.
- **If using ENB**, the game may freeze while starting. If a pop-up appears, click **Wait for the program to respond**

## Fixing Crashes
**HURRAH!** Skyrim didn't crash! Before we can make any changes in-game, **start a new file**.

## In-game Changes
Upon loading, NAT will inform you of new spell in your inventory. **This is necessary for ENB Users, as we will need to change a few settings.**
- After `The Elder Scrolls V: Skyrim` dissappears, from your screen, hit `ESC` on your keyboard to open the pause menu and close the pop-up.
- Notice the `Mod Configuration` tab. It isn't needed for our mods, but you can use it to change settings for certain mods that support it.
- **The next settings are for ENB Users**
  - To open and close the ENB Menu, hold **Shift** and press **Enter**.
  - Once you are unbound, open the magic menu and equip the **NAT Settings** spell.
    - Click `Graphics Options`
    - Click `Sub-surface Scattering`, `Dawn & Dusk Natural Lighting`, and `Wet Effects` so they say `Enable`. This disables them as Ultimate Immersion's ENB implements them through ENB Shaders.

## That's It!
Thank you for using my mod list for your modded Skyrim SE adventures! If you encounter an issue while running these mods or have a suggestion for an update to this page, please create a new issue [here](https://github.com/C-Stew/SkyrimSE-Modlist/issues). You can also submit an issue to suggest mod additions to the list.
