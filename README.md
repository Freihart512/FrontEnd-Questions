# Entrevista técnica Front End Development

Las entrevistas técnicas en la industria de desarrollo de software en general
tienen por objetivo identificar el mejor talento tech. Esto implica diferentes
estrategias de acuerdo a la madurez y contexto de la empresa.

## Guía para Entrevistadores

El objetivo principal de una entrevista técnica es conocer más de cerca el
potencial técnico de la candidata.

Para esto hay tres puntos importantes que contrastar y observar:

- Conocimiento/entendimiento del lenguaje.
- Método de análisis y solución de problemas. ¿Cómo se enfrentó al ejercicio?
- Comunicación. La claridad para explicar su entendimiento de terminos técnicos,
  experiencia y propuesta de solución.

### El proceso

El proceso podemos dividirlo en:

- **Contexto**

  Es importante dejarle claro a la candidata el proceso de la entrevista: _"Te
  comento el proceso, inicialmente te haré una serie de preguntas conceptuales,
  y luego continuamos con uno o dos ejercicios de código"_.
  Además es importante recordarle que esta es una entrevista de práctica,
  es sobre todo para identificar que haría en una entrevisa real,
  cómo se comportaría si esta nerviosa, o que recursos puede usar para controlar
  o manejar esas situaciones.

- **Presentación**

  En este punto, te presentas como entrevistadorx, a continuación preguntas por
  la experiencia en desarrollo de la candidata. Trata que su presentación sea
  breve, clara y aporte al puesto al que postula.

- **Trivia / Preguntas Teórico Conceptuales**

  Algunas frases anteriores pueden hacer sentir más cómodas a las personas de
  manera que puedan expresar lo que entienden  libremente.
  Al momento de hacer las preguntas, recordar vocalizar los términos con
  claridad, y si es necesario escribirlas para que quede claro el término que se
  le está preguntando.

  Este es un buen punto para identificar el nivel de confianza con la que llega
  lx candidata. Esto te ayudará a decidir un ejercicio de calentamiento.

  Puedes usar las preguntas en
  [Preguntas Conceptuales](0-preguntas-conceptuales.md).

- **Ejercicio de calentamiento**

  El ejercicio de calentamiento tiene como objetivo que lx candidata comprenda
  el proceso que seguirán para el ejercicio. Además de generarle confianza.

  Estos ejercicios no necesitan tener restricciones y la idea es que la
  respuesta sea relativamente directa.

  Algunos ejemplos:

  1. Imagina el siguiente ejercicio:

     > Escribe una función que dado un arreglo de planetas, imprima en consola
     > `Hola, soy el planeta [nombre] y estoy en la posición [x]`
     > Para cada planeta.

     Si bien este ejercicio es directo, no implica complejidad extra ni nada por
     el estilo, solo implica entendimiento del lenguaje y puedes preguntarle por
     más de una forma de hacerlo.

  2. El ejercicio de [`Stringitis`](1-stringitis.md) puede ser usado para estos
     casos, si es que no agregas restricciones.

- **Ejercicio**

  Este ejercicio normalmente tiene dos factores de complejidad. Esta complejidad
  suele ser el diseño de la solución (_cómo afronta un problema desconocido_).
  Y en algunos casos, si el entrevistador lo considera necesario algún tipo de
  restricción al uso regular del lenguaje. Algunas sugerencias de restricciones:

  - Uso de papel/lápiz o algún tipo de documento que no tenga intellisense para
    completar el código.

  - Restricción de uso algunas funciones como `.map`, `.forEach` o similares.
    Sin ir a extremos. Si lo usa, que explique el funcionamiento de la función.

  - Si la candidata llegó a una solución, puedes preguntar por casos en los que
    esta solución fallaría o encontraría problemas.

  - Si la candidata llegó a una solución, puedes sugerir que pruebe una solución
    alternativa, por ejemplo: usando conceptos de programación funcional como
    [method chaining](https://medium.com/backticks-tildes/understanding-method-chaining-in-javascript-647a9004bd4f)
    o [partial application](https://medium.com/@JosephJnk/partial-function-application-in-javascript-and-flow-7f3ca87074fe).

  - Si la candidata llegó a una solución, puedes proponer que pruebe una
    solución en la que alguno de los métodos que usó no existiera. Recuerda, no
    te vayas al extremo. No es que tenga que reescribir JavaScript.

  Un punto interesante de observar es que tan abierta esta la persona a recibir
  pistas, guías o recomendaciones, que tan cómoda esta en actividades similares
  como pair programming.

  Quizás sea importante que le recuerdes el tiempo que le queda para que lo
  tenga presente.

- **Cierre**

  Este puede ser un buen momento para indicar posibles soluciones, dar feedback
  a la candidata y observar cómo responde a ese feedback.

### Mitos

- **¿Pasa o no pasa?**

  Si es una contratación para Laboratoria pensaría lo siguiente:

  - ¿Si estuviera en mis manos, la contrataría en este momento?
  - ¿Me gustaría trabajar con esta persona?
  - ¿Aportará en el equipo al que entra?

  No siempre tienen que ser Si directamente en los tres, porque depende mucho
  de la empresa y el equipo, al final de cuentas, y esto termina de
  responderse en un consenso con todos los involucrados.

  Para el caso de nuestras candidatas en **_Job Application_**, la idea es si
  *Iteraría* o *Seguiría Iterando*.

  - **Sigue iterando porque No me repondió xxxx como lo dice exactamente en MDN**

    No buscamos observar que tan buena memoria tiene la estudiante, sino su
    entendimiento de dichos conceptos. Aquí lo importante es ver si no te esta
    "floreando", sino saber si en realidad entiende dicho concepto y/o su uso.
  - **No terminó el ejercicio, que itere.**

    Esto puede variar de ejercicio a ejercicio. Pero en términos generales aquí
    es importante observar cómo se enfrenta al problema y qué solución le da.
    Algunas sugerencias para manejar los tiempos:

    - Si ya está por llegar a la solución _"Karina, llevas muy buen avance y veo
      que te falta muy poco para poder terminarlo. El tiempo ya no nos da
      oportunidad de continuar pero me gustó como afrontaste el problema...
      (inserte aquí el feedback)"_.
    - Si aún le falta bastante _"Karina, creo que aquí podemos parar la
      entrevista porque el tiempo ya no nos da oportunidad de continuar. Pero no
      te preocupes, estas entrevistas son justo para conocer... (inserte aquí el
      feedback)"_.

- **No puedes googlear, si googleas no sabes.**

  Hola, todos googleamos, no es un _memory contest_. Sobretodo cosas de
  sintaxis, no es un problema googlear. Tampoco es que busque directamente el
  problema. Observar claramente qué busca. Nos sirve para evaluar cómo
  investiga.
