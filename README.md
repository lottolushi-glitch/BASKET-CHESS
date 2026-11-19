# Basket Chess 🏀♟️

Jeu mobile dans lequel le basket rencontre les échecs.

## Jouer en ligne avec GitHub Pages

1. Crée un nouveau dépôt GitHub nommé `basket-chess`.
2. Envoie les **5 fichiers** de ce dossier à la racine du dépôt :
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon.svg`
   - `README.md`
3. Dans le dépôt, ouvre **Settings → Pages**.
4. Dans **Build and deployment**, choisis **Deploy from a branch**.
5. Sélectionne la branche `main` et le dossier `/(root)`, puis clique sur **Save**.
6. Attends quelques minutes. GitHub affichera l'adresse de ton jeu dans la section Pages.

Ton jeu sera accessible à une adresse du type :
`https://TON-PSEUDO.github.io/basket-chess/`

## Installation sur téléphone

Ouvre le lien GitHub Pages dans Chrome ou un navigateur compatible, puis utilise
le menu du navigateur et choisis **Ajouter à l'écran d'accueil** / **Installer**.

Le service worker met en cache les fichiers principaux pour permettre le lancement
hors ligne après le premier chargement réussi.

## Notes

- Le fichier principal du jeu est `index.html`.
- Aucune bibliothèque externe n'est nécessaire.
- Les préférences et la progression du jeu sont conservées localement dans le navigateur.
