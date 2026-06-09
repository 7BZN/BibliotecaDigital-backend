# BibliotecaDigital-backend

# Backend - Biblioteca Digital

## Tecnologias Utilizadas

* Node.js
* Express
* SQLite3
* CORS

## Instalação

Acesse a pasta do backend:

```bash
cd backend
```

Instale as dependências:

```bash
npm init -y

npm install express cors sqlite3
```

## Execução

Inicie o servidor:

```bash
node server.js
```

A API ficará disponível em:

```text
http://localhost:3000
```

## Endpoints

### Listar Livros

```http
GET /livros
```

### Cadastrar Livro

```http
POST /livros
```

Exemplo de JSON:

```json
{
  "titulo": "Clean Code",
  "autor": "Robert Martin",
  "ano": 2008,
  "categoria": "Programação"
}
```

### Atualizar Livro

```http
PUT /livros/:id
```

### Excluir Livro

```http
DELETE /livros/:id
```

## Estrutura

```text
backend/
│
├── server.js
├── database.js
│
├── routes/
├── controllers/
└── models/
```
