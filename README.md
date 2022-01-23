# Projet Docker Compose
## Description du projet
Nous allons dockeriser Node.JS, React et MongoDB dans des conteneurs séparés. Ensuite, nous allons utiliser DOCKER COMPOSE pour exécuter l'application multi-conteneurs.
Enfin, à partir d'une seule commande, nous pouvons créer et démarrer tous les services de notre configuration.
## Initialisation du projet
Clonez le lien GitHub vers un dossier local sur votre ordinateur. Ouvrez le dossier à l'aide de VSCode ou de tout éditeur de texte de votre choix.

1. Dans le répertoire principal du projet, (en dehors du fontend/backend) vous trouverez un fichier nommé docker-compose.yml.
2. Executer ce fichier avec la commande suivante: 
```
docker-compose up -d
```
## Vérification de l'application 
Pour verifier que votre application est bien executée, allez sur http://localhost:3000/
