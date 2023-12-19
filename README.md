# CRUD simples
Este repositório contém um projeto CRUD simples construído usando Java Spring. O objetivo deste repositório é praticar e compartilhar como você pode construir todos os métodos CRUD usando Java Spring.

## Índice

- [Instalação](#instalação)
- [Configuração](#configuração)
- [Endpoints da API](#endpoints-da-api)
- [Banco de dados](#banco-de-dados)

## Instalação

1. Clone o repositório:

```bash
$ git clone https://github.com/wladsonramos/crud-java.git
```

2. Instale dependências com Maven

## Uso

1. Inicie a aplicação com Maven
2. A API estará acessível em http://localhost:8080


## Endpoints da API
A API fornece os seguintes endpoints:

```markdown
GET /product – Retorna uma lista de todos os dados.

POST /product - Cadastre um novo dado.

PUT /product - Altera dados.

DELETE /product/{id} - Inativa dados.
```

## Banco de dados
O projeto usa PostgresSQL como banco de dados. As migrações de banco de dados necessárias são gerenciadas usando Flyway.

Para instalar o PostgresSQL localmente você pode [clicar aqui](https://www.postgresql.org/download/).
