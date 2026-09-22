
work 
# NestJS E-Commerce API — Senior Backend

Production-ready e-commerce backend built with NestJS, PostgreSQL, Prisma, Redis, BullMQ, Docker.

## Stack
- NestJS + TypeScript
- PostgreSQL + Prisma
- Redis + BullMQ for jobs
- JWT Auth (access 15m + refresh 7d)
- Paystack webhook with signature verification

## Run with Docker
docker-compose up --build

## API Docs
http://localhost:3000/api/docs

## Features
- Auth with refresh token rotation
- Products CRUD with pagination
- Orders with Paystack integration
- Queue for emails
- Tests with Jest
