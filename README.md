# PS4 Complete Guide!

This repository contains a complete guide on how to install HEN (Hombrew ENabler) on your PlayStation 4 and everything to do with it. If you're in 9.00 you need to have a USB Flash Drive and an Internet Connection, and if you're on 5.05 you don't need any external components or anything just an Internet Connection to a website that can be either self hosted or visited if hosted.

## Up-to-Date?

Every single file of this guide links to the repository release's. And every single file was downloaded from the original source. If you want check if there's any outdated files, simply go to releases and all links will either redirect you to the original source or a section where the original source link is written in a word. (If you found out an outdated app, pull a request for others)

### Last Check

- HEN Guide: Up-to-date for 5.05 and 9.00
- Installation: Cannot be outdated.
- Modify: Cannot be outdated, if there's any more, easier or advanced modifying or patches and etc. I will try to cover it.
- Customize: Cannot be outdated, if there's any more, easier or advanced customizing i will try to cover it.
- Online Services (PSN): Sadly, there's no way to connect to PSN services without updating to the latest firmware.
    - Note: I am aware of saving a flash dump, so you can update and revert later. But these methods use soldering which will not be covered.

# Repository Navigation

As this repository almost covers everything you can do with your PlayStation 4, it has a lot of pages, but easy to follow. And I suggest that you follow the guide as numbered:

