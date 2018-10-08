#
## 1- Define "Ciclo de vida del software".
Es una secuencia estructurada y bien definida de las etapas en ingeniería de software para desarrollar el producto software deseado.
## 2- Nombra las fases principales del desarrollo de software y explica brevemente que se hace en cada una de ellas.
Podemos diferenciar varias fases:
##### Análisis de requisitos
Se extraen los requisitos y se analizan con el cliente. El resultado se plasma en el documento ERS (Especificación de Requerimientos del Sistema)
##### Diseño y arquitectura
Determina como funcionará de forma general sin entrar en detalles. Se definen los casos de uso para cubrir las funciones que realizará el sistema y se transforman las entidades definidas en el análisis de requisitos en clases de diseño, obteniendo un modelo cercano a la programación orientada a objetos.
##### Programación
Reducir un diseño a código puede ser la parte más obvia del trabajo de ingeniería de software, pero no es necesariamente la porción más larga. La complejidad y la duración de esta etapa está intimamente ligada al o a los lenguajes de programación utilizados.
##### Pruebas
Consiste en comprobar que el software realice correctamente las tareas indicadas en la especificación. Una técnica de prueba es probar por separado cada módulo del software, y luego probarlo de forma integral,para así llegar al objetivo. Se considera una buena practica el que las pruebas sean efectuadas por alguien distinto al desarrollador que la programó, idealmente un área de pruebas.
##### Documentación
Todo lo concerniente a la documentación del propio desarrollo del software y de la gestión del proyecto, pasando por modelaciones (UML), diagramas, pruebas, manuales de usuario, manuales técnicos, etc; todo con el propósito de eventuales correcciones, usabilidad, mantenimiento futuro y ampliaciones al sistema.
##### Mantenimiento
Mantener y mejorar el software para enfrentar errores descubiertos y nuevos requisitos. Esto puede llevar más tiempo incluso que el desarrollo inicial del software. Alrededor de 2/3 de toda la ingeniería de software tiene que ver con dar mantenimiento. Una pequeña parte de este trabajo consiste en arreglar errores, o bugs. La mayor parte consiste en extender el sistema para hacer nuevas cosas. De manera similar, alrededor de 2/3 de toda la ingeniería civil, arquitectura y trabajo de construcción es dar mantenimiento.

## 3- Explica brevemente en qué consiste el modelo en cascada cuando hablamos de desarrollo de software.
El desarrollo en cascada es aquel que ordena rigurosamente las etapas del proceso para el desarrollo del software, de tal forma que el inicio de cada etapa debe esperar a la finalización de la etapa anterior.
## 4- Ventajas e inconvenientes del modelo en cascada.
#### Ventajas:
- Se comienza con el software con bastante rapidez ya que se requiere un esfuerzo previo en la preparación.
- Estimar calendarios y presupuestos con mayor precisión
- Lograr un nivel de satisfacción del cliente más elevado que otros enfoques.

#### Desventajas:
- Alterar el diseño del proyecto en cualquier etapa es muy complicado.
- Una vez que una fase se ha completado, es casi imposible de realizar cambios.
- Es absolutamente necesario reunir todos los requisitos inicialmente.
- Muy difícil responder a los problemas que puedan surgir.
- Solucionar cualquier cuestión que se plantee, necesita gran cantidad de tiempo, esfuerzo y dinero.

## 5- ¿Qué se entiende por verificación? ¿Y por validación?
#### Verificación:
Proceso de determinar si los productos de una cierta fase del desarrollo de software cumplen o no los requisitos establecidos durante la fase anterior.

#### Validación:
Proceso de evaluación del software al final del proceso de desarrollo para asegurar el cumplimiento de las necesidades del cliente.

## 6- Explica como funciona el modelo de desarrollo mediante creación de prototipos.
En este modelo, se realiza un prototipo previo para probar varias suposiciones formuladas por analistas y usuarios. Su función principal es permitir a las personas usar el sistema propuesto para determinar que les gusta, que no les gusta e identificar las características que deben cambiar o añadir.

