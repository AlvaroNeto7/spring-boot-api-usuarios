# Spring Boot API de Usuários

Este é um projeto simples de uma API de Usuários, desenvolvida usando Spring Boot.

## Funcionalidades

- Cadastro de usuários
- Exibição de informações dos usuários
- API RESTful para acessar os dados dos usuários

## Como rodar o projeto

### Pré-requisitos

- Java 17 ou superior
- Maven (ou use o wrapper `mvnw`)

### Passos para executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/AlvaroNeto7/spring-boot-api-usuarios.git
Navegue até o diretório do projeto:

bash
Copiar
Editar
cd spring-boot-api-usuarios
Execute o projeto com Maven:

bash
Copiar
Editar
./mvnw spring-boot:run
Ou, se você tiver o Maven instalado globalmente:

bash
Copiar
Editar
mvn spring-boot:run
A API estará rodando em http://localhost:8080.

Endpoints
GET /usuarios - Retorna todos os usuários.

POST /usuarios - Cria um novo usuário (requisição com JSON).

GET /usuarios/{id} - Retorna um usuário específico pelo ID.

Como testar com Postman
Para testar os endpoints, você pode usar o Postman.

Teste o endpoint GET /usuarios para ver todos os usuários cadastrados.

Use o endpoint POST /usuarios para criar um novo usuário, enviando um corpo JSON.

Tecnologias usadas
Spring Boot

Java 17

Maven

Postman (para testar a API)

Contribuindo
Se você quiser contribuir com melhorias ou correções para este projeto, fique à vontade para enviar um pull request.

Fork este repositório.

Crie uma nova branch (git checkout -b feature/nova-funcionalidade).

Comite suas alterações (git commit -am 'Adicionando uma nova funcionalidade').

Envie para o seu repositório (git push origin feature/nova-funcionalidade).

Abra um pull request.
