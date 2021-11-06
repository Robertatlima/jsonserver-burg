# JSON-SERVER- HAMBURGUERIA 2.0

## Endpoints

A api possui endpoints para cadastro de novo usuario, login, acessar os produtos da loja e adicionar-los ao carrinho.

### Cadastro

POST /register
POST /signup
POST /users

Qualquer um desses 3 endpoints irá cadastrar o usuário na lista de "Users", sendo que os campos obrigatórios são os de email e password.
Você pode ficar a vontade para adicionar qualquer outra propriedade no corpo do cadastro dos usuários.

### Login

POST /login
POST /signin

Qualquer um desses 2 endpoints pode ser usado para realizar login com um dos usuários cadastrados na lista de "Users"

### Products

GET/products

Endpoint para listar produtos da loja, todos podem visualizar

### Cart

GET/cart
POST/cart

dndpoint para listar itens adicionados ao carrinho e adicionar itens ao carrinho de compras
