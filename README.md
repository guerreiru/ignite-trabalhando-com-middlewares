<h1 align="center">Desafio 02 </h1>
<h4 align="center">Ignite - <a href="https://rocketseat.com.br/" >Rocketseat</a> - Trilha Node js</h4>

## Descrição

Desenvolver middlewares para validação das rotas, com a aplicação de todo já criada. Dessa vez o usuário terá um plano, onde o ele só pode criar até dez todos e um plano Pro que irá permitir criar todos ilimitados.

## Funcionalidades

- Criar um usuário com `name` e `username`
- Criar uma novo todo
- Listar todos os _todos_;
- Alterar o `title` e `deadline` de um _todo_ existente;
- Marcar um _todo_ como feito;
- Excluir um _todo_;

## Rotas

- POST `/users` → criar um usuário.
- GET `/users/:id` → pesquisa um usuário pelo id
- PATCH `/users/:id/pro` → atualiza o plano do usuário para PRO caso não seja
- GET `/todos` → lista com todas as tarefas do usuário.
- POST `/todos` → criar um todo.
- PUT `/todos/:id` → atualiza um todo.
- PATCH `/todos/:id/done` → atualiza a propriedade `done` do todo para `true`.
- DELETE `/todos/:id` → deleta um todo pela `id`

## Instalação e uso

```bash
# Abra um terminal e copie este repositório com o comando
git clone https://github.com/guerreiru/ignite-trabalhando-com-middlewares.git
# ou use a opção de download.

# Entre na pasta web com 
cd ignite-trabalhando-com-middlewares

# Instale as dependências
yarn install

# Rode a aplicação
yarn start
```

<br>

[![Linkedin Badge](https://img.shields.io/badge/-Fernando%20Guerreiro-1293d2?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/guerreiru/)](https://www.linkedin.com/in/guerreiru/) 
[![Gmail Badge](https://img.shields.io/badge/-dev.fernandoguerreiro@gmail.com-EA4335?style=flat-square&logo=Gmail&logoColor=white&link=mailto:dev.fernandoguerreiro@gmail.com)](mailto:dev.fernandoguerreiro@gmail.com)
