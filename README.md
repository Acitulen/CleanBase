# **CleanBase**
This mod makes the base cleaner by removing some cracks, stains and blood spots.

# Preview



<details>
<summary>Examples</summary>


![Preview](https://github.com/Acitulen/CleanBase/blob/main/Gifs/CBP1.gif?raw=true)

![Preview](https://github.com/Acitulen/CleanBase/blob/main/CBP2.gif?raw=true)

![Preview](https://github.com/Acitulen/CleanBase/blob/main/CBP3.gif?raw=true)

![Preview](https://github.com/Acitulen/CleanBase/blob/main/CBP4.gif?raw=true)

![Preview](https://github.com/Acitulen/CleanBase/blob/main/CBP5.gif?raw=true)

![Preview](https://github.com/Acitulen/CleanBase/blob/main/CBP6.gif?raw=true)

![Preview](https://github.com/Acitulen/CleanBase/blob/main/CBP7.gif?raw=true)


</details>

# Features: 
## Objects:
This interface section allows to manipulate with all objects in a world.
- Get location of all objects of the class.  
*You can open variable inspector for located objects by pressing 'data' button.
- Teleport player to found objects (Tp to).
- Teleport objects to a player (Tp here).
- Teleport all objects to a player.
- Delete all objects of the class.


## Stats:
This interface section gives information about different important statistics in VotV and allows to manipulate some of them.
- Get information about ariral reputation.
- Set ariral reputation.
- Show the information about the amount of power left in transformers.
- Restore power in transformers.
- Get information about the status of servers.
- Break/fix/protect all servers.

## Base settings:
This interface section gives the ability to control states of the base.
- Turn on/off all the lights.
- Clean all base walls and floors from stains. 
- Get rid of all useless (non-recyclable) rubbish.
- Fix broken radio tower.

## World settings:
This interface section gives the ability to control some world settings.
- Disable annoying unsolvable labyrinth (backrooms).
- Open portable version of base console terminal. 
- Open menu that gives ability to travel across different levels (not saves).  
*Some levels may crash game.
- Open menu that allows you to run some events.  
*Most of events can only start in story mode.
- Open menu that allows you to create waypoints and teleport to them.
- Change speed of day/night cycle.

## Player settings:
This interface section gives the ability to control some player stats.
- Make player immortal.
- Make player satiety non-consumable (75%+).
- Make player sleepiness non-consumable (75%+). 
- Make flashlight charge endless (100%).
- Toggle spectator mode.


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
