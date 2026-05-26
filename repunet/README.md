# RepuNet

Sistema descentralizado de reputación para entornos de aprendizaje federado, diseñado para reducir el impacto de clientes maliciosos durante entrenamiento distribuido.

Artículo publicado en Computer Networks:

> [RepuNet: A Reputation System for Mitigating Malicious Clients in DFL](https://doi.org/10.1016/j.comnet.2026.112242)

## Stack

- Python para simulación, evaluación y servicios backend.
- FastAPI para APIs de experimentación y servicio.
- PyTorch para flujos de aprendizaje federado.
- SQLite para estado experimental ligero.
- Docker y GitHub Actions para ejecución reproducible.

## Capacidades Principales

- Cálculo de reputación para clientes de aprendizaje federado descentralizado.
- Modelado de confianza peer-to-peer.
- Mitigación adversarial frente a comportamiento malicioso.
- Seguimiento de experimentos y flujos de validación.
- Estructura modular para iteración de investigación.

## Arquitectura

```txt
FL client nodes -> reputation layer -> aggregation / peer selection
                         |
                         `-> experiment persistence
```

El sistema separa comportamiento de clientes, actualizaciones de reputación, escenarios adversariales y reportes de validación. Esto mantiene los experimentos reproducibles sin perder una ruta clara hacia límites de servicio más cercanos a producción.

## Foco de Validación

- Participación de clientes maliciosos.
- Degradación y recuperación de reputación.
- Convergencia de confianza entre pares.
- Tradeoffs entre precisión y robustez.
- Reproducibilidad experimental.

## Desarrollo Local

```bash
docker compose up --build
```

## Tests

```bash
pytest
```

## Documentación Pendiente

- Diseño del algoritmo de reputación.
- Modelo de amenazas y supuestos adversariales.
- Protocolo experimental.
- Resultados de benchmark y limitaciones.
