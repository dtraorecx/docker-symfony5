## Objectif ##
Avec ça vous avez une stack vous permettant de demarrer rapidement un projet basé sur du **Symfony 5 minimum**

Il vous suffit de cloner ce dépot.

## lancer le container

`docker-compose up -d`

## Entrer dans le container

`docker exec -it www_my_app bash`

Une fois dans le container installer votre projet symfony avec la version que vous voulez.

Exemple de projet  (Symfony 5, Syllius, Ibexa)

## Tester votre installation

Editer le fichier vhosts.conf dans le dossier **php/vhosts**

pour faire pointer votre server vers votre dossier d'installation.

Puis restart docker

`docker-compose restart`

et accéder à l'url http://localhost:8082