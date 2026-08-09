# Misión 20260809b — Clase de presentación de la asignatura

## Estado

**En curso — preparación avanzada y material de trabajo aprobado por bloques**

La misión permanecerá abierta hasta la realización y cierre de la primera clase del **10/08/2026**. La preparación documental realizada el 09/08/2026 queda registrada como avance aprobado, pero el cierre definitivo de la misión dependerá de la experiencia real de aula y de los ajustes posteriores que resulten necesarios.

## Fecha de la clase

**10/08/2026 — 18:15 a 21:15**

## Propósito

Preparar y desarrollar la primera clase de **FINANZAS A LARGO PLAZO — Grupo 80 — Economía — modalidad presencial — Sede ASU — 2026.2**, de modo que los estudiantes comprendan qué estudia la asignatura, cómo se trabajará durante el semestre, qué se espera de ellos y cuál es su punto de partida respecto de los conocimientos necesarios para abordar la Unidad I.

La clase debe ser coherente con la **Planificación Didáctica Semestral v30 aprobada**, con el programa oficial y con las reglas institucionales registradas en el proyecto.

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

El enfoque didáctico operativo se resume en:

**concepto → ejemplo desarrollado → ejercicio del estudiante → interpretación → decisión/recomendación**.

## Metodología operativa de esta misión

La clase de presentación se construye mediante un **documento fuente redactado en LaTeX**. El flujo de trabajo previsto es:

**LaTeX → PDF → Google NotebookLM → preguntas de los estudiantes → contraste crítico mediante Adversarial Pass Protocol**.

### Fuente LaTeX

- El contenido de la clase se redacta y revisa en LaTeX.
- El archivo `.tex` constituye la fuente reproducible del material.
- El trabajo se realiza progresivamente, revisando contenido, estructura, citas, consistencia institucional y claridad antes de compilar la versión final utilizada en clase.
- El borrador actual utiliza `longtable`; durante la revisión se detectó que el paquete no estaba cargado en una compilación previa y se incorporó `\usepackage{longtable}` en la fuente de trabajo.

### PDF para los estudiantes y para NotebookLM

- El LaTeX se compilará a **PDF**.
- El docente cargará ese PDF como fuente en **Google NotebookLM**.
- Los estudiantes interactuarán con NotebookLM formulando preguntas sobre la asignatura y sobre el contenido del documento.
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

## Estructura didáctica de la clase

### Inicio

- Bienvenida y presentación del docente y de la asignatura.
- Ubicación de Finanzas de Largo Plazo dentro de la formación del economista.
- Presentación del objetivo general del curso y de las cinco unidades.
- Explicación breve de la dinámica del semestre, materiales, herramientas y forma de trabajo.
- Presentación de la dinámica PDF + NotebookLM + Adversarial Pass Protocol.
- Inicio del diagnóstico de conocimientos previos.

### Desarrollo

- Exploración del documento fuente mediante preguntas formuladas por los estudiantes en NotebookLM.
- Observación docente de los tipos de preguntas, conceptos recuperados y dificultades detectadas.
- Conversación diagnóstica sobre conocimientos previos relevantes: estados financieros, valor del dinero en el tiempo, tasas, flujos, riesgo y rendimiento.
- Presentación de la lógica de las decisiones financieras de largo plazo: inversión, financiamiento, riesgo, estructura de capital, valoración y dividendos.
- Presentación del criterio de calidad de datos: antes de calcular un indicador, verificar que la información sea coherente y económicamente plausible.
- Uso de planillas de cálculo, programación y otras herramientas apropiadas, manteniendo el foco en formular, verificar, interpretar y justificar.
- Aplicación del Adversarial Pass Protocol sobre algunas respuestas de la IA.
- Puente hacia la Unidad I: costo de capital, tasa de descuento, presupuesto de capital y creación de valor.

### Cierre

- Síntesis conjunta de la lógica general de la asignatura.
- Discusión breve sobre qué respuestas de la IA estuvieron bien sustentadas, cuáles requirieron corrección y por qué.
- Verificación formativa informal de conocimientos que requieren nivelación.
- Presentación de los materiales iniciales y de la siguiente clase.
- Registro docente de necesidades de ajuste sin publicar información individual en GitHub.

## Diagnóstico inicial

El diagnóstico será **no calificativo**. El documento de trabajo contiene una indagación inicial de **18 ítems** con tres niveles de autopercepción: **Lo entiendo bien / Más o menos / Nada de nada**.

