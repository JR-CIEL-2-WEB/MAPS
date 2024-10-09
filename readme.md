# Nginx Web Server with Custom App

## Description

Ce dépôt contient les fichiers nécessaires pour exécuter un serveur web Nginx avec une application personnalisée située dans le dossier `app1`. 



Le serveur Nginx écoutera sur le port `8092` et servira le contenu du dossier `app1` situé dans le répertoire racine du dépôt.

## Structure du dépôt


| Dossier/File         | Description                                           |
|------------------------|-------------------------------------------------------|
| ├── app1/              | `Dossier contenant votre application web (HTML, CSS, JS, etc.)`  |
| ├── docker-compose.yml |  `Fichier docker-compose pour exécuter le conteneur Nginx` |
| └── README.md          | `Le fichier README de votre projet`                     |




## Prérequis

Avant de commencer, assurez-vous d'avoir installé les logiciels suivants sur votre machine :
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/) (si vous optez pour la méthode `docker-compose`)




## Lancer le service web
```bash
# Clonez ce dépôt en utilisant la commande suivante :
git clone https://github.com/votre-utilisateur/votre-repo.git
cd votre-repo

# Utiliser docker-compose
Cette méthode est simple si vous souhaitez gérer plusieurs conteneurs ou des configurations complexes.

Étapes :
Assurez-vous que vous êtes dans le répertoire racine du dépôt cloné, où se trouve le fichier docker-compose.yml.
Exécutez la commande suivante pour démarrer le serveur Nginx :

docker-compose up -d
```

## Développement
- coder les exercices donnés dans l'énoncé dans les différents répèrtoires appropriès.
