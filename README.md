
# Bus Ticketing (Spring Boot) - JWT Auth Added

This project adds JWT authentication to the Bus Ticketing backend.

Endpoints:
- POST /api/auth/register
- POST /api/auth/login -> returns { token: '...' }
- Protected endpoints must include header: Authorization: Bearer <token>

Default admin (data.sql):
- username: admin
- password: adminpass

Notes:
- Change app.jwt.secret in application.yml to a secure random value before production.
