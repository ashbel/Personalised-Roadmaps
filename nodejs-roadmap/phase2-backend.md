# Phase 2 – Backend Deep Dive

## Goals
- Build robust backend APIs using Express and NestJS with TypeScript.
- Understand RESTful design, authentication & authorization, database integration, and testing.
- Apply CI/CD and containerization practices to backend services.

## Topics & Resources
- **Express.js fundamentals**: middleware, routing, error handling. Resources: [Express docs](https://expressjs.com/).
- **NestJS framework**: controllers, modules, dependency injection, pipes & guards. Resources: [NestJS docs](https://docs.nestjs.com/).
- **API Design**: REST vs GraphQL, versioning, pagination, filtering.
- **Authentication & Authorization**: JWT, OAuth2, role-based access control; integration with Passport.js.
- **Databases**: relational (PostgreSQL, MySQL) and NoSQL (MongoDB); ORMs like TypeORM, Prisma.
- **Testing**: unit & integration tests using Jest, SuperTest, and testing strategies for controllers and services.
- **CI/CD**: GitHub Actions for linting, testing and deploying; environment variables & secrets management.

## Practice Tasks
- Extend your Phase 1 API into a full CRUD service with proper routing, validation, and error handling.
- Build a NestJS-based service that replicates the API, using modules and dependency injection patterns.
- Integrate a database (e.g., PostgreSQL via Prisma) for persistence.
- Add JWT-based authentication to secure endpoints.
- Write unit and integration tests for critical routes and services.
- Set up a simple GitHub Actions workflow to run tests on push.

## Deliverables
- A subfolder containing Express and NestJS implementations of your service.
- Database schema and migration files.
- A CI workflow file (`.github/workflows/ci.yml`) running linting and tests.
- Documentation detailing how to run the service locally and any architectural decisions.
