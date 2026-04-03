# Testes de API - Serverest

##  Login

### POST - Login com credenciais válidas
- Esperado: Status 200
- Deve retornar token de autenticação

### POST - Login com credenciais inválidas
- Esperado: Status 401
- Deve retornar mensagem de erro

---

##  Usuários

### POST - Criar usuário com dados válidos
- Esperado: Status 201
- Usuário criado com sucesso

### POST - Criar usuário sem dados obrigatórios
- Esperado: Status 400
- Deve retornar erro de validação

### GET - Listar usuários
- Esperado: Status 200
- Deve retornar lista de usuários

---

##  Produtos

### GET - Listar produtos
- Esperado: Status 200
- Deve retornar lista de produtos

### POST - Cadastrar produto com dados válidos
- Esperado: Status 201
- Produto criado com sucesso

### DELETE - Deletar produto existente
- Esperado: Status 200
- Produto removido com sucesso
