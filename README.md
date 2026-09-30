# AluraBooks (back-end)

> 🇧🇷 Repositório usado durante os cursos da [Formação Full Stack React + Node.js da Alura](https://www.alura.com.br/formacao-full-stack-react-node-js).
>
> 🇺🇸 Repository used during the [Alura Full Stack React + Node.js courses](https://www.alura.com.br/formacao-full-stack-react-node-js).

API da livraria AluraBooks, feita com Node.js e Express. Os dados ficam em `livros.json` e `favoritos.json`. O front-end está no repositório [alura-books-aulas](https://github.com/bernardosevero/alura-books-aulas).

## Como rodar

```sh
npm install
npx nodemon app.js
```

A API sobe em `http://localhost:8000`.

## Rotas

| Método | Rota | O que faz |
|---|---|---|
| GET | `/livros` | Lista os livros |
| GET | `/livros/:id` | Busca um livro |
| POST | `/livros` | Cria um livro |
| PATCH | `/livros/:id` | Edita um livro |
| DELETE | `/livros/:id` | Remove um livro |
| GET | `/favoritos` | Lista os favoritos |
| POST | `/favoritos/:id` | Adiciona um livro aos favoritos |
| DELETE | `/favoritos/:id` | Remove um livro dos favoritos |

Este repositório é material de aula e não recebe novas funcionalidades.
