# DevFlow System Architecture

## Architecture

Client (React)

↓

REST API

↓

FastAPI Backend

↓

PostgreSQL Database

---

## Layers

Presentation Layer
- React
- TypeScript
- Tailwind CSS

Business Logic Layer
- FastAPI
- Authentication
- Authorization
- Project Logic
- Task Logic

Data Layer
- PostgreSQL
- SQLAlchemy ORM

---

## Authentication

JWT Authentication

---

## Communication

Frontend communicates with Backend using REST APIs.

Backend communicates with PostgreSQL using SQLAlchemy ORM.

