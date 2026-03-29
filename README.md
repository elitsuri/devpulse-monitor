# DevPulse Monitor

> Developer productivity monitor with git stats and time tracking

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
TypeScript, Electron, React, SQLite

## 🏗️ Architecture
Backend service with TypeScript, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/devpulse-monitor
cd devpulse-monitor

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
