# Api com Graphql

## Executando

```
docker-compose up -d
```
Após subir os containers no docker executar o arquivo schema.sql disponivel no modulo database em seu gerenciador de banco de dados preferido para que seja criado e populado o banco.

```
http://localhost:3000/
```

Interface para montar a query e testar a API

### [SANDBOX APOLLO GRAPHQL](https://studio.apollographql.com/sandbox)


## Teste

Será necessário executar dentro do docker 

```
docker exec ${IDCONTAINER} sh -c "npm run test"
```

Obs.: Para rodar os testes não há necessidade de executar manual o arquivo de schema.sql

