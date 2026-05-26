# Solidarianid

Plataforma full-stack de orientación social construida alrededor de límites de servicio limpios, flujos autenticados y diseño de interfaz consciente de accesibilidad.

## Stack

- React y JavaScript para el frontend.
- NestJS para la API backend.
- MongoDB para persistencia documental.
- Docker y GitHub Actions para orquestación local y CI.

## Capacidades Principales

- Autenticación y autorización con JWT.
- Estructura de API REST con capas backend modulares.
- Pruebas automatizadas para comportamiento backend y frontend.
- Diseño de UI orientado a accesibilidad.
- Estructura de funcionalidades mantenible para flujos sociales.

## Arquitectura

```txt
React client -> NestJS API -> MongoDB
```

El backend debe mantener separados controladores, servicios y adaptadores de persistencia. El frontend debe priorizar flujos predecibles, componentes reutilizables y estados de interacción accesibles.

## Desarrollo Local

```bash
docker compose up --build
```

## Validación

```bash
docker compose exec backend npm test
docker compose exec frontend npm test
```

## Documentación Pendiente

- Referencia de API.
- Flujo de autenticación.
- Notas de accesibilidad.
- Estrategia de pruebas automatizadas.
