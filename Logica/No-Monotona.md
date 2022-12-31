# Trabajo de LPO

## Especificaciones

### Seleccion

- Durante los últimos 120 años se han realizado varias criticas a la lógica clásica, en muchos casos rechazando algunos de sus principios o axiomas.
- Explicar sus características y sus diferencias respecto a la lógica clásica
- Inteligencia artificial -> Las Logicas No-Monotonas intentan ser mas fieles al razonamiento humano. Hay que presentar sus puntos claves y la manera que se diferencia de la lógica clásica
- Hay que mencionar los fundadores y motivos principales para abandonar los principios clásicos
- Cabe mencionar aplicaciones, como por ejemplo en filosofía, informática o inteligencia artificial

### Valoracion

- Powerpoint 6-8 transparencias. Grabado con audio aprox 5 minutos.
- Voz de una o varias personas.
- Valora :
  - Relevacia y temas elegidos
  - Calidad de la informacion y precision de explicaciones
  - Aspecto visual (ordenacion y estructura)
  - Materia creada independientemente y presentada de forma original

## Logica

- Fuentes :
  - [**Wikipedia**](https://en.wikipedia.org/wiki/Non-monotonic_logic)
  - [**Stanford.edu**](https://plato.stanford.edu/entries/logic-nonmonotonic/)

### Introduccion

#### Logica Clásica

- En su incertidumbre, el hombre ha intentado dar respuestas a las preguntas que se plantea. Respuestas que sean coherentes y que no contradigan a otras respuestas. Una forma de **formalizar** su conocimiento.
- En esta premisa, nace la **logica**. Proporcionando al hombre una forma estructurada de razonar.
- El hombre crea **axiomas**, un conjunto de reglas para razonar, cuyo proposito es mantener la coherencia de sus premisas y conclusiones.
- El hombre logra plasmar sus conocimientos en un **lenguaje**. Ahora puede expresar sus ideas y razonamientos de forma **precisa** y **coherente**.

$$ \forall x\ \in\ Seres\ Vivos\newline Mamifero(x)\rarr Viviparo(x)$$

- Todo conocimiento es formalizado con un valor de verdad inmutable. La logica clásica solo conoce los extremos de la verdad y graba a fuego sus conclusiones.

#### Logica No-Monotona

- La logica clásica tan solo es capaz de representar hasta donde llegue su conocimiento. No puede representar la incertidumbre, la duda o la ambiguedad.
- La logica clásica no es capaz de aprender y adaptarse a nuevas situaciones, de admitir errores, y por tanto no es capaz de representar el conocimiento humano.

$$ \forall x\ \in\ Seres\ Vivos\newline Mamifero(x)\rarr Viviparo(x)\newline x : Ornitorrinco\newline Mamifero(x) \land \lnot Viviparo(x)$$

- Razonamientos como estos, en ambitos donde la base de conocimiento incrementa y puede ser contradictoria, no pueden ser representados por la logica clásica.
- Hace falta un sistema logico, capaz de anular sus propias conclusiones ante nuevas evidencias.
- Por ello nace el sistema logico no monotono, cuyas componentes principales son :
  - **Razonamiento por defecto**
  - **Razonamiento abductivo**
  - **Revision de creencias**
- Este nuevo sistema logico es capaz de lidiar con varias limitaciones de la logica clásica y aplicar su uso en la inteligencia artificial.

##### Definicion

- La logica no monotona es un sistema logico en el cual la relacion de consecuencia logica no es monotona.
- En un sistema logico monotono, incorporar una nueva formula a una teoria nunca provoca una reduccion de las consecuencias previas.
- Esto no es asi en la logica no monotona, añadir una nueva formula puede negar una conclusion previa y las consecuencias derivadas de esta, produciendo asi una reduccion.
- Esto se conoce como razonamiento anulable (defeasible reasoning).

##### Origen

- Para ver el origen de la logica no monotona, hay que ver el origen de su fundamento, el razonamiento anulable.
- Las primeras ideas de razonamiento anulable se remontan a la filosofia griega, concretamente a Aristoteles, ante el intento de aplicar la logica y la filosofia a la vida cotidiana.
- Es en los años 70, cuando John L. Pollock con su obra **Conocimiento y Justificacion** (1974) populariza la terminologica de socavar y refutar, acercando el razonamiento anulable a los otros filosofos. Aunque no fue tarea facil debido a que la fundacion del formalismo en la logica clasica es la contraparte al argumento que Pollock intentaba acercar.
- Fueron investigadores de la inteligencia artificial los que posteriormente trabajarían en mayor profundidad por desarrollar la logica no monotona, siendo los principales aportadoes John L. Pollock y Donald Nute.
- A dia de hoy, la logica no monotona tiene un amplio uso en la inteligencia artificial, la filosofia y la informatica.

##### Naturaleza

- La logica no monotona busca ser mas cercana al razonamiento humano, es por esto que se basa en la idea de que el conocimiento humano es incierto y que el hombre es capaz de aprender y adaptarse a nuevas situaciones.
- Con este fin, hace uso de uno de sus pilares, el razonamiento por defecto, capaz de crear conclusiones iniciales que pueden ser anuladas por nuevas evidencias, pero que permiten avanzar en el razonamiento y actuar en consecuencia.
- "A las mujeres les gusta el chocolate, asique a mi esposa le gustara que le compre chocolate" es un ejemplo que mantiene su validez a menos que no le guste el chocolate, con lo cual posteriormente se puede anular la conclusion. Se ha creado una conclusion a partir de informacion parcial.
- Para representar esto en logica de proposiciones se le suele añadir un modal M (modalidad) a la formula, indicando que la formula es una conclusion por defecto y se puede desechar si se encuentra una contradiccion.

