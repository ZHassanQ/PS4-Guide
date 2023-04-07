Finally in this section you will customize your PS4 by changing your profile picture, icons, PS4 login intro, PS4 main music, &  hiding unwanted programs.

- **DB Browser for SQLite** [Website](https://sqlitebrowser.org/dl/)


## Changing Profile Picture

**In your PS4:**

1. Launch FTP server.

---

**In your Computer:**

1. Create copy of your picture sizes down below.
2. Rename the picture you want like down below.
3. Replace the avatar you want from `system_data/priv/cache/profile/`

- **"440x440"** Called **"avatar.png"**
- **"440x440"** Called **"avatar440.dds"**
- **"260x260"** Called **"avatar260.dds"**
- **"128x128"** Called **"avatar128.dds"**
- **"64x64"** Called **"avatar64.dds"**


## Hiding Unwanted Apps

**In your PS4:**

1. Start FTP server.

---

**In your Computer:**

1. Run **“FileZilla”**
2. Connect to your PS4.
3. Go to `system_data/priv/mms`
4. Copy **“app.db”** two times the other one is for backup.

---

5. Run **"DB Browser for SQLite.exe"**
6. Choose the **"app.db"**
7. Click Browse Data
8. Select the Table `tbl_appbrowse_0413713369`
9. Scroll to the right side until you see **"visible"** Cell
- If the Filter is **"0"** it means hidden.
- If the filter is **"1"** it means visible.
10. Save it and replace it to your PS4 in `system_data\priv\mms`


## Customizing PS4 Home Screen

**For Icons:**

1. Launch **“Icon Mask”** in your PS4.
- There are already customized icons. 

**If you want "Customized Icons" from yourself:**

1. Plug your USB Flash Drive in your Computer.
2. Create a folder in the root of your USB Flash Drive named `ICONS`
3. Put the **".png's"** icons in `ICONS` folder.
- The size of the icons should be **“512x512”**

---

**In your PS4:**

1. Press **"X"** button on **"Pre-made Icons"**
2. Choose which icons you want to put & which one to Replace with.


## Changing PS4 Main Music

**In your PS4:**

1. Run FTP server.

---

**In your Computer:**

1. Run **"FileZilla"**.
2. Connect to your PS4 using it IP Address.
3. Go to `mnt/sandbox/NPXS20001_000FTP/app0/systembgm/`
4. Rename `bgm_main.at9` to `bgm_main.at91` it will be original backup.
- If you want it back just rename it back.

5. Download any Music you want and convert it to **".at9"** by **“AT9-AT3-converter”**
- `bgm_main.at9` It will play constantly in the main screen.


## Changing PS4 Login Intro Music

**In your PS4:**

1. Run FTP server

---

**In your Computer**

1. Run **"FileZilla"**.
2. Connect to your PS4 using it IP Address.
3. Go to `preinst/priv/systembgm/`
4. Rename `bgm_login.at9` to `bgm_login.at91` it will be original backup.
- If you want it back just rename it back.

5. Select any Music you want and convert it to **".at9"** by **“AT9-AT3-converter".**
- `bgm_intro.at9` It will play Once the PS4 start.

 
