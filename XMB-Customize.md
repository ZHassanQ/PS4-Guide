In this file **"XMB-Customize.md"** there's a tutorial on how to customize your PS4 Home Screen with changing your Profile Picture, Login Intro, Main Music, Apps Icons, and Hiding Apps.

🧭 Table of Contents

1. 🌍 Apps:
    - **[Icons]()**
    - **[Hide, Show]()**
2. Music:
    - **[Login Music]()**
    - **[Main Music]()**
3. Others:
    - **[Profile Picture]()**



## Icons


1. Launch **“Icon Mask”** in your PS4.
- There are already customized icons. 

---

**If you want "Customized Icons" from yourself:**

1. Plug your USB Flash Drive in your Computer.
2. Create a folder in the root of your USB Flash Drive named `ICONS`
3. Put the **".png's"** icons in `ICONS` folder.
- The size of the icons should be **“512x512”**

---

2. Select **"Pre-made Icons"**
3. Choose which icons you want to put & which one to Replace with.

## Hide, Show

**In your PS4:**

1. Go to **"GoldHEN"** Settings.
2. Go to **"Server Settings"** and check **"Enable FTP Server"**

---

**In your Computer:**

1. Run your FTP Client.
2. Connect to your PS4.
3. Go to `system_data/priv/mms` folder.
4. Copy **“app.db”** two times.
- The other one is for backup.

---

5. Run **"DB Browser for SQLite"** app.
6. Choose **"app.db"**
7. Click **"Browse Data"**
8. Select the Table `tbl_appbrowse_0413713369`
9. Scroll to the right side until you see **"visible"** Cell
- If the filter is **"0"** it means hidden.
- If the filter is **"1"** it means visible.
10. Save it and replace it to your PS4 in `system_data\priv\mms`


# Music
## Login Music

**In your PS4:**

1. Go to **"GoldHEN"** Settings.
2. Go to **"Server Settings"** and check **"Enable FTP Server"**

---

**In your Computer**

1. Run your FTP Client.
2. Connect to your PS4.
3. Go to `preinst/priv/systembgm/` folder.
4. Rename `bgm_login.at9` to `bgm_login.at91`
- It will be original backup.
- If you want it back just rename it back.
5. Select any Music you want and convert it to **".at9"** by **“AT9-AT3-converter"** app.

 
## Main Music

**In your PS4:**

1. Go to **"GoldHEN"** Settings.
2. Go to **"Server Settings"** and check **"Enable FTP Server"**

---

**In your Computer**

1. Run your FTP Client.
2. Connect to your PS4.
3. Go to `mnt/sandbox/NPXS20001_000FTP/app0/systembgm/` folder.
4. Rename `bgm_main.at9` to `bgm_main.at91` 
- It will be original backup.
- If you want it back just rename it back.
5. Download any Music you want and convert it to **".at9"** by **“AT9-AT3-converter”** app.

# Others
## Profile Picture

**In your PS4:**

1. Go to **"GoldHEN"** Settings.
2. Go to **"Server Settings"** and check **"Enable FTP Server"**

---

**In your Computer**

1. Run your FTP Client.
2. Connect to your PS4.
3. Create copy of your picture sizes down below.
4. Rename the picture you want like down below.
5. Replace the avatar you want from `system_data/priv/cache/profile/` folder.

- **"440x440"** Called **"avatar.png"**
- **"440x440"** Called **"avatar440.dds"**
- **"260x260"** Called **"avatar260.dds"**
- **"128x128"** Called **"avatar128.dds"**
- **"64x64"** Called **"avatar64.dds"**