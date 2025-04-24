# DigitalMapV2  
This mod expands the capabilities of the digital map by adding a directional cursor and a built-in radar.  

**⚠️WARNING⚠️ This mod is designed to work with VotV-082b_0016. Using older or newer versions of the game may cause errors!**  

If you have any suggestions or find a bug, you can submit it as an "issue" in my [GitHub repository](https://github.com/Acitulen/DigitalMapV2).

# Configs:
Configs can be accessed in the game settings under the **Mod configs** category or by pressing **Ctrl+Shift+C**.

**RadarPointSize** – Changes the size of radar points. Default value: `1.8`  
**PlayerIconSize** – Changes the size of the player icon. Default value: `1.8`  
**CoordinatesSize** – Changes the size of the coordinates display text. Default value: `1.8`  
**DebugMode** – Enables a debug widget that shows more information about radar actors. Default value: `false`  
**DebugModeDelay** - Changes the delay of debug mode widget update. Default value: `0.1`  
**ExcludedActors** – A list of objects that won't be shown on the digital map or debug widget (use `,` as a separator). Default value: `prop_ABFriend_c,NewBlueprint8_c`  


## Preview  
![Preview](https://github.com/Acitulen/DigitalMapV2/blob/1.4.0/Preview/Preview1.png?raw=true)  

## Features  
- Displays the player's direction.  
- Displays entities.  
- Different colors for radar blips (requires the radar colors module).  
- Different entity scanning speeds (depends on the radar speed module upgrade).  
- Customizable map elements.  

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
   *You have to create the `Acitulen-DigitalMapV2` folder manually.  
</details>
