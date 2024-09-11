# NestJS API Boilerplate

Este repositório serve como um modelo padrão (boilerplate) para novos projetos utilizando o [NestJS](https://nestjs.com/), um framework progressivo para a construção de aplicações Node.js escaláveis, com foco em APIs RESTful.

## 📋 Funcionalidades

- Estrutura básica de um projeto NestJS com módulos, serviços e controladores.
- Suporte a padrões de autenticação com JWT.
- Conexão com banco de dados usando TypeORM e suporte a várias bases de dados (PostgreSQL, MySQL, etc.).
- Validação de entrada com `class-validator`.
- Mecanismos de controle de exceções e erros padrão.
- Configuração pronta para uso do `.env` para variáveis de ambiente.
- Suporte a testes unitários com Jest.
- Swagger UI integrada para documentação automática de APIs.
  
## 🚀 Tecnologias Utilizadas

- **NestJS** - Framework para construção da API.
- **TypeScript** - Linguagem de desenvolvimento.
- **TypeORM** - ORM para gerenciar a interação com o banco de dados.
- **JWT** - Autenticação baseada em token.
- **Swagger** - Documentação da API.
- **Jest** - Framework de testes.

## 📁 Estrutura de Pastas

```bash
src/
├── app.module.ts        # Módulo raiz da aplicação
├── auth/                # Módulo de autenticação
├── common/              # Módulo com utilitários e decorators comuns
├── config/              # Configurações da aplicação
├── users/               # Módulo de usuários (exemplo)
├── main.ts              # Arquivo de inicialização da aplicação
└── ...                  # Outras pastas e arquivos
