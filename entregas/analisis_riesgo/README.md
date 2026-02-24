# Actividad práctica: _modelos de riesgo_: FMEA y OCTAVE Allegro

Si bien el dominio en el que nos desempeñamos y en el que este curso busca
profundizar es el de la computación, las _metodologías de modelos de
riesgo_ pueden aplicarse a situaciones de orígenes muy distintos.

Realizar análisis de riesgos puede entenderse como una _competencia
transversal_, que podemos aplicar en muy distintos contextos
organizacionales, e ilustra también cómo la seguridad de nuestros sistemas
y datos dependen de situaciones más allá de las meramente técnicas /
tecnológicas.

Les pido que realicen, para entregar el _martes 3 de marzo_ (mediante un
_pull request_ a este repositorio, realizado _antes del inicio de la clase_
de ese día), la siguiente evaluación de riesgos.

(PD- Admito, sí, que la siguiente redacción viene al >80% de un LLM 😉)

### Evaluación de Riesgos Comparada (Fuera del Aula de Cómputo)

**Objetivo:** Demostrar que los modelos de evaluación de riesgos son
herramientas de pensamiento universal. Los alumnos deberán seleccionar un
proceso cotidiano (**no informático**) y analizarlo bajo dos ópticas
distintas: la de un modelo de ingeniería de fallos
([FMEA](https://pmstudycircle.com/fmea/)) y la de un modelo orientado a
activos y contexto operativo ([OCTAVE
Allegro](https://www.sei.cmu.edu/library/introducing-octave-allegro-improving-the-information-security-risk-assessment-process/)).

**Instrucciones para los alumnos:**

**1. Selección del escenario (LIBRE)**

Elige un proceso, evento o actividad _de la vida real_ que te sea familiar
y que **no** esté directamente relacionado con el desarrollo de software o
sistemas informáticos. Algunas ideas para inspirarse (no limitativas):

*   La logística de organizar una fiesta sorpresa.
*   El proceso de preparar y servir comida en un restaurante
*   La mudanza de una casa o departamento.
*   La producción de un _fanzine_ periódico.
*   El mantenimiento de un jardín comunitario.
*   La organización de un viaje familiar al extranjero.

**2. Aplicación de FMEA (Enfoque en Fallos Técnicos/Proceso)**

Analiza tu escenario utilizando la lógica de **Failure Mode and Effects
Analysis**. Identifica:

*   **Modos de fallo:** ¿Qué puede salir mal en las tareas concretas?
    (Ej. en una mudanza: “se rompe un mueble”, “el camión no llega”, “se
    pierde una caja”).
*   **Causas:** ¿Por qué ocurriría ese fallo?
*   **Efectos inmediatos:** ¿Qué pasa justo después del fallo?

**3. Aplicación de OCTAVE Allegro (Enfoque en Activos y Contexto)**

Ahora analiza el **mismo** escenario, pero con la mentalidad de OCTAVE:

*   **Identifica el/los activos críticos:** ¿Qué es lo más valioso que hay
    que proteger en este proceso? No son cosas técnicas. (Ej. en la
    mudanza: “La colección de discos de vinilo heredada”, “El bienestar de
    la mascota durante el viaje”).
*   **Contenedores:** ¿Dónde están esos activos? ¿Quién tiene acceso a
    ellos?
*   **Escenarios de preocupación:** Piensa en amenazas, no solo
    fallos. (Ej. “Que el vecino se lleve una caja por error”, “Que el perro
    se escape durante la carga”, “Que los discos se deformen por el calor
    dentro del camión”).
*   **Impacto:** ¿Cuál sería el impacto real? (Ej. “Pérdida sentimental
    irreparable”, “Multa por extravío de mascota”, “Gastar más dinero en
    reemplazar lo dañado”).

**4. Entregable:**

Un documento breve (2-3 páginas) que contenga:

*   **Descripción del escenario** elegido.
*   **Tabla FMEA** con fallos, causas y efectos.
*   **Perfil OCTAVE** con activos, contenedores, escenarios de amenaza e
    impacto cualitativo.
*   **Reflexión final** ¿Qué diferencias encuentras entre la “fotografía”
    que da FMEA y la que da OCTAVE? ¿Cuál de los dos te ayudaría más a
    *decidir* dónde poner atención (o recursos) si tuvieras que repetir el
    proceso?

Entrega tu material en este repositorio, bajo
`entregas/analisis_riesgo/<tu_nombre>/`, mediante un _pull request_.
