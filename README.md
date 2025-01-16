# @denis_bruns/web-core-ts

> **A TypeScript library providing core interfaces and types for building modular, testable web applications.**

[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![npm version](https://img.shields.io/npm/v/@denis_bruns/web-core-ts.svg?style=flat-square&logo=npm)](https://www.npmjs.com/package/@denis_bruns/web-core-ts)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![GitHub](https://img.shields.io/badge/GitHub-181717.svg?style=flat-square&logo=github)](https://github.com/h3llf1r33/web-core-ts)

---

## Overview

`@denis_bruns/web-core-ts` contains **interfaces** and **types** that serve as foundational building blocks for multiple libraries in your ecosystem. Previously part of a larger monorepo, it’s now separated into smaller, more focused packages. This core library helps keep your codebase:

- **Modular** – By defining reusable contracts and abstractions.
- **Testable** – Through clearly separated concerns and consistent interfaces.
- **Extensible** – Encouraging a clean architecture approach with shared definitions.

---

## Installation

Using **npm**:

```bash
npm install @denis_bruns/web-core-ts
```

Or **yarn**:

```bash
yarn add @denis_bruns/web-core-ts
```

---

## Key Features

1. **Shared Contracts** – Common interfaces for HTTP clients, data filters, pagination, and more.
2. **Clean Architecture Support** – Define entity gateways, repositories, and domain models with reusable types.
3. **Type-Safe** – Written in TypeScript to provide robust type checking and IDE autocompletion.

---

## Related Packages

### 1. **@denis_bruns/data-reflector**
[![NPM](https://img.shields.io/npm/v/@denis_bruns/data-reflector?style=flat-square&logo=npm)](https://www.npmjs.com/package/@denis_bruns/data-reflector)  
[![GitHub](https://img.shields.io/badge/GitHub--181717.svg?style=flat-square&logo=github)](https://github.com/h3llf1r33/data-reflector)
> Type-safe data transformation and reflection utilities. Easily map complex data structures through JSON paths or custom schemas.

---

### 2. **@denis_bruns/nestjs-route-handler-builder**
[![NPM](https://img.shields.io/npm/v/@denis_bruns/nestjs-route-handler-builder?style=flat-square&logo=npm)](https://www.npmjs.com/package/@denis_bruns/nestjs-route-handler-builder)  
[![GitHub](https://img.shields.io/badge/GitHub--181717.svg?style=flat-square&logo=github)](https://github.com/h3llf1r33/nestjs-route-handler-builder)
> Streamlined route-handler generation for NestJS, reducing boilerplate and promoting organized, maintainable server code.

---

### 3. **@denis_bruns/aws-lambda-handler-builder**
[![NPM](https://img.shields.io/npm/v/@denis_bruns/aws-lambda-handler-builder?style=flat-square&logo=npm)](https://www.npmjs.com/package/@denis_bruns/aws-lambda-handler-builder)  
[![GitHub](https://img.shields.io/badge/GitHub--181717.svg?style=flat-square&logo=github)](https://github.com/h3llf1r33/aws-lambda-handler-builder)
> A composable Lambda handler builder with type-safe input/output, integrated error handling, and robust middleware support.

---

### 4. **@denis_bruns/http-client-axios**
[![NPM](https://img.shields.io/npm/v/@denis_bruns/http-client-axios?style=flat-square&logo=npm)](https://www.npmjs.com/package/@denis_bruns/http-client-axios)  
[![GitHub](https://img.shields.io/badge/GitHub--181717.svg?style=flat-square&logo=github)](https://github.com/h3llf1r33/http-client-axios)
> An RxJS-powered Axios client with clean architecture in mind—provides middleware, interceptors, and type-safe request options.

---

### 5. **@denis_bruns/http-client-angular**
[![NPM](https://img.shields.io/npm/v/@denis_bruns/http-client-angular?style=flat-square&logo=npm)](https://www.npmjs.com/package/@denis_bruns/http-client-angular)  
[![GitHub](https://img.shields.io/badge/GitHub--181717.svg?style=flat-square&logo=github)](https://github.com/h3llf1r33/http-client-angular)
> Angular-friendly HTTP client abstraction integrating RxJS and a clean middleware approach for easier, testable HTTP calls.

---

### 6. **@denis_bruns/http-client-middleware**
[![NPM](https://img.shields.io/npm/v/@denis_bruns/http-client-middleware?style=flat-square&logo=npm)](https://www.npmjs.com/package/@denis_bruns/http-client-middleware)  
[![GitHub](https://img.shields.io/badge/GitHub--181717.svg?style=flat-square&logo=github)](https://github.com/h3llf1r33/http-client-middleware)
> Middleware framework for building layered, configurable HTTP clients—supports AWS Secrets Manager, environment-based headers, caching, and more.

---

### 7. **@denis_bruns/nosql-mongodb-service**
[![NPM](https://img.shields.io/npm/v/@denis_bruns/nosql-mongodb-service?style=flat-square&logo=npm)](https://www.npmjs.com/package/@denis_bruns/nosql-mongodb-service)  
[![GitHub](https://img.shields.io/badge/GitHub--181717.svg?style=flat-square&logo=github)](https://github.com/h3llf1r33/nosql-mongodb-service)
> A ready-to-use NoSQL data service for MongoDB, offering common CRUD operations, query abstractions, and integration with your domain logic.

---

### 8. **@denis_bruns/nosql-dynamodb-service**
[![NPM](https://img.shields.io/npm/v/@denis_bruns/nosql-dynamodb-service?style=flat-square&logo=npm)](https://www.npmjs.com/package/@denis_bruns/nosql-dynamodb-service)  
[![GitHub](https://img.shields.io/badge/GitHub--181717.svg?style=flat-square&logo=github)](https://github.com/h3llf1r33/nosql-dynamodb-service)
> A DynamoDB-focused service layer built for clean architecture scenarios—handles expression building, advanced filtering, and RxJS integration.

---

### 9. **@denis_bruns/base-database-service**
[![NPM](https://img.shields.io/npm/v/@denis_bruns/base-database-service?style=flat-square&logo=npm)](https://www.npmjs.com/package/@denis_bruns/base-database-service)  
[![GitHub](https://img.shields.io/badge/GitHub--181717.svg?style=flat-square&logo=github)](https://github.com/h3llf1r33/base-database-service)
> A foundational database service for bridging domain models and data stores—abstracts CRUD operations, validations, and logging.

---

## Contributing

Contributions, feature requests, and bug reports are **welcome**! Please open an issue or submit a pull request on [GitHub](https://github.com/h3llf1r33/web-core-ts).

---

## License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/h3llf1r33">h3llf1r33</a>
</p>