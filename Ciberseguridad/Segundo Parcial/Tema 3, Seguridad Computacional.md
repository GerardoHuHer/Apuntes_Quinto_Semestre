# Conceptos y principios 

PAM (Priviliged Access Monitoring)
Casos de uso:
- **Descubrir cuentas privilegiadas** en sistemas, dispositivos y aplicaciones, para su posterior gestión.
Single Sign On (SSO)
PAM _Herramienta_ (Privileged Access Monitoring): Ayudan a las organizaciones a brindar acceso privilegiado 
Casos de uso (PAM):
- Descubrir cuentas priviliegiadas en sistemas, dispositivos y aplicaciones, para su posterior gestión.
- Almacenar y administrar automáticamente contraseñas aleatorias y otras credenciales para cuentas administrativas, servicios y aplicaciones.
- Controlar el acceso a las cuentas privilegiadas, incluyendo cuentas compartidas o de emergencia.
- Aislar, monitorear, registrar/grabar y auditar sesiones, comandos y acciones en accesos privilegiados, _graba todo lo que hacemos en consola por ejemplo_.
**Con estas herramientas hay algo importante, podemos configurar por ejemplo por zona para que mande una alerta en caso de estar en otro lado.**

# Técnicas de indentificación y autenticación
## Identificación
Es la capacidad de identificar de forma exclusiva a un usuario en un sistema o en una aplicación en ejecución en el sistema.
En un sistema, se identifica a un usuario cuando intenta establecer conexión.
## Autenticación
Provisión de seguridad, de que una característica declarada de una entidad, es correcta.

# Single Sign On

# Control de Acceso
**Física:** Es un mecanismo, sistema o dispositivo que autoriza la entrada a determinada ubicación o instalación.

**Digital:** En ciberseguridad, son herramientas o aplicaciones cuyo objetivo es gestionar quién está autorizado para acceder a determinados activos de información.

## Tipos
- Por teclado.
- Huella dactilar.
- Reconocimiento facial.
- Tarjeta de identificación.
- RFID (**Radio Frequency Identification**).
- En red.
_No repudio: podemos estar seguros de que la persona que hizo esa acción fue esa persona._

# Administración del control de acceso
- Política de control de acceso:
	- Establecerla, documentarla y actualizarla, basada en los requerimientos del negocio y de seguridad de la información.
- Acceso a redes y servicios de red:
	- Los usuarios sólo deben contar con accesos a las redes y servicios que tienen autorizados.
- Gestión de acceso de usuarios: Asegurar el acceso autorizado y prevenir el acceso no autorizado.
	- Registro y eliminado de usuarios.
	- Aprovisionamiento de acceso a usuarios.
	El proceso debe de implementarse para asignar o revocar privilegios de acceso para todo tipo de usuarios a todos los sistemas y servicios.
# Mecanismos de autenticación y control de acceso
- MFA: Multiple Factor Authentication.
- SSO: Single Sign On.
- IAM: Identity Access Management. Llevar a cabo un proceso de gestión de usuarios, asociar cierta información que solo yo conozca.
- PAM: Priviliged Access Monitoring 

# Identity and Access Management
De acuerdo con Gartner, permite:  a las personas adecuadas acceder a los recursos correctos en el tiempo correcto por las razones correctas.

# Tendencias 2022 (Gartner: Consultoría que a nivel mundial genera, estudios, tendencias etc.)
- La conexión hacia la nube, pronto necesitará control de acceso más eficiente.
- Mejorar la experiencia de usuario para todos los usuarios será escencial el negocio digital seguro. 
- Llaves, secretos (_Todas las contraseñas, usuarios, conexiones, direcciones IP_), certificados y máquinas requerirán mayor atención.
- La nube híbrida y el multicloud llevará a la evolución o mantenimiento de la arquitectura IAM.
- Nuevas aplicaciones y APIs necesitan aprovechar las últimas guías/pautas de desarrollo o IAM.
- Las plataformas de gestión de acceso deben volverse más sofisticadas para diferenciar entre usuarios válidos, bots maliciosos, estafadores, sin generar molestia a los usuarios legítimos.
# Hackers, crackers y sus variantes
¿Qué es hacking?
Es la explotación de vulnerabilidades y el compromiso de controles de seguridad para ganar acceso no autorizado a recursos en un sistema.
Utiliza diversas tecnicas:
- Virus.
- Ataques DoS.
- Establecer acceso remoto mediante troyanos o backdoors.
- Botnets.
- Sniffing de paquetes en la red.
- Ingeniería Social.
- Crackin de contraseñas.
## ¿Por qué suceden?
- Obtener prestigio o poder.
- Robo de información.
- Reto intelectual.
- Curiosidad.
- Venganza.
- Competencia.
- Dañar algún sistema.

# Hacker vs Cracker