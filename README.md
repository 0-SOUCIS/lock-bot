### Aide de KAWAKI227 pour déployer le BOT 'lock-bot' de venom sur Termux.

---

Cette aide est destinée à ceux qui souhaitent déployer le bot **lock-bot** sur **Termux**  sans avoir à télécharger les fichiers. Vous êtes libres de fork le repo pour modifier le code en cas d'erreur.

<a><img src='https://i.imgur.com/2mOFN2e.jpeg'/></a><a><img src='https://i.imgur.com/LyHic3i.png'/></a>


# Termux Deployment
```
termux-setup-storage
apt update
apt upgrade
pkg update && pkg upgrade
pkg install bash
pkg install libwebp
pkg install git -y
pkg install nodejs -y
pkg install ffmpeg -y 
pkg install wget
pkg install yarn
git clone (copie et passe le lien du repo que tu a fork avec tes modifications ) 
cd lock-bot
sh instalar.sh
venom
venom
Appuie sur entrer deux fois !
```

### Dès que le chargement fini vous devez choisir la fonction "1" pour le pairing code et "2" pour le code qr

### À cet stade vous mettez votre numéro comme l'inscrit sur la console termux et link avec le code donner avec WhatsApp

### NB: après si le bot s'arrête vous ne devriez que faire :

```
cd lock-bot
npm start
```

<a><img src='https://i.imgur.com/LyHic3i.gif'/></a><a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
- If you want Command For 24/7 (might no work) 
```js
npm i -g forever && forever index.js && forever save && forever logs
```
<br>

<a><img src='https://i.imgur.com/LyHic3i.gif'/></a><a><img src='https://i.imgur.com/LyHic3i.gif'/></a>
<br>

- [`KAWAKI227`](github.com/kawaki227)
- [`0-SOUCIS`](github.com/0-SOUCIS)
