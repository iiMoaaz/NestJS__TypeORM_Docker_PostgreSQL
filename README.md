# Nest.js + TypeORM + PostgreSQL Backend

This repository contains a robust server-side application built with **Nest.js**, **TypeScript**, and **PostgreSQL**. The project demonstrates a modular architecture, clean separation of concerns using Services and Controllers, and seamless database integration using TypeORM.

## ✨ Key Features

- **Modular Architecture:** Organized into feature modules for high maintainability.
- **RESTful API:** Cleanly defined endpoints with structured request/response handling.
- **Data Validation:** Strict input validation using `class-validator` and `Data Transfer Objects (DTOs)`.
- **Database Persistence:** Integrated with PostgreSQL via **TypeORM**.
- **Containerization:** Ready-to-use Docker configuration for the database environment.
- **Dependency Injection:** Efficient resource management and cross-module service sharing.

---

## 🛠️ Technical Stack

- **Framework:** [Nest.js](https://nestjs.com/)
- **Database:** PostgreSQL
- **ORM:** TypeORM
- **Validation:** Class-validator & Class-transformer
- **Environment:** Docker & Docker Compose

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- Docker Desktop
- npm / yarn / pnpm

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/vahid-nejad/nest-project.git](https://github.com/vahid-nejad/nest-project.git)
   cd nest-project

### 🚀 Run the Application

| Mode | Command |
| :--- | :--- |
| **Development** | `npm run start:dev` |
| **Production** | `npm run start:prod` |

---

### 📂 Project Structure

```text
src/
 ├── modules/     # Feature modules (e.g., Users, Products)
 ├── entities/    # TypeORM database models
 ├── dtos/        # Data Transfer Objects for validation
 ├── services/    # Business logic layer
 └── controllers/ # API route handlers