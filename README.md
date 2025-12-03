# Mercurion — Inventory & Sales Management (Backend)

**Mercurion** is a production-style Django REST backend for Inventory & Sales management.
This repository contains the version 1 REST API (JWT authentication + email-based users). The backend is frontend-agnostic and can be consumed by any web or mobile client.

---

## Features (v1)
- Email + Password authentication (JWT)
- User roles: admin, manager, staff
- Product & inventory management (stock per warehouse)
- Stock adjustments & audit trail
- Purchase Orders & Sales Orders
- Reports: inventory summary, sales summary
- Utility: send transactional emails via API
- Swagger/OpenAPI documentation
- Health check endpoint

---

## Tech Stack
- Python, Django, Django REST Framework
- PostgreSQL (recommended)
- SimpleJWT for token auth
- drf-spectacular for API docs
- Docker-compose for local dev (Postgres + Redis if needed)

---

## Quickstart (local)
1. Clone repo:
```bash
git clone https://github.com/gomu-aravind/mercurion.git
cd mercurion
