# Personal Finance Manager

Aplicación full-stack de gestión financiera personal enfocada en sesiones seguras, seguimiento estructurado de gastos e información preparada para dashboards.

## Stack

- React y JavaScript para el cliente web.
- Python y FastAPI para la API backend.
- PostgreSQL para persistencia relacional.
- Docker y GitHub Actions para desarrollo reproducible y CI.

## Capacidades Principales

- Autenticación JWT y flujos de cuenta protegidos.
- Seguimiento de gastos con modelado orientado a categorías.
- Estructura de API REST preparada para documentación OpenAPI.
- Capa de visualización para análisis de gasto.
- Estrategia de pruebas automatizadas para backend y frontend.

## Arquitectura

La aplicación sigue una estructura full-stack orientada a servicios:

```txt
React client -> FastAPI REST API -> PostgreSQL
```

El backend concentra autenticación, validación, lógica de dominio y persistencia. El frontend se encarga de flujos conscientes de sesión, presentación de datos lista para gráficas y gestión de estado de cara al usuario.

## Desarrollo Local

```bash
docker compose up --build
```

## Validación

```bash
docker compose exec backend pytest
docker compose exec frontend npm test
```

## Documentación Pendiente

- Referencia de API con ejemplos OpenAPI.
- Notas de esquema de base de datos.
- Flujo de autenticación y autorización.
- Captura del panel principal y notas de experiencia de usuario.
