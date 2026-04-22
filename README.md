# Redis Practice

## Start
docker compose up -d

## Open CLI
docker exec -it redis-practice redis-cli

## Run practice
docker exec -i redis-practice redis-cli < practice.txt

## Stop
docker compose down