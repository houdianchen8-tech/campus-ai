# Campus AI - Smart Campus AI Assistant System

## Overview

Campus AI is an intelligent campus assistant system powered by AI technology, featuring AI chat, PDF intelligent reading, smart customer service, comfort simulation, and other smart services to help campuses achieve digital and intelligent management.

## Tech Stack

### Backend
- **Spring Boot** 2.5.15
- **RuoYi** 4.7.8 — Permission Management System
- **Shiro** — Authentication & Authorization
- **MyBatis** — ORM Framework
- **Druid** — Database Connection Pool
- **RabbitMQ** — Message Queue
- **MySQL** — Relational Database
- **Redis** — Cache

### Frontend (Vue)
- **Vue 3** — Progressive JavaScript Framework
- **Vite** — Build Tool
- **Pinia** — State Management
- **Vue Router** — Routing

### Frontend (Java)
- **Java Spring MVC** — Admin Dashboard

## Features

- 🤖 **AI Chat** — LLM-powered Q&A interaction
- 📄 **PDF Reader** — Upload PDF documents for AI-assisted reading & analysis
- 🎮 **Game Chat** — Gamified interactive chat mode
- 🛋️ **Comfort Simulator** — Campus environment comfort assessment
- 💬 **Smart Customer Service** — Automated Q&A system
- 🔐 **Permission Management** — Role-based access control

## Quick Start

### Prerequisites
- JDK 1.8+
- MySQL 5.7+
- Redis
- Node.js 16+

### Database Setup
```
source campusai.sql
```

### Run Backend
```
cd backend
mvn clean package -Dmaven.test.skip=true
java -jar target/backend.jar
```

### Run Vue Frontend
```
cd vue
npm install
npm run dev
```

## Project Structure

```
campus-ai/
├── backend/          # Java Spring Boot Backend
├── frontend/         # Java Admin Frontend
├── vue/              # Vue 3 Frontend Application
├── campusai.sql      # Database Schema
└── README.md         # Documentation
```
