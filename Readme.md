# Kafka server

docker compose -f docker-compose.yml up
docker compose -f docker-compose.yml start
docker compose -f docker-compose.yml stop

## Following command deletes the containers, so please export json data before hand

docker compose -f docker-compose.yml down
