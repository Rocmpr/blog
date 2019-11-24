La mayoría de los programadores de este inicio de siglo hemos sido formados y hemos trabajado con metodologías ágiles, incluso sin haber sido conscientes de ello. Esta es una consecuencia directa de las grandes crisis del software de finales de los años 90, cuando un grupo de influyentes desarrolladores1 pusieron en común una serie de prácticas con la intención de superar sus respectivas capacidades, sentando así las bases de su manifiesto por un desarrollo ágil del software (Agile). Desde entonces, universidad y empresa han actualizado progresivamente sus métodos de trabajo, con el objetivo de desprenderse de procedimientos rígidos y adaptarse así a los cambios que impone el avance tecnológico.

Hoy día se aplican metodologías ágiles en sectores muy diferentes de aquel que las originó. Es cierto que transmiten la idea de ser un conjunto de prácticas capaces de llevar a éxito un proyecto en situaciones complejas o cambiantes. Pero Agile es mucho más. Como paradigma del desarrollo de software, sus métodos cubren todas las fases del ciclo de vida de un proyecto (requisitos, planificación, diseño, desarrollo, testeo e implementación), facilitando además la gestión de riesgos y la mejora continua. Agile puede aplicarse a grupos pequeños, que normalmente responden bien a situaciones cambiantes y mantienen una cultura de respuesta frente a estas. Y también permite a grupos grandes, capaces de desarrollar un mayor número de funcionalidades, corregir su cultura de demanda y restricciones. Esto es posible gracias a que las metodologías ágiles permiten ajustar las prácticas y los artefactos más beneficiosos a cada terreno de acción. Conocer bien los métodos que abarcan sus diferentes marcos de trabajo, es vital para entender cómo y para qué sirve Agile.

# Una cuestión de enfoque

Según el tipo de proyecto a gestionar, se pueden usar unos métodos u otros para facilitar la toma de requerimientos y mejorar la asimilación de cambios. Un par enfoques de trabajo adaptados con ayuda de Agile, como el desarrollo por características y la integración continua, son ejemplo suficiente de cómo pueden gestionarse proyectos de software con la ayuda de las metodologías ágiles.

`CI. Continous integration.` Se refiere al desarrollo de prototipos funcionales que van incrementando su número de características a lo largo de distintas iteraciones (sprints). Este es un enfoque adaptativo, ya que las nuevas funcionalidades se adecuan al prototipo y a los cambios que va sufriendo a lo largo del proyecto. Un marco de trabajo que suele funcionar bien en el desarrollo a medida, donde la definición de requerimientos iniciales puede no ser muy precisa.

`FDD. Feature-driven development.` Es un método de trabajo mediante características, donde se diseñan las distintas funcionalidades, se definen y se trabajan por separado. Este es un enfoque claramente predictivo, ya que permite planificar exactamente qué requerimientos se completan en un momento determinado. Suele encajar bien en fases de proyecto avanzadas, cuando las principales funcionalidades ya están desarrolladas y se apuesta por la mejora continua del producto. También puede utilizarse en desarrollos a medida en los que los requerimientos estén claramente definidos.

Con independencia del enfoque utilizado, Agile ofrece una serie de herramientas o artefactos dirigidos a la normalización de requerimientos y características. Si se observa con detenimiento el ciclo de vida del desarrollo de software, es posible determinar cuáles de estos artefactos encajan en el marco de trabajo elegido.

### Desarrollo mediante características
1. Se toman requisitos por cada característica.
2. Se desarrollan características de forma independiente pero ordenada.
3. Las características se testean por separado.
4. Se despliegan conjuntos de características.

### Integración continua
1. Se toman requisitos para una versión inicial.
2. Se desarrolla una versión inicial completamente funcional.
3. Se testea cada versión funcional.
4. Se despliega cada versión funcional.

