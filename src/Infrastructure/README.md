# Infrastructure Layer

The Infrastructure layer contains implementations of external concerns.

## Responsibilities
- Database access (EF Core)
- External services (email, messaging, caching)
- File storage, integrations

## Rules
- Implements interfaces defined in Application
- Depends on Application and Domain
