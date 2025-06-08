# Laundry Management System

A modern laundry management system built with Flask and React.

## Architecture

- Backend: Python Flask microservices
- Frontend: React (Admin, Customer Portal) + React Native (Mobile App)
- Database: PostgreSQL
- Cache: Redis
- Storage: MinIO
- Proxy: NGINX
- Authentication: Keycloak

## Project Structure

```plaintext
laundry-management/
├── .github/
│   └── workflows/
│       ├── backend-ci.yml
│       └── frontend-ci.yml
├── backend/
│   ├── services/
│   │   ├── order_service/
│   │   ├── notification_service/
│   │   └── report_service/
│   ├── tests/
│   └── docker/
├── frontend/
│   ├── admin/
│   ├── customer/
│   └── mobile/
├── nginx/
├── docker-compose.yml
└── README.md
