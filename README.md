<p align="center">
  <img src="https://github.com/Fingolfin420/Ainulindale/blob/main/page_assets/morgoth_fingolfin.jpg">
</p>

# Ainulindale - A Skyrim Wabbajack Mod List

Ainulindale is a mod list that expands Skyrim's visuals, overhauls locations, and includes minor combat tweaks. It doesn't go overboard changing game mechanics. Expect lots of city and location overhauls and great (imo) visuals. 

I named it Ainulindale because Skyrim modding seemed (still seems) to get me completely engrossed in a fantasy world, just like how I felt when I first read the Silmarillion. But don't worry, this isn't a Tolkien themed mod list. It retains what makes Skyrim, Skyrim, while bringing it closer to a modern game.

# [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/163572) | [Load Order Library](https://loadorderlibrary.com/lists/ainulindale-2) | Gameplay Guide | Changelog

>[!IMPORTANT]
>Ainulindale requires the four free AE mods (Fishing, Rare Curios, Survival Mode, and Saints and Seducers) included in the Skyrim Anniversary Edition update from November 2021. This modlist does **NOT** utilize the AE DLC, only these four free AE mods are used.

>[!WARNING]
>You must update Skyrim to the latest version (1.6.1170) on Steam to install this list.

# Table of Contents
1. [Pre-Installation](#pre-installation)
   - [Installing Microsoft Visual C++ and .NET](#installing-microsoft-visual-c-and-net)
   - [Steam Set-Up](#steam-set-up)
   - [Changing The Game Language](#changing-the-game-language)
   - [Installing Creation Club Files](#installing-creation-club-files)
2. [Wabbajack Installation](#wabbajack-installation)
   - [Installing Wabbajack](#installing-wabbajack)
3. [Downloading and Installing Ainulindale](#downloading-and-installing-ainulindale)
4. [Updating the Modlist](#updating-the-modlist)
5. [Removing the Modlist](#removing-the-modlist)

Before installing this list using Wabbajack, there are several pre-installation steps that **MUST** be followed. 

## Pre-Installation

### Installing Microsoft Visual C++ and .NET
1. Install [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe).
2. Install [.NET Runtime 9.X.X Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/9.0).
3. Install [.NET 6.0 Runtime Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.30-windows-x64-installer).

<p align="center">
  <a href="#ainulindale---a-skyrim-wabbajack-mod-list">
    <span>🔼 Back to top</span>
  </a>
</p>

### Steam Set-Up

If you have your Steam Library in Program Files, read [this article](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) by LostDragonist. Locations such as Desktop, Documents, Downloads, OneDrive, etc. *will* cause issues with installing and playing the list.

Alternatively, if you have multiple drives set up for your computer, you can move your steam installation from your Windows C drive to another by following the steps below (images provided).

Go to you steam installation and find your copy of Skyrim Special Edition. Click on the gear icon in the top right, and click on `properties`.

<p align="center">
  <img src="https://github.com/Fingolfin420/Ainulindale/blob/main/page_assets/move_steam_1.png">
</p>

Navigate to `Installed Files`, then click on `move install folder`.

<p align="center">
  <img src="https://github.com/Fingolfin420/Ainulindale/blob/main/page_assets/move_steam_2.png">
</p>

Lastly, choose the drive where you'd like to move the installation to. 

<p align="center">
  <img src="https://github.com/Fingolfin420/Ainulindale/blob/main/page_assets/move_steam_3.png">
</p>

Next, perform the following to ensure steam updates for Skyrim do not interfere with your mod list installation. 

 1. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
 2. Right click on Skyrim SE and click on properties, untick the `Enable Steam Overlay while in-game.`
 3. Please ensure you follow the steps outlined in the [Installing Creation Club Files](#installing-creation-club-files) section.

<p align="center">
  <a href="#ainulindale---a-skyrim-wabbajack-mod-list">
    <span>🔼 Back to top</span>
  </a>
</p>

### Changing the Game Language

>[!WARNING]
>**The English Steam version of Skyrim SE is the only supported version.**

I understand that this may be frustrating for non-English speaking users or users with the GOG/Bethesda.net versions, but due to the core file differences between the different versions, I am only able to support one game version.

To change your Skyrim SE's language:

 1. Right click on Skyrim SE in Steam
 2. Click `Properties`
 3. Click `Language`
 4. Set the Language to `English`

<p align="center">
  <a href="#ainulindale---a-skyrim-wabbajack-mod-list">
    <span>🔼 Back to top</span>
  </a>
</p>

### Installing Creation Club Files
>
>[!WARNING]
> ***Do NOT skip this step or your install may fail!***

Since the 1.6.1130 update (January 17, 2024), Steam has begun including the free Creation Club (CC) files with the base installation of Skyrim. However, these files do not have the same file hash as the files that are downloaded from the in-game **Creations** menu for Anniversary Edition (AE) users. In order to comply with Wabbajack policy and minimize issues for users who own the AE update, Ainulindale is compiled using the versions of the CC content that are obtained from the in-game **Creations** menu.  

As a result of this, for users who do not own the AE, you must ensure that you download the correct version of the CC files. Steps below:

 - Navigate to your Skyrim SE's Steam Data folder
    - e.g. `D:\SteamLibrary\steamapps\common\Skyrim Special Edition\data`
 - Delete *both* Rare Curios files:
    - `ccbgssse037-curios.bsa`
    - `ccbgssse037-curios.esl`
 - Launch Skyrim SE from Steam and select **Creations** at the main menu
 - Select **Search** at the bottom and search for `Rare Curios`
 - Select the card titled `Rare Curios` and press **Download**
 - Once it is done, accept Bethesda's load order message and exit the game

<p align="center">
  <a href="#ainulindale---a-skyrim-wabbajack-mod-list">
    <span>🔼 Back to top</span>
  </a>
</p>

## Wabbajack Installation

### Installing Wabbajack

Once you have completed the pre-installation section, follow these steps to install Wabbajack:

1. Create an empty folder named `Wabbajack` on the root of your drive, such as `C:\Wabbajack` for example.
    > - **DO NOT place it in Program Files, User folders (such as Desktop, Documents, Downloads, OneDrive, etc.), in your Skyrim's Steam folder, or in any folders related to the modlist itself (the downloads or install folder).**
    > - The `Wabbajack` folder does not need to be on an SSD, but it makes installing faster. You can set this location to be on an HDD for the sake of saving space.

2. Download the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe) and place the `Wabbajack.exe` file inside the Wabbajack folder you created in Step 1.

3. Double-click the `Wabbajack.exe` file that is now inside your Wabbajack folder to set up the program.

>[!IMPORTANT]
>The list requires Wabbajack version **4.0.0.0 or later**. Installing the modlist on older versions of Wabbajack will result in issues.

<p align="center">
  <a href="#ainulindale---a-skyrim-wabbajack-mod-list">
    <span>🔼 Back to top</span>
  </a>
</p>

### Downloading and Installing Ainulindale

>[!CAUTION]
>**A legal copy of Skyrim Special Edition is required.** Pirated copies of the game will cause the installation to fail and even if you manage to somehow get around Wabbajack's built-in piracy prevention measures, SKSE does not work with the cracked exes.  

Downloading and installing Ainulindale can take a while depending on your internet connection, PC specs, and if you have Nexus Premium. Without Premium, you will need to manually click the **Slow Download** button for each mod. Nexus Premium is advised for the greatest convenience when installing the mod list. 

To install Ainulindale, complete the following steps:

 1. Open Wabbajack and click `Browse lists`
 2. Pick the **Skyrim Special Edition** option from the game filter drop-down box (or use the search bar to find the modlist). Make sure the "Non-featured" box is checked.
 3. Press the download arrow on the Ainulindale UI card and wait for it to download
 4. Set the `Installation Location` to a folder such as `C:\Ainulindale`.
    > - **DO NOT place it in Program Files, User folders (such as Desktop, Documents, Downloads, OneDrive, etc.), or in your Skyrim's Steam folder**
    > - The `Downloads Location` does not need to be on an SSD, but it makes installing faster. You can set this location to an HDD for the sake of saving space.
 5. Press the `Install` button.
 6. Turn on your favorite show or find something else to do as Wabbajack does its thing. Alternatively read through this readme again.
 7. If the installation is not successful, then try closing Wabbajack and restarting the installation. It should pick up where it left off. 

<p align="center">
  <a href="#ainulindale---a-skyrim-wabbajack-mod-list">
    <span>🔼 Back to top</span>
  </a>
</p>

## Updating the Modlist

Versioning for the list will adhere to the following format: `MAJOR.MINOR.PATCH`.

- `MAJOR`: Any release with a number change here will be considered a major update as at least 1 area of the list was massively overhauled. These updates with **NEVER** be save safe.
- `MINOR`: Any release with a number change here will be considered a minor update, these updates will **not** be save safe, unless otherwise specified.
- `PATCH`: Any release with a number change here will be considered a patch, these updates should be save safe and will be used primarily for bugfixes.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite installation` button. Please keep in mind any mods you have added will be deleted when updating. To make sure that Wabbajack does not delete your added mods upon updating, prefix your mods with `[NoDelete]`.

<p align="center">
  <a href="#ainulindale---a-skyrim-wabbajack-mod-list">
    <span>🔼 Back to top</span>
  </a>
</p>

>[!IMPORTANT]
>Saves can be continued across **Save-Safe** updates. Updates will be indicated whether or not they are **Save-Safe** on the [Changelog](). It is suggested that you backup your saves before updating if you plan on continuing them.

## Removing the Modlist

Simply delete the Ainulindale folder. That's it, you don't have to do anything else. Enjoy!

<p align="center">
  <a href="#ainulindale---a-skyrim-wabbajack-mod-list">
    <span>🔼 Back to top</span>
  </a>
</p>
