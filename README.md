# **DigitalMapV2**  
#### This mod expands the capabilities of the digital map by adding a directional cursor and a built-in radar.

## Preview  
![Preview](https://github.com/Acitulen/DigitalMapV2/blob/main/Preview_1.3.0.png?raw=true)  

## Features  
- Displays the player's direction.  
- Displays entities.  
- Different colors for radar blips (requires the radar colors module).  
- Different entity scanning speeds (depends on the radar speed module upgrade).  
- Customizable map elements.  

## Configs  
- **RadarPointSize** – Changes the size of radar points. Default value: `1.8`  
- **PlayerIconSize** – Changes the size of the player icon. Default value: `1.8`  
- **CoordinatesSize** – Changes the size of the coordinates display text. Default value: `1.8`  
- **DebugMode** – Enables a debug widget that shows more information about radar actors while holding the digital map. Default value: `false`  
- **ExcludedActors** – A list of objects that won't be shown on the digital map or debug widget (use `,` as a separator). Default value: `prop_ABFriend_c,NewBlueprint8_c`  

## Manual Installation Guide  

<details>  
<summary>Install Unreal Shimloader</summary>  

1. Copy `dwmapi.dll` into the `GAME/Binaries/Win64` directory. The new path should be `GAME/Binaries/Win64/dwmapi.dll`.  
2. Copy the contents of the `UE4SS` folder from the package into `GAME/Binaries/Win64`.  

`GAME/Binaries/Win64` should now contain the following *new* files and folders:  
- `GAME-Win64-Shipping.exe`  
- `ue4ss.dll`  
- `UE4SS-settings.ini`  
- `dwmapi.dll` ← *This is the Unreal Shimloader binary. It will load UE4SS for you.*  
- `Mods/`  
</details>  

<details>  
<summary>Install DigitalMapV2</summary>  

1. Copy `DigitalMapV2.pak` from the `pak` folder to the `GAME/Content/Paks/LogicMods` directory.  
2. Copy the contents of the `mod` folder to `GAME/Binaries/Win64/Mods/Acitulen-DigitalMapV2`.  
   - You have to create the `Acitulen-DigitalMapV2` folder manually.  
</details>
