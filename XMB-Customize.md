In this file **"XMB-Customize.md"** there's a tutorial on how to customize your PS4 Home Screen with changing your Profile Picture, Login Intro, Main Music, Apps Icons, and Hiding Apps. Note that the methods i am explaing requires two apps, one can connect to FTP-Servers like **[FileZilla](https://filezilla-project.org/)**, and one can read database files like **[DB Browser for SQLite](https://sqlitebrowser.org/)**.

🧭 Table of Contents

1. 🌍 **[Apps:](#-apps)**
    - [Icons](#icons)
    - [Hide, Show](#hide-show)
2. 🎼 **[Music:](#-music)**
    - [Login Music](#login-music)
    - [Main Music](#main-music)
3. 🧩 [Others:](#-others)
    - [Profile Picture](#profile-picture)


# 🌍 Apps

If you don't like your PSN apps and you would like to hide them, or you want to change the icons looks like. Then you can easily do that by doing the following steps.


## Icons

If you want to change the way your PSN apps, games icons looks like, do the following.

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

If you want to hide some PSN apps that can't be deleted, you can hide them by:

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

5. Run any app that can read databaes files.
- I am using DB Browser for SQLite app.
7. Choose **"app.db"**
8. Click **"Browse Data"**
9. Select the Table `tbl_appbrowse_0413713369`
10. Scroll to the right side until you see **"visible"** Cell
- If the filter is **"0"** it means hidden.
- If the filter is **"1"** it means visible.
10. Save it and replace it to your PS4 in `system_data\priv\mms`


# 🎼 Music

If you don't like, or got bored by the intro (login) music of PlayStation 4, or the main theme that plays in the background you can change them by the following steps.

## Login Music

To change the intro (login) music of your PlayStation 4, do the following:

**In your PS4:**

1. Go to **"GoldHEN"** Settings.
2. Go to **"Server Settings"** and check **"Enable FTP Server"**

---

**In your Computer:**

1. Run your FTP Client.
2. Connect to your PS4.
3. Go to `preinst/priv/systembgm/` folder.
4. Rename `bgm_login.at9` to `bgm_login.at91`
- It will be original backup.
- If you want it back just rename it back.
5. Select any Music you want and convert it to **".at9"** by **“AT9-AT3-converter"** app.

 
## Main Music

To change the main music (theme) of your PlayStation 4, do the following:

**In your PS4:**

1. Go to **"GoldHEN"** Settings.
2. Go to **"Server Settings"** and check **"Enable FTP Server"**

---

**In your Computer:**

1. Run your FTP Client.
2. Connect to your PS4.
3. Go to `mnt/sandbox/NPXS20001_000FTP/app0/systembgm/` folder.
4. Rename `bgm_main.at9` to `bgm_main.at91` 
- It will be original backup.
- If you want it back just rename it back.
5. Download any Music you want and convert it to **".at9"** by **“AT9-AT3-converter”** app.

# 🧩 Others
## Profile Picture

If you want to replace your profile picture, then you need to have a `512x512` picture. And then copy it to your PS4 in any directory. (Preferably `data\PS4Xplorer`) After that launch PS4Xplorer and go to your picture and set it as a profile picture.

- If you haven't already installed it go to **[PKG-Installation.md](https://github.com/ZHassanQ/PS4-Guide/blob/main/PKG-Installation.md)** to see how to install PKG-files in many different ways, and what to do if an there are an errors.
