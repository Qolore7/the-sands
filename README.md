<a href="https://www.nexusmods.com/newvegas/mods/81063"><img src="https://staticdelivery.nexusmods.com/mods/130/images/81063/81063-1683589677-1049224095.png" target="_blank"></a>

---

<p align="center">
  <a href="https://www.nexusmods.com/newvegas/mods/81063">Nexus Page</a> ·
  <a href="README.md">Installation</a> ·
  <a href="GAMEPLAY.md">Gameplay Guide</a> ·
  <a href="CHANGELOG.md">Changelog</a> ·
  <a href="https://discord.gg/SZGAXZYtHf">Discord</a> .
</p>

---

# Read-Me

- [Introduction](#introduction)
  - [List Contents](#list-contents)
  - [Requirements](#requirements)
- [Installation](#installation)
    - [Starting the Game](#starting-fallout-new-vegas)
    - [Downloading and Installing](#downloading-and-installing)
    - [Problems with Wabbajack](#problems-with-wabbajack)
- [Startup](#startup)
- [Credits](#credits)

## Introduction

The Sands A modlist focused on making the Mojave Wasteland more deserving of its name. The Sands aims to create difficult gameplay that rewards the player for proper planning and execution, while also improving/re-working copious amounts of vanilla content. New content has also been added to flesh out areas of the game I felt were lacking, but all new content is of an extremely high quality and integrates seamlessly into the game world.
## List Contents

You can browse the full list contents [here](https://loadorderlibrary.com/lists/the-sands) if you want to know exactly what you're getting.

You can find a summary of all changes on the [Gameplay Changes](GAMEPLAY.md) page.

## Requirements:

- An fresh installation of the **English** version of the game with the all of the DLCs from Steam or GOG
  * Only the English version is supported. I understand that this may be frustrating for non-English speaking users, but due to the core file differences between the different versions, only one version can be supported. 
  * The game MUST be installed outside of any default Windows folders, such as `Program Files`, your `Desktop`, or `Documents`. If you have your Steam library in any of these locations, please follow [these](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) instructions to move it.

- [Microsoft Visual C++ Redistributable Package](https://aka.ms/vs/16/release/vc_redist.x64.exe)

- The latest release of [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases) installed outside of any default Windows folders.

# Installation:

## Starting Fallout New Vegas
Start the game and exit once you're at the main menu. This will ensure any settings files needed by Wabbajack are created.

## Downloading and Installing

The download and installation process can take a little while (an hour or more) depending on your system specs. For optimal speed, it is advised to install Wabbajack and the modlist to an SSD.

1. Create a folder for the modist outside of any default Windows folders called **The Sands** (I recommend `C:\Games\The Sands`) 
3. Launch the Wabbajack app and select `Browse Modlists`
4. Make sure `Show Unofficial Lists` is checked and search for `The Sands`
5. Select the **Download** icon in the bottom right, then select he **Play** icon once the download is finished
7. In the **Modlist Installation Location** box, select the `The Sands` folder you created in the first step
  * The Resource Download Location box should automatically fill in `The Sands\Downloads`, but you can move this folder to a different drive if are low on space
8. Click the Go/Begin button and wait for Wabbajack to finish

## Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you won't lose any progress.

**REMINDER:** This list does not work with non-English and non-Steam/GOG versions of the game. 

If you have any other installation issues, I may need to update the list. Please drop by the [Discord](https://discord.gg/SZGAXZYtHf) to report any errors!

# Startup

Open the installation folder and double click on the program called `ModOrganizer.exe`.

Right-click on the mod in the left pane called `4GB Patcher` and seelct **Open in Explorer**

> IMPORTANT: The 4GB Patcher is still needed with the GOG version of the game for the NVSE integration

Inside the opened folder, move `FNVPatcher.exe` to the game's `Root` folder (i.e. where you installed Fallout New Vegas)

Once the file has been moved, double-click `FNVPatcher.exe` to run the patcher 

A command prompt should show up and read:
`Patching FalloutNV.exe [US]...
FalloutNV.exe patched!
Press any key to continue . . .`

Exit out of the command prompt and make sure that the `4GB Patcher` mod is enabled in the left pane of MO2

Make sure the dropdown box on the right is set to `New Vegas` and press the Run button.

You're all set! Everything is already configured by default so you can hope right into a new game!

## Optional Steps

### BSA Decompressor

The BSA Decompressor is a tool that can provide marginally improved performance and decreased load times. It is only optional due to Wabbajack not being able to handle how it modifies files from the base game. It is very easy to do and is highly recommended.

1. Navigate to the `Tools\BSA Decompressor` folder inside of the folder you installed `The Sands` to
2. Run `FNV BSA Decompressor.exe` and make sure the filepath is correctly detecting your Fallout New Vegas installation location
3. Select **Decompress** and wait for the installer to finish (can take up to a few minutes)
  > If you get a message about `Fallout - Misc.bsa` already being modified, then you did not properly do a clean installation of the game!
4. Done! Simply exit the program and you are good to go.

### DXVK and New Vegas Reloaded

There are two optional mods in The Sands that users may want to experiement with. These mods are located under the `Optional` separator at the bottom of the left pane in Mod Organizer 2. First is [DXVK](https://www.nexusmods.com/newvegas/mods/79299). DXVK essentially makes the game use the much faster Vulkan renderer instead of DirectX 9. IT IS VERY IMPORTANT that if you want to try DXVK, you check the mod description linked above for details. DXVK's benefits vary widely system-to-system and it may not be right for you. The second optional mod is New Vegas Reloaded, or NVR. NVR is a brand new rendering pipeline for the game that, among other incredible features, adds real-time shadows and ambient occlusion to the game. NVR is what is used in all of the screenshots for The Sands. NVR is still fairly experimental, and therefore can be very performance intensive and/or slightly buggy. It is recommended to enable at your own discretion. If you do decide to enable NVR, it is highly recommended to disable New Vegas Heap Replacer, as they often do not play well together.

# Credits

Thanks to [Guitarninja2](https://github.com/Lost-Outpost/dragonborn/commits?author=Guitarninja2) for the read-me format taken from their wonderful [Dragonborn](https://github.com/Lost-Outpost/dragonborn) modlist.
