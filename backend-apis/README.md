# Backend APIs

Coleccion de notas de APIs backend y patrones de servicio enfocados en seguridad, rendimiento y contratos mantenibles.

## Stack

- Python y FastAPI.
- Node.js y NestJS.
- PostgreSQL, MongoDB y SQLite.
- Docker y GitHub Actions.

## Foco de Ingenieria

- Diseno seguro de endpoints.
- Contratos de API REST y documentacion OpenAPI.
- Flujos de autenticacion y autorizacion.
- Tests automatizados y validacion en CI.
- Benchmarks de rendimiento y notas operativas.

## Direccion Arquitectonica

Los servicios backend deben mantener separadas las responsabilidades de transporte, logica de dominio y persistencia:

```txt
controller / route -> service layer -> repository / adapter -> database
```

## Validacion

```bash
pytest
```

## Documentacion Pendiente

- Ejemplos de referencia de API.
- Lista de verificacion de seguridad.
- Notas de benchmarks de rendimiento.
- Despliegue y configuracion de entorno.
