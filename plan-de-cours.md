# Plan de cours

## INTRODUCTION AUX CONTENEURS
* Présentation du concept de conteneur Linux
* Cas d’utilisation des conteneurs Linux
* Les différences entre conteneurs et machines virtuelles
* Présentation de Docker et de son architecture

## CRÉER SES PREMIERS CONTENEURS DOCKER
* Installation de Docker
* Le cycle de vie d’un conteneur
* Lancer un conteneur avec docker run (en mode interactif, en mode detaché…)
* Intéragir avec un conteneur depuis le host (exec, inspect, logs…)

## LES IMAGES DOCKER
* Qu’est-ce qu’une image Docker
* Créer une image à partir d’un conteneur
* Créer une image à partir d’un Dockerfile
* Stocker et récuperer des images depuis le Docker Hub
* Mettre en place un registry privé et y stocker ses images

## LE RÉSEAU AVEC DOCKER
* Comprendre la stack réseau de Docker
* Utiliser les links Docker
* Créer des networks Docker et connaître les drivers réseaux

## LA PERSISTANCE DES DONNÉES AVEC DOCKER
* Créer et persister des volumes Docker (host/conteneur, inter-conteneurs)
* Bonnes pratiques de persistance de données avec Docker

## L’ÉCOSYSTÈME DOCKER
* Créer des instances Docker avec Docker Machine
* Créer sa stack logicielle avec Docker Compose
* Orchestrer le déploiement de conteneurs sur plusieurs machines avec Docker Swarm

## CONCEPTS AVANCÉS
* Mettre en place une architecture microservices avec Docker (Service Discovery, automatisation…)
* Sécuriser son infrastructure Docker (TLS, App Armor, SELinux…)
* Docker in Docker
