# Solidarianid

Plataforma full-stack de orientacion social construida alrededor de limites de servicio limpios, flujos autenticados y diseno de interfaz consciente de accesibilidad.

## Stack

- React y JavaScript para el frontend.
- NestJS para la API backend.
- MongoDB para persistencia documental.
- Docker y GitHub Actions para orquestacion local y CI.

## Capacidades Principales

- Autenticacion y autorizacion con JWT.
- Estructura de API REST con capas backend modulares.
- Testing automatizado para comportamiento backend y frontend.
- Diseno de UI orientado a accesibilidad.
- Estructura de funcionalidades mantenible para flujos sociales.

## Arquitectura

```txt
React client -> NestJS API -> MongoDB
```

El backend debe mantener separados controladores, servicios y adaptadores de persistencia. El frontend debe priorizar flujos predecibles, componentes reutilizables y estados de interaccion accesibles.

## Desarrollo Local

```bash
docker compose up --build
```

## Validacion

```bash
docker compose exec backend npm test
docker compose exec frontend npm test
```

## Documentacion Pendiente

- Referencia de API.
- Flujo de autenticacion.
- Notas de accesibilidad.
- Estrategia de testing automatizado.
