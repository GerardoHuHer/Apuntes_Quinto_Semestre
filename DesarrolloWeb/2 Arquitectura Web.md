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
**Nube:** Las aplicaciones se despliegan en servicios de nube pública (como AWS, Azure, Google Cloud), nube privada e híbrida (combinación de nubes públicas y privadas).
- Ventajas: Escalabilidad bajo demanda, alta disponibilidad, reducción de costos de infraestructura.
- Desventajas: Dependencia del proveedor de la nube, posibles problemas de latencia y seguridad.
**Funciones(serverless):** Las aplicaciones se dividen en funciones pequeñas que se ejecutan en respuesta de eventos específicos, sin necesidad de gestionar servidores (usando plataformas como AWS lambda, Azure Functions). *Tú haces una petición y esa función te responde*.
- Ventajas: Escalabilidad automática, pago por uso, simplicidad en las gestión de infraestructura.
- Desventajas: Restricciones en el tiempo de ejecución, latencia en el inicio de funciones, imitaciones en el control sobre el entorno de ejecución.
**Edge Computing:** Procesamiento y almacenamiento de datos se realizan en dispositivos o servidores más cercanos al lugar donde se generan los datos, en lugar de en un centro de datos centralizado. *Todos funcionan como microservidores*
- Ventajas: Reducción de latencia, mejora en el rendimiento de aplicaciones en tiempo real.
- Desventajas: Complejidad en la gestión de infraestructura distribuida, desafios en la sincronización y consistencia de datos.

Tarea:
Investigar códigos de error de las peticiones http unos 5 de cada petición.
100 5 más importantes
200 5 más importantes
300 5 más importantes
400 5 más importantes
500 5 más importantes