Algo que comparten todos los marcos de desarrollo, es que las versiones evolucionan añadiendo correcciones y nuevas características. Aquí es dónde se encuentra la verdadera batalla de los desarrolladores. Ya que el aumento de características va ligado a un aumento de la hediondez y por tanto, a un aumento de la complejidad. Entendiendo complejidad por dificultad técnica, no de tiempos o esfuerzos.

 
# Toma de Requisitos

La toma de requisitos es parte vertebral de cualquier proyecto de desarrollo de software, ya que facilita el negociado de las distintas funcionalidades que estarán presentes en el producto final. Existen multitud de métodos, pero todos conservan estructuras y procesos comunes para la identificación y descripción de características.

Básicamente, una toma de requisitos ha de contemplar las siguientes operaciones:

* Entrevistas con los interesados.
* Redacción de restricciones del proyecto.
* Redacción de requerimientos funcionales.

Los requerimientos o especificaciones de desarrollo se convierten a veces en un torrente difícil de canalizar. Para dirigirlos correctamente hacia un flujo de trabajo auto-organizado, se necesita una rápida respuesta de desarrollo y aligerar el peso de la documentación.

# Planificación

Por regla general, las planificaciones y las grandes especificaciones iniciales de los proyectos, suelen producir gran cantidad de residuos que se traducen en una merma económica y técnica. Por esto, desde una visión Agile se considera de gran importancia el llamado salto de fe inicial, lo que significa que al inicio de un proyecto de desarrollo, se ha de desviar el foco de atención hacia el logro de mayor importancia. Esto puede traducirse como la búsqueda de mejores definiciones de los requerimientos o todo lo contrario, la del aseguramiento de la arquitectura para el entorno de despliegue deseado.

Por otro lado, cabe destacar que toda planificación ha de reflejar, no sólo los tiempos de operación, sino también los de testeo y entrega. Y además, el equipo debe mantener un calendario de reuniones activo, una práctica que aporta salubridad al proyecto.

# Desarrollo

El ciclo de vida de las metodologías ágiles de desarrollo tiene un carácter repetitivo, iterativo e incremental. Mediante prácticas como Scrum, Kanban, Lean o XP, se facilita el desarrollo de funcionalidades que son añadidas al producto durante repeticiones cortas, pero efectivas.

`Scrum.` Es un marco de trabajo (<a href="https://en.wikipedia.org/wiki/Jeff_Sutherland" target="_blank">Sutherland</a>-<a href="https://en.wikipedia.org/wiki/Ken_Schwaber" target="_blank">Schwaber</a>) pensado para entornos que necesitan mejorar su rendimiento o intervenir gran cantidad de procesos. Funciona liberando pequeños incrementos del producto dentro de unos tiempos muy marcados. Para ello, establece una cultura de roles y fomenta reuniones semanales para la puesta en común de las tareas y la revisión continua de los desarrollos.

`Kanban.` Es un método de origen japonés (<a href="https://es.wikipedia.org/wiki/Taiichi_Ohno" target="_blank">Ohno</a>-<a href="https://web.archive.org/web/20140114161522/http://www.djaa.com/principles-kanban-method" target="_blank">Anderson</a>) basado en el principio de la entrega a tiempo. En la práctica, trata de reducir el trabajo en curso (WIP) desarrollando prioritariamente las funcionalidades requeridas y sin incurrir en el desperdicio de la multitarea. Para la gestión de su ciclo de vida se ayuda de un tablero cartas (de ahí su nombre), que representan el producto a desarrollar. Cada incremento consume cartas del tablero, que son repuestas con nuevos requerimientos. Se crea así un sistema de demanda que funciona en entornos bien organizados.

