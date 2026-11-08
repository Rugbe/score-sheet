# Feuilles de scores

Feuilles de scores pour le 10 000, les dominos, le rami et le backgammon.
Une seule page HTML, sans serveur : les parties sont enregistrées sur le téléphone
(localStorage) et peuvent être envoyées vers Obsidian en Markdown.

## Installation sur Android

1. Ouvrir l’adresse GitHub Pages du dépôt dans Chrome : https://rugbe.github.io/score-sheet/
2. Menu ⋮ puis « Ajouter à l’écran d’accueil » (ou « Installer l’application »).
3. L’application fonctionne ensuite hors connexion.

## Mises à jour

Modifier `index.html`, puis `git commit` et `git push`. Le téléphone récupère la nouvelle
version à la prochaine ouverture avec une connexion. Pour forcer le vidage du cache,
changer le numéro de version de `CACHE` dans `sw.js`.
