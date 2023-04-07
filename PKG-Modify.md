In this file **"PKG-Modify"** there's a tutorial on how to modify PKG files with many things; with PS4-AIO app. (**[Direct Download]()**)

🧭 Table of Contents

1. 🗃️ Marry:
    - **[Remarry]()**
    - **[Merge]()**
2. 🛠️ Backports:
    - **[Backup]()**
    - **[Reverse]()**
3. 💊 DLCs:
    - **[Region]()**
    - **[Unlock]()**
    - **[Remove Data]()**
    - **[Restore Data]()**
4. 🧩 Others
    - **[Fix Game Info]()**


# Marry
## 🗃️ 1. Remarry Game + Update

1. Put your GAME PKG file to `GAME` folder.
2. Put your UPDATE PKG file to `UPDATE` folder.
- After it finishes you can install them.
- This should fix an error while installing UPDATE PKG file.

## 🗃️ 2, 5. Merge Game + Update, + Backport 

1. Put your GAME PKG file to `GAME` folder.
2. Put your UPDATE PKG file to `UPDATE` folder.
- Optionally: Put your BACKPORT PKG file to `BACKPORT` folder.
- If you put your BACKPORT PKG file to `BACKPORT` folder, choose option `5` else choose option `2`

# Backports
## 🛠️ 3. Backup Backports Files

This will only backup backported files from @opoisso893 / @CyB1K / @mrBOOT... backported FPKGs. Keeping Game, Untouched Update and Backported update need a lot space on PC hdd. If you keep only backported files you can easy create backported FPKG again with untouched update. 


## 🛠️ 4.  PS4 Rebuild PKG - Backport

See option 3. Put game FPKG in GAME folder, update FPKG in UPDATE folder & backported files in BACKPORTED FILES folder.


# DLCs
## 💊 7. DLC - Change Region 

Change DLC region. Just put dlcs in DLC folder. If you put game PKG (game for which you want to change DLC region) in GAME folder everything will be auto finished. Without game in GAME folder, you must input when asked EP/UP and CUSA number.

 
## 💊 8. PS4 DLC Unlocker

This will create only simple unlockers with @stooged's psDLC v26 (Article / PSDLC 2.1 Mogi PPSA GUI).

## 💊 10. Data DLC to Without Data DLC

If you have DLC unlockers without data which need to be installed with USB method, because RPI over network cant install DLC without data. Generic picture will be added, picture from game or can choose picture you want. Put DLCs in DLC Folder. 

## 💊 9. Without Data DLC to Data DLC

For some games: Soul Calibur VI, Cities: Skylines... if you have unlockers with extra data, game will have slow loading, menu lag... because still searching for DLCs. Picture will be preserved for any PKGViewer / PKGEditor, but on PS4 will be displayed with no name, no icon. Put DLCs in DLC Folder.


# Others
## 🧩 6. Fix Game Info

If you install a merged PKG (BASE+Update) on your PlayStation 4, then it will reads it as a 1.00 version and to fix it:

**In your Computer:**

1. Launch **"PS4-AIO"** app.
2. Put **"MERGED.pkg"** in `GAME` folder.
3. And you will get small PKG update **"Dummy_Update.pkg"** around 5-10MB in `PS4-AIO` folder.
4. Install it. 
