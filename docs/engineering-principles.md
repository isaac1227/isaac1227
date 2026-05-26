# Principios de Ingenieria

## Valores por Defecto Orientados a Produccion

- Preferir limites de servicio explicitos frente a acoplamiento oculto.
- Mantener la configuracion de entorno fuera del codigo fuente.
- Validar entradas cerca del limite del sistema.
- Hacer que el setup local sea reproducible.
- Mantener la CI lo bastante rapida para ejecutarse en cada pull request.

## Calidad Backend

- Disenar APIs alrededor de contratos estables y modelos de error claros.
- Usar autenticacion y autorizacion de forma consistente.
- Mantener el acceso a base de datos aislado tras capas de servicio o repositorio.
- Documentar supuestos operativos y modos de fallo.

## Calidad de Investigacion

- Separar experimentos del codigo de aplicacion.
- Registrar supuestos de datasets, simulacion y configuracion.
- Preferir scripts de validacion reproducibles frente a evaluacion manual.
- Tratar resultados negativos y limitaciones como informacion tecnica util.

## Calidad Documental

- Escribir documentacion para mantenedores, revisores y futuros colaboradores.
- Mantener los README de proyecto suficientemente breves para escanearlos.
- Enlazar detalles tecnicos profundos desde `docs/`.
- Usar capturas y diagramas para aclarar comportamiento real, no como decoracion.
