João dos Santos Cardoso de Jesus
RM560400

-------------------------------

Execute os seguintes comandos:

cd example-voting-app

docker compose up -d --build

docker compose ps

docker ps

docker compose logs

docker network ls

docker volume ls

-------------------------------

Acesse as páginas:

localhost:5000

localhost:5001

-------------------------------

Entrar no Terminal do Postgres:

docker exec -it postgres psql -U postgres

\c postgres

Realize um SELECT na tabela votes:

select * from votes;

-------------------------------

Entrar no Terminal do Redis:

docker exec -it redis redis-cli

Execute os comandos:

select 0

KEYS *