# 📷 Mini-site – Photographie Numérique

Site web statique éducatif réalisé en **HTML et CSS uniquement** (sans JavaScript),
destiné à un public lycéen.

## Structure du projet

```
photo-site/
├── index.html        → Page 1 : Historique de la photographie numérique
├── capteur.html      → Page 2 : Les images et le capteur photo
├── traitement.html   → Page 3 : Le traitement d'image
├── exif.html         → Page 4 : Les métadonnées EXIF
├── style.css         → Feuille de style commune (10+ propriétés CSS)
└── README.md         → Ce fichier
```

## Pages du site

| Page | Titre | Fichier |
|------|-------|---------|
| 1 | Historique de la photographie numérique | `index.html` |
| 2 | Les images et le capteur photo | `capteur.html` |
| 3 | Le traitement d'image | `traitement.html` |
| 4 | Les métadonnées EXIF | `exif.html` |

## Éléments présents sur chaque page

- ✅ Titre clair et bandeau d'introduction
- ✅ Paragraphe explicatif structuré
- ✅ Liste ordonnée `<ol>`
- ✅ Liste non ordonnée `<ul>`
- ✅ Tableau HTML `<table>`
- ✅ Image avec légende `<figure>` / `<figcaption>`
- ✅ Vidéo YouTube intégrée `<iframe>`
- ✅ Lien externe fiable (Wikipedia)
- ✅ Menu de navigation entre les 4 pages

## Feuille de style CSS – Propriétés utilisées

1. `background-color` – fond de la page et des cartes
2. `color` – couleurs des textes
3. `font-family` – polices différentes pour titres et corps
4. `font-size` – tailles typographiques variées
5. `line-height` – interligne pour la lisibilité
6. `border` – bordures sur l'en-tête, les tableaux, etc.
7. `padding` – espacement interne des éléments
8. `margin` – espacement externe
9. `box-shadow` – ombres sur les cartes et médias
10. `list-style` – suppression des puces natives des listes
11. `border-radius` – coins arrondis
12. `display` (flex/grid) – mise en page moderne
13. `position` – en-tête sticky
14. `transition` – effets de survol sur les liens
15. `text-decoration` – liens sans soulignement
16. `overflow-x` – tableaux responsive
17. `object-fit` – images bien cadrées

## Déploiement sur GitHub Pages

1. Créer un dépôt GitHub public
2. Uploader tous les fichiers à la racine du dépôt
3. Aller dans **Settings** → **Pages**
4. Choisir la branche `main` et le dossier `/root`
5. Le site sera accessible à l'adresse :
   `https://votre-nom.github.io/votre-depot/`

## Contraintes respectées

- ✅ HTML et CSS uniquement (aucun JavaScript)
- ✅ Code commenté et structuré
- ✅ Contenu original (niveau lycée)
- ✅ Design cohérent avec feuille de style séparée
- ✅ Responsive mobile (media queries)
- ✅ Prêt pour GitHub Pages
