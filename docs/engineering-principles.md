# Principios de Ingeniería

## Valores por Defecto Orientados a Producción

- Preferir límites de servicio explícitos frente a acoplamiento oculto.
- Mantener la configuración de entorno fuera del código fuente.
- Validar entradas cerca del límite del sistema.
- Hacer que la configuración local sea reproducible.
- Mantener la CI lo bastante rápida para ejecutarse en cada pull request.

## Calidad Backend

- Diseñar APIs alrededor de contratos estables y modelos de error claros.
- Usar autenticación y autorización de forma consistente.
- Mantener el acceso a base de datos aislado tras capas de servicio o repositorio.
- Documentar supuestos operativos y modos de fallo.

## Calidad de Investigación

- Separar experimentos del código de aplicación.
- Registrar supuestos de datasets, simulación y configuración.
- Preferir scripts de validación reproducibles frente a evaluación manual.
- Tratar resultados negativos y limitaciones como información técnica útil.

## Calidad Documental

- Escribir documentación para mantenedores, revisores y futuros colaboradores.
- Mantener los README de proyecto suficientemente breves para revisarlos con rapidez.
- Enlazar detalles técnicos profundos desde `docs/`.
- Usar capturas y diagramas para aclarar comportamiento real, no como decoración.
