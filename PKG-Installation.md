In this file **"PKG-Installation"** there's a tutorial on how to install PKG files wether they were Game, Game Update, Game's DLC, Themes, Hombrew apps.

🧭 Table of Contents
1. 🧪 Integrity Check:
    - **[Compatiblity to System](#compatibility-to-system)**
    - **[Compatiblity to BASE](#compatiblity-to-base)**
2. ⚙️ Installation
    - **[Flash Drive](#flash-drive)**
    - **[Internal Storage](#internal-storage)**
3. 🧰 Installation Errors
    - **[Error #1](#error-1)**
    - **[Error #2](#error-2)**


# 🧪 Integrity Check

Before installing any PKG file on your PlayStation 4 first open it with **[PS4PKGViewer](https://github.com/ZHassanQ/PS4-Guide/releases/download/Computer/PS4PKGViewer.v1.5-LMAN.zip)** to see if it's matches with your PlayStation 4 System, BASE, Update, and DLC.

## Compatibility to System

**In your Computer:**

1. Open your PKG file with **"PS4PKGViewer"**
2. See bottom left corner. **"<"**
- If it's lower or the same as your System Version you can install it.
- If it's higher than your System Version you can't install it. (See **""**)


## Compatiblity to BASE

If you will install an update or DLC for your Game BASE then you need to check a few things to see if it will be installed to the BASE game.

### Title ID

**In your Computer:**

1. Open your PKG file with **"PS4PKGViewer"**
2. See the **"TITLE_ID"** if they match. `CUSA10101` - `CUSA10101`
3. See the bottom left corner if it is **"FAKE"** or it will require license to launch the pkg in your PS4.
- If it's not **"FAKE"** you will need to put in your account that you bought the game with.

### DLC Required Version

1. Open your DLC PKG file with **"PS4PKGViewer"**
2. See the bottom left corner. `<VERSION>`
- If it's the same as your Game's Version you can install it.
- If it's higher or lower than your Game's Version you can't install it. 


# ⚙️ Installation

Now that you checked the integrity and if the PKG file info matched with your System Version, and/or Update, and/or DLC. You will install it, and there are three ways to do that:

## Flash Drive

**In your Computer:**

- Your USB Flash Drive need to be on exfat or FAT32 format.
1. Then put the PKG files in the root of your HDD, or your Flash Drive.

---

**In your PlayStation 4:**

2. Connect your USB Flash Drive to your PS4.
3. Go to **"Settings"** --> **"Debug Settings"** --> **"Package Installer"**
4. Select your PKG file.
- If you have many PKG files then, install BASE then, Update, then DLC's.


## Internal Storage

**In your PlayStation 4:**

1. Go to **"GoldHEN"** --> **"Server Settings"**
2. Check **"Enable FTP Server"**

---

**In your Computer:**

3. Launch your FTP Client.
4. Transfer your PKG file to `data` folder.

--- 

**In your PlayStation 4:**

5. Launch **[Internal PKG Installer](https://github.com/ZHassanQ/PS4-Guide/releases/download/PKG/IV0000-BREW00050_00-IPI0000000000000.pkg)** app.
- It should exit in a seconds then it will start installing.

# 🧰 Installation Errors

This section may help you if you can't install PKG files on your PlayStation 4 due to errors.

## Error #1

This error will be likely because the BASE game only had offline mode then update has an online mode like "The Last of Us" game.

**In your Computer:**

1. Launch **"Duxa's PS4 patch repackager"**
- You can download it **[here](https://github.com/ZHassanQ/PS4-Guide/releases/download/Computer/Duxas.PS4.patch.repackager.7.2.18.zip)**.
3. Put your `Update.pkg/file/location` in **"Patch:"**
4. Put your `Base.pkg/file/location` in **"Game:"**
5. Select **"Force Scenario 0"**
6. Click **"GO"** (It will Approximately take 20 Minutes)

## Error #2 

This error may pop-up because you downloaded from two different sources. So they weren't from the same console or disk and etc. To fix it see this **[Section](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Modify.md#%EF%B8%8F-1-remarry-game--update)** from **[PKG-Modify.md](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Modify.md)** file.
