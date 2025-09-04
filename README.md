# Projeto de Estudo: MySQL com Docker
Este é um projeto de estudo para aprender a usar Docker junto com MySQL. Ele contém scripts DDL para criação de tabelas e um container pronto para rodar o banco.

## Estrutura do Projeto
- **DDL/**: scripts SQL para criar tabelas e índices.
- **docker-compose.yml**: configuração do container MySQL.
- **README.md**: este arquivo.

## Como usar

1. Clone o repositório:
   git clone <link-do-repo>
   cd projeto-mysql-docker
   
2. Subir o container
docker-compose up -d

3. O banco testdb estará disponível na porta 3306.
docker-compose down -v
docker-compose up -d
