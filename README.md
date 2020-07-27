## Docker

Ambiente de desenvolvimento NodeJS com Docker e Docker Compose

```bash

Javascript (EcmaScript)
NodeJS
Docker
Docker Compose (Orquestrador para gerenciar os Containers)

```

Criando maquina/imagem no docker
Comando: `docker build -t silvano/dockernode .`

Rodando a aplicação
Comando: `docker run -p 3000:3000 -d silvano/dockernode`

Para rodar a aplicação com o docker-compose
Comando: `docker-compose up`