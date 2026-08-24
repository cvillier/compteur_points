# Compte-Points 🎲

Application web pour compter les points de mes jeux de société/cartes préférés, entre potes. Pas de backend, pas d'installation : juste des pages HTML/CSS/JS statiques.

🔗 **En ligne : https://cvillier.github.io/compteur_points/**

## Jeux disponibles

- Jeu des cochons 🐖🐖 (compteur manuel, ou simulateur avec tirage automatique)
- Président 👑 vs Trouduc 💩
- 10.000 🎲🎲🎲🎲🎲

Chaque jeu suit le même parcours : sélection des joueurs → (configuration des points, selon le jeu) → partie → résultats (classement + statistiques).

## Utilisation

Ouvrir `index.html` dans un navigateur, ou utiliser directement le lien ci-dessus. Aucune installation ni compilation nécessaire.

## Structure

- `index.html`, `style.css`, `common.js` — page d'accueil et styles/scripts partagés entre tous les jeux
- `cochons/`, `président/`, `dix-mille/` — un dossier par jeu, avec ses propres pages