Los ítems cubren, entre otros:

- balance general y estado de resultados;
- utilidad contable y flujo de efectivo;
- coherencia de datos financieros;
- valor presente y valor futuro;
- tasas y correspondencia con periodos;
- flujo de fondos de proyectos;
- costo de capital, deuda y capital propio;
- CAPM y WACC;
- VAN, TIR, IR y Payback;
- escenarios y sensibilidad;
- riesgo y rendimiento;
- correlación, diversificación y portfolios;
- apalancamiento;
- FCF, NOF, tasa de descuento y valor residual;
- uso de planillas de cálculo.

El instrumento incluye además un espacio para que el estudiante identifique el número del tema que considera que necesita reforzar más.

## Puntos de control de la primera clase

El material incorpora los siguientes puntos de referencia operativa:

- **18:15** — inicio de la clase y presentación general.
- **18:45** — finalización prevista de la presentación e inicio de la indagación.
- **19:15** — cierre previsto de la indagación y presentación de fuentes/NotebookLM.
- **19:45** — receso.
- **20:00** — regreso del receso.
- **20:15** — actividad práctica con NotebookLM.
- **20:45** — revisión crítica mediante protocolo adversarial.
- **21:00** — síntesis.
- **21:15** — finalización.

Los horarios son referencias de conducción, no límites rígidos.

## Calendario académico y de evaluaciones incorporado

El material registra, como fechas previstas y sujetas a confirmación institucional:

- Primer examen parcial: **14/09/2026**.
- Segundo examen parcial: **12/10/2026**.
- Tercer examen parcial: **23/11/2026**.
- Examen final: **14/12/2026**.
- Examen extraordinario: **21/12/2026**.

También se incorporó el calendario de clases de los lunes y la secuencia prevista de las cinco unidades.

## Carga académica

Se corrigió el bloque principal para utilizar exclusivamente la carga oficial de la asignatura:

- **51 horas totales**;
- **36 horas teóricas**;
- **15 horas prácticas**;
- clases presenciales los lunes de **18:15 a 21:15**.

No se atribuyen a la asignatura créditos, 72 horas independientes ni 144 horas totales sin una fuente institucional de la Universidad Americana que los establezca.

### Pendiente importante

El borrador de trabajo conserva todavía una subsección heredada posterior al bloque de carga académica que menciona **4 horas de trabajo acompañado, 4 horas de trabajo independiente, 8 horas semanales y un normalizador de 27 horas por crédito de FP-UNA**. Esa subsección no corresponde a la Universidad Americana y deberá depurarse antes de considerar el PDF como versión final.

La referencia bibliográfica de FP-UNA se considera **legada y temporal**, no fuente rectora de esta asignatura.

## Relación con la carrera

Se sustituyó la antigua sección transversal de carreras de FP-UNA por una sección específica de **Relación con la carrera**, vinculando Finanzas a Largo Plazo con la formación del estudiante de **Economía** y con decisiones sobre inversión, riesgo, financiamiento, portfolios, valoración y dividendos.

## Control de calidad

El control de calidad de los trabajos se amplió para contemplar, según la actividad:

- procedencia y calidad de los datos;
- fórmulas, cálculos y resultados;
- coherencia entre tasas y periodos;
- interpretación financiera;
- correspondencia entre conclusiones y análisis;
- fuentes y referencias bibliográficas.

El proceso es iterativo: presentación → revisión → observaciones → corrección → nueva versión cuando resulte necesario.

## Identificación de los trabajos

Se aprobó la sustitución del antiguo bloque **Datos del estudiante** por **Datos de identificación del trabajo**, alineándolo con la estructura que se exige posteriormente en las entregas.

El encabezado modelo contiene:

- nombre y apellido;
- asignatura: Finanzas a Largo Plazo;
- carrera: Economía;
- Facultad de Ciencias Económicas y Administrativas;
- Universidad Americana;
- Grupo 80 — Presencial;
- docente: Roger Román Armoa García;
- fecha.

Se eliminan del encabezado el **número de C.I.** y la **firma manuscrita real**, de acuerdo con el criterio de minimización de datos y con la advertencia de seguridad ya incluida en el documento para trabajos almacenados en carpetas compartidas.

La sección posterior de requisitos de identificación se alinea con la misma estructura.

## Bibliografía y citas

Se realizó una pasada específica de citación sobre la fuente LaTeX sin modificar el contenido sustantivo de los bloques revisados.

La bibliografía de trabajo de la clase contempla:

