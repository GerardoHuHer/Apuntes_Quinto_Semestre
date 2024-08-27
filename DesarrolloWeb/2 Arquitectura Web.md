## ¿ Qué es la arquitectura web ? 
- Se refiere al *diseño estructural de aplicaciones* y sistemas web, incluyendo los componentes, la disposición, y la interacción entre ellos.
- La arquitectura web tiene como objetivo asegurar que los sitios y aplicaciones web sean eficientes, escalables, seguros y fáciles de mantener.

**Inyección de código:** Cuando mediante un script alguien ajeno a tú página logra extraer información.

## Principios clave de la arquitectura web
##### Cliente - Servidor
La base de la comunicación web.
Los clientes (generalmente navegadores web) solicitan recursos, y los servidores responden a esas solicitudes proporcionando los recursos solicitados.

## Capas de la arquitectura
#### Capa de presentación: 
	Es la interfaz y experiencia del usuario, dónde se maneja la interacción directa con el usuario.
Lazy loading: Solo se carga lo que se necesita.
1. Se ve bien.
2. Interactivo 
3. Funciona bien. 
#### Capa de lógica de negocio:
	Procesa la lógica de la aplicación, reglas de negocio y gestiona las interacciones entre la presentación y la base de datos.
	Se distribuye tanto en el backend como en frontend
#### Capa de datos:
	Se encarga del almacenamiento, recuperación y gestión de datos. Incluye bases de datos y otros sistemas de almacenamiento de datos.

## Modelos de despliegue
#### La manera en que las aplicaciones y servicios son organizados, distribuidos y ejecutados en los entornos de desarrollo, prueba y producción.

Estos modelos determinan cómo se estructuran los componentes de una aplicación y cómo se comunican entre sí, influyendo en aspectos como las escalabilidad, el rendimiento, la mantenibilidad y la seguridad del sistema.

**Monolítico:**
La aplicación se construye y despliega como una sola unidad. Todos lo componentes de la aplicación (frontend, backend, base de datos) están integrados y ejecutados juntos.
- Ventajas: Simplicidad en el desarrollo y despliegue, fácil de probar y depurar.
- Desventajas: Difícil de escalar, mantener y actualizar debido a su tamaño y complejidad.
**Microservicios:**
La aplicación se divide en servicios pequeños, independientes y desplegables de forma autómata. Cada microservicio tiene su propia logica y bases de datos

## Modelos derivados:
**Nube:** Servidores de terceros. Las aplicaciones se despliegan en servicios de nube pública (como AWS, Azure, Google Cloud), nube privada e híbrida (combinación de nubes públicas y privadas).
- Ventajas: Escalabilidad bajo demanda, alta disponibilidad, reducción de costos de infraestructura.
- Desventajas: Dependencia del proveedor de la nube, posibles problemas de latencia y seguridad.
**Funciones(serverless):** Las aplicaciones se dividen en funciones pequeñas que se ejecutan en respuesta de eventos específicos, sin necesidad de gestionar servidores (usando plataformas como AWS lambda, Azure Functions). *Tú haces una petición y esa función te responde*.
- Ventajas: Escalabilidad automática, pago por uso, simplicidad en las gestión de infraestructura.
- Desventajas: Restricciones en el tiempo de ejecución, latencia en el inicio de funciones, imitaciones en el control sobre el entorno de ejecución; la arquitectura tiene muchas dependencias.
**Edge Computing:** Procesamiento y almacenamiento de datos se realizan en dispositivos o servidores más cercanos al lugar donde se generan los datos, en lugar de en un centro de datos centralizado. *Todos funcionan como microservidores*, me conecto al servidor más cercano a mi, no hay un servidor central como tal, puede haber un servidor central pero le quitamos peso.
- Ventajas: Reducción de latencia, mejora en el rendimiento de aplicaciones en tiempo real.
- Desventajas: Complejidad en la gestión de infraestructura distribuida, desafios en la sincronización y consistencia de datos.

Tarea:
Investigar códigos de error de las peticiones http unos 5 de cada petición.
100 5 más importantes
200 5 más importantes
300 5 más importantes
400 5 más importantes
500 5 más importantes

## HTTP  (HyperText Transfer Protocol)
Protocolo fundamental utilizado en la WWW para la transferencia de información entre los navegadores web (clientes) y los servidores web.

Define cómo los mensajes son formateados y transmitidos, y cómo los navegadores y servidores deben responder a varias solicitudes.

#### Stateless
Protocolo sin estado.
Cada solicitud del cliente se realiza de forma independiente, sin conservar información sobre las solicitudes anteriores.
Requiere que los desarrolladores gestionen la persistencia de datos mediante cookies, sesiones o tokens.

#### Importancia
- Interoperabilidad: Comunicación entre diferentes sistemas y dispositivos de la web.
- Flexibilidad: Soporta una amplia variedad de tipos de datos (HTML, JSON, XML, imágenes, videos ) y métodos de transferencia.
- Simplicidad: Sin librerías, paquetes o integraciones.
## Métodos de solicitud: 
1. GET: Solicita un recurso del servidor con parámetros en la url. El más común.
2. POST: Envía datos al servidor con los parámetros ocultos. Típicamente usado para formularios.
3. PUT: Actualiza un recurso existente en el servidor.
4. HEAD: Similar a los GET pero solo solicita los encabezados de la respuesta.
5. DELETE: Elimina un recurso en el servidor.
6. OPTIONS: Describe las opciones de comunicación para el recurso destino.
7. PATCH: Aplica modificaciones parciales a un recurso.
## Estructura de un mensaje HTML 
#### Solicitud HTTP
Incluye una línea de solicitud (método, URI, versión HTTP), encabezados de solicitud (información adiciconal como el cuerpo de un contenido, agente de usuario), y un cuerpo de solicitud (opcional, usualmente en solicitudes POST).
#### Respuesta HTTP
Incluye una línea de estado (versión HTTP, código de estado, frase de razón), encabezados de respuesta (información adicional como tipo de contenido, longitud de contenido), y un cuerpo de respuesta (los datos solicitados).

URL: Uniform Resource Locator.
URN: Uniform Resource Number.
URI: Uniform Resorce Identifier.


