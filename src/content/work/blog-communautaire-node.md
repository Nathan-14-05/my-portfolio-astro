---
# TITRE
title: 'Développement d’un Blog Communautaire (Full-Stack Node.js)'

# DATE DE PUBLICATION (Date de réalisation pendant la 2e année de BTS SIO)
publishDate: 2024-05-15 

# IMAGE DE LA CARTE
img: '/assets/image-blog-node.png' 

# TEXTE ALTERNATIF DE L'IMAGE
imgAlt: "Interface d'une application web de blog communautaire, affichant des articles et une zone de connexion/inscription."

# DESCRIPTION (Sera affichée sur la carte d'aperçu)
description: |
  Conception et réalisation d'une application web de type blog dans le cadre du BTS SIO SLAM. Le projet met en œuvre une architecture MVC complète, le développement Full-Stack avec Node.js/Express, et la gestion des sessions d'authentification et du CRUD des articles.
tags:
  - Node.js
  - Express
  - Full-Stack
  - MVC
  - SQL
---

### Objectifs Atteints et Compétences Clés

Ce projet a permis de valider des compétences fondamentales en développement d'applications métiers, notamment :

* **Architecture Logicielle :** Implémentation réussie de l'architecture **MVC (Modèle-Vue-Contrôleur)** pour garantir la séparation des préoccupations, la maintenabilité et l'évolutivité du code.
* **Développement Back-end (Node.js/Express) :** Maîtrise de l'environnement d'exécution Node.js et du framework Express pour la gestion des **routes**, des requêtes HTTP et de la **logique applicative** côté serveur.
* **Gestion des Données (CRUD) :** Mise en œuvre des opérations **CRUD (Création, Lecture, Modification, Suppression)** pour la gestion des articles, en interagissant avec une base de données **SQLite**.
* **Rendu Serveur (SSR) :** Utilisation du moteur de template **Handlebars (HBS)** pour le rendu dynamique des vues, offrant une première approche du rendu d'applications.

### Stack Technique Détaillée

| Composant | Technologie | Rôle dans le Projet |
| :--- | :--- | :--- |
| **Back-end/Serveur** | Node.js | Environnement d'exécution pour la logique du blog. |
| **Framework Web** | Express | Gestion des API et des routes MVC. |
| **Moteur de Template** | Handlebars (HBS) | Rendu dynamique des pages côté serveur. |
| **Base de Données** | SQLite | Persistance des données (utilisateurs, articles). |

### Fonctionnalités Implémentées

#### 1. Gestion des Utilisateurs et Authentification
* **Sécurité :** Création sécurisée de comptes (Inscription).
* **Sessions :** Système d'authentification basé sur les sessions (Connexion/Déconnexion).
* **Profils :** Vue permettant l'accès aux informations personnelles et aux articles publiés par l'utilisateur.

#### 2. Gestion des Articles (CRUD)
* **Publication :** Formulaires sécurisés pour l'ajout de nouveaux articles.
* **Édition/Suppression :** Contrôle des droits permettant uniquement à l'auteur de modifier ou de retirer ses propres publications.
* **Affichage :** Liste des articles et vue détaillée individuelle.

### Apports Personnels et Perspectives

Ce projet a été fondamental pour ma compréhension du développement **Full-Stack**. Il a transformé mes connaissances théoriques en une application fonctionnelle et sécurisée.

* **Compétence en Développement (SLAM) :** J'ai renforcé ma capacité à concevoir une application de A à Z en respectant les bonnes pratiques de l'architecture MVC.
* **Autonomie :** J'ai géré l'ensemble du cycle de vie du développement, depuis la conception de la base de données jusqu'au rendu final en Front-End.
* **Évolution :** L'utilisation de Node.js ouvre la voie à une future refonte du Front-End vers une architecture découplée (API REST + Vue.js/React), ce qui était l'une des perspectives du projet.

En résumé, ce projet de BTS SIO SLAM démontre ma maîtrise des technologies Full-Stack modernes et ma capacité à livrer une application web complète et bien structurée.