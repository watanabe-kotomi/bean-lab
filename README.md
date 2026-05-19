# bean-lab

Coffee recommendation platform built with NestJS, React, and PostgreSQL.

## Prerequisites

- Node.js 22+
- Docker

## Getting started

### 1. Start the database

```bash
docker compose up -d
```

### 2. Backend

```bash
cd backend
cp .env.example .env   # then fill in JWT_SECRET
npm install
npx prisma migrate dev
npm run start:dev
```

### 3. Frontend

```bash
cd frontend
npm install
npm run dev
```

## Stack

- **Backend** — NestJS, Prisma, PostgreSQL
- **Frontend** — React, Vite
