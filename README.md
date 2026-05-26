# Isaac1227

<p align="center">
  <img src="/screenshots/LinkedIn.png" alt="Banner profesional de Isaac como ingeniero de software" />
</p>

<p align="center">
  <a href="https://github.com/isaac1227">
    <img alt="Perfil de GitHub" src="https://img.shields.io/badge/GitHub-isaac1227-181717?style=flat-square&logo=github" />
  </a>
  <img alt="Ingenieria backend" src="https://img.shields.io/badge/Foco-Backend-2563eb?style=flat-square" />
  <img alt="Sistemas distribuidos" src="https://img.shields.io/badge/Sistemas-Distribuidos-14b8a6?style=flat-square" />
  <img alt="Aprendizaje federado" src="https://img.shields.io/badge/Investigacion-Aprendizaje%20Federado-7c3aed?style=flat-square" />
</p>

## Perfil

Ingeniero de software enfocado en desarrollo backend, sistemas distribuidos, diseno de APIs e investigacion aplicada en aprendizaje federado. Construyo servicios orientados a produccion con limites claros, arquitectura pragmatica, validacion automatizada y documentacion pensada para operar sistemas con criterio.

Mi linea tecnica actual combina plataformas backend, diseno seguro de servicios y entornos descentralizados de aprendizaje automatico, con foco en fiabilidad, mantenibilidad y validacion experimental.

## Stack Tecnologico

| Backend                 | Frontend                          | Datos                                     | DevOps y Calidad                            |
| ----------------------- | --------------------------------- | ----------------------------------------- | ------------------------------------------- |
| Python, FastAPI, NestJS | React, JavaScript                 | PostgreSQL, SQLite, MongoDB               | Docker, GitHub Actions, CI/CD               |
| APIs REST, JWT, OpenAPI | Interfaces basadas en componentes | Diseno de esquemas, capas de persistencia | Tests automatizados, entornos reproducibles |

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
  <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-116149?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
</p>

## Proyectos Destacados

### Personal Finance Manager

Plataforma full-stack de finanzas personales disenada alrededor de acceso seguro, seguimiento de gastos y visualizacion clara de datos financieros.

**Stack:** React, FastAPI, PostgreSQL, Docker  
**Foco de ingenieria:** autenticacion JWT, diseno de API REST, modulos backend orientados al dominio y modelos preparados para dashboards.

Capacidades principales:

- Seguimiento de gastos y reportes por categoria.
- Flujo de autenticacion seguro con sesiones basadas en tokens.
- Entorno local containerizado para backend, frontend y base de datos.
- Capa de visualizacion para analizar patrones de gasto.

Notas del proyecto: [`finanzas-personales/`](./finanzas-personales)

### RepuNet

Sistema descentralizado de reputacion para entornos de aprendizaje federado, centrado en identificar y reducir el impacto de clientes maliciosos durante el entrenamiento distribuido.

**Stack:** Python, FastAPI, PyTorch, SQLite, Docker  
**Foco de ingenieria:** calculo de reputacion, sistemas de confianza peer-to-peer, mitigacion adversarial y validacion experimental reproducible.

Publicacion en progreso:

> RepuNet: A Reputation System for Mitigating Malicious Clients in DFL

Capacidades principales:

- Calculo de reputacion para clientes de aprendizaje federado descentralizado.
- Coordinacion entre pares basada en confianza.
- Validacion experimental bajo participacion adversarial.
- Persistencia ligera para simulacion y auditabilidad.

Notas del proyecto: [`repunet/`](./repunet)

### Solidarianid

Plataforma full-stack de orientacion social con arquitectura backend limpia y experiencia frontend pensada para accesibilidad y flujos claros.

**Stack:** React, NestJS, MongoDB  
**Foco de ingenieria:** arquitectura limpia, autenticacion JWT, testing automatizado y diseno orientado a accesibilidad.

Capacidades principales:

- Diseno modular de API con autenticacion y autorizacion.
- Estructura frontend preparada para crecimiento mantenible.
- Estrategia de tests automatizados para servicios e interfaz.
- Decisiones de UI orientadas a accesibilidad.

Notas del proyecto: [`solidarianid/`](./solidarianid)

## Areas Tecnicas

