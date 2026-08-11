# Protocolo `informefeliz`

## Estado y activación

Este protocolo pertenece al proyecto **Finanzas a Largo Plazo — ECO-132 — Economía — Grupo 80 — 2026.2**, pero permanece **inactivo por defecto**.

Se activa únicamente cuando el docente escribe explícitamente:

`protocolo informefeliz`

La activación es **de una sola ejecución** para el informe solicitado en ese turno o secuencia inmediata de trabajo. El protocolo se desactiva automáticamente después de entregar el informe correspondiente. No modifica el comportamiento normal de conversaciones posteriores.

También puede cancelarse expresamente mediante `cancelar protocolo informefeliz` o una instrucción equivalente.

## 1. Reconfirmación obligatoria del nombre completo

Antes de redactar, generar o versionar cualquier informe, el protocolo debe **reconfirmar siempre el nombre completo del alumno**, incluso si ese nombre ya apareció anteriormente en la conversación, en archivos o en otra misión.

No se genera el informe hasta recibir una confirmación explícita.

Si existe un nombre candidato, la pregunta será equivalente a:

> Confirmo antes de generar el informe: ¿el nombre completo del alumno debe figurar exactamente como **«NOMBRE COMPLETO»**?

Si no existe un nombre candidato, se solicitará el nombre completo.

El nombre confirmado se conservará **exactamente**, con sus tildes, mayúsculas/minúsculas y apellidos, dentro del documento.

## 2. Resolución de la misión y de las especificaciones vigentes

Al activarse, el protocolo debe determinar cuál es la misión correspondiente al informe y aplicar únicamente las especificaciones vigentes del proyecto.

Debe consultar, cuando sean relevantes:

- la misión activa;
- el programa rector vigente;
- la planificación didáctica aprobada;
- las reglas institucionales del proyecto;
- las instrucciones particulares de la actividad;
- la bibliografía y las fuentes vigentes;
- las reglas de privacidad, estilo, control de calidad y versionado.

No se mezclan silenciosamente requisitos de misiones o versiones anteriores.

Si más de una misión pudiera corresponder al informe y la misión correcta no pudiera resolverse con seguridad, el protocolo deberá pedir confirmación antes de generar la salida.

## 3. Nombre normalizado del archivo

La especificación del proyecto establece como estructura base para las evidencias PDF:

`YYYYMMDDa_nombrealumno_titulo.pdf`

El Protocolo `informefeliz` amplía esa convención añadiendo obligatoriamente la versión al final del nombre, inmediatamente antes de la extensión:

`YYYYMMDDa_nombrealumno_titulo_vXX.pdf`

Donde:

- `YYYYMMDDa` es el identificador cronológico de la misión o actividad correspondiente, respetando la letra asignada a esa misión;
- `nombrealumno` deriva del **nombre completo previamente confirmado**, normalizado para nombre de archivo, preferentemente en minúsculas, sin espacios, tildes ni caracteres especiales;
- `titulo` es la denominación breve aprobada por la misión o por las especificaciones de la actividad; si no existe una denominación expresa, se utiliza una descripción breve, inequívoca y coherente con la misión;
- `vXX` es la versión incremental de la salida dentro de esa misión, con dos dígitos: `v01`, `v02`, `v03`, etc.;
- `.pdf` es la extensión de la evidencia principal.

La versión debe ser siempre el **último componente del nombre antes de `.pdf`**.

Ejemplo:

`20260811a_juancarlosperezlopez_costodecapital_v01.pdf`

## 4. Regla de versionado `vXX`

El contador de versión se administra dentro de la misión correspondiente.

- La primera salida del informe es `v01`.
- Cada nueva generación o revisión que produzca un nuevo entregable incrementa exactamente en `+1`.
- No se reutiliza un número ya empleado.
- No se sobrescribe una versión anterior.
- Antes de generar el archivo, se verifica el historial disponible de la misión para determinar el siguiente `vXX`.
- Si no existe evidencia suficiente para conocer el último número utilizado, el protocolo debe preguntar o indicar explícitamente la incertidumbre antes de asignar la versión.

## 5. Identificación mínima dentro del informe

Todo informe generado bajo este protocolo debe contener, como mínimo y cuando corresponda al formato de la actividad:

- nombre y apellido completos del alumno, exactamente como fueron confirmados;
- asignatura: **Finanzas a Largo Plazo**;
- código: **ECO-132**;
- carrera: **Economía**;
- Facultad de Ciencias Económicas y Administrativas;
- Universidad Americana;
- grupo/sección: **Grupo 80 — Presencial**;
- docente: **Roger Román Armoa García**;
- fecha de realización;
- misión o actividad correspondiente;
- versión `vXX` del informe.

## 6. Requisitos particulares de la misión

Además de la identificación mínima, el informe debe satisfacer **todos los requisitos específicos de la misión o actividad**.

El protocolo debe construir una lista interna de requisitos antes de redactar y verificarla nuevamente antes de la entrega. No debe omitir silenciosamente un requisito de la misión.

