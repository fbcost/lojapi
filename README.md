# Baozi Store API

API REST desenvolvida utilizando Java e Spring Boot para gerenciamento de clientes, produtos e pedidos da Baozi Store.

---

# Objetivo do Projeto

O projeto foi desenvolvido para a disciplina de Desenvolvimento Web Back End com o objetivo de aplicar conceitos de:

- APIs REST
- Arquitetura MVC
- Spring Boot
- Spring Data JPA
- Persistência com MySQL
- CRUD de entidades
- Testes com Postman

---

# Tecnologias Utilizadas

- Java
- Spring Boot
- Spring Data JPA
- MySQL
- Maven
- Postman

---

# Estrutura do Projeto

O sistema possui três entidades principais:

## Cliente

Responsável pelo cadastro dos clientes da loja.

### Campos

- id
- nome
- clienteDesde

---

## Produto

Responsável pelo cadastro dos produtos vendidos.

### Campos

- id
- nome
- preco
- estoque

---

## Pedido

Responsável pelo registro dos pedidos realizados.

### Campos

- id
- clienteId
- produtoId
- quantidade

---

# Endpoints Implementados

## Cliente

- POST /clientes
- GET /clientes
- GET /clientes/{id}
- DELETE /clientes/{id}

---

## Produto

- POST /produtos
- GET /produtos
- GET /produtos/{id}
- DELETE /produtos/{id}

---

## Pedido

- POST /pedidos
- GET /pedidos
- GET /pedidos/{id}
- DELETE /pedidos/{id}

---

# Banco de Dados

O projeto utiliza MySQL com persistência realizada através do Spring Data JPA.

---

# Testes da API

Os testes da API foram realizados utilizando o Postman.

Foram realizados testes de:

- Criação de registros
- Listagem geral
- Consulta por ID
- Remoção de registros
