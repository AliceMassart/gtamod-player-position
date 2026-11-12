# GTA MOD : player_position

Affiche les coordonnées (x, y, z) du joueur.

## Fonctionnalités

- Affiche en bas à droite de l'écran les coordonnées du joueur en temps réel, au format `Joueur : X ... | Y ... | Z ...`
- Écrit aussi les coordonnées dans la console F8 au moment de l'activation

## Prérequis

- Serveur FiveM à jour avec accès admin

## Installation

1. Télécharge ce dépôt et renomme le dossier `gtamod-player-position` en `player_position`
2. Copie le dossier `player_position` dans `resources/`
3. Ajoute `ensure player_position` dans ton `server.cfg`
4. Redémarre le serveur

## Utilisation

Appuie sur **F4** (ou tape `player_position` dans la console F8) pour afficher ou masquer tes coordonnées (x, y, z) à l'écran.

## Structure du dossier

```
player_position/
├─ client.lua             -- script principal
├─ fxmanifest.lua
└─ README.md
```

## Crédits

Tuto et mod réalisés par :
Alice MASSART, PAD EMD 2026.
