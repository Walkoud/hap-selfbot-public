[![aaa](https://i.imgur.com/4M7IWwP.gif)](https://discord.link/hap)
# HΛP SELFBOT PREMIUM 2021
## ! embed command not work in 2022 !
Selfbot de la HAP

<p align="center">
<a href="https://discord.link/hap"><img src="https://img.shields.io/github/watchers/Walkoud/hap-selfbot-public?logoColor=purple&style=social"></a>
  <a href="https://discord.link/hap"><img src="https://img.shields.io/github/last-commit/Walkoud/hap-selfbot-public"></a>
<a href="https://discord.link/hap"><img src="https://img.shields.io/discord/736923536475684974?label=Join%20HΛP&logo=discord&style=flat-square"></a>
 


</p>

Selfbot with richpresence, backup commands, nitro sniper, giveaway auto, message logger, and more...

http://discord.link/hap
## Pages
- [Installation](#Installation)
  - [Installation Windows](#InstallationWindows)
  - [Installation Linux or Termux (Android)](#InstallationLinux)
- [Configuration](#Configuration)
  - [Configuration TOKEN , ID , PREFIX](#ConfigurationTOKENIDPREFIX)
  - [Configuration Simple](#ConfigurationSimple)
  - [Presence Configuration](#PresenceConfiguration)
- [Pour avoir son token](#token)
- [Auto restart when crash ](#crash)

## Screens


![image](https://user-images.githubusercontent.com/38588921/114311021-4e81fb00-9aed-11eb-878c-f226882d959e.png)
![image](https://user-images.githubusercontent.com/38588921/114311037-65285200-9aed-11eb-9e66-f41670fde506.png)
 ![image](https://user-images.githubusercontent.com/38588921/125161761-6ae11280-e184-11eb-9f79-39035c3177da.png)

Besoin de nodejs et de git installé sur votre Windows

 
## Installation : <a id="Installation"></a>


### Installation Windows :<a id="InstallationWindows"></a>
-Download the zip https://github.com/Walkoud/hap-selfbot-public/archive/master.zip <br/>
Téléchargez le zip https://github.com/Walkoud/hap-selfbot-public/archive/master.zip <br/>

-Download Nodejs [Node.js](https://nodejs.org/) v4+ to run. <br/>
-Téléchargez Nodejs  [Node.js](https://nodejs.org/) version 4 ou + .

-Download Git for Windows [Git](https://git-scm.com/download/win) <br/>
-Télécharger Git pour Windows [Git](https://git-scm.com/download/win) 

-Cliquer sur le fichier Install pour installer les fichiers du bots <br/>
-Click on Install.bat to install <br/>

-Pour démarrer le bot, cliquez sur run.bat <br/>
-Click on run.bat to boot the bot <br/>

N'oubliez pas de changer votre configuration dans le settings.json !<br/>
Don't forget to change your configuration in settings.json!

### Installation Linux or Termux (Android) <a id="InstallationLinux"></a>
Possibilité de lancer sur Android avec l'application Termux <br/>
dans ce cas installez git en utilisant les commandes (dans le dossier du selfbot)
```sh
$ apt update && apt upgrade
$ termux-setup-storage
$ apt-get install git
$ git clone https://github.com/Walkoud/hap-selfbot-public
$ apt-get install nodejs
$ cd hap-selfbot-public
$ npm install
$ npm install discord.js@11
$ node index.js
```
N'oubliez pas de changer votre configuration dans le settings.json !

## Configuration : <a id="Configuration"></a>

### Configuration TOKEN , ID , PREFIX <a id="ConfigurationTOKENIDPREFIX"></a>

Necessary:
- Vous devez changer obligatoirement votre token
- You must change your token!

Vous pouvez changer la configuration en tapant des commandes! <br/>
You can change the configuration by typing commands! <br/>

Tapez la commande node index help pour voir la liste des commandes <br/>
Type the command node index help to see the list of commands <br/>

```sh
$ node index help
```

![image](https://user-images.githubusercontent.com/38588921/111067512-f42d5480-84c4-11eb-9a8c-094183ff9d24.png)

Exemple for prefix:  <br/>
```sh
$ node index prefix !
```
![image](https://user-images.githubusercontent.com/38588921/111067532-19ba5e00-84c5-11eb-94ed-73425381bcd9.png)

### Configuration Simple <a id="ConfigurationSimple"></a>
| Key config | Explanation | Default |
| ------ | ------ | ----- | 
| token | Your token discord | no |
| prefix | Prefix of commands | .
| ID | Your ID DIscord | default (automatic id)
| autoclaimnitro | Auto claim when nitro is droped (OFF ON) | ON
| messagelogger | DM message logger when user delete messsage (OFF ON) | ON
| backupprefix | Prefixs of backups commands | ["x!", "!x"]
| giveawayauto | Auto add reaction to participate giveaway (OFF ON) | ON
| giveawaywebhook | Logs of giveaway, Discord Webhook Link (channel configuration) | nothing

### Presence Configuration <a id="PresenceConfiguration"></a>

| Presence config | Explanation | Default |
| ------ | ------ | ----- | 
| presence | Type of presence : richpresence, normal, multipresence | richpresence |
||||
| status | Your Discord Status (Watching this, playins this) | lofi chill
| statustype | LISTENING or WATCHING or STREAMING or PLAYING | LISTENING
||||
| richpresencetype | Type of RichPresence : spotify, STREAMING, LISTENING, WATCHING | STREAMING |
| richpresenceID | ApplicationID : go to here https://www.reddit.com/r/discordapp/comments/a2c2un/how_to_setup_a_custom_discord_rich_presence_for/ | 805871101179068438 |
| richpresencedetail | Text of rich presence | HΛP SELFBOT |
| richpresenceurl | Url of stream status | https://twitch.tv/lofi |
|richpresenceIMAGEid|Id of image in Developper Application Rich Presence| noname |
|richpresenceSpotifyLargeImage| Spotify Large Image: you must use images hosted on spotify (album cover / playlist)| spotify:f2ed07272dec9cfc3b6805e9c59eac3391a59bed|
|richpresenceSpotifySmallImage|Spotify Small Image| spotify:f2ed07272dec9cfc3b6805e9c59eac3391a59bed|
||||
| multipresence | Auto change status with multiple text (OFF, ON) | ON
| multipresencetype | Same of Status Type | WATCHING
| multipresenceSECONDS | Seconds of interval | 15

<br/>
[How to change spotify image in RichPresence](#spimage.md#how-to-change-image-spotify-for-richpresence-)


### Pour avoir son token <a id="token"></a>
 
 ##### Pour le token de votre compte
 
Téléchargez https://mega.nz/file/dEIGTI6b#Kb0DjmsH6FMbiwJ_q8Mrkd93kFazRDkVsxDZA4WTgJ8

Puis installez l'apk, ouvrez l'application, puis appuyez sur la petite flèche en haut à gauche, cliquez sur Token Track, puis mettez vos identifiants discord, puis cliquez sur Track Token, et voilà vous aurez votre token affiché devant vous.



## Auto restart when crash : <a id="crash"></a>

To restart automaticly when it crash <br/>
Pour redémarrer automatiquement quand ça crash <br/>

```sh
$ npm i -g pm2
$ pm2 start index.js
$ pm2 save
```

To stop <br/>
Pour stopper  <br/>

```sh
$ pm2 stop index.js
$ pm2 delete all
$ pm2 save
```

[![aaa](https://i.imgur.com/4M7IWwP.gif)](https://discord.link/hap)