1. **[HEN Wiki](#hen-wiki)**
2. **[PKG-files](#pkg-files)**
3. **[HEN-Plugins](#goldhen-plugins)**
- **[User - PSN, Savedata](#user)**
- **[XMB - Customize](#xmb)**
- **[Others](#others)**


## HEN Wiki

This section contains a guide on how to install (Homebrew ENabler) on your PlayStation 4, and how to:

### CFW Wiki Navigation

1. **[Preparing](https://github.com/ZHassanQ/PS4-Guide/wiki/1.-Preparing)**
    - [Firmwares](https://github.com/ZHassanQ/PS4-Guide/wiki/1.-Preparing#firmwares)
      - [What to Choose?](https://github.com/ZHassanQ/PS4-Guide/wiki/1.-Preparing#what-to-choose)
    - [Compatibility](https://github.com/ZHassanQ/PS4-Guide/wiki/1.-Preparing#compatibility)
      - [Settings](https://github.com/ZHassanQ/PS4-Guide/wiki/1.-Preparing#settings)
2. **[Self Host](https://github.com/ZHassanQ/PS4-Guide/wiki/2.-Websites,-Host))**
    - [Websites](https://github.com/ZHassanQ/PS4-Guide/wiki/2.-Websites,-Host#websites)
      - [Online](https://github.com/ZHassanQ/PS4-Guide/wiki/2.-Websites,-Host#online)
      - [Offline, Self Host](https://github.com/ZHassanQ/PS4-Guide/wiki/2.-Websites,-Host#offline-self-host)
        - [Entering the Website](https://github.com/ZHassanQ/PS4-Guide/wiki/2.-Websites,-Host#entering-the-website)
3. **[9.00 Magic USB Setup](https://github.com/ZHassanQ/PS4-Guide/wiki/3.-9.00-Magic-USB-Setup)**
    - [Setup](https://github.com/ZHassanQ/PS4-Guide/wiki/3.-9.00-Magic-USB-Setup#setup)
      - [Image-file](https://github.com/ZHassanQ/PS4-Guide/wiki/3.-9.00-Magic-USB-Setup#image-file)
      - [The Magic Drive](https://github.com/ZHassanQ/PS4-Guide/wiki/3.-9.00-Magic-USB-Setup#the-magic-drive)
        - [Injecting the exploit](https://github.com/ZHassanQ/PS4-Guide/wiki/3.-9.00-Magic-USB-Setup#injecting-the-exploit)
        - [Reset "System Volume Information"](https://github.com/ZHassanQ/PS4-Guide/wiki/3.-9.00-Magic-USB-Setup#reset-system-volume-information)
      - [Resetting the whole drive](https://github.com/ZHassanQ/PS4-Guide/wiki/3.-9.00-Magic-USB-Setup#resetting-the-whole-drive) 
4. **[GoldHEN](https://github.com/ZHassanQ/PS4-Guide/wiki/4.-GoldHEN)**
    - [Inject Exploits](https://github.com/ZHassanQ/PS4-Guide/wiki/4.-GoldHEN#injecting-the-exploit)
      - [Notes](https://github.com/ZHassanQ/PS4-Guide/wiki/4.-GoldHEN#notes)

## PKG-files

This section is important for nearly everything, if you want to know how install PKG-files, or why they aren't installing. And how to modify or, patch them and more.

### Installation

In **"PKG-Installation"** file there's a tutorial on how to install PKG files wether they were Game, Game Update, Game's DLC, Themes, Hombrew apps.

🧭 Table of Contents
1. 🧪 Integrity Check:
    - **[Compatiblity to System](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Installation.md#compatibility-to-system)**
    - **[Compatiblity to BASE](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Installation.md#compatiblity-to-base)**
2. ⚙️ Installation
    - **[Flash Drive](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Installation.md#flash-drive)**
    - **[Internal Storage](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Installation.md#internal-storage)**
    - **[Internet Connection](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Installation.md#internet-connection)**
3. 🧰 Installation Errors
    - **[Error #1](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Installation.md#error-1)**
    - **[Error #2](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Installation.md#error-2)**


### Modify

In **"PKG-Modify"** file there's a tutorial on how to modify PKG files with many things; with PS4-AIO app.

🧭 Table of Contents

1. 🗃️ Marry:
    - **[Remarry](#%EF%B8%8F-1-remarry-game--update)**
    - **[Merge](#%EF%B8%8F-2-5-merge-game--update--backport)**
2. 🛠️ Backports:
    - **[Backup](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Modify.md#%EF%B8%8F-3-backup-backports-files)**
    - **[Reverse](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Modify.md#%EF%B8%8F-4--ps4-rebuild-pkg---backport)**
3. 💊 DLCs:
    - **[Region](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Modify.md#-7-dlc---change-region)**
    - **[Unlock](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Modify.md#-8-ps4-dlc-unlocker)**
    - **[Restore Data](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Modify.md#-9-without-data-dlc-to-data-dlc)**
    - **[Remove Data](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Modify.md#-10-data-dlc-to-without-data-dlc)**
4. 🧩 Others
    - **[Fix Game Info](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Modify.md#-6-fix-game-info)**


### Patches

In file "PKG-Patches.md" file there will more things you can do with your PKG games. Like cheat and modify ingame values, or removing assets to save some space.


🧭 Table of Contents
- **[Cheats and Modifications](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Patches#cheats-and-modifications)**
    - [GoldHEN Cheats Manager](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Patches#goldhen-cheats-manager)
- **[Storage (Removing Assets)](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Patches#storage-removing-assets)**
    - [PKG-Ripper](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Patches#pkg-ripper)


## GoldHEN Plugins

I highly recommend using [GoldHEN Plugins](https://github.com/GoldHEN/GoldHEN_Plugins_Repository) as they have many customizable and important features, and i will list some of them:

- **[Swap Buttons:](https://github.com/GoldHEN/GoldHEN_Plugins_Repository#button-swap)** Swap X and O buttons.
- **[Force 1080p:](https://github.com/GoldHEN/GoldHEN_Plugins_Repository#force-1080p-display)** Forces 1080p display.
- **[Force 30Fps:](https://github.com/GoldHEN/GoldHEN_Plugins_Repository#force-30-fps)** Limits to 30Fps.
- **[Fliprate Remover:](https://github.com/GoldHEN/GoldHEN_Plugins_Repository#fliprate-remover)** Removes the framerate limit if used by the game.
- **[No Share Blocks](https://github.com/GoldHEN/GoldHEN_Plugins_Repository#no-share-blocks)** Removes image watermark video and screenshot blocks from games.
- **[GamePad Helper](https://github.com/GoldHEN/GoldHEN_Plugins_Repository?tab=readme-ov-file#gamepad-helper-plugin)** Customize deadzone, touchpad, button mapping, and viration intensity.

    - To install any of them, follow these [simple steps.](https://github.com/GoldHEN/GoldHEN_Plugins_Repository?tab=readme-ov-file#quick-start)
    - You can see the plugins sources [here.](https://github.com/GoldHEN/GoldHEN_Plugins_Repository/tree/main/plugin_src)

### GoldHEN Cheats Manager

Patches your games in many different ways, and you too can create patches. Visit this link if you want to see [how to.](https://github.com/GoldHEN/GoldHEN_Patch_Repository#developing-patches) To use or install any of them use the app (GoldHEN Cheats Manager) or Itemzflow Game Manager.

Mostly the patches are:

- Lowering resolution for more framerate or vice versa.
- Godmode and etc.
- Debug Menu.

## User

This section is optional, if you want to know how to use your real `ACC_ID` so that every savedata is automatically signed for your account, and etc. Then follow this section.

### PSN - Savedata

In **"PSN-Savedata.md"** file, there's a tutorial on how to create an activated PSN either from real account or a fake ID. And how to install encrypted savedata that are not signed to your account, and more. All that using "Apollo Save Tools". If you haven't already installed it go to **[PKG-Installation.md](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Installation.md)** to see how to install PKG-files in many different ways, and what to do if an there are an errors.

🧭 Table of Contents

1. 🌍 PSN ID:
    - **[Fake PSN ID](https://github.com/ZHassanQ/PS4-Guide/blob/main/PSN-Savedata.md#-fake-psn-id)**
    - **[Real PSN ID](https://github.com/ZHassanQ/PS4-Guide/blob/main/PSN-Savedata.md#-real-psn-id)**
2. 💾 Savedata:
    - **[Encrypted](https://github.com/ZHassanQ/PS4-Guide/blob/main/PSN-Savedata.md#-encrypted)**
    - **[Region Change](https://github.com/ZHassanQ/PS4-Guide/blob/main/PSN-Savedata.md#-region-change)**
    - **[Retail](https://github.com/ZHassanQ/PS4-Guide/blob/main/PSN-Savedata.md#-fpkg-to-retail)**

## XMB

This section is optional, if you want to see how you can customize your XMB by, changing games icons, and/or the main theme, music of your PlayStation 4 and more.

### Customize

In **"XMB-Customize.md"** file there's a tutorial on how to customize your PS4 Home Screen with changing your Profile Picture, Login Intro, Main Music, Apps Icons, and Hiding Apps.

🧭 Table of Contents

1. 🌍 **[Apps:](https://github.com/ZHassanQ/PS4-Guide/blob/main/XMB-Customize.md#-apps)**
    - [Icons](https://github.com/ZHassanQ/PS4-Guide/blob/main/XMB-Customize.md#icons)
    - [Hide, Show](https://github.com/ZHassanQ/PS4-Guide/blob/main/XMB-Customize.md#hide-show)
2. 🎼 **[Music:](https://github.com/ZHassanQ/PS4-Guide/blob/main/XMB-Customize.md#-music)**
    - [Login Music](https://github.com/ZHassanQ/PS4-Guide/blob/main/XMB-Customize.md#login-music)
    - [Main Music](https://github.com/ZHassanQ/PS4-Guide/blob/main/XMB-Customize.md#main-music)
3. 🧩 [Others:](https://github.com/ZHassanQ/PS4-Guide/blob/main/XMB-Customize.md#-others)
    - [Profile Picture](https://github.com/ZHassanQ/PS4-Guide/blob/main/XMB-Customize.md#profile-picture)
    - [Shortcuts](https://github.com/ZHassanQ/PS4-Guide/blob/main/XMB-Customize.md#shortcuts) 


## Others

Here i will list some other useful things that aren't mentioned in the guide.

- **[Chiaki](https://sr.ht/~thestr4ng3r/chiaki/#chiaki)** Free and Open Source PlayStation Remote Play Client.
- **[ESP32-S](https://youtu.be/Cllj6yDha6o)** (9.00) A youtube video demonstrates on how to setup ESP32-S which is really useful. It jailbreaks the PS4 without the need to plug/unplug anything.
- **[Revert Firmware](https://youtu.be/JxeSP1PJtEs)** (Requires Soldering) A youtube video demonstrates on how to revert to a previous firmware.


# Other Guides

If you have PS3, or PSVita then go check out these repositories! They have a full guide on how to do nearly everything on them covered about the PlayStation 3 and Vita homebrew. And how to jailbreak them or, to exploit them.

- **[PS3 Guide](https://github.com/ZHassanQ/PS3-Guide)** contains a guide on how to install either HEN or, CFW on your PlayStation 3 and more.
- **[PSVita Guide](https://github.com/ZHassanQ/PSVita-Guide)** contains a guide on how to install HENKaku, and how to make it permanent if your PSVita is compatible and more.
