# ⚡ Lazar.dev — Portfolio & App Store

## 📁 Structure des dossiers

```
portfolio/
├── index.html                      ← Le site complet (fichier unique)
├── downloads/
│   ├── LISEZMOI.txt
│   └── Dev_Kanban_Setup.exe        ← Place ton .exe ici
└── README.md
```

## 🚀 Déploiement

### Option 1 : GitHub Pages (gratuit)
1. Crée un repo GitHub (ex: `mon-portfolio`)
2. Pousse les fichiers (index.html + dossier downloads/)
3. Va dans **Settings > Pages > Source: main branch**
4. Ton site sera sur `https://ton-pseudo.github.io/mon-portfolio/`

### Option 2 : Vercel (gratuit)
1. Connecte ton repo GitHub à Vercel
2. Déploiement automatique à chaque push

### Option 3 : Local
```bash
# Ouvre simplement index.html dans ton navigateur
# Ou lance un serveur local :
npx serve .
```

## ✏️ Personnalisation

Tout est dans `index.html`. Modifie :

- **Ligne ~270** : Ton nom/logo (`Lazar.dev`)
- **Ligne ~346** : L'accroche de la Hero
- **Ligne ~420+** : La description du logiciel
- **Ligne ~540+** : Les projets web (ajoute/retire des cartes)
- **Ligne ~600** : Ton email de contact
- **Ligne ~640** : Tes liens GitHub/LinkedIn

Pour ajouter un nouveau logiciel, duplique le bloc
`<!-- SOFTWARE CARD -->` et modifie le contenu.

## ⚠️ Important pour les .exe

GitHub Pages a une limite de **100 MB par fichier**.
Si ton .exe dépasse cette taille, utilise GitHub Releases
et pointe le lien du bouton vers l'URL de la Release.
