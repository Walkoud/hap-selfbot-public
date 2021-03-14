[![aaa](https://i.imgur.com/4M7IWwP.gif)](https://discord.link/hap)
# HΛP SELFBOT PREMIUM 2021
Selfbot de la HAP

<p align="center">
<a href="https://discord.link/hap"><img src="https://img.shields.io/github/watchers/Walkoud/hap-selfbot-public?logoColor=purple&style=social"></a>
  <a href="https://discord.link/hap"><img src="https://img.shields.io/github/last-commit/Walkoud/hap-selfbot-public"></a>
<a href="https://discord.link/hap"><img src="https://img.shields.io/discord/736923536475684974?label=Join%20HΛP&logo=discord&style=flat-square"></a>

</p>


http://discord.link/hap


## Screens

![Capture](https://user-images.githubusercontent.com/38588921/111040103-e67abf00-8431-11eb-8d3d-a48535a32077.PNG)

Besoin de nodejs et de git installé sur votre Windows

 
## Installation :


### Installation Windows
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

### Installation Linux or Termux (Android)
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

## Configuration :

### Configuration TOKEN , ID , PREFIX

Ouvrez settings.json du dossier, puis changez le [token](https://youtu.be/2GBOYptubk4) en la votre et le prefix(pas obligé le préfix )! <br/>

Open folder settings.json, then change the [token](https://youtu.be/2GBOYptubk4) to your own and the prefix (not required the prefix)! <br/>


| Key config | Explanation | Default |
| ------ | ------ | ----- | 
| token | Your token discord | no |
| prefix | Prefix of commands | .
| ID | Your ID DIscord | default (automatic id)
| status | Your Discord Status (Watching this, playins this) | lofi chill
| statustype | LISTENING or WATCHING or STREAMING or PLAYING | LISTENING
| multipresence | Auto change status with multiple text (OFF, ON) | ON
| multipresencetype | Same of Status Type | WATCHING
| multipresenceSECONDS | Seconds of interval | 15
| autoclaimnitro | Auto claim when nitro is droped (OFF ON) | ON
| backupprefix | Prefixs of backups commands | ["x!", "!x"]


### Pour avoir son token
 
 ##### Pour le token de votre compte
 
Téléchargez https://mega.nz/file/dEIGTI6b#Kb0DjmsH6FMbiwJ_q8Mrkd93kFazRDkVsxDZA4WTgJ8

Puis installez l'apk, ouvrez l'application, puis appuyez sur la petite flèche en haut à gauche, cliquez sur Token Track, puis mettez vos identifiants discord, puis cliquez sur Track Token, et voilà vous aurez votre token affiché devant vous.



## Auto restart when crash :

To restart automaticly when it crash
Pour redémarrer automatiquement quand ça crash

```sh
$ npm i pm2
$ pm2 start index.js
```


[![aaa](https://i.imgur.com/4M7IWwP.gif)](https://discord.link/hap)
