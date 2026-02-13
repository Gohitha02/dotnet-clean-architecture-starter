[![CI](https://github.com/Gohitha02/dotnet-clean-architecture-starter/actions/workflows/ci.yml/badge.svg)](https://github.com/Gohitha02/dotnet-clean-architecture-starter/actions/workflows/ci.yml)

![.NET](https://img.shields.io/badge/.NET-ASP.NET%20Core-blue)
![Architecture](https://img.shields.io/badge/Architecture-Clean%20Architecture-brightgreen)
![Database](https://img.shields.io/badge/Database-EF%20Core-informational)

# Dotnet-clean-architecture-starter

## 🧩 Architecture Diagram
> Diagram will be added here (Domain → Application → Infrastructure → API)

# .NET Clean Architecture Starter

Production-ready ASP.NET Core starter template designed using
Clean Architecture principles for scalable, testable, and maintainable systems.

## 🎯 Purpose

This repository serves as a reference implementation of Clean Architecture
for real-world ASP.NET Core applications, demonstrating best practices
used in enterprise systems.

## ✨ Key Features

- Clean Architecture layering (Domain, Application, Infrastructure, API)
- ASP.NET Core Web API
- Entity Framework Core (SQL Server / PostgreSQL ready)
- Centralized validation and error handling
- Unit testing with xUnit
- CI pipeline with GitHub Actions

## 🧩 Architecture Diagram

The solution follows strict dependency rules:

Domain  
⬇  
Application  
⬇  
Infrastructure  
⬇  
API

## ▶ How to Run

```bash
dotnet build
dotnet test
dotnet run --project src/Api


This tells reviewers **you know developer experience matters**.

---

### 6️⃣ Add a final “Status” section (mature touch)
```md
## 📦 Project Status

Actively maintained and intended as a reusable starter
for enterprise-grade ASP.NET Core applications.
