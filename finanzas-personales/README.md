# Personal Finance Manager

Aplicacion full-stack de gestion financiera personal enfocada en sesiones seguras, seguimiento estructurado de gastos e informacion preparada para dashboards.

## Stack

- React y JavaScript para el cliente web.
- Python y FastAPI para la API backend.
- PostgreSQL para persistencia relacional.
- Docker y GitHub Actions para desarrollo reproducible y CI.

## Capacidades Principales

- Autenticacion JWT y flujos de cuenta protegidos.
- Seguimiento de gastos con modelado orientado a categorias.
- Estructura de API REST preparada para documentacion OpenAPI.
- Capa de visualizacion para analisis de gasto.
- Estrategia de tests automatizados para backend y frontend.

## Arquitectura

La aplicacion sigue una estructura full-stack orientada a servicios:

```txt
React client -> FastAPI REST API -> PostgreSQL
```

El backend concentra autenticacion, validacion, logica de dominio y persistencia. El frontend se encarga de flujos conscientes de sesion, presentacion de datos lista para graficas y gestion de estado de cara al usuario.

## Desarrollo Local

```bash
docker compose up --build
```

## Validacion

```bash
docker compose exec backend pytest
docker compose exec frontend npm test
```

## Documentacion Pendiente

- Referencia de API con ejemplos OpenAPI.
- Notas de esquema de base de datos.
- Flujo de autenticacion y autorizacion.
- Captura del dashboard y notas de experiencia de usuario.
