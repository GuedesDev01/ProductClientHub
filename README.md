# 🚀 ProductClientHub API

API REST desenvolvida com foco em aprendizado de backend utilizando .NET e C#.  
O projeto foi construído durante um bootcamp prático com ênfase em criação de APIs, manipulação de usuários e persistência de dados.

---

## 📖 Sobre o Projeto

O **ProductClientHub** é uma API REST que permite gerenciar usuários e dados persistidos em banco de dados.

O objetivo principal foi aplicar conceitos fundamentais de:

- Criação de APIs com .NET
- Estruturação de Controllers
- Registro de usuários
- Integração com banco de dados
- Persistência de dados com ORM

---

## 🧠 Estrutura baseada nos módulos do curso

### 🔹 1. Criando uma API
- Configuração inicial do projeto ASP.NET Core
- Estruturação de Controllers
- Mapeamento de rotas
- Testes via Swagger

🔹 2. Registrando Usuários
- Criação de modelo de usuário
- Implementação de endpoints:
  - POST (Cadastro)
  - GET (Listagem)
  - PUT (Atualização)
  - DELETE (Remoção)
- Validações básicas

 🔹 3. Introdução a Banco de Dados
- Conceitos de persistência
- Configuração do banco de dados
- Conexão com a aplicação

🔹 4. Persistindo Dados no Banco
- Integração com Entity Framework
- Mapeamento de entidades
- Migrations
- Salvando dados no banco de forma estruturada

---

 🛠 Tecnologias Utilizadas

- C#
- .NET
- ASP.NET Core
- Entity Framework Core
- SQL Server
- Swagger

---

## 📌 Endpoints principais

| Método | Rota            | Descrição              |
|--------|----------------|------------------------|
| GET    | /users         | Lista todos usuários   |
| GET    | /users/{id}    | Busca usuário por ID   |
| POST   | /users         | Cadastra novo usuário  |
| PUT    | /users/{id}    | Atualiza usuário       |
| DELETE | /users/{id}    | Remove usuário         |

---

## ▶ Como executar o projeto

1. Clone o repositório:
   
git clone https://github.com/seu-usuario/ProductClientHub.git
Abra no Visual Studio

Configure a string de conexão no appsettings.json

Execute as migrations:

Update-Database
Rode o projeto

Acesse o Swagger:

https://localhost:porta/swagger


🎯 Objetivo Educacional
Este projeto foi desenvolvido com fins educacionais durante um bootcamp prático de backend.

Após a conclusão dos módulos base, melhorias futuras poderão incluir:

Autenticação com JWT

Validações mais robustas

Paginação

Filtros avançados

Arquitetura em camadas (Application / Domain / Infrastructure)

📈 Status do Projeto
✅ Estrutura base da API
✅ CRUD de usuários
✅ Persistência em banco
🔄 Em evolução contínua

👨‍💻 Autor
Desenvolvido por Bruno Guedes
