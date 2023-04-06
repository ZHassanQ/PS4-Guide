In this file "PKG-Installation" there's a tutorial on how to install PKG files wether they were Game, Game Update, Game's DLC, Themes, Hombrew apps.

Table of Contents
1. 🧪 Integrity Check:
    - **[Compatiblity to System]()**
    - **[Compatiblity to BASE]()**
2. ⚙️ Installation
    - **[Flash Drive]()**
    - **[Internet Connection]()**
3. 🧰 Installation Errors
    - **[Error #1]()**
    - **[Error #2]()**
4. 🔎 Others
    - **[Fix Game's Info]()**


# Integrity Check

Before installing any PKG file on your PlayStation 4 first open it with **"PS4PKGViewer"** to see if it's matches with your PlayStation 4 System, BASE, Update, and DLC.

## Compatibility to System

**In your Computer:**

1. Open your PKG file with **"PS4PKGViewer"**
2. See **""**
- If it's lower or the same as your System Version you can install it.
- If it's higher than your System Version you can't install it. (See **""**)


## Compatiblity to BASE

If you will install an update or DLC for your Game BASE then you need to check a few things to see if it will be installed to the BASE game.

### Title ID

**In your Computer:**

1. Open your PKG file with **"PS4PKGViewer"**
2. See the **"Title_id"** if they match. `CUSA10101` - `CUSA10101`
3. See if it is **"FAKE"** or it will require license to launch the pkg in your PS4.
- If it's not **"FAKE"** you will need to put in your account that you bought the game with.

### DLC Required Version

1. Open your DLC PKG file with **"PS4PKGViewer"**
2. See **""**
- If it's the same as your Game's Version you can install it.
- If it's higher or lower than your Game's Version you can't install it. 


# PKG Installation

Now that you checked the integrity and if the PKG file info matched with your System Version, and/or Update, and/or DLC.

## USB Flash Drive

**In your Computer:**

1. Format the **"HDD"** ,**"Flash"** to format **"exFAT"**
2. Then put the **".pkg"** files in the root of the **"HDD"** ,**"Flash"**

---

**In your PlayStation 4:**

3. Connect your USB Flash Drive to your PS4.
4. Go to "Settings" --> "Debug Settings" --> "Package Installer"
5. Select your PKG file.
- If you have many PKG files, then install BASE then, Update, then DLC's.


## Internet Connection

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
