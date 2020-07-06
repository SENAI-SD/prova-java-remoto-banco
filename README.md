# Prova Java  IST - Banco

O banco de dados deve ser iniciado via docker com o comando (na pasta raiz desse projeto, onde encontra-se o arquivo *docker-compose.yaml*):

`docker-compose up -d`

Verificar possíveis conflitos de porta, caso já haja alguma instancia usando a porta 5432 do *localhost*.

Para parar o servidor usar o comando:

`docker-compose down`

## Dados de conexão

A imagem docker contem à seguinte configuração do banco:

- host: localhost (ou 127.0.0.1)
- port: 5432
- database: ist
- user: ist
- pass: ist

#### String de conexão jdbc:

jdbc:postgresql://localhost:5432/ist

## Docker

Note que para a iniciação do banco de dados, o *Docker* deve estar instalado no computador.

Verificar as instruções de instalação no pŕoprio site do *Docker* em https://docs.docker.com/get-docker/