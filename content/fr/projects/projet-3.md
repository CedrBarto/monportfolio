---
title: "TamaGo - Jeu web mobile"
slug: "tamago"
date: 2026-06-01
period: "Octobre 2025 à janvier 2026"
description: "Projet de développement web fullstack. TamaGo, un jeu inspiré du Tamagotchi, pensé pour le mobile, avec un compagnon à nourrir, à laver et à divertir grâce à des mini-jeux."
intro: "Projet de développement web fullstack. TamaGo est un jeu inspiré du Tamagotchi qui en garde les bases, nourrir, laver et divertir son compagnon, et y ajoute des fonctionnalités plus immersives pensées pour le mobile, comme secouer son téléphone pour faire éclore l'œuf ou jouer à des mini-jeux."
featured: true
image: "images/projets/tamago/cover.webp"
imageAlt: "Trois iPhone avec les écrans de TamaGo, l'œuf à faire éclore, le Tamagotchi Yoshi dans son jardin et le mini-jeu Catch Game"
thumb: "images/projets/tamago/miniature.webp"
thumbLight: true
imagePosition: "50% 50%"
---

## Contexte

Le projet consistait à concevoir et développer une application complète, du serveur à l'interface. Le choix s'est porté sur un jeu inspiré du Tamagotchi, réinterprété pour le téléphone.

TamaGo est une application web, développée et jouée dans le navigateur du téléphone, sans application mobile dédiée à installer.

## Le jeu

Le joueur crée son compte, se connecte et adopte un compagnon. Quatre jauges résument son état et baissent avec le temps.

- **Hunger**, à remplir en le nourrissant.
- **Hygiene**, à remonter en le lavant et en nettoyant ses besoins.
- **Fun**, qui augmente en jouant aux mini-jeux.
- **Energy**, qui diminue au fil des activités.

## Technique

Le projet est développé en JavaScript, de bout en bout.

1. **Backend** avec Node.js et Express.js, une API REST, des WebSockets pour le temps réel, une authentification JWT et une base de données MongoDB.
2. **Frontend** avec Vue.js en Single Page Application, des stores Pinia pour l'état du jeu et Socket.io pour recevoir les mises à jour en direct.
3. **Mobile first**, chaque écran étant d'abord conçu pour le téléphone, le support pour lequel le jeu est pensé.

## L'application

### Faire éclore son Tamagotchi

La partie commence par un œuf. Le joueur secoue son téléphone cinq fois pour le faire éclore, puis choisit le nom de son compagnon.

![Éclosion et choix du nom](images/projets/tamago/naissance.webp)

### Prendre soin de lui

L'écran principal montre le Tamagotchi dans son jardin, avec ses jauges en haut. Elles passent du vert au jaune quand il a faim, s'ennuie ou laisse des besoins à nettoyer.

![Jauges pleines puis à surveiller](images/projets/tamago/soins.webp)

### Jouer aux mini-jeux

L'arcade réunit trois mini-jeux, Memory, Catch Game et Simon Says. Chaque partie réussie fait remonter la jauge Fun.

![Arcade, Catch Game et Memory](images/projets/tamago/mini-jeux.webp)

### Profil et compte

Le profil présente le compagnon, permet de modifier son nom et affiche ses statistiques. À la connexion, le joueur reprend sa partie ou en commence une nouvelle.

![Profil et accueil du joueur](images/projets/tamago/profil.webp)

## Résultat

Le projet aboutit à un jeu web fonctionnel et jouable sur le navigateur d'un téléphone, avec comptes utilisateurs, sauvegarde de la partie, jauges mises à jour en temps réel et trois mini-jeux.
