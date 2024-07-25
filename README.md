# Template Garcia

## Descrição

Template Garcia é um modelo de projeto utilizando Sequelize, Express e outras dependências essenciais para a construção de APIs RESTful. Este projeto está configurado para usar PostgreSQL como banco de dados.

## Instalação

#### Pré-requisitos

- Node.js (>=14.x)
- PostgreSQL

#### Passos para Instalação

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/template-garcia.git
```

2. Navegue até o diretório do projeto:

```bash
cd template-garcia
```

3. Instale as dependências:

```bash
npm install
```

4. Configure as variáveis de ambiente criando um arquivo `.env` na raiz do projeto e preenchendo-o com suas configurações de banco de dados:

```
DB_HOST=localhost
DB_USER=seu_usuario
DB_PASSWORD=sua_senha
DB_NAME=seu_banco_de_dados
DB_DIALECT=postgres
JWT_SECRET=sua_chave_secreta
```

## Scripts Disponíveis

### Iniciar o Servidor

```bash
npm start
```

### Iniciar o Servidor em Modo de Desenvolvimento

```bash
npm run dev
```

### Executar Migrações

```bash
npm run db:migrate
```

### Desfazer Migrações

```bash
npm run db:migrate:undo
```

### Executar Seeders

```bash
npm run db:seed
```

### Desfazer Seeders

```bash
npm run db:seed:undo
```

### Gerar Documentação Swagger

```bash
npm run start:gendoc
```

## Dependências

- `bcrypt`: Para hashing de senhas.
- `cors`: Para habilitar CORS.
- `dotenv`: Para carregar variáveis de ambiente.
- `express`: Framework web para Node.js.
- `jsonwebtoken`: Para autenticação via JWT.
- `pg` e `pg-hstore`: Para conexão com o PostgreSQL.
- `sequelize`: ORM para Node.js.
- `swagger-autogen` e `swagger-ui-express`: Para geração e exibição da documentação da API.
- `yup`: Para validação de esquemas.

## Documentação da API

A documentação da API é gerada automaticamente usando `swagger-autogen` e pode ser acessada em `http://localhost:3000/api-docs` após iniciar o servidor.

## Licença

Este projeto está licenciado sob a licença ISC.

## Autor

- **Autor:** [Glauton Osório](https://github.com/glautonOsorio)
- **Gato do Autor:** [Uni](https://github.com/glautonOsorio)
