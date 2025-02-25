- 👋 Hi, I’m @mikaelsonangel844
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
mikaelsonangel844/mikaelsonangel844 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<p align="center"><h1>murphy-2.0.0 🚀</h1><br> </p>

![banner](murphy.jpg.jpg)

Zokou est un bot multi-devices conçu pour enrichir vos conversations WhatsApp avec des fonctionnalités utiles et amusantes. Qu'il s'agisse de gérer des fichiers, d'interagir avec des stickers ou de faciliter la gestion de groupe, Zokou est là pour vous aider ! 🎉💬

## Fonctionnalités Principales ✨

- **Téléchargement de Fichiers :** murphy-md télécharger des fichiers audio et vidéo à partir de liens que vous lui envoyez, pour que vous puissiez les partager facilement avec vos contacts. 🎶📹

- **Exportation de Stickers :** Vous pouvez exporter des stickers de Telegram et les utiliser dans vos conversations WhatsApp en les envoyant simplement à Zokou. 😄✨

- **Gestion de Groupe :** murphy-md env
PREFIXE=.
LECTURE_AUTO_STATUS=non
TELECHARGER_AUTO_STATUS=non
NOM_BOT=Zokou-MD
LIENS_MENU=LUFFY
PM_PERMIT=non
MODE_PUBLIC=oui
ETAT=1
SESSION_ID=zokk
NOM_OWNER=ᴍᴜʀᴘʜʏ᭄ғғ⚠️
NUMERO_OWNER=242057954499
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


Profitez des fonctionnalités variées du Bot WhatsApp murphy-md pour améliorer vos conversations et rendre votre expérience WhatsApp plus intéressante ! 🎊💬

## Développeurs :offre des fonctionnalités de gestion de groupe, comme l'ajout ou la suppression de membres, la configuration de règles et d'autres paramètres. 👥📋

- **Text to Image :** Les meilleurs logos ont été sélectionnés pour votre confort. 🖼️🎨

## Fonctionnalités Ludiques 🎉

- **Blagues et Devinettes :** murphy-md est équipé d'une collection de blagues et de devinettes pour égayer vos conversations. 😂🤔

- **Citations Inspirantes :** Recevez des citations inspirantes pour vous motiver au quotidien. 💪🌟
