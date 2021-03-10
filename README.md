# Docker_Symfony


docker-compose up -d


// Installation Symfony
docker exec www_docker_symfony composer create-project symfony/website-skeleton project

( project => change name in vhost.conf )


cd project


// Propriété des routes : ls -l 

sudo chown -R $USER ./

// .env

DATABASE_URL=mysql://root:test@db_docker_symfony:3306/db_name?serverversion=5.7


docker exec -it www_docker_symfony bash


cd project


symfony console d:d:c
