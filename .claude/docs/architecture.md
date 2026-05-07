# Arquitectura

Aplicación modular monolítica.

## Capas

- controller
- service
- repository

## Reglas

- Services actúan como interfaces
- ServicesImpl contienen lógica y son implementados por Services
- Controllers nunca acceden repositories
- Controllers nunca usan ServicesImpl, siempre usan Services
- Repositories solo acceso datos

## Base de datos

PostgreSQL + Flyway
