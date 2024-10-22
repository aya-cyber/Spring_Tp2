
  Introduction
Ce projet consiste en la création d’une application Java qui illustre l'intégration des technologies Hibernate et Spring pour la gestion efficace des données. L'objectif est de développer une application robuste, en appliquant les meilleures pratiques du développement logiciel, telles que la séparation des responsabilités, la gestion centralisée des transactions et l'injection des dépendances. Ce projet met en avant l'utilisation d'Hibernate pour l'accès aux données et leur persistance, tandis que Spring facilite la configuration et l'orchestration des différentes couches de l'application.

Objectifs du Projet
L’objectif principal de ce projet est de démontrer l’intégration harmonieuse entre Spring et Hibernate, permettant de développer une application en couches, avec une gestion optimisée des données et des transactions. Il s'agit de garantir la modularité et l'évolutivité de l’application tout en assurant une interaction fluide avec la base de données.

Technologies Utilisées
Java : Utilisé comme langage de programmation principal, il sert de base pour la logique métier et la structure de l'application.
Spring Framework : Permet la gestion des dépendances via l'Inversion de Contrôle (IoC) et l'injection des dépendances (DI). Il simplifie également la gestion des transactions, la sécurité et d'autres aspects complexes du développement Java.
Hibernate : Utilisé pour la persistance des données et la gestion de la couche d'accès aux données, Hibernate assure le mapping objet-relationnel (ORM) entre les objets Java et la base de données relationnelle.
MySQL : Base de données relationnelle choisie pour stocker et gérer les données. Elle est connectée à l’application via Hibernate, permettant l’exécution des opérations CRUD.
Maven : Outil de gestion de projet et de gestion des dépendances, Maven automatise le processus de compilation, de packaging et de gestion des librairies nécessaires pour exécuter le projet.

Architecture du Projet
Le projet suit une architecture en couches bien définie, avec les modules principaux suivants :

Couche DAO (Data Access Object) : Responsable de la gestion des entités et de la communication avec la base de données via Hibernate.
Couche Métier : Contient la logique métier de l’application, où les différentes opérations sont orchestrées.
Couche Présentation : Permet d’interagir avec l’utilisateur ou d’exposer des services. Cette couche peut être implémentée sous forme de services REST ou via une interface utilisateur plus traditionnelle.
Couche Utilitaire : Gère la configuration de Hibernate et Spring, notamment la configuration des transactions et la gestion des sessions.
Fonctionnalités

Gestion des entités : Le projet permet de créer, lire, mettre à jour et supprimer des entités (CRUD) dans la base de données via des opérations simplifiées grâce à l'utilisation de DAO et de services Spring.
Transactions : Gestion des transactions assurée par Spring, garantissant la cohérence et l'intégrité des données tout au long des opérations de la base de données.
Injection des Dépendances : Les objets et services sont gérés par le conteneur Spring, assurant une flexibilité et une testabilité améliorée du code.

https://github.com/user-attachments/assets/8f9a5491-85b9-4e2b-9acd-f6e6d6720814


