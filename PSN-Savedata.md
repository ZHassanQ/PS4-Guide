
In this section you will create an activated PSN account so you can copy your savedata from your jailbroken PS4 to retail PS4. And how to install encrypted savedata that are not signed to your account.

🧭 Table of Contents

1. 🌍 PSN ID:
    - **[Fake PSN ID]()**
    - **[Real PSN ID]()**
2. 💾 Savedata:
    - **[Encrypted]()**
    - **[Region Change]()**
    - **[Retail]()**


# PSN ID
## Fake PSN ID
## Real PSN ID

**In (Retail) PS4:**

1. Sign in in the account you want to use.
2. Copy any savedata to your USB Flash Drive.

---

**In your Computer:**

1. Connect the USB Flash Drive in your computer.
2. Copy your PSN_ID `USB:\PS4\SAVEDATA\PSN_ID\CUSAXXXXX\`


# Savedata 
## 💾 Encrypted

- Make sure the savedata you have match the **"Title_ID"** of the game you own. (If not read this **[section]()**)
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
- There may be 1 or 10 files depending on the game.
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
- It will copy a keystone file from: `data/apollo/PSN-ID/CUSA010101`
- Keystone file can be obtained by selecting **"Export keystone"** from a Savedata played in retail PS4 without resigning it.