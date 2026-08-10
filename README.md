# 🐾 Chama no Pet

### Sistema de Gerenciamento de Pets e Atendimentos Veterinários

Aplicação desenvolvida em **ASP.NET Core**, utilizando **C#** e **SQL Server**, com o objetivo de facilitar o cadastro e gerenciamento de pets, além do controle de atendimentos veterinários.

---

# 📑 Índice

* [📖 Sobre o Projeto](#-sobre-o-projeto)
* [🚀 Funcionalidades](#-funcionalidades)
* [🛠 Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [🗄 Banco de Dados](#-banco-de-dados)
* [📷 Telas do Sistema](#-telas-do-sistema)
* [▶️ Como Executar](#️-como-executar)
* [📁 Estrutura do Projeto](#-estrutura-do-projeto)
* [🎯 Objetivos de Aprendizagem](#-objetivos-de-aprendizagem)
* [👨‍💻 Créditos](#-créditos)

---

# 📖 Sobre o Projeto

O **Chama no Pet** é um sistema desenvolvido com o objetivo de auxiliar no **gerenciamento de pets e no controle de atendimentos veterinários**.

A aplicação permite cadastrar e gerenciar informações relacionadas aos animais, facilitando a organização dos dados e o acompanhamento dos atendimentos realizados.

O projeto foi desenvolvido utilizando **ASP.NET Core** como tecnologia principal para construção da aplicação e **SQL Server** para armazenamento e persistência dos dados.

O sistema tem como proposta proporcionar uma solução simples e organizada para o gerenciamento das informações de uma rotina de atendimento veterinário.

---

# 🚀 Funcionalidades

✅ Cadastro de pets

✅ Gerenciamento de informações dos pets

✅ Consulta de pets cadastrados

✅ Edição de registros

✅ Exclusão de registros

✅ Controle de atendimentos veterinários

✅ Registro de informações relacionadas aos atendimentos

✅ Persistência dos dados em banco de dados

---

# 🛠 Tecnologias Utilizadas

| Tecnologia   | Descrição                                           |
| ------------ | --------------------------------------------------- |
| C#           | Linguagem principal                                 |
| ASP.NET Core | Framework utilizado no desenvolvimento da aplicação |
| SQL Server   | Banco de dados                                      |
| HTML/CSS     | Estrutura e estilização das páginas                 |

---

# 🗄 Banco de Dados

A aplicação utiliza o **SQL Server** para armazenamento e persistência das informações.

O banco de dados é responsável por armazenar os registros dos pets e os dados relacionados aos atendimentos veterinários.

Para utilizar o projeto, é necessário possuir uma instância do **SQL Server** configurada e ajustar a string de conexão da aplicação.

A conexão pode ser configurada no arquivo:

```text
appsettings.json
```

Exemplo:

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Database=ChamaNoPet;Trusted_Connection=True;TrustServerCertificate=True;"
  }
}
```

---

# 📷 Telas do Sistema

## 🏠 Tela Inicial

![Tela Inicial](Chamanopett/imagens/telainicial.png)

---

## 🐾 Cadastro de Pets

Tela responsável pelo cadastro e gerenciamento das informações dos pets.

![Cadastro de Pets](PetCrud/imagens/cadastropet.png)

---

# ▶️ Como Executar

## 1. Clone o projeto

```bash
git clone https://github.com/guilherme-ogreofcodes/Chamanopett.git
```

Entre na pasta do projeto:

```bash
cd Chamanopett
```

---

## 2. Abra o projeto

Abra a solução utilizando o **Visual Studio 2022** ou outra IDE compatível com **ASP.NET Core**.

---

## 3. Configure a conexão com o banco

Abra o arquivo:

```text
appsettings.json
```

Configure a string de conexão de acordo com o seu ambiente e sua instalação do **SQL Server**.

---

## 4. Configure o banco de dados

Caso o projeto utilize **Entity Framework Core e Migrations**, execute no **Package Manager Console**:

```powershell
Update-Database
```

Ou, utilizando a CLI do .NET:

```bash
dotnet ef database update
```

---

## 5. Execute o projeto

No Visual Studio, pressione:

```text
F5
```

ou clique em **Iniciar** para executar a aplicação.

---

# 📁 Estrutura do Projeto

```text
Chamanopett
│
├── Controllers
├── Models
├── Views
├── Data
├── Migrations
├── wwwroot
├── imagens
│   ├── telainicial.png
│   └── cadastropet.png
├── appsettings.json
├── Program.cs
└── README.md
```

> A estrutura pode variar de acordo com a organização final do projeto.

---

# 🎯 Objetivos de Aprendizagem

Este projeto foi desenvolvido com o propósito de praticar e aplicar conhecimentos relacionados a:

* ASP.NET Core
* C#
* Desenvolvimento Web
* Arquitetura MVC
* SQL Server
* Integração entre aplicação e banco de dados
* Operações CRUD
* Cadastro e gerenciamento de dados
* Controle de atendimentos veterinários
* Organização e estruturação de aplicações web

---

# 🐶 Objetivo do Sistema

O **Chama no Pet** busca facilitar a organização de informações relacionadas aos animais e seus atendimentos veterinários.

Por meio do sistema, é possível manter os dados dos pets organizados e registrar os atendimentos realizados, proporcionando maior controle sobre o histórico de atendimento.

---

# 👨‍💻 Créditos

### Desenvolvedor

**Guilherme Pereira Dantas de Oliveira Santos**

---

### Professor

**Wallace Oliveira dos Santos**

---

### ⭐ Se este projeto foi útil para você, deixe uma estrela no repositório!
