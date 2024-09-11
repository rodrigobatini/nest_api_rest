# NestJS API Boilerplate

This repository serves as a standard boilerplate for new projects using [NestJS](https://nestjs.com/), a progressive framework for building scalable Node.js applications, with a focus on RESTful APIs.

## 📋 Features

- Basic structure of a NestJS project with modules, services, and controllers.
- Support for JWT authentication patterns.
- Database connection using TypeORM with support for multiple databases (PostgreSQL, MySQL, etc.).
- Input validation with `class-validator`.
- Standard exception and error handling mechanisms.
- Ready-to-use `.env` configuration for environment variables.
- Unit testing support with Jest.
- Integrated Swagger UI for automatic API documentation.

## 🚀 Technologies Used

- **NestJS** - Framework for building the API.
- **TypeScript** - Development language.
- **TypeORM** - ORM for managing database interactions.
- **JWT** - Token-based authentication.
- **Swagger** - API documentation.
- **Jest** - Testing framework.

## 📁 Folder Structure

```bash
src/
├── app.module.ts        # Root module of the application
├── auth/                # Authentication module
├── common/              # Module with common utilities and decorators
├── config/              # Application configurations
├── users/               # Users module (example)
├── main.ts              # Application bootstrap file
└── ...                  # Other folders and files
```

## 📝 Requirements
- `docker-engine` and `docker-compose`

## ⚙️ Installation
To install the project, follow these steps:

- Clone the repository using the command git clone <repository URL>
- Run the command `docker-compose up` to run the application on foreground (use `-d` for running on background)
    - depending on which version and how you installed docker-compose, you may need to run as `docker compose up
    
## 💻 Testing
The testing module is under development.