# Architecture

This project follows Clean Architecture principles to ensure maintainability,
testability, and separation of concerns.

## Layers

### Domain
- Core business entities and rules
- No dependencies on external frameworks

### Application
- Use cases, DTOs, validation
- Interfaces for persistence and external services

### Infrastructure
- EF Core persistence
- External integrations and implementations

### API
- HTTP endpoints
- Authentication & authorization
- Middleware and Swagger
