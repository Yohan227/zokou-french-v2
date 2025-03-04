<p align="center"><h1>Zokou-2.0 🚀</h1><br> </p>

![banner](Zokou.jpg)

Zokou est un bot multi-devices conçu pour enrichir vos conversations WhatsApp avec des fonctionnalités utiles et amusantes. Qu'il s'agisse de gérer des fichiers, d'interagir avec des stickers ou de faciliter la gestion de groupe, Zokou est là pour vous aider ! 🎉💬

## Fonctionnalités Principales ✨

- **Téléchargement de Fichiers :** Zokou peut télécharger des fichiers audio et vidéo à partir de liens que vous lui envoyez, pour que vous puissiez les partager facilement avec vos contacts. 🎶📹

- **Exportation de Stickers :** Vous pouvez exporter des stickers de Telegram et les utiliser dans vos conversations WhatsApp en les envoyant simplement à Zokou. 😄✨

- **Gestion de Groupe :** Zokou offre des fonctionnalités de gestion de groupe, comme l'ajout ou la suppression de membres, la configuration de règles et d'autres paramètres. 👥📋

- **Text to Image :** Les meilleurs logos ont été sélectionnés pour votre confort. 🖼️🎨

## Fonctionnalités Ludiques 🎉

- **Blagues et Devinettes :** Zokou est équipé d'une collection de blagues et de devinettes pour égayer vos conversations. 😂🤔

- **Citations Inspirantes :** Recevez des citations inspirantes pour vous motiver au quotidien. 💪🌟

## Obtenir Zokou 🛠️