- **Ingenieria Backend:** diseno de APIs, autenticacion, limites de servicio, validacion, persistencia y claridad operativa.
- **Sistemas Distribuidos:** coordinacion descentralizada, diseno tolerante a fallos, confianza entre pares y simulaciones reproducibles.
- **Aprendizaje Federado:** mitigacion adversarial, sistemas de reputacion, flujos experimentales y documentacion de investigacion.
- **Arquitectura de Software:** capas limpias, modulos mantenibles, contratos explicitos y decisiones tecnologicas alineadas con restricciones.
- **Seguridad:** flujos JWT, configuracion de minimo privilegio, validacion de entrada y valores por defecto seguros.
- **DevOps:** desarrollo basado en Docker, checks de CI, plantillas de entorno y setup local repetible.

## Estructura del Repositorio

```txt
.
|-- .github/workflows/      # Ejemplos de CI y automatizacion del repositorio
|-- backend/                # Espacio de trabajo backend
|-- backend-apis/           # Notas y referencias de APIs backend
|-- docs/                   # Documentacion de arquitectura e ingenieria
|-- finanzas-personales/    # Notas del proyecto Personal Finance Manager
|-- frontend/               # Espacio de trabajo frontend
|-- repunet/                # Notas de investigacion e implementacion de RepuNet
|-- screenshots/            # Marcadores para capturas y diagramas
|-- solidarianid/           # Notas del proyecto Solidarianid
|-- tests/                  # Espacio compartido de validacion
|-- docker-compose.yml
|-- .env.example
|-- .gitignore
|-- LICENSE
`-- README.md
```

## Arquitectura

Este repositorio de perfil esta organizado como un workspace de portfolio tecnico, no como una unica aplicacion. Cada proyecto destacado mantiene su propia documentacion, mientras que las referencias compartidas de ingenieria viven en [`docs/`](./docs).

Lectura recomendada:

- [Vision de Arquitectura](./docs/architecture.md)
- [Portfolio de Proyectos](./docs/projects.md)
- [Principios de Ingenieria](./docs/engineering-principles.md)

## Configuracion Local

Clona el repositorio y revisa el workspace de documentacion:

```bash
git clone https://github.com/isaac1227/isaac1227.git
cd isaac1227
```

Crea las variables de entorno locales a partir de la plantilla:

```bash
cp .env.example .env
```

Arranca el stack de servicios de ejemplo:

```bash
docker compose up --build
```

El archivo de Compose es intencionalmente minimo y funciona como plantilla de desarrollo para servicios backend, frontend y bases de datos.

## Calidad

Este repositorio incluye un workflow de GitHub Actions que valida estructura, referencias Markdown e higiene documental. Los tests especificos de cada proyecto pueden anadirse dentro de su directorio de implementacion a medida que evolucionen los servicios.

```bash
python3 -m compileall backend tests
```

## Actividad en GitHub

Puedes revisar mi actividad tecnica directamente desde GitHub:

| Area | Enlace |
| --- | --- |
| Perfil publico | [github.com/isaac1227](https://github.com/isaac1227) |
| Repositorios | [github.com/isaac1227?tab=repositories](https://github.com/isaac1227?tab=repositories) |
| Actividad reciente | [github.com/isaac1227?tab=overview](https://github.com/isaac1227?tab=overview) |
| Proyectos destacados | [`finanzas-personales`](./finanzas-personales), [`repunet`](./repunet), [`solidarianid`](./solidarianid) |

## Roadmap

- Anadir capturas de produccion y diagramas de arquitectura por proyecto.
- Ampliar los reportes experimentales de RepuNet con benchmarks y notas de reproducibilidad.
- Anadir ejemplos OpenAPI para servicios backend.
- Publicar entornos demo containerizados para proyectos seleccionados.
- Anadir notas de diseno de sistemas sobre autenticacion, persistencia y coordinacion distribuida.

## Contribucion

Las issues y pull requests son bienvenidas cuando mejoran la calidad documental, la claridad arquitectonica, la reproducibilidad o la organizacion del proyecto.

Antes de abrir una pull request:

- Mantener los cambios enfocados y faciles de revisar.
- Incluir documentacion cuando cambie comportamiento o estructura.
- Anadir tests o pasos de validacion para cambios de implementacion.
- Evitar commits con secretos, artefactos generados o archivos locales de entorno.

## Licencia

Este repositorio se publica bajo la [Licencia MIT](./LICENSE).
