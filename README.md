# Salut, moi c’est Thomas 👋

**Étudiant en développement à Holberton School · Applications web, API et bases de données**

Je construis des applications en travaillant sur leurs interfaces comme sur leur logique côté serveur. J’aime comprendre ce qui se passe derrière une action simple : recalculer un budget, ouvrir une session ou réserver la dernière place d’un événement.

## Mon parcours

Mon apprentissage a commencé par le **C, les algorithmes et l’environnement Unix**, avant de s’étendre au développement web avec **Python, JavaScript et TypeScript**.

Les projets collectifs occupent une place importante dans mon parcours : développer une fonctionnalité, la relier au reste de l’application, écrire ses tests et la faire relire en pull request.

Je m’intéresse particulièrement à la conception d’API, aux règles métier, au contrôle des accès et à l’automatisation des vérifications. J’explore également les outils d’IA appliqués au développement.

## Technologies utilisées

Ces technologies ont été utilisées dans mes projets pédagogiques. Mon expérience varie selon les outils ; mes explorations sont présentées plus bas.

**Langages**

![C](https://img.shields.io/badge/C-334155?style=flat&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-334155?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-334155?style=flat&logo=javascript&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-334155?style=flat&logo=typescript&logoColor=white)

**Interfaces web**

![React](https://img.shields.io/badge/React-334155?style=flat&logo=react&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte-334155?style=flat&logo=svelte&logoColor=white)

**Backend et API**

![FastAPI](https://img.shields.io/badge/FastAPI-334155?style=flat&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-334155?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-334155?style=flat&logo=express&logoColor=white)

**Bases de données**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-334155?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-334155?style=flat&logo=mysql&logoColor=white)

**Outils et vérifications**

![Git](https://img.shields.io/badge/Git-334155?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-334155?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-334155?style=flat&logo=githubactions&logoColor=white)

Docker Compose pour les environnements locaux ; pytest, Jest et Vitest pour les tests.

## Quelques projets

### 🐷 [Cashmire](https://github.com/Tomsonne/holbertonschool-cashmire)

**Gestion des dépenses et des budgets mensuels — projet collectif.**

Une application pour suivre ses dépenses, définir des budgets par catégorie et consulter une synthèse mensuelle, dans un univers inspiré des Trois Petits Cochons.

- **Technologies :** Svelte, TypeScript, FastAPI, SQLAlchemy, PostgreSQL et Docker Compose.
- **Ma contribution :** API des budgets et calcul de leur consommation, interface de gestion des budgets, tableau de bord mensuel, tests métier et vérifications automatiques avec GitHub Actions.
- **Un point concret :** limiter chaque utilisateur à ses propres budgets et conserver les dépenses lorsqu’un budget est supprimé.

[API budgets](https://github.com/Tomsonne/holbertonschool-cashmire/pull/36) · [Tableau de bord](https://github.com/Tomsonne/holbertonschool-cashmire/pull/44) · [CI](https://github.com/Tomsonne/holbertonschool-cashmire/pull/51)

### 🤝 [Re-Tired Hearts](https://github.com/Tomsonne/holbertonschool-re-tired-hearts)

**Rencontres et activités locales pour les plus de 60 ans — projet collectif en cours.**

Une plateforme pédagogique pour découvrir des personnes partageant ses centres d’intérêt et participer à des sorties.

- **Technologies du projet :** NestJS, TypeScript, TypeORM, Vue 3, PostgreSQL et Docker Compose.
- **Ma contribution réalisée :** cycle de vie des événements, filtres de recherche, inscriptions et désinscriptions, accès aux participants et à l’adresse exacte, tests unitaires et d’intégration.
- **Un point concret :** utiliser une transaction et un verrou PostgreSQL pour gérer deux demandes simultanées sur la dernière place disponible.

[Gestion des événements](https://github.com/Tomsonne/holbertonschool-re-tired-hearts/pull/43) · [Inscriptions](https://github.com/Tomsonne/holbertonschool-re-tired-hearts/pull/45) · [Accès aux participants](https://github.com/Tomsonne/holbertonschool-re-tired-hearts/pull/48)

### 🎟️ [Nightfall](https://github.com/ClaymeCall/holbertonschool-nightfall)

**Réservation d’expériences pour un parc à thème fictif — projet collectif.**

Une application proposant un catalogue filtrable, des réservations et des espaces membre et administrateur.

- **Technologies :** React, JavaScript, Node.js, Express, MySQL et Docker Compose.
- **Ma contribution :** inscription, connexion et gestion des sessions côté backend, ainsi que les pages de connexion et d’inscription côté frontend.
- **Un point concret :** relier le parcours de connexion de l’interface aux sessions persistées côté serveur.

[Connexion](https://github.com/ClaymeCall/holbertonschool-nightfall/pull/38) · [Inscription](https://github.com/ClaymeCall/holbertonschool-nightfall/pull/51)

### 🐚 [Simple Shell](https://github.com/Tomsonne/holbertonschool-simple_shell)

**Implémentation d’un shell Unix simplifié — projet réalisé en binôme.**

Un retour aux fondations : lire une commande, rechercher son exécutable dans le `PATH`, lancer un processus et récupérer son code de sortie.

- **Technologies :** C, environnement Unix et appels système comme `fork` et `execve`.
- **Ma contribution identifiable :** implémentation de `_getenv` et intégration de cette fonction dans la recherche des commandes.
- **Ce projet m’a fait travailler :** les processus, les variables d’environnement, les pointeurs et la gestion de la mémoire.

[Voir cette contribution](https://github.com/Tomsonne/holbertonschool-simple_shell/commit/26d5163f861bc10e1e3785e4c1cd53822d7b9f97)

## 🌱 Approfondissements et explorations

**Pratique récente : NestJS et TypeORM**

Mes travaux récents sur Re-Tired Hearts portent sur les services NestJS, les transactions PostgreSQL, les permissions et les tests d’intégration.

**Exploration pédagogique : outils d’IA et MCP**

J’expérimente avec les outils accessibles aux assistants de développement, notamment un serveur MCP de démonstration exposant des opérations sur un CRM fictif.

[Parcourir mes exercices d’IA appliquée au développement](https://github.com/Tomsonne/holbertonschool-agentic_ai/tree/main/agentic_ia)

## 📫 Échanger

Une question technique ou une proposition de collaboration ?

Tu peux ouvrir une issue dans le dépôt concerné et me mentionner avec **@Tomsonne**.

[Retrouver mes dépôts sur GitHub](https://github.com/Tomsonne?tab=repositories)
