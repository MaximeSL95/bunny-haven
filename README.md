# 🐰 Bunny Haven — Refuge pour lapins

> *"Give every bunny a safe haven"*

Site web complet pour **Bunny Haven**, une association fictive dédiée au recueil, aux soins et à l'adoption de lapins abandonnés. Projet réalisé à des fins de **démonstration portfolio**.

---

## 🌐 Demo en ligne

👉 **[Voir le site](https://votre-pseudo.github.io/bunny-haven)**

---

## 📸 Aperçu

| Page | Description |
|------|-------------|
| 🏠 Accueil | Hero animé, stats compteur, mission |
| 🐇 Nos lapins | Galerie filtrée dynamiquement |
| 📖 À propos | Histoire, valeurs, équipe |
| 🤝 Adopter | Processus + formulaire validé |
| 📍 Nous trouver | Carte Google Maps + horaires |
| 📩 Contact | Formulaire avec validation JS |
| 💛 Faire un don | Page de don fictive interactive |

---

## ✨ Fonctionnalités

- ✅ **SPA** (Single Page Application) — navigation sans rechargement
- ✅ **Filtres dynamiques** — recherche par nom, statut, caractère, âge
- ✅ **Validation de formulaires** — messages d'erreur propres
- ✅ **Mode sombre** — persisté en localStorage
- ✅ **Compteurs animés** — statistiques du refuge
- ✅ **Scroll reveal** — animations au défilement
- ✅ **Burger menu** — navigation mobile
- ✅ **Responsive** — mobile, tablette, desktop
- ✅ **Illustrations SVG** — dessin de lapin custom

---

## 🛠️ Technologies

| Technologie | Usage |
|-------------|-------|
| HTML5 | Structure sémantique |
| CSS3 | Variables, Grid, Flexbox, animations |
| JavaScript Vanilla | SPA, filtres, formulaires, compteurs |
| Google Fonts | Playfair Display + DM Sans |

> Aucune dépendance externe — zéro framework, zéro npm.

---

## 🚀 Lancer le projet localement

```bash
# 1. Cloner le repository
git clone https://github.com/votre-pseudo/bunny-haven.git

# 2. Ouvrir le dossier
cd bunny-haven

# 3. Ouvrir dans le navigateur
open index.html
# ou double-cliquez simplement sur index.html
```

Aucune installation requise. Le site fonctionne directement dans le navigateur.

---

## 📁 Structure du projet

```
bunny-haven/
├── index.html      # Site complet (HTML + CSS + JS dans un seul fichier)
└── README.md       # Documentation
```

---

## 🎨 Palette de couleurs

| Nom | Hex | Usage |
|-----|-----|-------|
| Crème | `#fdf8f3` | Fond principal |
| Beige | `#f0e8d8` | Sections alternées |
| Vert sauge | `#5a7a5a` | Couleur principale (boutons, accents) |
| Rose doux | `#e8b4b0` | Accents secondaires |
| Brun | `#4a3628` | Titres, footer |

---

## 🐇 Données fictives

La base de données des lapins est définie en JavaScript pur dans `index.html` :

```javascript
const rabbits = [
  {
    id: 1,
    name: "Luna",
    age: 2,
    personality: "Calme",
    status: "adoptable",
    desc: "Luna est une lapine douce qui adore les câlins le matin."
  },
  // ...9 lapins au total
];
```

---

## 📱 Compatibilité

| Navigateur | Support |
|------------|---------|
| Chrome 90+ | ✅ |
| Firefox 88+ | ✅ |
| Safari 14+ | ✅ |
| Edge 90+ | ✅ |
| Mobile (iOS/Android) | ✅ |

---

## 🙏 Crédits

- Projet fictif créé à des fins de portfolio
- Illustrations SVG dessinées en CSS/SVG custom
- Typographies : [Google Fonts](https://fonts.google.com)

---

## 📄 Licence

Ce projet est libre d'utilisation à des fins personnelles et éducatives.  
**Association Bunny Haven = entité 100% fictive.**

---

*Made with 🐇 & 💚 par [Votre Nom]*
