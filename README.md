# Time Travel Simulation — Website

Site de présentation public du projet **Time Travel Simulation**.

## Publication

Le site est publié avec GitHub Pages via GitHub Actions.

1. Dans **Settings → Pages**, choisir **GitHub Actions** comme source de publication.
2. Pousser un commit sur `main` ou lancer manuellement le workflow **Publish project website** depuis l'onglet Actions.
3. Après un déploiement réussi, le site sera disponible à l'adresse :
   https://cyrilletixier.github.io/time-travel-simulation-website/

## Formulaire d'intérêt

Le formulaire e-mail est présent dans `index.html`, mais la collecte n'est pas activée.
Pour l'activer, créer un formulaire chez un prestataire tel que Formspree, puis remplacer la constante `FORM_ENDPOINT` dans le script par l'URL fournie par ce service.

GitHub Pages héberge uniquement les fichiers statiques : il ne stocke pas les adresses e-mail.

## Dépôt du jeu

Le code du jeu reste dans le dépôt privé :
https://github.com/cyrilletixier/time-travel-simulation
