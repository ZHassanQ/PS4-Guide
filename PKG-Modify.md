In this file **"PKG-Modify"** there's a tutorial on how to modify PKG files with many things; with PS4-AIO app. (**[Direct Download]()**)

🧭 Table of Contents

1. 🗃️ Marry:
    - **[Remarry](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/blob/main/PKG-Modify.md#%EF%B8%8F-1-remarry-game--update)**
    - **[Merge](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/blob/main/PKG-Modify.md#%EF%B8%8F-2-5-merge-game--update--backport)**
2. 🛠️ Backports:
    - **[Backup](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/blob/main/PKG-Modify.md#%EF%B8%8F-3-backup-backports-files)**
    - **[Reverse](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/blob/main/PKG-Modify.md#%EF%B8%8F-4--ps4-rebuild-pkg---backport)**
3. 💊 DLCs:
    - **[Region](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/blob/main/PKG-Modify.md#-7-dlc---change-region)**
    - **[Unlock](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/blob/main/PKG-Modify.md#-8-ps4-dlc-unlocker)**
    - **[Restore Data](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/blob/main/PKG-Modify.md#-9-without-data-dlc-to-data-dlc)**
    - **[Remove Data](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/blob/main/PKG-Modify.md#-10-data-dlc-to-without-data-dlc)**
4. 🧩 Others
    - **[Fix Game Info](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/blob/main/PKG-Modify.md#-6-fix-game-info)**


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

This will only backup backported files from @opoisso893, @CyB1K, @mrBOOT.

1. Put your BACKPORTED PKG file in:
- If it's BASE or MERGED PKG file then, `GAME` folder.
- If it's Update PKG file then, `UPDATE` folder.

## 🛠️ 4.  PS4 Rebuild PKG - Backport

See option 3. Put game FPKG in GAME folder, update FPKG in UPDATE folder & backported files in BACKPORTED FILES folder.

1. Put your GAME PKG file to `GAME` folder.
2. Put your UPDATE PKG file to `UPDATE` folder.
3. Put your BACKPORT PKG file to `BACKPORT` folder.

# DLCs
## 💊 7. DLC - Change Region 

1. Put your DLC PKG files to `DLC` folder.
2. Input `EP` or `UP`
- `EP` command is for EU region.
- `UP` command is for US region.
3. Inputs `CUSAXXXXX` where `X` is the `TITLE_ID`

 
## 💊 8. PS4 DLC Unlocker

This will create only simple unlockers with @stooged's psDLC v26.

1. Put your DLC PKG files to `DLC` folder. 

## 💊 9. Without Data DLC to Data DLC

For some games: "Soul Calibur VI", "Cities: Skylines" and more. If you have unlockers with extra data, game will have slow loading, menu lag. Because it's still searching for DLCs. 

1. Put your DLC PKG files to `DLC` folder.
 
## 💊 10. Data DLC to Without Data DLC

If you have DLC unlockers without data which need to be installed with USB method, because RPI over network cant install DLC without data.

1. Put your DLC PKG files to `DLC` folder. 


# Others
## 🧩 6. Fix Game Info

If you install a merged PKG (BASE+Update) on your PlayStation 4, then it will reads it as a 1.00 version and to fix it:

**In your Computer:**

1. Launch **"PS4-AIO"** app.
2. Put **"MERGED.pkg"** in `GAME` folder.
3. And you will get small PKG update **"Dummy_Update.pkg"** around 5-10MB in `PS4-AIO` folder.
4. Install it. 
