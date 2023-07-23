In this file **"PSN-Savedata.md"** there's a tutorial on how to create an activated PSN either from real account or a fake ID. And how to install encrypted savedata that are not signed to your account, and more.

🧭 Table of Contents

1. 🌍 PSN ID:
    - **[Fake PSN ID](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/blob/main/PSN-Savedata.md#fake-psn-id)**
    - **[Real PSN ID](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/blob/main/PSN-Savedata.md#real-psn-id)**
2. 💾 Savedata:
    - **[Encrypted](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/blob/main/PSN-Savedata.md#-encrypted)**
    - **[Region Change](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/blob/main/PSN-Savedata.md#-region-change)**
    - **[Retail](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/blob/main/PSN-Savedata.md#-fpkg-to-retail)**


# PSN ID
## Fake PSN ID

1. Select **"User Tools"** menu.
2. Select **"Activate PS4 Accounts"**
- By default the local account will be activated with an auto-generated account-id value.

## Real PSN ID

To activate an account offline, go to the `User Tools` menu, and select Activate PS4 Accounts. By default the local account will be activated with an auto-generated account-id value. This default account value can be edited using the on-screen keyboard.

- How to know your PSN ID?
    - Simply copy any savedata from your account to your USB Flash Drive. It will create a directory like this: `X:PS4\SAVEDATA\PSN_ACC_ID\CUSAXXXXX`

# Savedata 
## 💾 Encrypted

- Make sure the savedata you have match the **"Title_ID"** of the game you own. (If not read this **[section](https://github.com/ZHassanQ/PS4-GoldHEN-Guide/blob/main/PSN-Savedata.md#-region-change)**)
- For example your Game ID = `XXXXX01010` then the savedata you want to copy `XXXXX01010`

---

**In your Computer:**

1. Put the savedata in your USB Flash like this `USB:PS4/SAVEDATA/YOUR_PSN_ID/"Savedata Folder"`

---

**In your PS4:**

1. Connect your USB Flash Drive in PS4
2. Run **"Apollo Save Tool"**
3. Go to **"USB SAVES"**
4. Select the **"Savedata"** you want
5. Press **"X"** on **"Copy Save game to HDD"**
6. Say Yes (To resign the savedata to your PSN ID)
- Any savedata that you want and has been copied from PS4 with the game installed in higher update than yours then it may not work for your PS4.


## 💾 Region Change

1. Launch **“Apollo Save Tool”.**
2. Copy the **"Savedata"** to your PS4.
3. Go to **"HDD Saves"** then, choose the Savedata you want to transfer. 
4. Select **"Export decrypted save files"** and export them all.
- There may be 1-10 files depending on the game.
5. Go to `/data/apollo/ACC_ID/`
6. Rename `CUSAXXXXX` to the `TITLE_ID` of your game.
7. Create Savedata for your game to replace it later.
- If the game has slots make sure they both have the same slot.
8. Return to **"Apollo Save Tool"**
9. Go to **"HDD Saves"** then, choose the Savedata you created to replace it.
10. Select **"Import decrypted save files"** then, "Apply Changes & Resign"


## 💾 FPKG to Retail

**In your PS4:**

1. Launch **"Apollo Save Tool"**
2. Go to **"HDD Saves"** then, choose your savedata.
4. Select **"Import keystone"**
- It will copy a keystone file from: `data/apollo/PSN-ID/CUSAXXXXX`
- Keystone file can be obtained by selecting **"Export keystone"** from a Savedata played in retail PKG-file game without resigning it.
