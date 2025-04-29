# 🌟 CRUD de lugares/locais com Angular e Tailwind CSS

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker)

## 📝 Sobre o Projeto

Uma aplicação web moderna e responsiva desenvolvida com Angular e TailwindCSS, demonstrando uma arquitetura frontend robusta e escalável. O projeto implementa autenticação segura, rotas protegidas e integração com APIs RESTful, servindo como um excelente exemplo de desenvolvimento web moderno.

### ✨ Destaques do Projeto

- **Arquitetura Modular**: Implementação de módulos lazy-loading para otimização de performance
- **Design Responsivo**: Interface adaptativa construída com TailwindCSS
- **Autenticação Robusta**: Sistema de login com suporte a OAuth 2.0 (Google)
- **API RESTful**: Integração com backend simulado usando JSON Server
- **Containerização**: Ambiente isolado e reproduzível com Docker

## 🚀 Funcionalidades

- 🔐 Sistema completo de autenticação e autorização
- 📁 CRUD completo para gerenciamento de categorias
- 📍 Sistema de gerenciamento de lugares/locais
- 🖼️ Galeria de imagens com lazy loading
- 🎨 Interface moderna e responsiva
- 🛡️ Rotas protegidas com Guards

## 🛠️ Tecnologias Principais

- **Frontend**: Angular 16+
- **Estilização**: TailwindCSS
- **API**: JSON Server
- **Containerização**: Docker
- **Linguagem**: TypeScript
- **Autenticação**: OAuth 2.0

## 💻 Como Executar

### Pré-requisitos

- Node.js 16+
- npm ou yarn
- Docker (opcional)

### Instalação e Execução

1. Clone o repositório:

   ```bash
   git clone [url-do-repositório]
   cd Angular-TailwindCSS-API
   ```

2. Instale as dependências:

   ```bash
   npm install
   ```

3. Inicie o servidor de desenvolvimento:

   ```bash
   npm start
   ```

4. Execute a API simulada:

   ```bash
   json-server --watch api/db.json --port 3000
   ```

### 🐳 Usando Docker

```bash
docker-compose up -d
```

## 📂 Estrutura do Projeto

```txt
src/
├── app/                # Componentes e lógica principal
│   ├── auth/          # Autenticação e autorização
│   ├── categorias/    # Módulo de categorias
│   ├── lugares/       # Módulo de lugares
│   ├── galeria/       # Módulo de galeria
│   └── template/      # Componentes de layout
├── environments/      # Configurações de ambiente
└── assets/           # Recursos estáticos
```

## 🌐 Ambientes

- **Desenvolvimento**: `http://localhost:4200`
- **API Local**: `http://localhost:3000`
