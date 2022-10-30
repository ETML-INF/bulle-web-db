# Guidelines

Version : ce document est pour l'instant dans un état de brouillon. 
Tout ce qui est écrit ci-dessous doit être validé par l'ensemble des enseignants de la bulle web DB.

## But de ce document :
- Définir la collaboration au sein de la bulle
- Permettre aux autres bulles de connaître les outils et les technologies utilisés par la bulle web.
- Définir les interactions avec les autres bulles
exemple : On veut faire tourner une application web dans un conteneur => Utiliser les mêmes outils et bonnes pratiques que la bulle dev-ops

## Règles de la collaboration entre enseignants de la bulle

Les règles ci-dessous doivent être adoptées et appliquées par tous les enseignants de la bulle.

- le partage par défaut de toutes les productions (documents, cours, exercices, tests, code, etc) réalisées par les différents enseignants de la bulle
- les documents sont déposés en priorité dans sharepoint (Sauf pour les documents confidentiels) 
- pour chaque document déposé dans sharepoint, un lien est présent sur K:\
- pour chaque module ICT contenant des sources (code source, sql, json, etc) un dépôt github privée est créé contenant le code des exercices, des tests formatifs et sommatifs, des exemples, etc

## Langages et Frameworks

Avec les nouveaux modules web le javascript devient le langage dominant.
- front end : js + react
- back end : js + nodejs et express

## L'écosystème js 

- npm
- webpack (le strict minimum) 
- Style Guide : https://airbnb.io/javascript/
- linter
- debugger
- tests automatiques (unitaires, fonctionnels) avec Jest ? Cypress ? autre ?
- logging
- CI : github actions et/ou pipeline gitlab

## Outils

outils pour le dev web : 
- vs code 
- extensions vs code : 
    - ESLint : Permet d'obtenir des informations en cas d'erreurs
    - Prettier : Permet de formater le code automatiquement lors de la sauvegarde de la page
    - Auto Import : Permet de gérer les imports js
    - Material Icon Theme

outils pour MySQL : à définir

outils pour mongoDB : à définir

## Tester une nouvelle technologie

Pour tester une technologie, un language (PHP, JS, etc), un framework (Laravel, React, etc), une DB (MySQL, MongoDB) une version de l'application des surnoms des enseignants est réalisée.
Ainsi, nous ne nous préoccuperons pas du QUOI (qu'est ce qu'il faut faire?) mais bien du COMMENT (comment le réaliser à l'aide de la techno x ou y).
Il sera ensuite plus simple de comparer telle ou telle technologie en comparant le code source de la même application.

Liste non exhaustive des technologies à tester :

- [ ] version php non MVC + MySQL
- [ ] version php MVC + MySQL
- [ ] version laravel + MySQL
- [ ] version front React + API REST + backend php + MySQL
- [ ] version front React + API REST + backend laravel + MySQL
- [ ] version front React + API REST + backend nodejs et express + MySQL
- [ ] version front React + API REST + backend nodejs et express + MongoDB
