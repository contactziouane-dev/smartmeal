# SMARTMEAL — Site Web de Présentation & Startup

> **« Un distributeur. Deux expériences. Une nouvelle opportunité commerciale. »**

Projet de startup technologique combinant la **distribution automatique de produits alimentaires** et un **réseau d'écrans publicitaires numériques connectés (SMARTMEAL ADS)**.

---

## 👥 Porteurs du Projet (Fondateurs)

- **Ziouane Fethi** — Étudiant Ingénieur
- **Mejdoub El Mahdi** — Étudiant Ingénieur

> *« Nous travaillons sur ce projet depuis deux mois. Nous avons déjà développé et validé un premier prototype fonctionnel axé sur la technologie de communication et de pilotage avec le distributeur. Aujourd'hui, nous recherchons des partenaires et des financements pour passer à l'échelle industrielle. Le schéma d'ingénierie et la feuille de route sont déjà parfaitement structurés dans nos esprits. »*

---

## 🌟 Points Clés du Projet

1. **SMARTMEAL FOOD** : Distribution automatique de sandwichs, repas frais, snacks, café de qualité et boissons, disponible 24h/24 et 7j/7.
2. **SMARTMEAL ADS** : Vrais écrans numériques haute luminosité intégrés physiquement à la structure des distributeurs (côtés gauche/droit et façade), pilotés à distance via cloud.
3. **Plateforme Annonceur en Libre-Service** : Portail web et application mobile permettant aux annonceurs de cibler un établissement, sélectionner un écran, définir leurs dates et suivre les diffusions en temps réel.
4. **Modèle Économique Hybride Résilient** : Double flux de revenus (marges sur les ventes alimentaires + régie publicitaire continue).

---

## 📁 Structure du Projet

```text
smartmeal-web/
├── index.html              # Site web complet (12 sections, responsive, mode clair)
├── css/
│   └── style.css           # Charte graphique (Vert émeraude #059669, blanc, gris clair)
├── js/
│   └── app.js              # Moteur interactif (simulateur publicitaire, lightbox, filtres)
├── images/                 # Galerie complète des 9 photographies réelles du projet
├── server.js               # Serveur HTTP local ultra-léger (Node.js natif, zéro dépendance)
├── LANCER_LE_SITE.bat      # Lancement rapide en un double-clic sous Windows
├── .gitignore              # Configuration Git pour GitHub
└── README.md               # Documentation officielle du projet
```

---

## 🚀 Comment Lancer le Site

### Méthode 1 : En un double-clic (Recommandé)
Double-cliquez simplement sur le fichier **`LANCER_LE_SITE.bat`**.  
Le serveur démarrera automatiquement et le site s'ouvrira dans votre navigateur par défaut à l'adresse :  
👉 `http://localhost:3000`

### Méthode 2 : Avec Node.js
Dans un terminal, placez-vous dans le dossier et tapez :
```bash
node server.js
```
Puis ouvrez `http://localhost:3000` dans votre navigateur.

### Méthode 3 : Directement sans serveur
Vous pouvez également faire un double-clic direct sur **`index.html`** pour l'ouvrir dans n'importe quel navigateur web (Chrome, Edge, Firefox, Safari).

---

## 🐙 Comment Publier ce Projet sur GitHub

1. Ouvrez un terminal dans ce dossier et initialisez le dépôt Git :
```bash
git init
git add .
git commit -m "Initial commit: Site web de présentation SmartMeal"
```

2. Créez un nouveau dépôt vide sur votre compte GitHub (ex: `smartmeal-web`).

3. Liez votre dépôt local et publiez vos fichiers :
```bash
git branch -M main
git remote add origin https://github.com/VOTRE_PSEUDO/smartmeal-web.git
git push -u origin main
```

4. *(Optionnel)* Pour mettre le site en ligne gratuitement accessible à tous via le web, activez **GitHub Pages** dans les paramètres de votre dépôt GitHub (`Settings` > `Pages` > sélectionner la branche `main` / `root`).

---

## 📄 Licence & Mention Académique
Projet d'innovation technologique et d'entrepreneuriat étudiant — Tous droits réservés © 2026 Ziouane Fethi & Mejdoub El Mahdi.
