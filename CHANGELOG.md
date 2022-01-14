*Use this to check changes across versions, or **if you are updating from an earlier version and aren't reinstalling from scratch**.*
# ~~v1.2~~ v0.3
### *Don't like the way Third Person Play works? Not Anymore.*
***Save files from v1.1 ARE COMPATIBLE **if [3PCO](https://www.nexusmods.com/skyrimspecialedition/mods/18515) is uninstalled properly!***

## Removed Mods:
- [360 Movement Behavior](https://www.nexusmods.com/skyrimspecialedition/mods/33139)
  - Delete through Vortex
  - *The game will warn you about the missing plugin when loading your save post-deletion. Continue anyway.*
- [Simple Lock-On](https://www.nexusmods.com/skyrimspecialedition/mods/18086)
  - Delete **SimpleLockOn.dll** and **SimpleLockOn.ini** from `Data/SKSE/Plugins` in your Skyrim SE installation.
- [3PCO](https://www.nexusmods.com/skyrimspecialedition/mods/18515)
  - **REQUIRES UNINSTALLATION FROM MCM IN-GAME**
  - Do the following **before deleting the mod!**
    - Load your most recent save with 3PCO installed.
    - Open **Mod Configuration** from the **System tab in the Journal**
    - Click `3PCO - 3rd Person Camera Overhaul`
    - Set ***ALL*** settings to default by hovering over each one and pressing **R**
    - Set ***ALL*** crosshairs to ON
    - Go to the **Uninstall** tab and check `Uninstall Mod` and press `Enter` on your keyboard.
    - ***Save your game at this point!***
    - Quit to Desktop and delete the mod from Vortex
  - *The game will warn you about the missing plugin when loading your save post-deletion. Continue anyway.*

## Mod Additions
- [Grass FPS Booster](https://www.nexusmods.com/skyrimspecialedition/mods/20082?tab=files)
  - Select `Performance` and `No`
  - Under Patches, select `Folkvangr`
- [No Grassias](https://www.nexusmods.com/skyrimspecialedition/mods/35639?tab=files)
  - Download **NoGrassias Extended**
- [MCM Helper](https://www.nexusmods.com/skyrimspecialedition/mods/53000?tab=files)
  - Download **MCM Helper SE (1.5)**
- [Realistic Boat Bobbing Patch](https://www.nexusmods.com/skyrimspecialedition/mods/44311?tab=files)
  - Download **Realistic Boat Bobbing - JK's Skyrim**

## Third Person Enhancements (New Section)
- [True Directional Movement](https://www.nexusmods.com/skyrimspecialedition/mods/51614?tab=files)
- [SmoothCam](https://www.nexusmods.com/skyrimspecialedition/mods/41252?tab=files)
  - Select `SmoothCam SSE`
  - Select `ESP`
- [Animation Motion Revolution](https://www.nexusmods.com/skyrimspecialedition/mods/50258?tab=files)
- Add [Verolevi's](https://www.nexusmods.com/users/3812151?tab=user+files&BH=1) animations to cover as much as possible (*basically all but spellcasting/staffs and jumping*).
  - [Vanargand Male Idle Walk and Run](https://www.nexusmods.com/skyrimspecialedition/mods/52488?tab=files)
    - Ignore additional requirements
  - [Vanargand Sprint](https://www.nexusmods.com/skyrimspecialedition/mods/53381?tab=files)
  - [Vanargand Sneak idle walk and run](https://www.nexusmods.com/skyrimspecialedition/mods/54351?tab=files)
  - [Vanargand Sneak Strike Attacks](https://www.nexusmods.com/skyrimspecialedition/mods/55420?tab=files)
    - Download the Main File
  - [Vanargand Sneak Thrust Attacks](https://www.nexusmods.com/skyrimspecialedition/mods/55031?tab=files)
    - Download the Main File
  - [Vanargand Sneak Archery](https://www.nexusmods.com/skyrimspecialedition/mods/56788?tab=files)
  - [Vanargand Archery](https://www.nexusmods.com/skyrimspecialedition/mods/60323?tab=files)
  - [Vanargand One Handed Mid Stance](https://www.nexusmods.com/skyrimspecialedition/mods/57544?tab=files)
  - [Vanargand One Handed Normal Attacks](https://www.nexusmods.com/skyrimspecialedition/mods/58326?tab=files)
  - [Vanargand One Handed Power Attacks](https://www.nexusmods.com/skyrimspecialedition/mods/58997?tab=files)
  - [Leviathan Two-Handed High Stance](https://www.nexusmods.com/skyrimspecialedition/mods/47092?tab=files)
  - [Leviathan Two-Handed Normal Attacks](https://www.nexusmods.com/skyrimspecialedition/mods/48550?tab=files)
  - [Leviathan Two-Handed Power Attacks](https://www.nexusmods.com/skyrimspecialedition/mods/50545?tab=files)
  - Verolevi's [Modern SmoothCam Preset](https://www.nexusmods.com/skyrimspecialedition/mods/41636?tab=files)
    - Right Alt : Toggle full body portrait mode.
    - C : Shoulder swap
- [YY Animation Replacer - Mystic Knight](https://www.nexusmods.com/skyrimspecialedition/mods/9179?tab=files)
  - Select `Magic` Idle Animation, `Magics` Equip/Unequip Animation, ALL boxes in **Magics** and **Casting**, and ALL BUT `Master Spell` in **Casting Animations**
- [Light Foot - Jumping Animation SSE](https://www.nexusmods.com/skyrimspecialedition/mods/5106?tab=files)
- [Dynamic Swimming](https://www.nexusmods.com/skyrimspecialedition/mods/34853?tab=files)
- [Look what you see](https://www.nexusmods.com/skyrimspecialedition/mods/19189?tab=files)
  - Select `ESP`

## LOOT/SSEEdit
N/A

## In-game Changes
First, we need to update MCM's Menus
- After loading your save file, open the console using **~**
- Type `setstage ski_configmanagerinstance 1`
- Close the console using **~** and wait until you see `SkyUI - Registered # New Menus` in the top left

Now, go to the System tab in the Journal and open **Mod Configuration**
- Click `Look what you see !`
  - Hover over each of the keybinds and press **R**
  - Go to the previous menu
- Click `SmoothCam`
  - Select `Presets` on the left
  - Under **Load Preset**, check **Slot 4** and press Enter twice
  - Go to the previous menu
- Scroll down and click `True Directional Movement`
  - Select `Target Lock` on the left and set your keybinds under the right menu
  - Select `Boss Bar Widget` on the left and uncheck **Show Boss Bar**
    - The boss bar doesn't update properly, so I don't use it.

To ensure changes take effect, save your game and reload the save. 

---

# v1.1
### *Got bored. Scrolled through Nexus Mods for a few hours. Here's the result.*
***Save files from v1.0 are INCOMPATIBLE with v1.1!***

*Remember, download mods through Vortex unless otherwise specified!*

## Added Mods:
- [ENB Helper SE](https://www.nexusmods.com/skyrimspecialedition/mods/23174/?tab=files)
  - **For ENB users only**
  - Download **ENB Helper SE 1.5 for SSE 1.5.97**
- [HD LODs Textures SE](https://www.nexusmods.com/skyrimspecialedition/mods/3333?tab=files)
  - Download **HD Lods Textures SE V9.0 512 - Performance friendly** from Optional Files.
  - Load HD LODs BEFORE Majestic Mountains
  - Hit `Deploy`
- [Better Dialogue Controls](https://www.nexusmods.com/skyrimspecialedition/mods/1429?tab=files)
- [Better Messagebox Controls](https://www.nexusmods.com/skyrimspecialedition/mods/1428?tab=files)
- [Auto Hide Ammo](https://www.nexusmods.com/skyrimspecialedition/mods/1882?tab=files)
- [SSE Display Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/34705?tab=files)
- [D13 Faster GET UP](https://www.nexusmods.com/skyrimspecialedition/mods/5890?tab=files)
  - Download **D13 Faster Get Up Stand Up SSE**
- [NPC's Run and Walk at Your Pace](https://www.nexusmods.com/skyrimspecialedition/mods/2482?tab=files)
- [Lore-Based Loading Screens](https://www.nexusmods.com/skyrimspecialedition/mods/1185?tab=files)
- [DLL Plugin Loader](https://www.nexusmods.com/skyrimspecialedition/mods/10546?tab=files)
  - **It is CRUCIAL you follow the below instructions, otherwise removing this mod makes the game unplayable!**
  - **BEFORE DOWNLOADING**, navigate to your Skyrim SE installation in File Explorer (the folder with SkyrimSE.exe).
  - Rename **binkw64.dll** to **binkw64_.dll** by right-clicking the file and selecting `Rename`.
  - Download the .zip to the **same folder as SkyrimSE.exe**.
  - Open **DLL Plugin Loader v1-10546-1.zip** and copy the .dll to the folder containing **SkyrimSE.exe**.
- [.NET Script Framework](https://www.nexusmods.com/skyrimspecialedition/mods/21294?tab=files)
- [3rd Person Camera Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/18515?tab=files)
  - *You can change the camera settings using the Mod Configuration Menu in-game.
- [Simple Lock-On SE](https://github.com/NasiRawon/SimpleLockOn/releases/tag/v2.1.2)
  - The Nexus version is too outdated to work, but the GitHub version works.
  - Download **Simple.Lock-On.v2.1.2.7z** to your Skyrim SE installation (the folder with SkyrimSE.exe).
  - Right-click it and select `7-Zip >`, then `Extract Here`
  - Now, open the `Data` folder, then `SKSE`, then `Plugins`.
  - Open **SimpleLockOn.ini** with your desired text editor.
    - Here is where the hotkey for targeting is set.
    - Use [this link](https://www.creationkit.com/index.php?title=Input_Script#DXScanCodes) and find your desired keybind by using `CTRL+F` and typing it.
    - Once you find it, copy the **Dec** code (numerical value to the left of the name) and paste it in place of `42` in the INI file.
    - Save the file and close your text editor.
- [Simple Lock-On SE Reticle Replacers](https://www.nexusmods.com/skyrimspecialedition/mods/18138?tab=files)
  - Select `Circle with name`
- [Diverse Werewolves Collection SE](https://www.nexusmods.com/skyrimspecialedition/mods/7009?tab=files)
- [Follower Trap Safety](https://www.nexusmods.com/skyrimspecialedition/mods/2755?tab=files)
- [Smaller Vanilla Cursors SE](https://www.nexusmods.com/skyrimspecialedition/mods/20617?tab=files)
  - **100% Optional**
  - `Right` is recommended
- [Fences of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/5664?tab=files)
  - Download **Fences of Skyrim**
  - Load Fences of Skyrim AFTER all conflicting files
  - Hit `Deploy`
- [Realistic Boat Bobbing SE](https://www.nexusmods.com/skyrimspecialedition/mods/26080?tab=files)
  - Download **Realistic Boat Bobbing SE** and **RBB - SMIM Meshes** (under Optional Files)
  - Load the mod BEFORE the SMIM patch
  - Hit `Deploy`
- [Skyrim Priority SE AE](https://www.nexusmods.com/skyrimspecialedition/mods/50129?tab=files)
  - Download the Main File
- [eFPS](https://www.nexusmods.com/skyrimspecialedition/mods/54907?tab=files)
  - Also download its [Official Patch Hub](https://www.nexusmods.com/skyrimspecialedition/mods/54998?tab=files)
    - Leave first page unchecked
    - Check `JK's Skyrim - Complete`
    - Leave all other pages unchecked
- [First Person Sneak Strafe-Walk Stutter Fix](https://www.nexusmods.com/skyrimspecialedition/mods/31165?tab=files)
- [Crime Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/19647?tab=files)
- [Crime Overhaul Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/35853?tab=files)
  - Download **Crime Overhaul Fixes** and **Crime Overhaul - Cutting Room Floor Patch** (under Optional Files).
  - Load Crime Overhaul BEFORE its fixes and Cutting Room Floor patch
  - Hit `Deploy`
- [Crime Bounty Decay SE](https://www.nexusmods.com/skyrimspecialedition/mods/25457?tab=files)
- [NARC Remade](https://www.nexusmods.com/skyrimspecialedition/mods/17946?tab=files)
  - Select `NARC`
  - Leave patches unchecked
- [BlockSteal](https://www.nexusmods.com/skyrimspecialedition/mods/18732?tab=files)
  - Download **Blocksteal_010_SKSE2017**
- [Serana's Hood Fix](https://www.nexusmods.com/skyrimspecialedition/mods/20243?tab=files)
  - Select `Realistic`
- [Dragon Souls to Perk Points](https://www.nexusmods.com/skyrimspecialedition/mods/2879?tab=files)
  - Download the Main File
- [Security Overhaul SKSE](https://www.nexusmods.com/skyrimspecialedition/mods/58224?tab=files)
  - Select `2K Textures` (recommended) and `SSE v1.5.97`
- [No Silly Physics Damage](https://www.nexusmods.com/skyrimspecialedition/mods/36132?tab=files)
- [Bed Head](https://www.nexusmods.com/skyrimspecialedition/mods/8528?tab=files)
  - Download **Bed Head V.2.3 Brown Fabric**
  - **If using ENB**, also download the Normal Map Replacers from Optional Files.
  - Load Bed Head BEFORE its Normal Map Replacer
  - Hit `Deploy`
- [Rude Imperial Soldiers Escort Prisoner fix](https://www.nexusmods.com/skyrimspecialedition/mods/894?tab=files)
- [360 Movement Behavior SE](https://www.nexusmods.com/skyrimspecialedition/mods/33139?tab=files)

## LOOT/SSEEdit
Open **LOOT** and Sort Plugins using the three lines icon in the top right.
- **Crime Overhaul.esp** has 3 ITM records that need cleaned.
- **Realistic Boat Bobbing.esp** has two notices about unused patches. These can be ignored.
Close LOOT and open **SSEEditQuickAutoClean.exe**
- Find **Crime Overhaul.esp** and click its checkbox.
- Click `OK` in the bottom right.
- Close SSEEdit once it finishes.
