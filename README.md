# Projets & Expérimentations

Site vitrine pour documenter et valoriser des projets autour de la pédagogie agricole, l'innovation en élevage herbager, l'expérimentation technique et le numérique au service de l'agriculture.

## Structure du site

```
├── index.html              # Page d'accueil
├── a-propos.html           # Page À propos
├── projets.html            # Liste des projets (avec filtres)
├── projet-detail.html      # Modèle de fiche projet détaillée
├── ressources.html         # Bibliothèque de ressources
├── lab.html                # Espace laboratoire / prototypes
├── medias.html             # Vidéos, podcasts, publications
├── contact.html            # Formulaire de contact
├── style.css               # Feuille de style unique
├── main.js                 # JavaScript (navigation, filtres, animations)
└── README.md
```

> **Tous les fichiers sont à la racine** pour une compatibilité maximale avec GitHub Pages (pas de problème de chemins relatifs).

## Déploiement sur GitHub Pages

1. Créer un repository sur GitHub
2. Pousser l'ensemble des fichiers à la racine du repo
3. Aller dans **Settings → Pages**
4. Sélectionner la branche `main` et le dossier `/ (root)`
5. Le site sera accessible à `https://votre-nom.github.io/nom-du-repo/`

## Technologies

- HTML5, CSS3 (variables CSS, grid, flexbox, animations), JavaScript vanilla
- Fonts : DM Serif Display, Outfit, JetBrains Mono (Google Fonts)

## Personnalisation

- **Couleurs** : modifier les variables CSS dans `:root` de `style.css`
- **Contenu** : éditer directement les fichiers HTML
- **Projets** : dupliquer `projet-detail.html` pour chaque nouveau projet
- **Formulaire** : intégrer un service comme [Formspree](https://formspree.io) pour le traitement des messages