Cuando una consigna requiera procedimientos, cálculos, imágenes, capturas, tablas, comparación de métodos, interpretación, conclusiones, síntesis personal, fuentes u otros elementos, estos deben incorporarse conforme a la consigna vigente.

## 7. Fuentes y trazabilidad académica

Los contenidos deben estar sustentados por las fuentes que correspondan a la actividad y al proyecto.

Cuando se utilicen fuentes bibliográficas:

- se identifica la obra y edición correctas;
- se conservan los rangos de páginas únicamente cuando hayan sido verificados para esa edición;
- no se trasladan páginas entre ediciones;
- se diferencia, cuando sea necesario, la paginación impresa de la numeración del visor PDF;
- se identifican claramente las fuentes consultadas;
- no se inventan citas, datos, fechas ni referencias.

Cuando el informe utilice inteligencia artificial o NotebookLM como herramienta de apoyo, el documento fuente y las referencias verificadas conservan la autoridad académica de la actividad.

## 8. Control de calidad financiero y metodológico

Antes de entregar el informe, el protocolo debe comprobar, cuando corresponda:

- coherencia y confiabilidad de los datos utilizados;
- fórmulas y operaciones;
- unidades y magnitudes;
- consistencia entre tasas y periodos;
- resultados numéricos;
- interpretación económica y financiera;
- relación entre resultados y conclusiones;
- fuentes utilizadas;
- correspondencia con la misión y con el programa vigente;
- ausencia de afirmaciones institucionales no sustentadas.

Se mantiene como lógica general del proyecto:

**datos confiables → formulación correcta → cálculo con herramientas adecuadas → interpretación → decisión fundamentada**.

Y como secuencia didáctica preferente:

**concepto → ejemplo desarrollado → ejercicio del estudiante → interpretación → decisión/recomendación**.

## 9. Estilo

Los informes deben utilizar español institucional neutro, claro y correcto.

Se evita:

- voseo rioplatense y argentinismos;
- redacción innecesariamente recargada;
- terminología inconsistente;
- afirmaciones administrativas no confirmadas;
- correcciones silenciosas de fuentes institucionales.

Cuando el informe transcriba información oficial, se preserva la terminología y el contenido de la fuente correspondiente.

## 10. Privacidad y seguridad

Los informes de estudiantes contienen datos identificables y **no deben subirse al repositorio GitHub público del proyecto**.

El protocolo no publicará en GitHub:

- nombres de estudiantes asociados con evidencias individuales;
- C.I.;
- correos o teléfonos;
- calificaciones;
- asistencia individual;
- formularios completados;
- firmas manuscritas reales.

Cuando una actividad enseñe eliminación de fondo o tratamiento gráfico de firmas, se utilizará una **firma ficticia, trazo de práctica u otro elemento creado para el ejercicio**, salvo instrucción privada específica y compatible con las reglas de seguridad.

## 11. Formato de salida

La evidencia principal generada bajo `informefeliz` será un **PDF**, salvo que la misión establezca expresamente otro formato.

Si se genera además una fuente editable (`.docx`, `.tex` u otra), deberá utilizar el mismo nombre base y la misma versión `vXX` cuando represente exactamente la misma iteración del informe.

Ejemplo:

- `20260811a_juancarlosperezlopez_costodecapital_v03.pdf`
- `20260811a_juancarlosperezlopez_costodecapital_v03.docx`

## 12. Control final obligatorio antes de entregar

Antes de presentar el archivo al docente, el protocolo verificará como mínimo:

1. nombre completo reconfirmado y escrito correctamente dentro del documento;
2. misión correcta;
3. título correcto de la actividad;
4. nombre del archivo conforme a `YYYYMMDDa_nombrealumno_titulo_vXX.pdf`;
5. versión `vXX` incremental correcta y ubicada al final;
6. identificación institucional vigente;
7. cumplimiento de todos los requisitos particulares;
8. fuentes y citas revisadas;
9. cálculos y conclusiones controlados cuando corresponda;
10. ausencia de datos personales innecesarios o firmas reales expuestas;
11. revisión visual del PDF para detectar cortes, desbordamientos, páginas vacías, textos superpuestos o problemas de legibilidad.

Si alguno de estos controles falla, el informe no se considera terminado.

## 13. Desactivación automática

Después de entregar el informe solicitado y comunicar su nombre de archivo y versión, el protocolo queda **automáticamente desactivado**.

No continúa activo para el siguiente mensaje, actividad, estudiante o misión.

Para volver a utilizarlo, el docente debe escribir nuevamente:

`protocolo informefeliz`

## Regla de precedencia

Este protocolo complementa las especificaciones existentes del proyecto para la generación de informes individuales.

En particular, la adición obligatoria de `_vXX` al final del nombre de archivo constituye una especificación posterior y específica para las salidas generadas mediante `informefeliz`.

Ante cualquier contradicción con una misión vigente, no se improvisará una conciliación: se identificará la discrepancia y se solicitará confirmación al docente antes de generar el informe.