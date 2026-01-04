# Architecture Overview

## Stack
- Frontend: React + Vite
- Backend: Node.js (native HTTP server)
- Reverse Proxy: Nginx
- Database: PostgreSQL
- Cache: Redis
- Containerization: Docker + Docker Compose

## Request Flow
Browser
→ Nginx (port 80)
→ Backend API
→ PostgreSQL / Redis

