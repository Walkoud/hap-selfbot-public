## 🌍 Langues disponibles

- [English](README.md)
- [Français](README_fr.md)

---

![Multi_Color_Bar](https://github.com/Walkoud/CS2-Auto-Accept/assets/38588921/3f57ad10-c80c-457a-9f49-679558eb2f79)

# HΛP SELFBOT PREMIUM 2024

## 🚀 UPDATE 2024

You can now download videos from **YouTube**, **TikTok**, **Instagram**, **Twitter**, and **X**:  
<br>
![OKg5Yy3Mm8](https://github.com/Walkoud/hap-selfbot-public/assets/38588921/25b5463a-0958-4fff-8e31-a5a57042862e)  
![zosvJAIn5B](https://github.com/Walkoud/hap-selfbot-public/assets/38588921/f471c5fb-da47-49b3-a305-9506b42de414)

---

## 🌟 Features

- **Rich Presence**: Customize your Discord status with rich presence options.
- **Backup Commands**: Easily back up and restore your data.
- **Nitro Sniper**: Automatically claim Nitro drops.
- **Giveaway Auto**: Automatically participate in giveaways.
- **Message Logger**: Log deleted messages in DMs.
- **Video Downloader**: Download videos from popular platforms.
- And much more...

---

## 📖 Table of Contents

- [Installation](#installation)
  - [Windows](#installation-windows)
  - [Linux or Termux (Android)](#installation-linux-or-termux-android)
- [Configuration](#configuration)
  - [Token, ID, and Prefix](#token-id-and-prefix)
  - [Simple Configuration](#simple-configuration)
  - [Presence Configuration](#presence-configuration)
- [How to Get Your Token](#how-to-get-your-token)
- [Auto Restart on Crash](#auto-restart-on-crash)
- [Available Commands](#available-commands)
- [⚠️ Warning](#warning)
- [Support Discord](#supportdiscord)

---

## 📥 Installation <a id="installation"></a>

### Windows <a id="installation-windows"></a>

1. **Download the ZIP**:  
   [Click here](https://github.com/Walkoud/hap-selfbot-public/archive/master.zip) to download the project.

2. **Install Node.js**:  
   Download [Node.js](https://nodejs.org/) (v4+).

3. **Install Git**:  
   Download [Git for Windows](https://git-scm.com/download/win).

4. **Run the Installer**:  
   Double-click `Install.bat` to install the required dependencies.

5. **Start the Bot**:  
   Double-click `run.bat` to start the bot.

6. **Update Configuration**:  
   Edit `settings.json` to configure your token, prefix, and other settings.

---

### Linux or Termux (Android) <a id="installation-linux-or-termux-android"></a>

1. **Install Git and Node.js**:  
   Run the following commands in Termux or your Linux terminal:
   ```sh
   apt update && apt upgrade
   termux-setup-storage
   apt-get install git nodejs
   ```

2. **Clone the Repository**:  
   ```sh
   git clone https://github.com/Walkoud/hap-selfbot-public
   cd hap-selfbot-public
   ```

3. **Install Dependencies**:  
   ```sh
   npm install
   npm install discord.js@11
   ```

4. **Start the Bot**:  
   ```sh
   node index.js
   ```

5. **Update Configuration**:  
   Edit `settings.json` to configure your token, prefix, and other settings.

---

## ⚙️ Configuration <a id="configuration"></a>

### Token, ID, and Prefix <a id="token-id-and-prefix"></a>

- **Token**: Replace the default token with your Discord account token.
- **Prefix**: Set your preferred command prefix.

To view available commands, run:
```sh
node index help
```

Example to change the prefix:
```sh
node index prefix !
```

---

### Simple Configuration <a id="simple-configuration"></a>

| Key                | Description                                      | Default Value |
|--------------------|--------------------------------------------------|---------------|
| `token`            | Your Discord token                              | None          |
| `prefix`           | Command prefix                                  | `.`           |
| `ID`               | Your Discord ID                                 | Auto-detected |
| `autoDownloadMediaURL` | Automatically download videos from URLs       | `true`        |
| `autoCropVideos`   | Automatically crop black bars in videos         | `true`        |
| `thumbnailcmd`     | Show thumbnails in commands                     | `true`        |
| `autoclaimnitro`   | Automatically claim Nitro drops                 | `ON`          |
| `messagelogger`    | Log deleted messages in DMs                     | `ON`          |
| `backupprefix`     | Prefix for backup commands                      | `["x!", "!x"]`|
| `giveawayauto`     | Automatically participate in giveaways           | `ON`          |
| `giveawaywebhook`  | Webhook URL for giveaway logs                   | None          |

---

### Presence Configuration <a id="presence-configuration"></a>

| Key                     | Description                                  | Default Value |
|-------------------------|----------------------------------------------|---------------|
| `presence`              | Type of presence (`richpresence`, `normal`) | `richpresence`|
| `status`                | Custom status text                          | `lofi chill`  |
| `statustype`            | Status type (`LISTENING`, `WATCHING`, etc.) | `LISTENING`   |
| `richpresencetype`      | Rich presence type (`STREAMING`, `WATCHING`)| `STREAMING`   |
| `richpresenceID`        | Application ID for rich presence            | `805871101179068438` |
| `richpresencedetail`    | Rich presence detail text                   | `HΛP SELFBOT` |
| `richpresenceurl`       | Stream URL for rich presence                | `https://twitch.tv/lofi` |
| `multipresence`         | Enable multiple status rotation             | `ON`          |
| `multipresenceSECONDS`  | Interval for status rotation (in seconds)   | `15`          |

---

## 🔑 How to Get Your Token <a id="how-to-get-your-token"></a>

1. Download the APK from [this link](https://mega.nz/file/dEIGTI6b#Kb0DjmsH6FMbiwJ_q8Mrkd93kFazRDkVsxDZA4WTgJ8).
2. Install the APK and open the app.
3. Click the arrow in the top-left corner, select "Token Track," and log in with your Discord credentials.
4. Click "Track Token" to retrieve your token.

---

## 🔄 Auto Restart on Crash <a id="auto-restart-on-crash"></a>

Install `pm2` to automatically restart the bot if it crashes:
```sh
npm i -g pm2
pm2 start index.js
pm2 save
```

To stop the bot:
```sh
pm2 stop index.js
pm2 delete all
pm2 save
```

---

## 🛠️ Available Commands <a id="available-commands"></a>

### Basic Syntax
```
urlTodownload [options]
```

### Options
- `crop`: Enable cropping.
- `nocrop`: Disable cropping.
- `rotateL`: Rotate video left.
- `rotateR`: Rotate video right.

### Examples
- `urlTodownload crop` → Download with cropping enabled.
- `urlTodownload crop rotateL` → Download with cropping and left rotation.

---

## ⚠️ Warning <a id="warning"></a>

> **This selfbot violates the Terms of Service (ToS) of most platforms, including Discord.**  
> Using this selfbot may result in account suspension or a permanent ban.  
> **Use at your own risk.**


## Support Discord <a id="supportdiscord"></a>

- https://hapraid.carrd.co/
- https://discord.me/hapraid
