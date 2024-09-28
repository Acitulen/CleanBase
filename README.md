# **CleanBase**
This mod makes the base cleaner by removing some cracks, stains and blood spots.

# Preview



<details>
<summary>Examples</summary>


![Preview](https://github.com/Acitulen/CleanBase/blob/main/Gifs/CBP1.gif?raw=true)

![Preview](https://github.com/Acitulen/CleanBase/blob/main/Gifs/CBP2.gif?raw=true)

![Preview](https://github.com/Acitulen/CleanBase/blob/main/Gifs/CBP3.gif?raw=true)

![Preview](https://github.com/Acitulen/CleanBase/blob/main/Gifs/CBP4.gif?raw=true)

![Preview](https://github.com/Acitulen/CleanBase/blob/main/Gifs/CBP5.gif?raw=true)

![Preview](https://github.com/Acitulen/CleanBase/blob/main/Gifs/CBP6.gif?raw=true)

![Preview](https://github.com/Acitulen/CleanBase/blob/main/Gifs/CBP7.gif?raw=true)


</details>

# Features: 

* Replaced 34 textures.  
 *[Version without texture replacements](https://github.com/Acitulen/CleanBase/raw/refs/heads/main/CleanBaseLite/CleanBase.zip)  
* Main base window is always clean.  
 *Can be disabled in configs.  
* Removed the branch sticking out of the ground.  
 *Can be disabled in configs.  
 *You need to reenter the world to apply configs.



## Manual instalation guide.

<details>
<summary>Install unreal shimloader</summary>

1. Copy `dwmapi.dll` into the `GAME/Binaries/Win64` directory. Its new path should be `GAME/Binaries/Win64/dwmapi.dll`.
2. Copy the contents of the `UE4SS` folder in the package into `GAME/Binaries/Win64`.

`GAME/Binaries/Win64` should now contain the following *new* files and folders:
- `GAME-Win64-Shipping.exe`
- `ue4ss.dll`
- `UE4SS-settings.ini`
- `dwmapi.dll` ← *This is the unreal-shimloader binary. It will load UE4SS for you.*
- `Mods/`
</details>

<details>
<summary>Install VoidMod-2.0.0</summary>

1. Copy `VoidMod2.pak` from the pak floader to `GAME/Content/Paks/LogicMods` directory. 
</details>

<details>
<summary>Install Fusion</summary>

1. Copy `everything (except mod floader)` from the archive to `GAME/Binaries/Win64/Mods/NynrahGhost-Fusion` directory.  
*you have to create `NynrahGhost-Fusion` floader manually.
2. Copy the contents of the `mod` folder in `GAME/Binaries/Win64/Mods/NynrahGhost-Fusion` directory.
3. Create floader `Bina` in `GAME` directory
4. Make an empty `mods.yml` file in `GAME/Bina` directory.
5. Run `Fusion.exe` from `GAME/Binaries/Win64/Mods/NynrahGhost-Fusion` directory.
</details>
<details>

<summary>Install CleanBase</summary>

1. Copy `CleanBase.pak` from the `pak` floader to `GAME/Content/Paks/LogicMods` directory. 
2. Copy the contents of the `mod` folder in `GAME/Binaries/Win64/Mods/Acitulen-CleanBase` directory.  
*you have to create 'Acitulen-CleanBase' floader manually.
3. Run `Fusion.exe` from `GAME/Binaries/Win64/Mods/NynrahGhost-Fusion` directory.
</details>
