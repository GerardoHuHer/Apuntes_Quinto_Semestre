Tema: **Criptografía**
Tags: [[Ciberseguridad]]
Date: ==25/09/2024==

---
# Definición y usos
## ¿Qué es la criptografía?
La UNAM señala: Son las técnicas utilizadas para cifrar y descifrar información utilizando técnicas matemáticas que permiten el intercambio de mensajes que sólo puedan ser leídos por las personas a quien van dirigidos.

Kryptos + Graphos o Graphia: Kryptographia: Ocultar la escritura.

## ¿En qué ayuda la criptografía?
- **Confidencialidad:** Usar el cifrado para proteger información sensible o crítica, incluso cuando encuentra en transmisión o almacenada.
- **Integridad:** Verificar la autenticidad o integridad de la información sensible o crítica almacenada y transmitida.
- **Autenticación:** Al utilizar técnicas criptográficas para autenticar usuarios y otras entidades o sistemas, solicitado acceso o transacciones con usuarios de sistemas, entidades y recursos.
- **No repudio:** Al utilizar técnicas criptográficas para proveer evidencia de que ocurrió o no ocurrió un evento o una acción.
## Usos (algunos ejemplos)
- Documentos y cualquier tipo de archivo.
- Correo electrónico.
- Hardware.
- Seguridad en las comunicaciones.
- Firma electrónica.

# Hash
Es una función, que transforma matemáticamente la información de forma irreversible, en una cadena de caracteres de una longitud fija.

Podemos descifrar un hash con Rain

| Palabra | Hash   |
| ------- | ------ |
| Hola    | aasda  |
| Adios   | asñdjf |
| Oso     | sdfasf |
## Ejemplos de números Hash
- MD4.
- MD5.
- SHA-1.
- SHA-2.
- SHA-256.
- SHA-512.
## Hash collision
Ocurre cuando dos documentos distintos (con contenido distinto tienen el mismo hash).

## Criptografía
**Simétrica:** La llave que usa para cifrar y descifrar es la misma.

| Ventajas                              | Desventajas                                                    |
| ------------------------------------- | -------------------------------------------------------------- |
| Es de aplicación simple y eficiente.  | El intercambio de la llave o clave secreta.                    |
| Tiene longitud de llaves cortas.      | Requiere administrar muchas llaves distintas.                  |
| El tiempo de procesamiento es rápido. | Se necesita un acuerdo/relación para el intercambio de llaves. |

**Asimétrica:** La llave que usa para cifrar y descifrar es diferente.
**Utiliza dos llaves para cifrado:**
- Pública: Se comparte al **emisor** para el cifrado de la información.
- Privada: Permite descifrar la información y cuenta con una contraseña de protección de la llave. Sólo es conocida y resguardada por el propietario.

| Ventajas                                                                       | Desventajas                                                                               |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------- |
| Evita la divulgación de las llaves secretas.                                   | Las llaves deben de ser de mayor tamaño con respecto a las simétricas.                    |
| Solo es posible descifrar con la llave privada.                                | La velocidad de procesamiento es lenta.                                                   |
| Soporta firmas digitales.                                                      | Si se pierde la llave privada, no se podrá descifrar y necesitará un nuevo par de llaves. |
| No requiere una relación previa entre emisor/receptor, sólo de un repositorio. |                                                                                           |

# Algoritmos de llaves públicas.
**PKI: Public Key Infrastructure** 
Es un conjunto de políticas, roles, procedimientos e infraestructura que permiten crear, gestionar, utilizar, almacenar y revocar certificados digitales así cómo gestionar el cifrado de llave pública.
- Políticas y procedimientos.
- Aplicaciones.
- Certificados digitales.
- Autoridad certificadora (CA): almacenar, expedir y firmar certificados digitales. 
- Autoridad registradora (RA): Verifica la identidad de las entidades que solicitan que los certificados se almacenen en la CA.
- Criptografía de clave pública y privada.

# Cifrado
Desde los comienzos de la humanidad, se han creado diversos sistemas de escritura como parte de la comunicación, por ejemplo:
- Jeroglíficos.
- Pinturas rupestres.
Desde esos tiempos, el ser humano ..

En épocas antiguas se utilizaron sistemas complejos con símbolos para proteger...

Desde la época del inicio del imperio romano y la época moderna los científicos y matemáticos han hecho...

# ¿Qué es el cifrado?
Proceso utilizado para transformar un texto a una forma ininteligible de manera que los datos originales no puedan ser recuperados (cifrado de una vía) o sólo puedan ser recuperados usando un proceso inverso de descifrado (cifrado de dos vías).

# El cifrado más antiguo
Fue inventado por Julio César para comunicarse mientras conquistaba Europa, pues existían riesgos al enviar sus cartas con mensajeros que podrían ser espías, traidores o en el camino, ser emboscados por el enemigo así que desarrolló el ahora conocido, cifrado César.

## Ataque de fuerza bruta
- Consiste en intentar cada posible clave hasta que 