# Misión 20260809b — Clase de presentación de la asignatura

## Estado

**En curso**

## Fecha de la clase

**10/08/2026 — 18:15 a 21:15**

## Propósito

Preparar y desarrollar la primera clase de **FINANZAS A LARGO PLAZO — Grupo 80 — Economía — modalidad presencial — Sede ASU — 2026.2**, de modo que los estudiantes comprendan qué estudia la asignatura, cómo se trabajará durante el semestre, qué se espera de ellos y cuál es su punto de partida respecto de los conocimientos necesarios para abordar la Unidad I.

La clase debe ser coherente con la **Planificación Didáctica Semestral v30 aprobada** y con las reglas institucionales registradas en el proyecto.

## Objetivos de la misión

1. Presentar la asignatura, su propósito, las cinco unidades y la lógica general del semestre.
2. Explicar el enfoque de trabajo del curso: teoría aplicada, resolución de problemas, uso inteligente de herramientas computacionales e interpretación financiera.
3. Presentar la base bibliográfica y los materiales de apoyo que se utilizarán, incluyendo los **Cuadernos de Economía Aplicada** del docente.
4. Explicar de manera general la evaluación, distinguiendo diagnóstico, evaluación formativa y evaluación sumativa.
5. Realizar un diagnóstico inicial no calificativo para identificar conocimientos previos y necesidades de nivelación.
6. Introducir conceptualmente la Unidad I — **Costo de capital y presupuesto de capital** — sin convertir la primera clase en una exposición extensa de contenido técnico.
7. Cerrar la clase con una síntesis clara de qué deberán poder hacer los estudiantes a medida que avance la asignatura.

## Mensaje central para los estudiantes

**Finanzas de largo plazo no consiste solamente en calcular indicadores: consiste en obtener datos confiables, construir correctamente el problema financiero, calcular con herramientas apropiadas, interpretar el resultado y tomar una decisión fundamentada.**

Este mensaje resume el enfoque didáctico de los materiales propios del docente:

**concepto → ejemplo desarrollado → ejercicio del estudiante → interpretación → decisión/recomendación**.

## Metodología operativa de esta misión

La clase de presentación se construirá mediante un **documento fuente redactado en LaTeX**. Ese archivo será el material maestro editable del proyecto y se trabajará paso a paso dentro de una carpeta específica del repositorio que el docente creará para esta misión.

El flujo de trabajo será:

**LaTeX → PDF → Google NotebookLM → preguntas de los estudiantes → contraste crítico mediante Adversarial Pass Protocol**.

### Fuente LaTeX

- El contenido de la clase se redactará y versionará en LaTeX.
- El archivo `.tex` será la fuente reproducible para futuras modificaciones del material.
- El trabajo se realizará progresivamente, revisando contenido, estructura y claridad antes de compilar la versión utilizada en clase.

### PDF para los estudiantes y para NotebookLM

- El LaTeX se compilará a **PDF**.
- El docente cargará ese PDF como fuente en **Google NotebookLM**.
- Los estudiantes interactuarán con NotebookLM formulando ellos mismos preguntas sobre la asignatura y sobre el contenido del documento.
- El docente entregará a los estudiantes el **PDF**, no será necesario distribuirles el archivo fuente `.tex`.
- Para esta actividad, el PDF constituye la **fuente académica canónica**: las respuestas generadas por NotebookLM son interpretaciones de esa fuente y no sustituyen el contenido del documento.

### Adversarial Pass Protocol

Además del PDF, los estudiantes recibirán un archivo `.txt` con el **Adversarial Pass Protocol**.

Su función dentro de la actividad será fomentar una interacción crítica con la IA: los estudiantes podrán utilizar el protocolo para cuestionar, verificar y auditar las respuestas obtenidas, en lugar de aceptarlas de manera automática.

El uso conjunto de PDF + NotebookLM + Adversarial Pass Protocol busca que el estudiante practique tres capacidades desde la primera clase:

1. formular buenas preguntas;
2. contrastar la respuesta de una IA con una fuente explícita;
3. detectar errores, omisiones, supuestos o respuestas insuficientemente sustentadas.

### Regla metodológica de fuente

**La IA es una interfaz de consulta; el documento fuente conserva la autoridad académica de la actividad.** Si NotebookLM produce una respuesta que no puede sustentarse en el PDF, dicha respuesta deberá considerarse una ampliación, inferencia o posible error y no contenido oficial de la asignatura.

Esta metodología no depende de una plataforma específica como principio pedagógico. NotebookLM se utiliza en esta misión porque resulta práctico para la dinámica de aula y para el acceso disponible a los estudiantes.

## Estructura didáctica de la clase

### Inicio

- Bienvenida y presentación del docente y de la asignatura.
- Ubicación de Finanzas de Largo Plazo dentro de la formación del economista.
- Presentación del objetivo general del curso y de las cinco unidades.
- Explicación breve de la dinámica del semestre, materiales, herramientas y forma de trabajo.
- Presentación de la dinámica PDF + NotebookLM + Adversarial Pass Protocol.
- Inicio del diagnóstico de conocimientos previos a través de las preguntas que formulen los propios estudiantes y de la interacción en clase.

### Desarrollo

