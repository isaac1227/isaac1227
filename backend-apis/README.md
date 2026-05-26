# Backend APIs

Colección de notas de APIs backend y patrones de servicio enfocados en seguridad, rendimiento y contratos mantenibles.

## Stack

- Python y FastAPI.
- Node.js y NestJS.
- PostgreSQL, MongoDB y SQLite.
- Docker y GitHub Actions.

## Foco de Ingeniería

- Diseño seguro de endpoints.
- Contratos de API REST y documentación OpenAPI.
- Flujos de autenticación y autorización.
- Pruebas automatizadas y validación en CI.
- Benchmarks de rendimiento y notas operativas.

## Dirección Arquitectónica

Los servicios backend deben mantener separadas las responsabilidades de transporte, lógica de dominio y persistencia:

```txt
controller / route -> service layer -> repository / adapter -> database
```

## Validación

```bash
pytest
```

## Documentación Pendiente

- Ejemplos de referencia de API.
- Lista de verificación de seguridad.
- Notas de benchmarks de rendimiento.
- Despliegue y configuración de entorno.
