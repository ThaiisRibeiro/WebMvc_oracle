
# 🛍️ Product Management System

Bem-vindo ao **Product Management System**! Este é um projeto desenvolvido em C# utilizando o ASP.NET Core para o back-end e Entity Framework Core para gerenciar o banco de dados, incluindo suporte a migrations. Também possui uma interface de front-end simples para interagir com o sistema de gerenciamento de produtos. 📦

## 🚀 Funcionalidades

- ✅ **CRUD Completo** (Criar, Ler, Atualizar e Excluir produtos)
- 🔄 **Migrations** para gerenciar as mudanças no banco de dados
- 🌐 **Interface do Usuário** amigável com integração front-end/back-end
- 💾 **Conexão com Banco de Dados** SQL via Entity Framework Core
- 📊 **Validação de Entrada** e **tratamento de erros**

## 📸 Preview da Tela

![Product Management UI](https://via.placeholder.com/1024x500?text=Product+Management+UI)

## 🛠️ Tecnologias Utilizadas

- **C#** e **ASP.NET Core**
- **Entity Framework Core** com Migrations
- **SQL Server** para o banco de dados
- **HTML/CSS** e **JavaScript** para o front-end
- **Bootstrap** para o design responsivo

## 📚 Pré-requisitos

Antes de rodar o projeto, você vai precisar ter instalado:

- [.NET Core SDK](https://dotnet.microsoft.com/download)
- [SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads) ou outro banco de dados compatível
- [Entity Framework Core](https://docs.microsoft.com/pt-br/ef/core/) para rodar as migrations

## 📦 Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/product-management-system.git
   cd product-management-system
   ```

2. Instale as dependências do projeto:
   ```bash
   dotnet restore
   ```

3. Configure o banco de dados no arquivo `appsettings.json`:
   ```json
   "ConnectionStrings": {
     "DefaultConnection": "Server=.;Database=ProductDB;Trusted_Connection=True;"
   }
   ```

4. Crie o banco de dados e aplique as migrations:
   ```bash
   dotnet ef database update
   ```

5. Rode o projeto:
   ```bash
   dotnet run
   ```

## 📋 Uso

### CRUD de Produtos

1. **Criar** um novo produto clicando no botão "Adicionar Produto" 🆕.
2. **Visualizar** todos os produtos cadastrados em uma tabela 📄.
3. **Editar** os detalhes de um produto existente clicando no ícone de edição ✏️.
4. **Excluir** um produto da lista clicando no ícone de lixeira 🗑️.

## 🚧 Como Funciona

- O **Entity Framework Core** é usado para mapear o modelo de domínio e interagir com o banco de dados.
- As **migrations** permitem alterar a estrutura do banco de dados conforme a aplicação evolui.
- O **front-end** foi desenvolvido em HTML/CSS com **Bootstrap** para fornecer uma interface intuitiva.
- O projeto segue o padrão MVC (Model-View-Controller).

## 🖥️ Estrutura do Projeto

```
/ProductManagementSystem
│
├── /Controllers        # Lógica dos controladores
├── /Models             # Modelos de dados e entidades
├── /Views              # Interface do usuário
├── /Migrations         # Histórico de migrations
└── appsettings.json    # Configurações da aplicação e banco de dados
```

## 🎉 Contribuições

Sinta-se à vontade para abrir issues e enviar pull requests para melhorar o projeto. Todas as contribuições são bem-vindas! 🤝

---

### 📧 Contato

Se você tiver alguma dúvida, entre em contato através de [seu-email@exemplo.com](mailto:seu-email@exemplo.com).

---

Feito com ❤️ por [Seu Nome](https://github.com/seu-usuario)
