## Create Laravel project

mkdir src
docker compose run --rm --user laravel composer create-project laravel/laravel .

## Run Docker Compose for production mode

docker compose -f docker-compose.yml -f docker-compose.prod.yml up --build
