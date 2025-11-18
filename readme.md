# FastAPI Calculator & User Authentication Service

This project implements a FastAPI-based backend that includes:

- A simple **calculator API** (`add`, `subtract`, `multiply`, `divide`)
- A **User system** with:
  - SQLAlchemy ORM model  
  - Postgres database  
  - Secure password hashing  
  - JWT authentication  
- Full **unit**, **integration**, and **end-to-end (Playwright)** test coverage  
- A Dockerized application with an image published on Docker Hub  

---

# Features

### Calculator API
- `POST /add`
- `POST /subtract`
- `POST /multiply`
- `POST /divide`

### User System
- Register a new user  
- Login with username/email + password  
- JWT-based authentication  
- Secure password hashing using **bcrypt**

### Testing
- Unit tests  
- Integration tests using PostgreSQL  
- End-to-end UI tests using Playwright  

### CI/CD
- GitHub Actions workflow runs:
  - Linting  
  - Database migrations  
  - All tests  
  - Docker build + push  

---

# Installation & Setup

## 1. Clone the Repository
```bash
git clone <your-repo-url>
cd <repo-folder>