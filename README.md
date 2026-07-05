# 🕹️ Mon Arcade Launcher

Bienvenue sur mon launcher d'arcade personnel ! Ce projet regroupe tous les jeux que j'ai codés au même endroit sur une seule et unique page, entièrement compatible avec les PC et les smartphones (iOS / Android).

Le site est hébergé en ligne grâce à **Render** avec un déploiement automatique à chaque mise à jour sur ce dépôt.

---

## 🚀 Les Jeux Inclus

Actuellement, le launcher contient 5 jeux fonctionnels :
1. **🕹️ Pac-Man Hardcore Edition** - Une version revisitée et plus difficile du classique d'arcade.
2. **❌ Tic-Tac-Toe** - Le jeu du morpion indémodable.
3. **🟩 Geo Platformer** - Un jeu de plateforme inspiré du style graphique géométrique avec des fonctionnalités de boost de saut et des ennemis à éliminer.
4. **🚀 Flappy Remastered** - Le célèbre jeu d'esquive avec une mécanique moderne de *Dash* (propulsion rapide).
5. **🎯 SlingBox Archer** - Un jeu d'adresse physique où il faut viser et détruire des caisses en bois avec un système de trajectoire.

---

## 🛠️ Comment ajouter un nouveau jeu ?

Ce projet a été conçu pour être **100% modulable**. Pour ajouter une nouvelle création :

1. Dépose les fichiers de ton nouveau jeu dans le dossier `jeux/` (ex: `jeux/mon-nouveau-jeu.html` ou un sous-dossier avec son propre `index.html`).
2. Ouvre le fichier `index.html` à la racine.
3. Trouve le tableau `mesJeux` dans le script et ajoute simplement une ligne comme ceci :

```javascript
const mesJeux = [
    ...
    { id: "nouveau", nom: "🔥 Mon Nouveau Jeu", url: "jeux/mon-nouveau-jeu.html" }
];
