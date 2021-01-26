# Trabalho Prático Final
## Autores: Sandyara Peres e Bruno Fernandes
Trabalho realizado para a disciplina de Sistemas Web 2 (ASP.NET MVC), ministrada por Wellington Tuller Moraes no Instituto Federal de São Paulo, campus Cubatão.

### Objetivo
Desenvolver uma aplicação com API, Web Site e aplicação Desktop

### Contém
- [x] Banco que dados capaz de armazenar informações de Usuário / Produto
- [x] API contem todos os métodos CRUD para o Usuário e Produto
- [x] A gestão de usuários efetuada através de uma aplicação Desktop
- [x] Operações de produto devem ser executadas através de WebSite

### Captura de tela da aplicação
#### Desktop
![Funcionamento do app](capturaDesktop.gif)
#### Web
![Funcionamento do app](capturaWeb.gif)

# Pacotes utilizados

**API**
- Microsoft.AspNetCore.Mvc.NewtonsoftJson (versão 3.0.0)
- Microsoft.EntityFrameworkCore.SqServer
- Microsoft.EntityFrameworkCore.Tools

**Desktop**
- Microsoft.AspNet.WebApi.Client
- Newstonsoft.Json

**Web**
- Newstonsoft.Json

# Pré-requisitos e como rodar a aplicação

Requisitos:

Visual Studio 2019.

Setup:

Crie o Banco com o comando "Update-Database" no Console do Gerenciador de Pacotes
