# Compte-Points 🎲

Application web pour compter les points de mes jeux de société/cartes préférés, entre potes. Pas de backend, pas d'installation : juste des pages HTML/CSS/JS statiques, ouvrables directement dans un navigateur ou hébergeables sur GitHub Pages.

## Jeux disponibles

- Jeu des cochons 🐖🐖
- Président 👑 vs Trouduc 💩
- 10.000 🎲🎲🎲🎲🎲

Chaque jeu suit le même parcours : sélection des joueurs → (configuration des points, selon le jeu) → partie → résultats (classement + statistiques).

## Utilisation

Ouvrir `index.html` dans un navigateur (mobile ou desktop). Aucune installation ni compilation nécessaire.

## Structure

- `index.html`, `style.css`, `common.js` — page d'accueil et styles/scripts partagés entre tous les jeux
- `cochons/`, `président/`, `dix-mille/` — un dossier par jeu, avec ses propres pages