1. Cliquez sur **[Fork](https://github.com/Luffy2ndAccount/zokou-french-v2/fork)** afin de copier le repo sur votre compte GitHub. N'oubliez pas d'ajouter une étoile 🌟 pour encourager les développeurs !

2. Obtenez une session du bot :  
   - [Session-1](https://zkscan.onrender.com)  
   - [Session-2](https://zokouscan-din3.onrender.com)

## Déploiement 🚀

- **Déploiement sur Heroku** :
  1. Si vous ne disposez pas de compte **Heroku**, cliquez [**ici**](https://id.heroku.com/login) pour en créer un.
  2. Cliquez [**ici**](https://dashboard.heroku.com/new?template=https://github.com/Luffy2ndAccount/zokou-french-v2) pour déployer le bot sur **Heroku**.

- **Déploiement sur Koyeb** :
  1. Si vous n'avez pas de compte **Koyeb**, cliquez [**ici**](https://dashboard.koyeb.com/signup) pour en créer un.
  2. Cliquez sur le bouton ci-dessous pour déployer sur Koyeb :<br>
     [![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?name=zokouvf&type=docker&image=docker.io%2Fluffy077%2Fzokouvf%3Alatest&env%5BPREFIXE%5D=.&env%5BLECTURE_AUTO_STATUS%5D=oui&env%5BTELECHARGER_AUTO_STATUS%5D=oui&env%5BNOM_BOT%5D=Zokou-MD&env%5BLIENS_MENU%5D=https%3A%2F%2Fwallpapercave.com%2Fuwp%2Fuwp3943464.jpeg&env%5BPM_PERMIT%5D=non&env%5BMODE_PUBLIC%5D=oui&env%5BETAT%5D=1&env%5BSESSION_ID%5D=mettez+votre+session&env%5BNOM_OWNER%5D=Djalega%2B%2B&env%5BNUMERO_OWNER%5D=22891733300&env%5BWARN_COUNT%5D=3&env%5BSTARTING_BOT_MESSAGE%5D=oui&env%5BANTI_VUE_UNIQUE%5D=oui&env%5BPM_CHATBOT%5D=non&env%5BHEROKU%5D=non&env%5BDATABASE_URL%5D=mettez+une+database&env%5BANTI_COMMAND_SPAM%5D=non&ports=8000%3Bhttp%3B%2F)

- **Déploiement sur Render** :
  1. Si vous n'avez pas de compte **Render**, cliquez [**ici**](https://dashboard.render.com) pour vous inscrire.
  2. Créez un nouveau sweb service.  
  3. Choisissez **Public Git Repository**.  
  4. Dans le champ , entrez `https://gitlab.com/bankai421341/senbonzakura.git`.
  5. Cliquez sur **Connect**.  
  6. Sélectionnez le **Free Plan** si vous ne voulez pas payer.  
  7. Dans la section **environemment variable**, cliquez sur **Add from .env** et copiez le contenu suivant :

```env
PREFIXE=.
LECTURE_AUTO_STATUS=non
TELECHARGER_AUTO_STATUS=non
NOM_BOT=Yohan-MD
LIENS_MENU=LUFFY
PM_PERMIT=non
MODE_PUBLIC=oui
ETAT=1
SESSION_ID="Zokou-MD-WHATSAPP-BOT;;;=>eyJub2lzZUtleSI6eyJwcml2YXRlIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiQVBxTUxPam12VEUxN1JIMnMzVE1lS1FTb0ZHaHRuRTVLVmROeWt4ZG5tbz0ifSwicHVibGljIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiYlNrZ2gzL0xuaUs5VnZZTmdaeUlRWERINWlldDlkQWdKL1d5elNWTURWST0ifX0sInBhaXJpbmdFcGhlbWVyYWxLZXlQYWlyIjp7InByaXZhdGUiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJ5RHVGUGF0dDBmdnVraXJ1MFZqLy8xMDBSUGFRbWtwTHhFa1NhVTQyZjFJPSJ9LCJwdWJsaWMiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJpcUdWQUtyMlJESmFBY1ZGaGNpMlByK1dLMURUOFUvWmpFVC94M2tWMUZ3PSJ9fSwic2lnbmVkSWRlbnRpdHlLZXkiOnsicHJpdmF0ZSI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6IjZFL3JzTzJBL3pTVGJoUlV2NHp5VmVxOHllVkZBelRaV1Jkb09RUzRlMjA9In0sInB1YmxpYyI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6IkI0bitJV0J6aUxLS3VHaU9YQXQ5dlhYQkticit3SUFXQTJrUHBKMElibms9In19LCJzaWduZWRQcmVLZXkiOnsia2V5UGFpciI6eyJwcml2YXRlIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiR0E5N3NPMnBJc2drcXJVWm1jSTlPZFNRbHFabUlmLzhjaHpCazVtakhVaz0ifSwicHVibGljIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiRW1UVDhsUFZKT3NwMEx4NUtQNEZjTVpobGxaTnZVeE83R255T1Rjb1QxTT0ifX0sInNpZ25hdHVyZSI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6Ik1vUkhTUDF0OVpCV2pTa1dlT3phU0lDVVg4Ym5JUzk0MWxjdmk2RFlOa1AyQTVYaG5DQXd4UUxaT24xcUpEMVpOUEVnVTk4UjgwVjJXZHVtSDMyeEJRPT0ifSwia2V5SWQiOjF9LCJyZWdpc3RyYXRpb25JZCI6NjcsImFkdlNlY3JldEtleSI6IlZZWFpNRmRCenJiTWM3ZGpuSzJZbEwwNHBlSURadTFSUnFEZ0lDYktNazA9IiwicHJvY2Vzc2VkSGlzdG9yeU1lc3NhZ2VzIjpbeyJrZXkiOnsicmVtb3RlSmlkIjoiMjIxNzc3MTk4Mzk1QHMud2hhdHNhcHAubmV0IiwiZnJvbU1lIjp0cnVlLCJpZCI6IkJGNThFRjMwNjg5RERCMTY0ODNCOTU5NUY5NDJCQjREIn0sIm1lc3NhZ2VUaW1lc3RhbXAiOjE3NDEwOTY1OTN9LHsia2V5Ijp7InJlbW90ZUppZCI6IjIyMTc3NzE5ODM5NUBzLndoYXRzYXBwLm5ldCIsImZyb21NZSI6dHJ1ZSwiaWQiOiIwQzEyNDE3ODA5N0UwOUIxMDk3RTlFNURFRTNBODRDMCJ9LCJtZXNzYWdlVGltZXN0YW1wIjoxNzQxMDk2NTk1fV0sIm5leHRQcmVLZXlJZCI6MzEsImZpcnN0VW51cGxvYWRlZFByZUtleUlkIjozMSwiYWNjb3VudFN5bmNDb3VudGVyIjoxLCJhY2NvdW50U2V0dGluZ3MiOnsidW5hcmNoaXZlQ2hhdHMiOmZhbHNlfSwicmVnaXN0ZXJlZCI6dHJ1ZSwicGFpcmluZ0NvZGUiOiI3SktaN0RGUCIsImxhc3RQcm9wSGFzaCI6IjNnUFVKayIsInJvdXRpbmdJbmZvIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiQ0EwSUNBPT0ifSwibWUiOnsiaWQiOiIyMjE3NzcxOTgzOTU6NjhAcy53aGF0c2FwcC5uZXQiLCJuYW1lIjoiWW9oYW4gTGllYmVydCBTUFkiLCJsaWQiOiIxNDE1MTk1NDE1NDcxMDc6NjhAbGlkIn0sImFjY291bnQiOnsiZGV0YWlscyI6IkNMQzgzZEFDRUllTm5MNEdHQXdnQUNnQSIsImFjY291bnRTaWduYXR1cmVLZXkiOiJERFZyZ3AxYytZd3JkNjR3Sm1CaW10QlBXZ2g4ZWtBZTJLWUNIbFRUMFhVPSIsImFjY291bnRTaWduYXR1cmUiOiJHZ1g1TFBsUVF1UkE1WDZwVUR4VklxNmlrQUdsU2lZcUVXRTRXOWdrR05PY3ZVNksvVnpMZExNcWJBWWlFYVBxdks2NWYwTUVpbE15cjhHOFd4YlRBdz09IiwiZGV2aWNlU2lnbmF0dXJlIjoiSjNNUWVncDZEOFBnaVZyTEc0anM2eWF6MDBVNHlLbWdqSkNQRWxHU2ZaVG40ZklqTC9Db1E4cFJmS2ZIc0RONXVaZTJzWWVTOWl0YVNmbnpteXNFQXc9PSJ9LCJzaWduYWxJZGVudGl0aWVzIjpbeyJpZGVudGlmaWVyIjp7Im5hbWUiOiIyMjE3NzcxOTgzOTU6NjhAcy53aGF0c2FwcC5uZXQiLCJkZXZpY2VJZCI6MH0sImlkZW50aWZpZXJLZXkiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJCUXcxYTRLZFhQbU1LM2V1TUNaZ1lwclFUMW9JZkhwQUh0aW1BaDVVMDlGMSJ9fV0sInBsYXRmb3JtIjoiYW5kcm9pZCIsImxhc3RBY2NvdW50U3luY1RpbWVzdGFtcCI6MTc0MTA5NjU4NiwibXlBcHBTdGF0ZUtleUlkIjoiQUFBQUFNb2kifQ=="
NOM_OWNER=Djalega++
NUMERO_OWNER=22891733300
WARN_COUNT=3
STARTING_BOT_MESSAGE=oui
ANTI_VUE_UNIQUE=oui
PM_CHATBOT=non
HEROKU=non
ANTI_COMMAND_SPAM=non
ANTI_DELETE_MESSAGE=oui
AUTO_REACT_MESSAGE=non
```

  8. Cliquez sur **Add env** pour enregistrer, puis modifiez selon vos besoins. N'oubliez pas d'entrer votre session ID.  
  9. Cliquez sur **Deploy service** et profitez-en !


 - **Déploiement GitHub**

  1. **Forkez le dépôt**.
  2. Modifiez le fichier `exemple_de_set.env` en `set.env` et ajoutez-y votre **session_ID**.
  3. Créez un nouveau fichier `.github/workflows/deploy.yml` et mettez-y ce contenu :

```yml
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main
  schedule:
    - cron: '0 */4 * * *'

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install ffmpeg
      run: |
        sudo apt-get update
        sudo apt-get install -y ffmpeg

    - name: Install dependencies
      run: |
        npm install -g pm2
        npm install

    - name: Start application with timeout
      run: |
        timeout 14520s npm run zokou

```


## Contributions 🤝

Les contributions à Zokou sont les bienvenues ! Si vous avez des idées pour de nouvelles fonctionnalités, des améliorations ou des corrections de bogues, n'hésitez pas à ouvrir une issue ou à soumettre une demande de pull. 🙌

### Remerciements :
- **Fatao**, qui a ajouté des commandes (Fancy, GPT, Dall-e, APK)  
- **CrazyPrice**, qui a hébergé un second site web pour les session_id  

## Licence 📜

Le Bot WhatsApp Zokou est publié sous la [Licence MIT](https://opensource.org/licenses/MIT).

Profitez des fonctionnalités variées du Bot WhatsApp Zokou pour améliorer vos conversations et rendre votre expérience WhatsApp plus intéressante ! 🎊💬

## Développeurs :
- [**Djalega++**](https://github.com/djalega8000/Zokou-MD/)
- [**᚛M๏𝓷keℽ D Lบffy᚜**](https://github.com/Faouz995)
