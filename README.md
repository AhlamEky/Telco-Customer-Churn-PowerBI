# Analyse de l’attrition des clients — Power BI

## Présentation du projet

Ce projet porte sur l’analyse de l’attrition des clients (*Customer Churn*) dans le secteur des télécommunications à l’aide de Power BI.

L’objectif est de comprendre le comportement des clients, d’identifier les facteurs associés à leur départ et de fournir des analyses interactives permettant d’appuyer l’étude de la fidélisation client.

Ce projet est basé sur le jeu de données **IBM Telco Customer Churn**.

## Objectifs métier

- Analyser le taux global d’attrition des clients.
- Comprendre les tendances de l’attrition selon les différents types de contrats.
- Étudier la relation entre l’ancienneté des clients et leur attrition.
- Analyser l’attrition selon les modes de paiement et les services souscrits.
- Identifier les segments de clients présentant des taux d’attrition plus élevés.

## Jeu de données

Le jeu de données contient des informations sur **7 043 clients**, notamment :

- Les caractéristiques démographiques des clients.
- Les informations relatives aux contrats.
- Les modes de paiement.
- Les services Internet et les services complémentaires.
- Les frais mensuels et les frais totaux.
- Le statut d’attrition des clients.

## Outils et technologies

- Power BI Desktop
- Power Query
- DAX
- Visualisation des données
- Nettoyage et transformation des données

## Préparation des données

La préparation des données a été réalisée à l’aide de Power Query.

Les principales étapes comprenaient :

- Le nettoyage et la transformation du jeu de données.
- Le traitement des valeurs manquantes dans la colonne `TotalCharges`.
- La conversion des colonnes numériques vers les types de données appropriés.
- La vérification de l’unicité des identifiants clients.
- La préparation des données pour l’analyse.

## Pages du tableau de bord

### 1. Vue d’ensemble des clients

Cette page présente une vue globale de la clientèle à travers des indicateurs clés de performance (KPI) et des visualisations.

Principaux indicateurs :

- Nombre total de clients
- Nombre de clients ayant quitté l’entreprise
- Nombre de clients fidèles
- Taux d’attrition des clients

Cette page analyse également l’attrition selon le type de contrat et le mode de paiement.

### 2. Analyse du comportement des clients

Cette page explore le comportement des clients et les tendances de l’attrition en fonction de :

- L’ancienneté des clients
- Les frais mensuels
- Le statut de senior (Senior Citizen)

### 3. Analyse des services

Cette page analyse l’attrition en fonction des services utilisés par les clients, notamment :

- Le type de service Internet
- La sécurité en ligne
- L’assistance technique
- La télévision en streaming
- Les films en streaming

## Principaux résultats

- Le taux global d’attrition des clients est de **26,54 %**.
- Les clients ayant un contrat mensuel présentent un taux d’attrition plus élevé que ceux ayant des contrats à plus long terme.
- Les clients utilisant une connexion Internet par fibre optique présentent un taux d’attrition plus élevé que ceux utilisant le DSL.
- Les clients ne disposant pas de services de sécurité en ligne ou d’assistance technique présentent des taux d’attrition plus élevés.
- Les clients ayant quitté l’entreprise ont des frais mensuels moyens plus élevés que les clients restés fidèles.

## Fonctionnalités interactives

Le tableau de bord comprend des filtres interactifs (segments) et une navigation entre les pages permettant d’explorer l’attrition des clients selon différents segments de clientèle.

## Fichiers du projet

- Tableau de bord Power BI (`.pbix`)
- Captures d’écran du tableau de bord
- Documentation README

## Conclusion

Ce projet met en évidence l’utilisation de Power BI pour la préparation des données, l’analyse métier, la création de mesures DAX et le développement de tableaux de bord interactifs.

Il permet de mieux comprendre les tendances de l’attrition des clients et de mettre en évidence les segments de clientèle nécessitant une analyse plus approfondie afin d’orienter les stratégies de fidélisation.
