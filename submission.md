Etapes pour le déploiement des images : 

docker compose -f docker-compose.build.yml build

Publication de l'image vote vers le registre privé. Repeter cette étape pour toutes les images.

docker tag projet_docker-vote:latest localhost:5000/vote-build:latest

docker compose up -d
Tu met nos deux noms tout en bas et c'est bon
moi je dépose le lien git et le rapport sur moodle
