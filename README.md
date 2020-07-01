# HΛP SELFBOT PREMIUM 2020
Selfbot de la HAPRAID HAP

http://hapraid.com

Besoin de nodejs et de git installé sur votre Windows



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
$ node index.js
```
N'oubliez pas de changer votre configuration dans le settings.json !


### Configuration TOKEN , ID , PREFIX

Ouvrez settings.json du dossier, puis changez le [token](https://youtu.be/2GBOYptubk4) en la votre, l'id de votre compte et le prefix(pas obligé le préfix )! <br/>

Open folder settings.json, then change the [token](https://youtu.be/2GBOYptubk4) to your own, your account id and the prefix (not required the prefix)! <br/>



### Pour avoir son token et id sous android
 
 ##### Pour le token de votre compte
 
Téléchargez https://mega.nz/file/dEIGTI6b#Kb0DjmsH6FMbiwJ_q8Mrkd93kFazRDkVsxDZA4WTgJ8

Puis installez l'apk, ouvrez l'application, puis appuyez sur la petite flèche en haut à gauche, cliquez sur Token Track, puis mettez vos identifiants discord, puis cliquez sur Track Token, et voilà vous aurez votre token affiché devant vous.

##### Pour l'ID de votre compte 

Allez dans l'application discord, puis dans les paramètres, cliquez sur la catégorie "Comportement", puis cochez la case "Mode développeur", <br/>
Maintenez votre image dans une conversation discord, puis descendez en bas et appuyez sur "Copier l'identifiant"
