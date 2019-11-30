La visión del desarrollo de aplicaciones ha evolucionado, como era de esperar, hacia una normalidad divulgativa. Facilitadora de conocimientos y adelantos. Hoy día, el uso generalizado de servidores propios y componentes de terceros confiables, han permitido a los profesionales de IT inspeccionar y controlar por sí mismos cualquier configuración. Sin embargo, pese a estas condiciones favorables, los riesgos de seguridad en los cada vez más complejos entramados de redes, abruma.

La carrera por el control de las redes de información, lleva a los profesionales de IT a demandar seguridad a los desarrolladores. Crear seguridad frente a una _contra-seguridad_, carente de normas y por tanto capaz de avanzar a mayor velocidad, puede parecer una batalla perdida. Ahora bien, el verdadero reto de la seguridad no es el enfrentamiento en desventaja, sino la protección y la prevención de riesgos. Aspectos que se alcanzan con capacidad de análisis, medios de control y procedimientos de actuación. 

Todo internet son aplicaciones que aceptan o envían solicitudes de información y recaban datos privados de los usuarios. En muchos casos, aplicaciones hospedadas en _infraestructuras sin esfuerzo_ o servidores de _instalación desatendida_ que no facilitan el control de las configuraciones. Aplicaciones que han evolucionado gracias a contenidos compartidos y código de terceros.  Desplegadas en repositorios, por lo general abiertos, donde rara vez se presta atención a quienes los proporcionan. Así que nos movemos a diario en un medio digital expuesto a la _ejecución de código desconocido_, a veces de manera inevitable y otras de manera superflua.

Como elemento de necesidad, destaca la programación de la seguridad desde el corazón de las aplicaciones. Equiparándola en importancia con elementos deseables. Como la compatibilidad entre aplicaciones y dispositivos, diseño, funcionalidades y tiempos de carga. La seguridad como aspecto inseparable de la calidad.

## Reconocer al enemigo

Comprender el delito informático resulta esencial de cara a la protección de datos valiosos, sobre todo cuando estos datos involucran a individuos, organizaciones o asuntos económicos. El delito se ha profesionalizado y ha multiplicado los motivos para _hackear_ redes. El soborno, el fraude de identidad o de tarjetas de crédito, el mercado negro, la guerra por el control de la información, el mercado o los territorios. Generan ilegalmente ganancias materiales, políticas y sociales.

Los delincuentes suelen usar el producto de los ataques para para sí mismos o  para venderlo con aparente impunidad en la web profunda, donde simplemente, se pierde trazabilidad. Los expertos de seguridad no conocen los métodos que se usan para infiltrarse en las redes de computadoras, pero si conocen que el 80% de las causas más comunes afectan a las bases de datos (_hijacking, injections_), al tránsito de la información (_phishing, pharming, DoS_) o al servicio de código malicioso (_malversiting_); mientras que el 20% restantes tienen que ver con el acceso físico a las computadoras. En dos palabras **hacking** y **leaking**.

## Adaptarse al entorno

Una aproximación a la seguridad de las aplicaciones requiere abarcar contextos distintos: como la protección personal, la protección de la información, la codificación segura, el control de transacciones o el seguimiento de vulnerabilidades. 

La propia protección de los usuarios y desarrolladores es el primer paso para comenzar a hablar de seguridad informática. En el caso de estos últimos es vital, ya que además de garantizar la seguridad de sus aplicaciones deben garantizar la seguridad de la información que manejan. Lo ataques dirigidos a desarrolladores son más comunes de lo que se piensa, ya que son en muchos casos, puerta y llave para la información de sus clientes. Así que asegurar nuestro propio entorno de trabajo y el acceso a redes, son claves para evitar que los datos que manejamos se vean comprometidos. 

Ya que no existen soluciones globales, mantener una cultura de seguridad tanto en el ámbito privado como en el laboral, es fundamental para la auto-protección. Hay que tener muy claro que el mero hecho de tener acceso a información, nos convierte en objetivos convincentes.

Un listado básico de pasos a completar para asegurarnos una buena auto-protección, sería el siguiente:

*	Revisar lo que se está haciendo actualmente e identificar las actividades y procesos de riesgo, de cara a aplicar mecanismos que nos ayuden en su control.
*	Usar gestores de contraseñas y estancar el acceso a los distintos sistemas bajo nuestro control, utilizando contraseñas complejas para cada servicio.
*	Asegurar y mantener las máquinas con las que se trabaja, usando como mínimo un antivirus, un anti-malware y un limpiador de registro.
*	Protegerse contra la exposición en redes y la ingeniería social, mediante campañas de revisión de la privacidad y el análisis de presencia.
*	Establecer protocolos para la instalación de software de terceros, ya sea para uso propio o en el desarrollo. 
*	Usar herramientas de acceso seguro a internet, con sesiones privadas y conexiones seguras.

## Programar seguro

Unos criterios básicos de codificación segura son la base para crear aplicaciones autoprotegidas. Es preferible que se programe usando una convención de código propia y que se tengan en cuenta las siguientes recomendaciones:

*	Utilizar autenticación de doble factor (A2F) y tratar de sustituir la seguridad de autenticación del código por capas de servicio intermedias o middleware.
*	No utilizar código de terceros si no podemos asegurar que se ejecutan procesos confiables.
*	Facilitar la aplicación de directivas y utilizar seguridad basada en roles o permisos.
*	Establecer capas de control de permisos como filtros previos a la ejecución de código en general.
*	No abusar de almacenamiento en variables públicas o limitarlo a datos no confidenciales.
*	Controlar todos los inputs/outputs de usuario, así como el acceso de estos a recursos (URL, uploads, etc.)
*	Utilizar métodos de criptografía internos para la información de persistencia.
*	Utilizar cifrado de conexiones a bases de datos.
*	Utilizar include de archivos de código cliente en lugar de escribirlo directamente.
*	No escribir datos de usuario en código que no forme parte del ensamblado.
*	Publicar código a través de protocolos seguros de comunicación.

Una última práctica a tener en cuenta es el seguimiento de vulnerabilidades. Lo que nos ayudará a asimilar e implementar estándares de seguridad para disminuir riesgos conocidos. Organizaciones como OWASP y CAPEC sirven perfectamente a sus cometidos de promover el conocimiento de los problemas y defectos que pueden afectar a nuestras aplicaciones. Aunque no todos los patrones pueden reproducirse o catalogarse, es conveniente la consulta periódica de las publicaciones que puedan afectarnos, ya que avisan de defectos que pueden aprovechar terceros. 

La seguridad de las aplicaciones no es un producto que pueda comprarse. Es más bien una cultura que hay adoptar y promover. Hay que programa seguror y alegrarse de la buena suerte.


