## Descripción

Como su propio nombre indica, el contrabando de solicitudes funciona mediante la captura y división de cadenas HTTP. Al dividir la solicitud capturada, se introducen partes extra en el cuerpo de la original, que entran en el servidor, ocultas o “de contrabando”. El contenido “extra” incluido en estas solicitudes suele servir para la ejecución de comandos sin autorización, para conseguir privilegios, leer datos o editarlos. Todas las solicitudes mediante protocolo HTTP quedan expuestas a este tipo de ataque, por lo que se recomienda, en la medida de lo posible, el uso de SSL. 

## Patrón de Ataque

**Investigar el entorno** de destino para determinar las tecnologías empleadas, como los tipos de navegadores, servidores web, firewalls, etc. Esto puede ayudar a determinar en cómo se procesan las solicitudes entrantes en dicho entorno.
Usar navegadores sin control estricto de solicitudes o herramientas de testeo de solicitudes personalizadas, para el envío de cabeceras erróneas. 

Esto permite la **división de las solicitudes** y el **envío de solicitudes maliciosas** mediante la introducción de fragmentos codificados o cabeceras extra.

## Arquitecturas Vulnerables

Servidores web que acepten y procesen los encabezados de las solicitudes HTTP manipuladas por el usuario.
