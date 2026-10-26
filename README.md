# Ma collection de jeux vidéo

Tableau de bord interactif de ma collection (drill down / roll up, filtres, recherche, favoris).
Page unique et autonome : tout est dans `index.html`, sans dépendance externe.

## Mise en ligne sur GitHub Pages
1. Sur github.com : **New repository** (par exemple `collection`). Dépôt **Public** pour un compte gratuit.
2. **Add file > Upload files** : glisser **le contenu** de ce dossier (`index.html`, `robots.txt`, `README.md`, `.nojekyll`), puis **Commit changes**.
   `.nojekyll` est facultatif : si ton explorateur de fichiers masque les fichiers commençant par un point, tu peux l'ignorer.
3. **Settings > Pages** : *Source* = **Deploy from a branch**, branche **main**, dossier **/ (root)**, puis **Save**.
4. Après 1 à 2 minutes, la page est disponible à : `https://TON-PSEUDO.github.io/NOM-DU-DEPOT/`

## Mettre à jour
Remplacer `index.html` dans le dépôt (**Add file > Upload files**, même nom) puis valider. La page se met à jour toute seule.

## À savoir
- **Le site est public** : toute personne qui connaît l'adresse voit la collection. `robots.txt` et la balise `noindex` demandent aux moteurs de recherche de ne pas l'indexer, mais ce n'est pas une protection.
  Pour l'indexer, supprimer `robots.txt` et la ligne `<meta name="robots" ...>` de `index.html`.
- Les **favoris** (étoiles) sont enregistrés dans le navigateur de chaque visiteur (localStorage) : ils ne sont ni partagés ni synchronisés entre appareils.
- Domaine personnalisé : **Settings > Pages > Custom domain**.
