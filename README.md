# CRUD de Usuários com NestJS

## Objetivo

Desenvolver uma API simples utilizando NestJS para realizar operações de CRUD (Create, Read, Update e Delete) de usuários.

---

## Funcionalidades

* Criar usuário
* Listar usuários
* Buscar usuário por ID
* Atualizar usuário
* Remover usuário

---

## Tecnologias utilizadas

* Node.js
* NestJS
* TypeScript
* SQLite
* TypeORM
* Thunder Client

---

## Banco de dados

O projeto utiliza SQLite como banco de dados, armazenando os dados em um arquivo local.

Inicialmente, os dados eram armazenados em memória. Depois, foi implementado o uso de banco de dados para persistência das informações.

---

## Como executar o projeto

Clonar o repositório:

```bash
git clone https://github.com/deva0o1/NestJS
```

Entrar na pasta:

```bash
cd projeto-nest
```

Instalar dependências:

```bash
npm install
```

Dependências utilizadas para banco de dados:

* @nestjs/typeorm
* typeorm
* sqlite3

Rodar o projeto:

```bash
npm run start:dev
```

Acessar:

```
http://localhost:3000/users
```

---

## Rotas

POST /users
Criar usuário

Exemplo:

```json
{
 "name": "pessoa1",
 "email": "teste@email.com"
}
```

GET /users
Listar usuários

GET /users/:id
Buscar usuário

PUT /users/:id
Atualizar usuário

Exemplo:

```json
{
 "name": "pessoa2",
 "email": "teste2@email.com"
}
```

DELETE /users/:id
Remover usuário

---

## Testes

A API foi testada utilizando Thunder Client.

---

## Autor

Devair Salasar Junior
Lucas Gianini
Gabriel Balbino
