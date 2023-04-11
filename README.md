# PimpoShop API

## Description

PimpoShop est une API de gestion de boutiques.
L'url du server de l'API est http://localhost:3000

## Made by
| Rôle       | Nom                | Email                            | 
|------------|--------------------|----------------------------------|
| Dev        | **Dolmazon Dylan** | dylan.dolmazon@etu.univ-lyon1.fr |  
| Dev        | **Girand Adrien**  | adrien.girand@etu.univ-lyon1.fr  | 

## Outils nécessaire

- MongoDB compass
- Node.js
- Yarn

## Lancement du projet

- ``git clone https://github.com/dylan-dolmazon/micro_service.git ``
- ``cd micro_service``
- ``yarn``
- Vous devez modifier certaines données dans le fichier de configuration .env
  - ``DB_ADDRESS`` par votre url de base de donnée MongoDB
  - ``MAIL_FROM`` par votre adresse d'envoie GMAIL
  - ``MAIL_PASSWORD`` par votre moit de passe d'application GMAIL
- ``node app.js``