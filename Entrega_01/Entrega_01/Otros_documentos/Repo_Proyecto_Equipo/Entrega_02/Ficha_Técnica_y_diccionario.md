# Ficha Técnica y Diccionario de Datos

## Fuente
Ministerio del Medio Ambiente de Chile – SINCA (https://sinca.mma.gob.cl/index.php/region/index/id/V)

## Metodología
Se descargaron los promedios anuales de contaminantes por estación. Se seleccionó PM2.5 como contaminante principal. Se limpiaron duplicados y se estandarizaron nombres de estaciones.

## Alcance
Datos de tres estaciones de Santiago (Pudahuel, Las Condes, Independencia) entre 2015 y 2025.

## Características
- Datos oficiales, confiables y replicables.
- Periodicidad anual.
- Algunas estaciones no tienen datos completos para todos los contaminantes.

## Diccionario de datos
| Variable       | Descripción                          | Tipo     | Valores posibles | Observaciones |
|----------------|--------------------------------------|----------|-----------------|---------------|
| estacion       | Nombre de la estación de monitoreo   | Texto    | Pudahuel, Las Condes, Independencia | Puede ampliarse |
| anio           | Año de medición                      | Entero   | 2015–2025       |               |
| contaminante   | Tipo de contaminante                 | Texto    | PM2.5           | Se priorizó PM2.5 |
| promedio_anual | Promedio anual del contaminante (µg/m³) | Numérico | ≥0              | Valores oficiales |