## 7- Explica como funciona el modelo espiral cuando se aplica al desarrollo orientado a objetos.
Los principios básicos del modelo en espiral son:
- La atención se centra en la evaluación y reducción del riesgo del proyecto dividiendo el proyecto en segmentos más pequeños y proporcionar más facilidad de cambio durante el proceso de desarrollo,  así como ofrecer la oportunidad de evaluar los riesgos y con un peso de la consideración de la continuación del proyecto durante todo el ciclo de vida.

- Cada viaje alrededor de la espiral atraviesa cuatro cuadrantes básicos: (1) determinar objetivos, alternativas, y desencadenantes de la iteración; (2) Evaluar alternativas; Identificar y resolver los riesgos; (3) desarrollar y verificar los resultados de la iteración, y (4) plan de la próxima iteración.

- Cada ciclo comienza con la identificación de los interesados y sus condiciones de ganancia, y termina con la revisión y examinación.

## 8- ¿Qué cuatro principios rigen el desarrollo ágil expresados en el Manifiesto Ágil?
- Individuos e interacciones sobre procesos y herramientas.
- Software funcionando sobre documentación extensiva.
- Colaboración con el cliente sobre negociación contractual.
- Respuesta ante el cambio sobre seguir un plan

## 9- ¿Qué es una historia de usuario?
Representación de un registro escrito en una o dos fases utilizando el lenguaje común del usuario. Las historias de usuario, son usadas en las metodologías de desarrollo ágiles para la especificación de requisitos.

## 10- Haz un resumen sobre que se entiende por Lean software y qué principios lo rigen
La idea principal de Lean Software consiste en eliminar el trabajo que no aporta valor al resultado final.

Los principios son:
- Eliminar los desperdicios
- Amplificar aprendizaje
- Decidir lo más tarde posible
- Entregar tan rápido como sea posible
- Capacitar al equipo
- Construir integridad intrínseca
- Visualizar todo el conjunto

## 11- KANBAN. Estudia las ventajas e inconvenientes de tener una pizarra web digital para la metodología Kanban.
#### Ventajas:
- Control del flujo de trabajo
- No necesita software adicional
- Promueve el trabajo en equipo
- Facilidad para añadir mejoras

#### Inconvenientes:
- Dificultad para realizar entregas a tiempo en grandes proyectos
- Falta de reglas
- Dificultad a la hora de preveer posibles problemas

## 12- KANBAN. Haz un resumen de la metodología Kanban e indica sus diferencias frente a SCRUM.
Es una metodología que se basa en gestionar el trabajo de una forma fluida, a menudo representada en un tablero Kanban para reflejar los procesos de su flujo de trabajo.

Duración:
S: Longitud fija es decir 2 semanas
K: Flujo continuo.

Entrega:
S: Al final de cada proyecto, si está aprobado por el propietario del producto.
K: Entrega continua o a decisión del equipo.

Roles:
S: Propietario del producto, scrum master, equipo de desarrollo.
K: No hay roles existentes. Algunos equipos consiguen la ayuda de un entrenador ágil.

Claves:
S: Velocidad
K: Tiempo de ciclo

Cambio de filosofía:
S: Los equipos deben esforzarse por no realizar cambios en el pronóstico.
K: El cambio puede ocurrir en cualquier momento.

## 13- SCRUM. Explica como funciona Scrum.
Es una metodología de trabajo que permite trabajar colaborativamente en equipo y obtener el mejor resultado posible de un proyecto.

Un proyecto se ejecuta en ciclos temporales y de duración fija, cada interacción tiene que proporcionar un resultado complejo, un incremento del producto final que sea susceptible de ser entregado con el mínimo esfuerzo al cliente cuando lo solicite.
El proceso parte de una lista de objetivos y requisitos priorizados del producto por el cliente.
Cada día el equipo realiza una reunión de sincronización (de 15 minutos máximo) delante de un tablero o pizarra. Cada miembro inspecciona el trabajo del resto para poder hacer adaptaciones necesarias para cumplir con los requisitos. En las reuniones, cada miembro del equipo responde tres cuestiones: ¿qué he hecho desde la última reunión?, ¿qué voy a hacer a partir de este momento?, ¿qué impedimentos tengo o voy a tener?
Durante la reunión el Scrum Master, se encarga de que el equipo cumpla con las normas.

