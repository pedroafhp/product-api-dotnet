API REST de Gerenciamento de Produtos

API REST desenvolvida em C# com ASP.NET Core para gerenciamento de produtos, implementando operações CRUD completas, integração com banco de dados relacional e documentação interativa.

Tecnologias
C#
ASP.NET Core Web API
Entity Framework Core
SQL Server
Swagger (OpenAPI)

Arquitetura

O projeto segue uma estrutura em camadas, separando responsabilidades em:

Controllers (camada de apresentação)
Services (regras de negócio)
Data/Repository (acesso a dados)

Funcionalidades
Cadastro de produtos
Listagem de produtos
Consulta por ID
Atualização de dados
Remoção de produtos

Documentação

A API possui documentação interativa via Swagger disponível ao executar o projeto.

Como executar
# Restaurar dependências
dotnet restore

# Aplicar migrations (caso utilize EF)
dotnet ef database update

# Executar aplicação
dotnet run

A API estará disponível em:
https://localhost:5001

Observações

Projeto desenvolvido com foco em boas práticas de desenvolvimento backend, organização de código e integração com banco de dados.
