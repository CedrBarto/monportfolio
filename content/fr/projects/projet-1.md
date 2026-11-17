---
title: "Customer Hub - Nidecker Group"
slug: "customer-hub-nidecker"
date: 2026-11-17
period: "7 août 2026"
description: "Travail de Bachelor chez Nidecker Group. Un espace client centralisé pour les marques du groupe, pensé avec les contraintes de Shopify plutôt que contre elles."
intro: "Réalisé au sein de Nidecker Group à Rolle, mon travail de Bachelor portait au départ sur la personnalisation de l'espace client des sites du groupe. Très vite, une contrainte a tout changé. Avec la migration vers Shopify et la mise à jour « New Customer Accounts », il n'était presque plus possible de modifier l'espace client côté développement. J'ai donc mené un audit de l'écosystème Shopify pour trouver une solution qui fonctionne dans ces limites, simple à prendre en main pour les équipes et réellement utile aux clients. Elle a pris la forme d'un Customer Hub, mis en place et testé sur l'environnement de test de l'entreprise."
featured: true
image: "images/projets/customer-hub/cover.webp"
imageAlt: "Le Customer Hub ouvert sur le site Emerica, avec les accès au statut pro, à la FAQ, au suivi de commande et aux retours"
thumb: "images/projets/customer-hub/miniature-v2.webp"
imagePosition: "50% 40%"
imageCaption: "Le Customer Hub sur le site Emerica, une des marques du groupe. Il s'ouvre en volet latéral depuis n'importe quelle page."
badges:
  - "Travail de Bachelor"
  - "HEIG-VD"
  - "Nidecker Group"
  - "Shopify"
  - "Klaviyo"
  - "Claude"
---

## Le contexte

Fondée en 1887 à Rolle, Nidecker Group est la plus ancienne entreprise de sports de planche au monde. Ce groupe familial réunit plusieurs marques de snowboard et de skate, distribuées dans plus de soixante pays. Comme il ne possède aucun magasin en propre, ses sites web sont le principal point de contact direct avec ses clients. L'espace client y joue un rôle clé, car c'est lui qui prolonge la relation après l'achat.

## Le défi

Le mandat de départ était ambitieux. Il s'agissait de créer un profil unifié pour les différentes marques du groupe, avec des espaces adaptés à chaque type de compte, une vue claire des avantages, de l'historique d'achat et des programmes, le tout dans une interface fidèle à l'identité des marques.

La migration vers Shopify a cependant fortement réduit la marge de manœuvre. La question est donc devenue la suivante. Comment répondre à ces besoins sans sortir des limites de la plateforme, sans nouvelle technologie à maintenir, et avec un vrai bénéfice pour les utilisateurs ?

## Une démarche inversée

Un projet UX part habituellement des utilisateurs pour aboutir à l'interface. Ici, l'écosystème était déjà en place techniquement et laissait peu de liberté, ce qui rendait des tests utilisateurs en amont peu pertinents. J'ai donc choisi d'inverser l'ordre des étapes.

1. **Faire l'état des lieux** de ce qui manque dans l'espace client actuel.
2. **Analyser la concurrence** pour repérer ce qui se fait de mieux ailleurs.
3. **Trier les tickets du service client** avec l'aide d'un connecteur Claude, afin de faire ressortir les questions et les problèmes les plus fréquents.
4. **Évaluer les applications Shopify** capables de combler ces manques.
5. **Valider le choix** avec les principaux profils de clients, à travers des personas, des parcours utilisateurs et des task flows.

J'ai mené ce projet seul, avec une grande liberté dans la démarche. J'ai organisé mon temps en autonomie, en commençant par une pré-étude et un planning des tâches, tout en m'appuyant sur les équipes de l'entreprise et sur mon mandant.

## Le Customer Hub comme solution

Plutôt que de développer une solution sur mesure, difficile à maintenir dans l'écosystème Shopify, j'ai retenu le Customer Hub de Klaviyo. Il s'agit d'un volet latéral accessible depuis n'importe quelle page, sans quitter le site. Il réunit les commandes, les recommandations, une FAQ ciblée et un accès direct à l'assistance. Il ajoute aussi les favoris, une fonctionnalité qui manquait jusque-là aux sites du groupe.

Associé à d'autres applications, comme Rich Returns pour les retours en libre-service ou Alliance Pro pour le programme des clients professionnels, il couvre les besoins identifiés pendant l'audit tout en restant simple à configurer pour les équipes.

## Valider la solution avec les principaux utilisateurs

### Trois personas

Pour vérifier que la solution répond aux vrais besoins, j'ai défini trois profils représentatifs des principaux clients du groupe. Lucas est un snowboardeur occasionnel qui veut suivre sa commande et savoir vers qui se tourner en cas de défaut. Sophie est monitrice et cliente pro, elle souhaite voir son statut et ses points. Théo achète régulièrement des chaussures de skate et veut pouvoir retourner une paire en quelques clics.

![Les trois personas du projet, avec leur profil, leur comportement et leurs attentes](images/projets/customer-hub/personas.webp "Les personas présentent le profil, le comportement et les attentes de chaque client envers l'espace client.")

### Des parcours utilisateurs

Pour chaque persona, un parcours suit une situation concrète, étape par étape, avec ce que la personne pense et ressent. Il montre à quel moment le Customer Hub intervient et où les frictions disparaissent.

![Les parcours utilisateurs de Lucas, Sophie et Théo](images/projets/customer-hub/user-flow.webp "Chaque parcours suit l'émotion du client, du premier contact jusqu'à la résolution de son besoin.")

### Des task flows

Les task flows détaillent ensuite le chemin exact dans le Customer Hub, de la connexion jusqu'à l'action. Ils confirment que chaque besoin se règle en quelques clics seulement.

![Les task flows de Lucas, Sophie et Théo dans le Customer Hub](images/projets/customer-hub/task-flow.webp "Suivre une commande, consulter son statut pro ou retourner une paire, chaque tâche tient en quatre ou cinq étapes.")

## Le résultat

La solution a été configurée et testée sur l'environnement de test de l'entreprise. J'ai documenté chacun de mes choix dans un rapport, puis formulé des recommandations à court et à long terme pour faire évoluer l'espace client.

Nidecker Group dispose ainsi d'un espace client à la hauteur de ses marques. Il réduit les frictions du parcours d'achat et allège la charge du service client, en rendant l'utilisateur plus autonome.