- Exploración del documento fuente mediante preguntas formuladas por los estudiantes en NotebookLM.
- Observación docente de los tipos de preguntas, conceptos recuperados y dificultades detectadas.
- Conversación diagnóstica y resolución breve de preguntas/problemas sobre conocimientos previos relevantes: valor del dinero en el tiempo, tasas, flujos, estados financieros, riesgo y rendimiento.
- Presentación de la lógica de las decisiones financieras de largo plazo: inversión, financiamiento, riesgo, estructura de capital, valoración y dividendos.
- Presentación del criterio de calidad de datos: antes de calcular un indicador, verificar que la información sea coherente y económicamente plausible.
- Explicación de que se permite y fomenta el uso de planillas de cálculo, programación y otras herramientas apropiadas; el foco está en formular, verificar, interpretar y justificar.
- Aplicación del Adversarial Pass Protocol sobre algunas respuestas de la IA para mostrar que una respuesta plausible no debe aceptarse sin contrastación.
- Puente hacia la Unidad I: costo de capital, tasa de descuento, presupuesto de capital y creación de valor.

### Cierre

- Síntesis conjunta de la lógica general de la asignatura.
- Discusión breve sobre qué respuestas de la IA estuvieron bien sustentadas, cuáles requirieron corrección y por qué.
- Verificación formativa informal: qué conceptos resultaron familiares y cuáles requerirán nivelación.
- Presentación de los materiales iniciales y de la siguiente clase.
- Registro docente de necesidades de ajuste detectadas en el diagnóstico, sin publicar información individual en GitHub.

## Diagnóstico inicial

El diagnóstico será **no calificativo** y no se reducirá necesariamente a una prueba escrita. Una parte importante del diagnóstico surgirá de las preguntas que los propios estudiantes formulen al documento mediante NotebookLM y de la manera en que evalúen críticamente las respuestas.

Áreas sugeridas:

- valor del dinero en el tiempo;
- tasas de interés y tasa de descuento;
- lectura básica de balance y estado de resultados;
- diferencia entre utilidad y flujo de efectivo;
- riesgo y rendimiento;
- uso de planillas de cálculo;
- capacidad para formular preguntas técnicas;
- capacidad para contrastar una respuesta de IA con una fuente;
- interpretación de un resultado financiero y formulación de una recomendación.

El objetivo no es clasificar a los estudiantes, sino determinar desde dónde comenzar y qué conocimientos conviene recuperar antes de avanzar.

## Materiales de apoyo previstos

- Documento fuente de presentación redactado en **LaTeX**.
- **PDF compilado** del documento de presentación, distribuido a los estudiantes y cargado como fuente en Google NotebookLM.
- Archivo **`.txt` del Adversarial Pass Protocol** como material complementario para auditoría de respuestas.
- Planificación Didáctica Semestral 2026.2 v30 como marco docente.
- Programa oficial de la asignatura.
- **Cuadernos de Economía Aplicada, Volumen 1 — Conceptos fundamentales de finanzas de largo plazo**.
- **Cuadernos de Economía Aplicada, Volumen 2 — Ejercicios sobre finanzas de largo plazo**.
- Van Horne & Wachowicz (2010) como referencia académica principal.
- Brigham & Houston (2020) como referencia académica complementaria.
- Pizarra, proyección y herramientas computacionales según disponibilidad.

## Entregables previstos de esta misión

- Fuente LaTeX versionada del documento de presentación.
- PDF compilado utilizado como fuente académica para NotebookLM y como material entregado a los estudiantes.
- Archivo `.txt` del Adversarial Pass Protocol utilizado en la actividad.
- Guion/estructura de conducción de la clase, si resulta necesario durante la preparación.
- Registro en el proyecto de cualquier regla o ajuste pedagógico que surja de la experiencia.

Los entregables creados conjuntamente se incorporarán al repositorio conforme a las reglas del proyecto.

## Criterios de calidad

La clase de presentación debe:

- ser clara y breve en lo administrativo;
- mostrar desde el comienzo el carácter aplicado de la asignatura;
- evitar sobrecargar la primera sesión con teoría;
- convertir a los estudiantes en participantes activos mediante la formulación de preguntas;
- enseñar desde el inicio que una respuesta de IA debe contrastarse con una fuente;
- conectar los conocimientos previos con los problemas financieros que se estudiarán;
- permitir al docente obtener información diagnóstica útil;
- dejar explícito que el uso de herramientas computacionales está permitido y que la interpretación financiera es central;
- mantener coherencia con la planificación v30 y la normativa institucional.

## Privacidad

El diagnóstico puede generar información sobre conocimientos o desempeño de estudiantes. Esa información se utilizará para ajustar la enseñanza, pero **no se registrará de forma identificable en el repositorio público**. Solo podrán documentarse conclusiones agregadas o pedagógicas sin datos personales.

La interacción con herramientas externas deberá evitar la inclusión innecesaria de datos personales de estudiantes en las consultas.

## Próximo paso

El docente creará la carpeta de trabajo para LaTeX. A partir de allí se redactará paso a paso el documento fuente, se revisará su contenido y finalmente se compilará el PDF que se utilizará como fuente de NotebookLM en la clase de presentación.
