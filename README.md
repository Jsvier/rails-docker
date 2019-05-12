# README

*(purga)
docker system prune
docker system prune --volumes

docker-compose run --rm web rails new . --force --database=postgresql

*(esto se hace cada vez que haces cambios en el Gemfile, para que instale/actualice las dependencias de gemas
docker-compose build

*(ejecuta el contenedor)
docker-compose up

*(ejecuta el contenedor con comandos de rails)
docker-compose run --rm web rails db:create
docker-compose up

* ...
