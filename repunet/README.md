# RepuNet

Sistema descentralizado de reputacion para entornos de aprendizaje federado, disenado para reducir el impacto de clientes maliciosos durante entrenamiento distribuido.

Articulo publicado en Computer Networks:

> [RepuNet: A Reputation System for Mitigating Malicious Clients in DFL](https://doi.org/10.1016/j.comnet.2026.112242)

## Stack

- Python para simulacion, evaluacion y servicios backend.
- FastAPI para APIs de experimentacion y servicio.
- PyTorch para flujos de aprendizaje federado.
- SQLite para estado experimental ligero.
- Docker y GitHub Actions para ejecucion reproducible.

## Capacidades Principales

- Calculo de reputacion para clientes de aprendizaje federado descentralizado.
- Modelado de confianza peer-to-peer.
- Mitigacion adversarial frente a comportamiento malicioso.
- Seguimiento de experimentos y flujos de validacion.
- Estructura modular para iteracion de investigacion.

## Arquitectura

```txt
FL client nodes -> reputation layer -> aggregation / peer selection
                         |
                         `-> experiment persistence
```

El sistema separa comportamiento de clientes, actualizaciones de reputacion, escenarios adversariales y reportes de validacion. Esto mantiene los experimentos reproducibles sin perder una ruta clara hacia limites de servicio mas cercanos a produccion.

## Foco de Validacion

- Participacion de clientes maliciosos.
- Degradacion y recuperacion de reputacion.
- Convergencia de confianza entre pares.
- Tradeoffs entre precision y robustez.
- Reproducibilidad experimental.

## Desarrollo Local

```bash
docker compose up --build
```

## Tests

```bash
pytest
```

## Documentacion Pendiente

- Diseno del algoritmo de reputacion.
- Modelo de amenazas y supuestos adversariales.
- Protocolo experimental.
- Resultados de benchmark y limitaciones.