## 14- SCRUM. Define los siguientes términos:
#### Product backlog:
Lista ordenada de todo lo que podrá necesitarse en el producto y es la única fuente de requisitos para cambios que se realizarán en el producto.

#### Sprint backlog:
Listado de tareas en el que se subdivide las historias de usuario que describen las funcionalidades que componen un proyecto.

## 15- CRUM. En la terminología Scrum qué terminos se utilizan como sinónimo de:
#### Jefe de proyecto.
Scrum Master
#### Cliente.
Product Owner
#### Equipo de desarrollo.
Development Team

## 16- SCRUM. Haz un resumen de los requisitos para poder utilizar Scrum.
- Cultura de empresa basada en el trabajo en equipo, delegación, creatividad y mejora continua.
- Compromiso del cliente en la dirección de los resultados del proyecto, gestión del ROI y disponibilidad para poder colaborar.
- Compromiso de la dirección de la organización para resolver los problemas endémicos y realizar cambios organizativos, formando equipos autogestionados y multidisciplinares y fomentando una cultura de gestión basada en una colaboración y en la facilidad llevada a cabo por líderes al servicio del equipo.
- Compromiso conjunto y colaboración de los miembros del equipo.
- Relación entre proveedor y cliente basada en ganr, colaboración y transparencia.
- Facilidad para realizar los cambios.
- Tamaño del equipo entre 5 y 9 personas.
- Equipo trabajando con el mismo espacio común.

## 17- XP. Explica los 5 valores de la Programación Extrema.
Se expone que:
Comunicación: Todos son parte del equipo y nos comunicamos cara a cara todos los días. Trabajamos juntos en todo, desde los requerimientos hasta la programación. En equipo crearemos la mejor solución al problema.
Simplicidad: Desarrollaremos lo que sea solicitado y necesario, pero no más que eso. De esa forma, se maximiza el valor de la inversión realizada. Nos dirigiremos a nuestro objetivo a pasos simples y pequeños, mitigando las fallas a medida que ocurran. Crearemos algo de lo cual podamos sentirnos orgullos y que pueda mantenerse en el largo plazo a costos razonables.
Retroalimentación:  Nos tomaremos seriamente los compromisos con el usuario establecidos en todas las iteraciones, entregando software en funcionamiento en cada una. Mostraremos al usuario nuestro software frecuentemente y de forma temprana, escuchando cuidadosamente sus observaciones y realizando los cambios que sean necesarios. Adaptaremos nuestros procesos al proyecto y no al contrario.
Respeto: Todos en el equipo dan y reciben el respeto que merecen como integrantes del equipo y los aportes de cada integrante son valorados valorados por todos. Todos contribuyen, así sea simplemente con entusiasmo. Los desarrolladores respetan la experticia de los clientes y viceversa. La Gerencia respeta el derecho del equipo de asumir responsabilidad y tener autoridad sobre su trabajo.
Coraje: Diremos la verdad en nuestros avances y estimados, no documentaremos excusas para el fracaso, pues planificamos para tener éxito. No tendremos miedo a nada pues sabemos que nadie trabaja solo. Nos adaptaremos a los cambios cuando sea que estos ocurran.

## 18- XP. ¿Cuáles son las características distintivas de XP frente a otras metodologías ágiles? Explícalas.
- Se considera al equipo de proyecto como el principal factor de éxito del proyecto.
- Software que funciona por encima de una buena documentación.
- Interacción constante entre el cliente y el equipo de desarrollo.
- Planificación flexible y abierta.
- Rápida respuesta a cambios.
