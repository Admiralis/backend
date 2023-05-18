# BACKEND

Répository du backend de l'application de gestion de formation.
Centralise tous les répositories du backend.

## Dépendances

- Spring Boot
- Spring Data MongoDB
- Spring Web
- Lombak
- Docker

## Installation

- Cloner le projet avec la commande `git clone --recurse`
- Démarrez la base de données MongoDB avec Docker `docker-compose up -d`
- Lancer le projet avec la commande `mvn spring-boot:run` ou depuis votre IDE.

## Les micro services

Voir la documentation de chaque MS dans le MS associé.
Chaque MS expose sur un port spécifique et a son propre swagger.

- [MS-COURSE](backend/ms-course/README.md) : 8080
- [MS-COMPUTER](backend/ms-computer/README.md) : 8081
- [MS-LOAN](backend/ms-loan/README.md) : 8082

Pour fonctionner correctement avec le front, il vous faudra utiliser le reverse proxy (voir ci-dessous).

## Dev Stack

Ce repository permet de lancer le reverse proxy en mode dev : [dev_stack](https://github.com/Admiralis/dev_stack).

## Production

Pour lancer la stack complète, rendez-vous sur ce repo : [admiralis](https://github.com/Admiralis/admiralis).