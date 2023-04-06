In this section you will install your own (Apps, Games, Updates, & Themes) which they are all in ".pkg" format file.

- **PS4PKGViewer** [Windows](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/releases/download/Computer/PS4PKGViewer.v1.5-LMAN.zip)
- **PS4 Apps** [5.05](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/releases/tag/5.05) - [9.00](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/releases/tag/9.00)
- **PS4-AIO** [Windows](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/releases/download/Computer/PS4-AiO.v27.zip)
- **Duxas PS4 patch repackager** [Windows](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/releases/download/Computer/Duxas.PS4.patch.repackager.7.2.18.zip)


# Integrity Check

Before installing any PKG file on your PlayStation 4 first open it with **"PS4PKGViewer"** to see if it's matches with your BASE, Update, and DLC info.

## PKG files Compatibility

**In your Computer:**

1. Open your **"pkg"** file with **"PS4PKGViewer"**
2. See the **"Title_id"** if they match. `CUSA10101` - `CUSA10101`
3. See the **"system"** if it is higher or lower than your firmware.
4. See if it is **"FAKE"** or it will require license to launch the pkg in your PS4.
- Meaning that you will need to put in your account that you bought the game with.
- Make sure if you will install an Update ,Dlc that they match Regions & Title_id.


## Update Combatibility

**In your PS4:**

1. Launch **"Patch Installer"**
2. Select your game
3. See the update **"Version"** you want

- If it is **"Green"** that means it **can** be Installed on your PS4 -Playable-
- If it is **"Red"** that means it **can't** be Installed on your PS4 -Unplayable-

---

If you have already an installed update that requires higher firmware version than yours:

**In your PS4:**

1. Launch **"Homebrew Store"**
2. Go To **"Installed Apps"**
3. Select The Game That Already Have An Installed Update
4. Press **"X"** On **"Remove Update"**


# PKG Installation

Now that you checked the integrity and if the PKG BASE file info matched with your Update and DLC's.


## Installing ".pkg's" files

**In your Computer:**

1. Format the **"HDD"** ,**"Flash"** to format **"exFAT"**
2. Then put the **".pkg"** files in the root of the **"HDD"** ,**"Flash"**

---

**In your PS4:**

3. Connect your USB Flash Drive to your PS4.
4. Go to `Settings/Debug Settings/Package Installer/"Install all"` ,Choose **".pkg"**


##  Fix Game Info (Merged Games)

If you install a merged PKG (BASE+Update) on your PlayStation 4, then it will reads it as a 1.00 version and to fix it:

**In your Computer:**

1. Extract **"PS4-AIO"**
2. Put **"game.pkg"** in GAME folder.
3. And you will get small PKG update **"Dummy_Update.pkg"** around 5-10MB.
4. After that install the **"Dummy_Update.pkg"** on PS4

# Installation Errors

This section may help you if you can't to install PKG files on your PlayStation 4 due to errors.

## Error #1

This error will be likely because the BASE game only had offline mode then update has an online mode like "The Last of Us" game.

**In your Computer:**

1. Extract **"Duxas PS4 patch repackager"**
2. Launch "Duxas PS4 patch repackager.exe"**
3. Check "Force Scenario 0"**
4. Put the **"Patch.pkg"** -Update.pkg- file directory in "Patch pkg:"**
5. Put the **"Base.pkg"** -Game.pkg- file directory in "Game pkg:"**
6. Click **GO"** (It will Approximately take 20 Minutes)

## Error #2 

This error may pop-up because you downloaded from two different sources.

1. Launch **"DUXA-Repackager-7.18.2.exe"**
2. Put your `Update/file/location` in **"Patch"**
3. Put your `Base/file/location` in **"Game"**
4. Uncheck everything down.
5. Click **"GO"** (It will Approximately take 20 Minutes) 
