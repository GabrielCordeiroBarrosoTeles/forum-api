# 🚀 Forum API

<p align="center">
  <a href="http://nestjs.com/" target="blank">
    <img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" />
  </a>
</p>

<p align="center">
  Uma API moderna para fórum construída com <strong>NestJS</strong> e <strong>Prisma</strong>
</p>

## 📋 Sobre o Projeto

Esta é uma API RESTful para um sistema de fórum, desenvolvida com as melhores práticas e tecnologias modernas:

- **NestJS**: Framework Node.js progressivo para aplicações server-side
- **Prisma**: ORM moderno para TypeScript e Node.js
- **TypeScript**: Superset do JavaScript com tipagem estática
- **PostgreSQL**: Banco de dados relacional robusto

## 🛠️ Tecnologias Utilizadas

- [NestJS](https://nestjs.com/) - Framework Node.js
- [Prisma](https://prisma.io/) - ORM e Database Toolkit
- [TypeScript](https://www.typescriptlang.org/) - Linguagem de programação
- [PostgreSQL](https://www.postgresql.org/) - Banco de dados

## 📦 Instalação

1. **Clone o repositório**
   ```bash
   git clone <url-do-repositorio>
   cd forum-api
   ```

2. **Instale as dependências**
   ```bash
   yarn install
   ```

3. **Configure o banco de dados**
   ```bash
   # Configure suas variáveis de ambiente no .env
   cp .env.example .env
   
   # Execute as migrações
   npx prisma migrate dev
   ```

## 🚀 Como Executar

```bash
# Desenvolvimento (com hot reload)
yarn start:dev

# Produção
yarn start:prod

# Modo padrão
yarn start
```

## 🧪 Testes

```bash
# Testes unitários
yarn test

# Testes e2e (integração)
yarn test:e2e

# Cobertura de testes
yarn test:cov
```

## 📁 Estrutura do Projeto

```
forum-api/
├── src/
│   ├── auth/          # Módulo de autenticação
│   ├── database/      # Configuração do Prisma
│   ├── users/         # Módulo de usuários
│   └── main.ts        # Arquivo principal
├── prisma/
│   ├── schema.prisma  # Schema do banco de dados
│   └── migrations/    # Migrações do banco
└── test/              # Testes da aplicação
```

## 🔧 Comandos Úteis do Prisma

```bash
# Gerar o cliente Prisma
npx prisma generate

# Visualizar o banco de dados
npx prisma studio

# Reset do banco de dados
npx prisma migrate reset

# Deploy das migrações
npx prisma migrate deploy
```

## 📚 Recursos e Documentação

- [Documentação do NestJS](https://docs.nestjs.com)
- [Documentação do Prisma](https://www.prisma.io/docs)
- [Guia de Deploy](https://docs.nestjs.com/deployment)

## 📄 Licença

Este projeto está sob a licença MIT.

## ⚡ Comandos de Desenvolvimento

### NestJS CLI
```bash
# Gerar módulo
nest g module <nome>

# Gerar controller
nest g controller <nome>

# Gerar service
nest g service <nome>

# Gerar guard
nest g guard <nome>
```

### Prisma Setup
```bash
# Instalar Prisma
yarn add prisma @prisma/client
yarn add prisma --dev

# Inicializar Prisma
npx prisma init

# Criar migração
npx prisma migrate dev --name <nome-da-migracao>

# Gerar cliente
npx prisma generate
```
```bash

```