![Multi_Color_Bar](https://github.com/Walkoud/CS2-Auto-Accept/assets/38588921/3f57ad10-c80c-457a-9f49-679558eb2f79)

# HΛP SELFBOT PREMIUM 2024

## 🚀 MISE À JOUR 2024

Vous pouvez désormais télécharger des vidéos depuis **YouTube**, **TikTok**, **Instagram**, **Twitter** et **X** :  
<br>
![OKg5Yy3Mm8](https://github.com/Walkoud/hap-selfbot-public/assets/38588921/25b5463a-0958-4fff-8e31-a5a57042862e)  
![zosvJAIn5B](https://github.com/Walkoud/hap-selfbot-public/assets/38588921/f471c5fb-da47-49b3-a305-9506b42de414)

---

## 🌟 Fonctionnalités

- **Rich Presence** : Personnalisez votre statut Discord avec des options de rich presence.
- **Commandes de sauvegarde** : Sauvegardez et restaurez facilement vos données.
- **Nitro Sniper** : Réclamez automatiquement les Nitro drops.
- **Participation automatique aux giveaways** : Participez automatiquement aux giveaways.
- **Logger de messages** : Enregistrez les messages supprimés dans les DM.
- **Téléchargeur de vidéos** : Téléchargez des vidéos depuis des plateformes populaires.
- Et bien plus encore...

---

## 📖 Table des matières

- [Installation](#installation)
  - [Windows](#installation-windows)
  - [Linux ou Termux (Android)](#installation-linux-ou-termux-android)
- [Configuration](#configuration)
  - [Token, ID et Préfixe](#token-id-et-prefixe)
  - [Configuration simple](#configuration-simple)
  - [Configuration de présence](#configuration-de-presence)
- [Comment obtenir votre token](#comment-obtenir-votre-token)
- [Redémarrage automatique en cas de crash](#redemarrage-automatique-en-cas-de-crash)
- [Commandes disponibles](#commandes-disponibles)
- [⚠️ Avertissement](#avertissement)

---

## 📥 Installation <a id="installation"></a>

### Windows <a id="installation-windows"></a>

1. **Téléchargez le ZIP** :  
   [Cliquez ici](https://github.com/Walkoud/hap-selfbot-public/archive/master.zip) pour télécharger le projet.

2. **Installez Node.js** :  
   Téléchargez [Node.js](https://nodejs.org/) (v4+).

3. **Installez Git** :  
   Téléchargez [Git pour Windows](https://git-scm.com/download/win).

4. **Exécutez l'installateur** :  
   Double-cliquez sur `Install.bat` pour installer les dépendances nécessaires.

5. **Lancez le bot** :  
   Double-cliquez sur `run.bat` pour démarrer le bot.

6. **Mettez à jour la configuration** :  
   Modifiez `settings.json` pour configurer votre token, préfixe et autres paramètres.

---

### Linux ou Termux (Android) <a id="installation-linux-ou-termux-android"></a>

1. **Installez Git et Node.js** :  
   Exécutez les commandes suivantes dans Termux ou votre terminal Linux :
   ```sh
   apt update && apt upgrade
   termux-setup-storage
   apt-get install git nodejs
   ```

2. **Clonez le dépôt** :  
   ```sh
   git clone https://github.com/Walkoud/hap-selfbot-public
   cd hap-selfbot-public
   ```

3. **Installez les dépendances** :  
   ```sh
   npm install
   npm install discord.js@11
   ```

4. **Lancez le bot** :  
   ```sh
   node index.js
   ```

5. **Mettez à jour la configuration** :  
   Modifiez `settings.json` pour configurer votre token, préfixe et autres paramètres.

---

## ⚙️ Configuration <a id="configuration"></a>

### Token, ID et Préfixe <a id="token-id-et-prefixe"></a>

- **Token** : Remplacez le token par défaut par le token de votre compte Discord.
- **Préfixe** : Définissez votre préfixe de commande préféré.

Pour voir les commandes disponibles, exécutez :
```sh
node index help
```

Exemple pour changer le préfixe :
```sh
node index prefix !
```

---

### Configuration simple <a id="configuration-simple"></a>

| Clé                | Description                                      | Valeur par défaut |
|--------------------|--------------------------------------------------|-------------------|
| `token`            | Votre token Discord                              | Aucun             |
| `prefix`           | Préfixe des commandes                            | `.`               |
| `ID`               | Votre ID Discord                                | Auto-détecté      |
| `autoDownloadMediaURL` | Télécharge automatiquement les vidéos depuis les URLs | `true`            |
| `autoCropVideos`   | Recadre automatiquement les bandes noires dans les vidéos | `true`            |
| `thumbnailcmd`     | Affiche les miniatures dans les commandes        | `true`            |
| `autoclaimnitro`   | Réclame automatiquement les Nitro drops         | `ON`              |
| `messagelogger`    | Enregistre les messages supprimés dans les DM    | `ON`              |
| `backupprefix`     | Préfixe pour les commandes de sauvegarde         | `["x!", "!x"]` |
| `giveawayauto`     | Participe automatiquement aux giveaways          | `ON`              |
| `giveawaywebhook`  | URL du webhook pour les logs de giveaways        | Aucun             |

---

### Configuration de présence <a id="configuration-de-presence"></a>

| Clé                     | Description                                  | Valeur par défaut |
|-------------------------|----------------------------------------------|-------------------|
| `presence`              | Type de présence (`richpresence`, `normal`) | `richpresence`    |
| `status`                | Texte du statut personnalisé                 | `lofi chill`      |
| `statustype`            | Type de statut (`LISTENING`, `WATCHING`, etc.) | `LISTENING`       |
| `richpresencetype`      | Type de rich presence (`STREAMING`, `WATCHING`) | `STREAMING`       |
| `richpresenceID`        | ID de l'application pour le rich presence    | `805871101179068438` |
| `richpresencedetail`    | Texte de détail pour le rich presence        | `HΛP SELFBOT`     |
| `richpresenceurl`       | URL du stream pour le rich presence          | `https://twitch.tv/lofi` |
| `multipresence`         | Active la rotation de statuts multiples      | `ON`              |
| `multipresenceSECONDS`  | Intervalle pour la rotation des statuts (en secondes) | `15`              |

---

## 🔑 Comment obtenir votre token <a id="comment-obtenir-votre-token"></a>

1. Téléchargez l'APK depuis [ce lien](https://mega.nz/file/dEIGTI6b#Kb0DjmsH6FMbiwJ_q8Mrkd93kFazRDkVsxDZA4WTgJ8).
2. Installez l'APK et ouvrez l'application.
3. Cliquez sur la flèche en haut à gauche, sélectionnez "Token Track" et connectez-vous avec vos identifiants Discord.
4. Cliquez sur "Track Token" pour récupérer votre token.

---

## 🔄 Redémarrage automatique en cas de crash <a id="redemarrage-automatique-en-cas-de-crash"></a>

Installez `pm2` pour redémarrer automatiquement le bot en cas de crash :
```sh
npm i -g pm2
pm2 start index.js
pm2 save
```

Pour arrêter le bot :
```sh
pm2 stop index.js
pm2 delete all
pm2 save
```

---

## 🛠️ Commandes disponibles <a id="commandes-disponibles"></a>

### Syntaxe de base
```
urlTodownload [options]
```

### Options
- `crop` : Active le recadrage.
- `nocrop` : Désactive le recadrage.
- `rotateL` : Pivote la vidéo vers la gauche.
- `rotateR` : Pivote la vidéo vers la droite.

### Exemples
- `urlTodownload crop` → Télécharge avec le recadrage activé.
- `urlTodownload crop rotateL` → Télécharge avec le recadrage et une rotation vers la gauche.

---

## ⚠️ Avertissement <a id="avertissement"></a>

> **Ce selfbot viole les Conditions d'Utilisation (ToS) de la plupart des plateformes, y compris Discord.**  
> L'utilisation de ce selfbot peut entraîner une suspension ou un bannissement permanent de votre compte.  
> **Utilisez-le à vos propres risques.**