`Lean.` Adaptación occidental (<a href="https://procognita.com/post/mary-poppendieck-four-metaphors-of-lean-403/" target="_blank">Poppendieck</a>) al campo del desarrollo de software, del modelo japonés de gestión del conocimiento (<a href="https://es.wikibooks.org/wiki/Gesti%C3%B3n_del_conocimiento/Modelo_de_creaci%C3%B3n_del_Conocimiento/Teor%C3%ADa_de_creaci%C3%B3n_de_conocimiento_por_Nonaka_y_Takeuchi" target="_blank">Nonaka-Takeuchi</a>), que aboga por la reducción constante de los residuos, el desarrollo de lo estrictamente útil y la mejora constante del flujo productivo. Lean plantea un ciclo de vida basado en el principio del mínimo viable, que se refiere a la entrega de versiones tan pronto como sea posible, dejando para un momento posterior la escritura de cualquier documentación o la adquisición de compromisos vinculantes sobre cuestiones arquitectónicas.

`XP.` Extreme programming (<a href="https://es.wikipedia.org/wiki/Kent_Beck" target="_blank">Beck</a>) es un método que prima la adaptabilidad sobre todo. En la práctica, asume la variabilidad de los requerimientos y la ineludible existencia de errores, por lo que no presta atención a la documentación previa. En cambio, utiliza ciclos cortos de desarrollo y pruebas de aceptación, que van completando funcionalidades de manera continua. Promueve la programación entre pares, valorando la calidad del código escrito, por encima de la inmediata afectación a la productividad.

# Pruebas

Agile promueve una cultura de testeo, donde cada iteración pasa por un ciclo de prueba unitaria y cada entrega supera una fase de aceptación por parte del cliente. Sea cual sea el modelo de gestión, las distintas fases de testeo siempre tienen por objeto la corrección de todos los errores y la aceptación de las funcionalidades desarrolladas. Todo para tratar de conseguir un producto lo más robusto posible, en el menor tiempo posible.

# Despliegue

Este es el punto crítico de todo desarrollo, ya que la implantación en un cliente supone la mayoría de las veces, añadir restricciones al sistema. Estas restricciones producen nuevos evolutivos que, a veces generan sobrecostes. Por tanto, para salvar posibles cuellos de botella durante las operaciones de despliegue, conviene la práctica de metodologías como DevOps (<a href="https://es.wikipedia.org/wiki/DevOps" target="_blank">Wasna-Debois</a>), que posibilitan el entendimiento de los desarrolladores con los administradores de IT. Punto crucial para un desarrollo más productivo, ya que conseguir una infraestructura ágil donde desplegar el software con garantías de calidad y tiempo, libera más horas para la programación.

# Mantenimiento

Las operaciones de mantenimiento del software comienzan tras el paso a producción del producto, con el objetivo de alargar la vida útil de las aplicaciones. Agile distingue entre:

`Mantenimiento Predictivo.` Es el que mejora el producto de manera planificada, adelantándose a los problemas de seguridad y/o funcionalidad que puedan surgir. Integra perfecciones en el sistema como resultado de una cultura de respuesta.

`Mantenimiento Adaptativo.` Las modificaciones correctivas y evolutivas llegan a demanda, como consecuencia del reporte de incidencias o la solicitud de mejora del cliente.

# Conclusiones

Como filosofía de desarrollo de software, Agile impulsa el estudio de metodologías de trabajo aplicables a sus distintas fases: toma de requisitos, planificación, desarrollo, pruebas, despliegue y mantenimiento. La aplicación de estas metodologías implica la adopción de sus prácticas y el uso de sus artefactos, para diseñar un marco de gestión de proyectos a medida.

Una forma ágil de afrontar la gestión de un proyecto de desarrollo de software sería la siguiente:

* Elegir el enfoque de gestión adecuado a nuestro proyecto.
* Realizar una planificación inicial abierta.
* Determinar acertadamente el alcance de los requisitos a tomar.
* Asegurar desde el principio el entorno de despliegue.
* Decidir sobre la metodología de desarrollo a seguir.
* Completar pruebas en cada iteración.
* Diseñar y ejecutar las operaciones de despliegue de manera correcta.
* Decidir la operativa para el sostenimiento de la vida útil del producto.
