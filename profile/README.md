# 💰 FinControl

Aplicativo mobile de **controle financeiro pessoal**, desenvolvido com **React Native e Expo**, integrado a uma API REST desenvolvida em **.NET**.

O objetivo do FinControl é permitir que o usuário organize sua vida financeira de forma simples, acompanhando **receitas, despesas e saldo**, além de utilizar recursos de autenticação para proteger seus dados.

## 📱 Sobre o projeto

O FinControl foi desenvolvido como um projeto para colocar em prática conhecimentos de **desenvolvimento mobile, desenvolvimento de APIs, banco de dados e autenticação**.

A aplicação possui uma arquitetura dividida entre o aplicativo mobile e uma API responsável pelo processamento e armazenamento dos dados.

### 🛠️ Tecnologias utilizadas

#### 📱 Mobile
- React Native
- Expo
- Expo Router
- TypeScript
- `.env` para configuração de ambiente
- Integração com API REST

#### ⚙️ Backend
- C#
- .NET
- ASP.NET Core
- Entity Framework Core
- SQL Server
- API REST
- JWT
- Swagger

#### 🔐 Segurança e autenticação
- Login de usuário
- Autenticação utilizando JWT
- Proteção de rotas
- Autenticação biométrica
- Recuperação de senha

## ✨ Funcionalidades

- 🔐 Cadastro e login de usuários
- 🔑 Autenticação com JWT
- 👆 Autenticação biométrica
- 💰 Cadastro de receitas
- 💸 Cadastro de despesas
- 📊 Acompanhamento financeiro
- 💵 Visualização do saldo
- 🔄 Comunicação entre aplicativo e API
- 🔒 Recuperação de senha
- 👤 Gerenciamento de informações do usuário

## 🏗️ Estrutura do projeto

O projeto é dividido em duas partes principais:

```text
FinControl
│
├── 📱 Mobile
│   ├── React Native
│   ├── Expo
│   ├── Expo Router
│   └── TypeScript
│
└── ⚙️ API
    ├── ASP.NET Core
    ├── C#
    ├── Entity Framework Core
    ├── SQL Server
    └── JWT
```

## 🔗 Comunicação com a API

O aplicativo mobile realiza requisições HTTP para a API desenvolvida em .NET.

Durante o desenvolvimento, as configurações da API são armazenadas através de variáveis de ambiente:

```env
EXPO_PUBLIC_API_URL=http://10.0.2.2:5082/api
```

O endereço pode ser alterado de acordo com o ambiente utilizado.

## 🗄️ Banco de dados

O backend utiliza **SQL Server** para armazenamento dos dados.

O acesso ao banco é realizado utilizando:

- Entity Framework Core
- Migrations
- Models
- DbContext

## 📚 O que este projeto demonstra

Com o FinControl, foram praticados conceitos como:

- Desenvolvimento de aplicações mobile
- Desenvolvimento de APIs REST
- C# e .NET
- React Native
- TypeScript
- Entity Framework Core
- SQL Server
- Autenticação JWT
- Integração entre frontend e backend
- Variáveis de ambiente
- Organização de projetos
- Git e GitHub
- Desenvolvimento de funcionalidades de autenticação

## 🚀 Como executar o projeto

### 1. Clone o repositório

```bash
git clone URL_DO_REPOSITORIO
```

### 2. Acesse a pasta do aplicativo

```bash
cd FinControl
```

### 3. Instale as dependências

```bash
npm install
```

### 4. Configure o arquivo `.env`

Crie um arquivo `.env` na raiz do projeto:

```env
EXPO_PUBLIC_API_URL=http://10.0.2.2:5082/api
```

### 5. Execute o projeto

```bash
npx expo start
```

Depois, escolha o ambiente desejado para executar o aplicativo.

## 👨‍💻 Desenvolvedores

**Caique Lima Alves**
**Guilherme Ribeiro**
**Pedro Augusto**
**Isaque de Sousa**
**Allan Queiroz**
**Henrique Almeida**

Estudante de Desenvolvimento de Sistemas, com foco em **C#, .NET, APIs, React Native, TypeScript e desenvolvimento Full Stack**.

---

⭐ Projeto desenvolvido para fins de aprendizado e portfólio.

