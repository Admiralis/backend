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

- [MS-COMPUTER](backend/ms-computer/README.md) : 8080
- [MS-COURSE](backend/ms-course/README.md) : 8081
- [MS-LOAN](backend/ms-loan/README.md) : 8082