# Projeto Microsserviços - Spring Boot
Este projeto consiste em uma arquitetura de microsserviços utilizando Spring Boot, com quatro serviços principais:
Serviços

## 📋 Descrição

## ⚙️ config-services:
Serviço responsável por configurar e orquestrar os demais serviços.

## cliente-service:
Serviço responsável pelo gerenciamento de clientes, incluindo operações de CRUD.
Responsável pelo gerenciamento de clientes.
Endpoint base: /clientes
Documentação Swagger: /clientes/swagger-ui.html

## produto-service:
Serviço responsável pelo gerenciamento de produtos, incluindo operações de CRUD.
Responsável pelo gerenciamento de produtos.
Endpoint base: /produtos
Documentação Swagger: /produtos/swagger-ui.html

## vendas-service:
Serviço responsável pelo gerenciamento de vendas, incluindo operações de CRUD, onde as vendas são cadastradas relacionadas com produtos e clientes.
Responsável pelo gerenciamento de vendas.
Endpoint base: /vendas
Documentação Swagger: /vendas/swagger-ui.html


## 🛠️ Tecnologias Utilizadas
Spring Boot: Framework utilizado para desenvolvimento dos microsserviços.
Swagger: Utilizado para visualização e documentação das rotas da API.

🗃️ Banco de Dados
A aplicação está configurada para utilizar o MongoDB como sistema de gerenciamento de banco de dados.

📝 Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para mais detalhes.
