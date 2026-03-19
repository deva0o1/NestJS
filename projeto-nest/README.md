# CRUD de Usuários com NestJS

## Objetivo

Desenvolver uma API simples utilizando NestJS para fazer operações de CRUD (Create, Read, Update e Delete) de usuários.

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

---

## Como executar o projeto

Clonar o repositório:

```
git clone https://github.com/deva0o1/NestJS
```

Entrar na pasta:

```
cd projeto-nest
```

Instalar dependências:

```
npm install
```

Rodar o projeto:

```
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

```
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

```
{
 "name": "pessoa2",
 "email": "teste2@email.com"
}
```

DELETE /users/:id
Remover usuário

---

## Testes

Testado usando Thunder Client.

---

## Autor

Devair Salasar Junior
Lucas Gianini
Gabriel Balbino
