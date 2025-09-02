# CleanBase
This mod makes the base and windows cleaner by removing some cracks, stains and blood spots.   
  
**⚠️WARNING⚠️ This version of CleanBase is designed to function with VotV 0.8.2c_0011. Using older or newer versions of the game may cause errors!**  

If you have any suggestions or encounter a bug, you can submit it as an issue on my [GitHub repository](https://github.com/Acitulen/CleanBase).

---

# **Configs**:
Configs can be accessed in the game settings under the **Mod configs** category or by pressing **Ctrl+Shift+C**.

- **RemoveBranch** - Sets the keybind to open main debug menu.  
  **Default:** `true`
 
- **CleanGlass** - Removes the branch sticking out of the ground.  
  **Default:** `true`

---

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

* Replaced 35 textures.  
 *[Version without texture replacements](https://github.com/Acitulen/CleanBase/raw/refs/heads/1.1.0/CleanBaseLite/CleanBaseLite.zip)  
* Main base window is always clean.  
 *Can be disabled in configs.  
* Removed the branch sticking out of the ground.  
 *Can be disabled in configs.  
---

## Manual installation guide.

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

<summary>Install CleanBase</summary>

1. Copy `CleanBase.pak` and `CleanBase_p.pak` from the `pak` floader to `GAME/Content/Paks/LogicMods` directory. 
</details>

*You need to install only one version either CleanBase or CleanBaseLite.  

<details>
<summary>Install CleanBaseLite manually</summary>

1. Download [CleanBaseLite.zip](https://github.com/Acitulen/CleanBase/raw/refs/heads/1.1.0/CleanBaseLite/CleanBaseLite.zip).  
2. Copy `CleanBaseLite.pak` from the `pak` floader to `GAME/Content/Paks/LogicMods` directory.

</details>

<details>
<summary>Install CleanBaseLite in launcher</summary>

1. Download [CleanBaseLite.zip](https://github.com/Acitulen/CleanBase/raw/refs/heads/1.1.0/CleanBaseLite/CleanBaseLite.zip).  
2.  
![Preview](https://github.com/Acitulen/CleanBase/blob/main/LauncherInstalationGuide.png?raw=true)
3. Choose downloaded zip archive and press 'import local mod'
</details>
