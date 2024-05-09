## Projeto web services com Spring Boot e JPA / Hibernate
Este projeto visa criar um serviço web utilizando Spring Boot e JPA/Hibernate, contemplando as seguintes funcionalidades:

**Objetivos:**
* Criar um projeto Spring Boot Java.
* Implementar um modelo de domínio.
* Estruturar as camadas lógicas: resource, service, repository.
* Configurar um banco de dados de teste (H2).
* Povoar o banco de dados com dados de teste.
* Implementar operações CRUD (Create, Retrieve, Update, Delete).
* Realizar o tratamento de exceções.
  
**Recursos utilizados:**
* Spring Boot: Framework para desenvolvimento de aplicações Java.
* JPA/Hibernate: Framework para mapeamento objeto-relacional.
* H2: Banco de dados em memória para testes.
* Maven: Ferramenta de gerenciamento de dependências e build.
  
**Estrutura do projeto:**
* O projeto segue uma arquitetura em camadas, com as seguintes responsabilidades:
* Domain Model: Define as entidades do domínio da aplicação, como User, Order, Product, Category, etc.
* Repositories: Responsáveis por interagir com o banco de dados, realizando operações CRUD.
* Services: Implementam a lógica de negócio da aplicação.
* Resources: Executam o controle das requisições HTTP e respostas.
  
**Funcionalidades implementadas:**
* CRUD de usuários: Permite criar, ler, atualizar e excluir usuários.
* Gerenciamento de pedidos: Permite criar pedidos, adicionar itens, calcular totais e associar pagamentos.
* Catálogo de produtos: Permite gerenciar produtos e suas categorias.
* Tratamento de exceções: A aplicação trata exceções como ResourceNotFoundException e DatabaseException.
  
**Configuração do banco de dados:**
* O projeto utiliza H2 para testes e PostgreSQL para o ambiente de produção (opcional). É possível configurar o ambiente de desenvolvimento com PostgreSQL localmente.
