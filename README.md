# dbinspect-cli

> DBInspect CLI: Database inspection CLI with schema diff and query runner

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway

## 🧰 Tech Stack
C++, Boost, SQLite, CMake

## 🏗️ Architecture
Three-tier architecture: C++, Boost backend, native frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/dbinspect-cli
cd dbinspect-cli

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
