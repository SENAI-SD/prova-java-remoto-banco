# Prova Java  IST - Banco

Na pasta raiz desse projeto, onde encontra-se o arquivo *docker-compose.yaml*, o banco de dados deve ser iniciado via docker, utilizando o cmd/terminal, com o comando:

`docker-compose up -d`

Verificar possíveis conflitos de porta, caso já haja alguma instancia usando a porta 5432 do *localhost*.

Para parar o servidor, utilizar o comando:

`docker-compose down`

## Dados de conexão

A imagem docker contem à seguinte configuração:

- **host**: localhost (ou 127.0.0.1)
- **port**: 5432
- **database**: ist
- **user**: ist
- **pass**: ist

#### String de conexão jdbc:

jdbc:postgresql://localhost:5432/ist

## Docker

Note que para a iniciação do banco de dados, o *Docker* deve estar instalado no computador.

Verificar as instruções de instalação no próprio site do *Docker* em https://docs.docker.com/get-docker/