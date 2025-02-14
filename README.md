# Santander Dev Week API

Este projeto é uma API RESTful desenvolvida com o Spring Boot para o gerenciamento de dados de usuários. Ele permite realizar operações básicas de CRUD (Create, Read, Update, Delete) para gerenciar os dados de usuários, além de oferecer documentação interativa com o Swagger.

## Tecnologias Utilizadas

- **Java 17**
- **Spring Boot 2.x**
- **Spring Data JPA**
- **H2 Database** (banco de dados em memória para testes)
- **Swagger** (para documentação da API)
- **Maven** (gerenciador de dependências)

## Funcionalidades

### Endpoints

1. **GET /api/usuarios**
   - Retorna todos os usuários cadastrados no banco de dados.

   **Resposta:**
   - Status: `200 OK`
   - Corpo: Lista de usuários.

2. **GET /api/usuarios/{id}**
   - Retorna um usuário específico com base no `id`.

   **Parâmetros de URL:**
   - `id`: ID do usuário a ser buscado.

   **Resposta:**
   - Status: `200 OK` (se encontrado)
   - Status: `404 Not Found` (se não encontrado)

3. **POST /api/usuarios**
   - Cria um novo usuário com os dados fornecidos no corpo da requisição.

   **Exemplo de Requisição:**
   ```json
   {
     "nome": "João",
     "email": "joao@example.com"
   }
# Santander Dev Week API

Este projeto é uma API RESTful desenvolvida com o Spring Boot para o gerenciamento de dados de usuários. Ele permite realizar operações básicas de CRUD (Create, Read, Update, Delete) para gerenciar os dados de usuários, além de oferecer documentação interativa com o Swagger.

## Tecnologias Utilizadas

- **Java 17**
- **Spring Boot 2.x**
- **Spring Data JPA**
- **H2 Database** (banco de dados em memória para testes)
- **Swagger** (para documentação da API)
- **Maven** (gerenciador de dependências)

## Funcionalidades

### Endpoints

1. **GET /api/usuarios**
   - Retorna todos os usuários cadastrados no banco de dados.

   **Resposta:**
   - Status: `200 OK`
   - Corpo: Lista de usuários.

2. **GET /api/usuarios/{id}**
   - Retorna um usuário específico com base no `id`.

   **Parâmetros de URL:**
   - `id`: ID do usuário a ser buscado.

   **Resposta:**
   - Status: `200 OK` (se encontrado)
   - Status: `404 Not Found` (se não encontrado)

3. **POST /api/usuarios**
   - Cria um novo usuário com os dados fornecidos no corpo da requisição.

   **Exemplo de Requisição:**
   ```json
   {
     "nome": "João",
     "email": "joao@example.com"
   }
