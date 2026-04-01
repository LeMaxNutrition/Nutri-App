# 🥗 Nutri — Analyseur Calorique PWA

Application mobile PWA d'analyse nutritionnelle par photo, alimentée par Claude AI.

## Fonctionnalités
- 📸 Photo de l'assiette → identification automatique des aliments + calories
- 📊 Dashboard journalier : calories consommées vs objectif, macros, courbe 7 jours
- 🗂️ Historique des repas par jour
- 💾 Stockage 100% local (localStorage) — aucune donnée envoyée à un serveur
- 📱 Installable sur iPhone comme une vraie app (PWA)

---

## Installer sur iPhone via GitHub Pages (GRATUIT)

### Étape 1 — Créer un compte GitHub
Rendez-vous sur [github.com](https://github.com) et créez un compte gratuit.

### Étape 2 — Créer un nouveau dépôt
1. Cliquez sur **"New repository"**
2. Nommez-le `nutri-app` (ou ce que vous voulez)
3. Cochez **"Public"**
4. Cliquez **"Create repository"**

### Étape 3 — Uploader les fichiers
Cliquez sur **"uploading an existing file"** et déposez ces 5 fichiers :
- `index.html`
- `manifest.json`
- `sw.js`
- `icon-192.svg`
- `icon-512.svg`

Cliquez **"Commit changes"**.

### Étape 4 — Activer GitHub Pages
1. Allez dans **Settings** → **Pages**
2. Source : **"Deploy from a branch"**
3. Branch : **main** → **/root**
4. Cliquez **Save**

⏳ Attendez 1-2 minutes. Votre app sera accessible sur :
`https://VOTRE_USERNAME.github.io/nutri-app/`

### Étape 5 — Installer sur iPhone
1. Ouvrez l'URL ci-dessus dans **Safari** sur votre iPhone
2. Appuyez sur le bouton **Partager** (carré avec flèche ↑)
3. Faites défiler et tapez **"Sur l'écran d'accueil"**
4. Tapez **"Ajouter"**

✅ L'app apparaît sur votre écran d'accueil comme une vraie application !

---

## Notes importantes
- L'analyse IA nécessite une connexion internet (appel à l'API Anthropic)
- Toutes vos données de repas sont stockées localement sur votre appareil
- L'app fonctionne hors-ligne pour consulter l'historique et le dashboard
