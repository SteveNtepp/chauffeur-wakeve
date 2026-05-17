# Wakëvé — Formulaire de Recrutement Transporteur

Un formulaire de recrutement transporteur moderne, immersif et responsive inspiré des expériences Typeform et Tally.

## ✨ Aperçu

Ce projet propose une expérience utilisateur fluide avec :

- Une question à la fois
- Animations de transition modernes
- Navigation clavier intuitive
- Barre de progression dynamique
- Design premium et responsive
- Logique conditionnelle intelligente
- Soumission asynchrone via Formspree
- Écran de confirmation personnalisé

---

## 📁 Structure du projet

```bash
/project
│
├── index.html
└── assets
    └── logo-wakeve.png
```

---

## 🚀 Fonctionnalités

### UX/UI moderne
- Inspiration Typeform / Tally
- Typographie élégante :
  - Playfair Display
  - Inter
- Glassmorphism léger
- Responsive mobile/tablette/desktop

### Navigation intuitive
- Entrée → question suivante
- Flèches clavier → navigation
- Boutons Suivant / Retour

### Logique conditionnelle
La question :

> "Type de semi-remorque"

s’affiche uniquement si :

> "Camion Semi"

a été sélectionné.

---

## 📬 Envoi des données

Le formulaire utilise :

```txt
https://formspree.io/f/xqejzjzl
```

L’envoi est géré en JavaScript avec `fetch()` afin de :
- éviter la redirection Formspree
- afficher un écran de succès personnalisé
- améliorer l’expérience utilisateur

---

## 🛠️ Technologies utilisées

- HTML5
- CSS3
- JavaScript Vanilla
- Formspree API
- Google Fonts

---

## ▶️ Lancer le projet

### Option simple
Ouvrir directement :

```bash
index.html
```

dans votre navigateur.

### Option recommandée
Utiliser un serveur local :

```bash
# VS Code
Live Server

# ou Python
python -m http.server
```

---

## 🌐 Déploiement GitHub Pages

1. Push du projet sur GitHub
2. Aller dans :
   - Settings
   - Pages
3. Sélectionner :
   - Branch : `main`
   - Folder : `/root`
4. Save

Votre formulaire sera disponible via :

```txt
https://votre-username.github.io/nom-du-repo/
```

---

## 🎨 Branding

Projet réalisé pour :

### Wakëvé
Transport & Logistique

---

## 📄 Licence

Usage interne Wakëvé.
