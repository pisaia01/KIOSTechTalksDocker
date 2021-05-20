Use the following commands to start-stop the containers

UP (remove any orphans left behind)

`docker-compose up -d --build --remove-orphans`

DOWN (remove any orphans and volumes left behind)

`docker-compose down --rmi local -v --remove-orphans`