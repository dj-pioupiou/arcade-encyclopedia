# Arcade Encyclopedia — Phase 2 Alpha PC

Version Alpha PC construite à partir du prototype fonctionnel validé.

## Lancement Windows
Double-cliquer sur :
`windows\LANCER_ARCADE_ENCYCLOPEDIA.bat`

Il est aussi possible d'ouvrir directement `index.html`.

## Contenu
- Fiches intégrées : Street Fighter II, Pac-Man, Metal Slug
- Recherche instantanée
- Collection, favoris et wishlist avec sauvegarde locale
- Ajout manuel de jeux avec sauvegarde locale
- Images de bornes et flyers provenant de sources Internet réelles
- Arcade Radio : Kohina (flux AAC sécurisé + lecteur officiel de secours)
- Structure séparée HTML / CSS / JavaScript
- `data/games.json` pour préparer l'extension du catalogue

## Connexion Internet
Les médias et Arcade Radio nécessitent Internet. Les données personnelles de collection et les jeux ajoutés sont stockés localement par le navigateur.

## Windows .EXE
Cette Alpha PC utilise un lanceur Windows `.bat` sans installation. Le véritable packaging `.exe` (Electron/Tauri ou équivalent) est prévu pour une étape ultérieure afin de ne pas alourdir cette Alpha.

## Arborescence
- index.html
- assets/css/app.css
- assets/js/app.js
- data/games.json
- windows/LANCER_ARCADE_ENCYCLOPEDIA.bat
- windows/LANCER_ARCADE_ENCYCLOPEDIA.ps1