- programa oficial de Finanzas a Largo Plazo;
- Planificación Didáctica Semestral v30;
- calendario académico presencial 2026.2;
- Resolución CSU N.º 016/2026;
- referencia institucional al Modelo de Aprendizaje Basado en Competencias (MAC);
- Google NotebookLM;
- Van Horne & Wachowicz (2010);
- Brigham & Houston (2020);
- Cuadernos de Economía Aplicada, Vols. 1–5;
- Markowitz (1952);
- Sharpe (1964);
- Modigliani & Miller (1958, 1963);
- Miller & Modigliani (1961).

Las antiguas citas vinculadas a FP-UNA deben desaparecer a medida que se depure el contenido heredado que todavía las necesita.

## Recursos gráficos aprobados

Durante la preparación se aprobaron dos recursos gráficos utilizados por la fuente LaTeX:

- `portada_presentacion_asignatura_v1.png` — portada de **Finanzas de Largo Plazo — Presentación de la asignatura**.
- `proceso_iterativo.png` — gráfico **Proceso iterativo de elaboración y revisión**.

La fuente requiere que ambos archivos estén presentes en la carpeta de compilación.

## Materiales de apoyo previstos

- Documento fuente de presentación redactado en LaTeX.
- PDF compilado del documento de presentación para estudiantes y NotebookLM.
- Archivo `.txt` del Adversarial Pass Protocol.
- Planificación Didáctica Semestral 2026.2 v30.
- Programa oficial de la asignatura.
- Cuadernos de Economía Aplicada, Volúmenes 1–5.
- Van Horne & Wachowicz (2010).
- Brigham & Houston (2020).
- Pizarra, proyección y herramientas computacionales según disponibilidad.

## Entregables de la misión

- Fuente LaTeX versionada del documento de presentación.
- Bibliografía BibLaTeX/BibTeX utilizada por el documento.
- PDF compilado utilizado como fuente académica para NotebookLM y como material entregado a los estudiantes.
- Recursos gráficos utilizados por la fuente.
- Archivo `.txt` del Adversarial Pass Protocol utilizado en la actividad.
- Registro de ajustes pedagógicos posteriores a la primera clase.

## Criterios de calidad

La clase de presentación debe:

- ser clara y breve en lo administrativo;
- mostrar desde el comienzo el carácter aplicado de la asignatura;
- evitar sobrecargar la primera sesión con teoría;
- convertir a los estudiantes en participantes activos;
- enseñar desde el inicio que una respuesta de IA debe contrastarse con una fuente;
- conectar conocimientos previos con problemas financieros;
- permitir al docente obtener información diagnóstica útil;
- mantener explícito que el uso de herramientas computacionales está permitido y que la interpretación financiera es central;
- mantener coherencia con la planificación v30, el programa y la normativa institucional.

## Privacidad

El diagnóstico puede generar información sobre conocimientos o desempeño de estudiantes. Esa información se utilizará para ajustar la enseñanza, pero **no se registrará de forma identificable en el repositorio público**.

No deben publicarse en GitHub nombres de estudiantes, C.I., firmas reales, calificaciones, asistencia individual, correos, teléfonos ni formularios completados.

La interacción con herramientas externas deberá evitar la inclusión innecesaria de datos personales.

## Avance aprobado — 09/08/2026

Quedan registrados como aprobados durante la preparación:

- portada de la presentación;
- gráfico del proceso iterativo;
- estructura de cinco unidades;
- explicación simplificada de IA y NotebookLM;
- criterio de selección y control de fuentes;
- indagación inicial de 18 ítems;
- horario de receso y puntos de control;
- calendario de evaluaciones;
- calendario académico y calendario de clases;
- bloque principal de carga académica oficial;
- relación con la carrera de Economía;
- control de calidad de los trabajos;
- estructura de identificación de los trabajos;
- estrategia bibliográfica y de citación.

## Próximos pasos

1. Depurar la subsección heredada de carga académica/créditos de FP-UNA que todavía permanece en el borrador.
2. Realizar una compilación completa y sin errores del LaTeX con bibliografía y recursos gráficos presentes.
3. Revisar visualmente el PDF completo.
4. Cargar el PDF definitivo en NotebookLM.
5. Preparar/distribuir el Adversarial Pass Protocol en `.txt`.
6. Desarrollar la primera clase del 10/08/2026.
7. Registrar después de la clase únicamente conclusiones pedagógicas agregadas y ajustes para futuras sesiones.
