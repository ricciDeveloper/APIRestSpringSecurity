# Spring Boot Security API

Este é um projeto de exemplo que demonstra como criar uma API REST segura usando Spring Boot com autenticação JWT e controle de acesso baseado em papéis.

## Funcionalidades

- Autenticação de usuários via JWT (JSON Web Token).
- Controle de acesso com base em papéis (roles).
- Criptografia de senha usando BCryptPasswordEncoder.
- CRUD de usuários com armazenamento seguro de senha.

## Tecnologias Utilizadas

### Spring Boot
Spring Boot é um framework Java baseado em Spring que simplifica o desenvolvimento de aplicativos Java. Ele oferece um conjunto de ferramentas e convenções para acelerar o desenvolvimento, permitindo que você crie aplicativos prontos para produção com facilidade.

### Spring Security
Spring Security é um framework poderoso e altamente personalizável para autenticação e autorização em aplicativos Java. Ele fornece recursos de segurança abrangentes, como autenticação baseada em formulário, autenticação baseada em token e controle de acesso baseado em URL e método.

### Spring Data JPA
Spring Data JPA é uma parte do ecossistema Spring que facilita a interação com bancos de dados relacionais em aplicativos Java. Ele fornece uma abordagem simplificada para escrever consultas e operações de banco de dados, reduzindo a quantidade de código boilerplate.

### JWT (JSON Web Token)
JWT é um padrão aberto (RFC 7519) que define um formato compacto e autossuficiente para transmitir informações entre partes de forma segura como um objeto JSON. Ele é comumente usado para autenticação e autorização em aplicativos web e APIs RESTful devido à sua facilidade de uso e segurança.

### BCryptPasswordEncoder
BCryptPasswordEncoder é uma implementação do PasswordEncoder do Spring Security que utiliza o algoritmo de hash bcrypt para criptografar senhas. Ele fornece uma maneira segura de armazenar senhas em aplicativos, protegendo-as contra ataques de força bruta.

## Configuração

O projeto contém as seguintes classes principais:

- `LoginController`: Controlador responsável pela autenticação de usuários.
- `UserController`: Controlador para operações CRUD de usuários.
- `WelcomeController`: Controlador de boas-vindas e endpoints de teste de acesso autorizado.
- `JWTFilter`: Filtro para validar e processar tokens JWT em todas as solicitações.
- `SecurityConfig`: Configuração de segurança com regras de autorização e configurações JWT.
- `UserService`: Serviço para criar usuários, incluindo a criptografia de senhas.

## Dependências

Este projeto usa as seguintes dependências principais:

- Spring Boot: Framework para criar aplicativos Java baseados em Spring de forma rápida e fácil.
- Spring Security: Para segurança de aplicativos.
- Spring Data JPA: Para integração com banco de dados.
- JWT (JSON Web Token): Para autenticação de usuários e controle de acesso.

## Instruções de Uso

1. Clone o repositório:2. Importe o projeto em sua IDE favorita como um projeto Maven.

3. Configure as propriedades do aplicativo em `application.properties` conforme necessário.

4. Execute o aplicativo e teste os endpoints disponíveis, como `/login` para autenticação e `/users` para operações CRUD de usuários.

## Redes sociais:
https://www.linkedin.com/in/joaoriccideveloper/
