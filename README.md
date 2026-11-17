# NodeJS 01 - Criando API: método POST e rotas

Projeto backend com Node.js + Express (aula "Node JS Criando API - #1 POST - CREATE").

## Como rodar
```bash
cd backend
npm install
npm start
```
Servidor em `http://localhost:3000`.

## Rotas
| Método | Rota | Descrição |
|---|---|---|
| GET | `/usuarios` | Retorna todos os usuários cadastrados (status 200) |
| POST | `/usuarios` | Cadastra um usuário enviado pelo body em JSON (status 201) |

Exemplo de body (Thunder Client):
```json
{
  "id": 1,
  "nome": "Renato",
  "ativo": true
}
```
