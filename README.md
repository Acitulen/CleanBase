# CleanBase
This mod makes the base and windows cleaner by removing some cracks, stains and blood spots.   
  
**⚠️WARNING⚠️ This version of CleanBase mod is designed to function with VotV 0.9.0j. Using older or newer versions of the game may cause errors!**  

If you have any suggestions or encounter a bug, you can submit it as an issue on my [GitHub repository](https://github.com/Acitulen/CleanBase).

---

# **Configs**
Configs can be accessed in the game settings under the **Mod configs** category or by pressing **Ctrl+Shift+C**.

- **RemoveBranch** - Removes the branch sticking out of the ground.   
  **Default:** `true`
 
- **CleanGlass** - Sets main base window to be always clean.   
  **Default:** `true`

- **RemoveGrime** - Cleans and fixes all base walls and floors from stains and cracks.   
 
- **RemovePiles** - Removes trash piles.   
---

# Preview



<details>
<summary>Examples</summary>


![Preview](https://github.com/Acitulen/CleanBase/blob/1.1.1/Preview/Stick.gif?raw=true)

![Preview](https://github.com/Acitulen/CleanBase/blob/1.1.1/Preview/Window.gif?raw=true)

</details>

# Features  

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

1. Copy `CleanBase.pak` from the `pak` folder to `GAME/Content/Paks/LogicMods` directory. 
</details>
