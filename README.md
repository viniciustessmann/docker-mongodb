# docker-mongodb
Esse repositório contém a infraestrutura para a criação de um banco de dados em MongoDB.

## instalação
Basta executar o seguinte comando:
`docker-compose up -d`

Para acessar o container, execute o seguinte comando:
`docker exec -ti mongodb bash`

Para criar uma database, execute o seguinte comando:
`use NOME_DO_BANCO_DE_DADOS`

Para criar uma collection, execute o seguinte comando:
`db.createCollection("NOME_DA_COLLECTION")`

A conexao do mongo fica em:
`mongodb://root:root@127.0.17/NOME_DO_BANCO_DE_DADOS`