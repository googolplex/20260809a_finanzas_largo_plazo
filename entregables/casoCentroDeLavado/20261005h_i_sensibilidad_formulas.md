# 20261005h-i — Sensibilidad con fórmulas explícitas

## Archivos

- `20261005h_CasocentroDeLavado_estacionamiento.pdf`: solución desarrollada.
- `20261005i_formulario_CasocentroDeLavado_estacionamiento.pdf`: formulario del estudiante, sin cambios de contenido respecto de la iteración anterior.

## Único cambio académico

La solución principal incorpora las fórmulas explícitas utilizadas para obtener los resultados de sensibilidad.

### Sensibilidad al precio

`Ingreso_park = N × P × O × 12`

`C_park = Ingreso_park - 18`

`FC = C_park + 126,36 + 64,68 - 96 - 45`

`VAN = -400 + FC × [1/(1,12) + 1/(1,12)^2 + 1/(1,12)^3 + 1/(1,12)^4] + 40/(1,12)^4`

### Sensibilidad a ocupación

`Ingreso_park = 20 × 0,5 × O × 12`

Se recalculan luego el flujo total y el VAN con la misma estructura.

### Caída de una contribución

`C'_j = 0,90 C_j`

`FC' = FC_base - 0,10 C_j`

El VAN se recalcula usando el flujo anual modificado y el valor residual de G. 40 millones.

### Shock conjunto

`FC' = 0,90 × (C_park + C_lav + C_det) - 96 - 45`

### Aumento del alquiler

Si el alquiler anual pasa de 96 a 144:

`FC' = 90 + 126,36 + 64,68 - 144 - 45 = 92,04`

`VAN' ≈ -95,02`

## Control de versión

No se modificaron los demás elementos de contenido, estructura ni diseño del formulario.

Próximo prefijo disponible: `20261005j_`.
