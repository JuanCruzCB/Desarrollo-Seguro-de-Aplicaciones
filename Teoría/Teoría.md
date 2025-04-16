<h1 align="center">Clase 1 - 25 de marzo, 2025</h1>

## CTF

### Concepto

- Un CTF es una **competición** que permite poner a prueba habilidades sobre el hacking vía diferentes desafíos.
- Al resolver cada uno de estos desafíos se llega a una **flag** que suele ser un texto con un formato específico como `FLAG{W3lc0m3_t0_CTF}`.
- Esta flag le permite a la plataforma de la competición confirmar que hemos resuelto el reto correctamente y generalmente se nos compensa con puntos por esto.

### Tipos de CTFs

- **Jeopardy**: retos de diferentes temas (crypto, web, forense, reversing, exploiting, etc) donde se ganan puntos al resolverlos.
- **Attack-Defense**: dos equipos, uno que protege su sistema y el otro que intenta atacarlo y ganar acceso no autorizado al mismo.

### CTFs en la materia

- En la materia se usará una plataforma de CTF estilo Jeopardy.
- La competición será en grupos.
- Las prácticas tendran desafíos obligatorios del CTF.
- Además habrá desafíos extra con dificultades varias.

### CTF UNLP

- El equipo de CTF de la UNLP se llama SYPER y está compuesto de docentes y alumnos.
- Compiten en CTFs nacionales e internacionales.

## Seguridad

### Riesgos

- Los recursos informáticos están expuestos a un conjunto extenso de riesgos:
  - Virus.
  - Gusanos.
  - Spyware.
  - Ransomware.
  - Malware.
  - DDoS.
  - Accesos no autorizados.
  - Modificación de los sistemas.
  - Robo de información.
  - Etc.

### Programación "segura"

- Un programa seguro es aquel que no puede ser usado para realizar funciones distintas de las que ha sido diseñado.
- La programación segura es el conjunto de técnicas, normas y conocimientos que permiten crear programas cuyo uso no pueda ser vulnerado.
- Programar de forma segura implica un mayor tiempo de desarrollo.
  - Los programadores suelen conformarse con que el programa funcione, es decir satisfaga los requerimientos funcionales.
  - Los fallos se corrigen luego y generalmente no se preveen.
- Como los programas son creados (generalmente) por personas, es casi imposible que no haya errores o vulnerabilidades.
- Hay poca conciencia sobre el problema de la seguridad.
- Los clientes ignoran este tema y solo se preocupan porque el programa haga lo que pidieron.

### Deface

- Deface o defacement es manipular la página principal de un servidor web sin autorización, dejando algún tipo de mensaje/imágen/video, lo cual podría ser con fines políticos, fines vandálicos, entre otros.

### Ciclo de vida del software

- El ciclo de vida del software tradicional no incluye (o incluye muy poco) temas de seguridad informática.
- Hoy en día, resulta fundamental que estos ciclos incluyan estos temas debido a la importancia que ha cobrado.

### Zero Trust

- Se trata de una estrategia de seguridad en redes que se basa en el principio de **nunca confiar y siempre verificar**.
- Se basa en la autenticación y autorización basadas en la identidad.
- Se adapta a la fuerza de trabajo móvil.
- Protege cuentas de usuario, dispositivos, aplicaciones y datos.
- Permite detectar, responder y bloquear eventos no deseados.
- Permite controlar el acceso a la información sensible.
- Permite aplicar controles de acceso estrictos.

### El problema de las aplicaciones web

- Las apps web están disponibles y accesibles (en general) desde cualquier parte del mundo 24/7-365 días al año.
- Esto las hace mucho más vulnerales que otros sistemas.
- Las URLs pueden ser explotadas fácilmente.

### Motivación de los ataques informáticos

- Antes (hace algunas décadas) los ataques se hacían generalmente por diversión, sin fines de lucro, y con poco impacto en las organizaciones.
- Hoy en día los ataques son mucho más organizados, se hacen casi siempre con fines de lucro, afectan severamente a la imagen de la víctima, se usa mucho cyber-espionaje, etc.

---

<h1 align="center">Clase 2 - 1 de abril, 2025</h1>

## Términos importantes

### Vulnerabilidad

- Debilidad en un activo.
- Ejemplo: ventaja sin rejas.

### Incidente de seguridad

- Evento adverso que afecta a los activos.
- Las amenazas sacan ventaja de las vulnerabilidades.
- Ejemplo: alguien puede entrar a través de la ventana que no tiene rejas.

### Amenaza

- Violación potencial de la seguridad.
- Ejemplo: concretación de la amenaza, un ladrón entra por la ventana sin rejas y se roba algo.

### Exploit

- Es un programa que aprovecha una vulnerabilidad para provocar un comportamiento no intencionado o imprevisto en un software, hardware o dispositivo electrónico.
- Un **kit de exploit** es una biblioteca de exploits creada por diferentes personas, cuya finalidad es agrupar el mayor número de exploits posibles para facilitar su búsqueda y uso.
- Un exploit puede ser ejecutado por cualquier persona, no necesariamente una experta.

### CVE (Common Vulnerabilities and Exposure)

- Se trata de un índice de vulnerabilidades informáticas a lo largo de la historia que se usa mundialmente.
- Es administrado por MITRE, una organización con fondos del estado de USA que trabaja en aspectos de seguridad informática.

### Known Exploited Vulnerabilities Catalog

- Se trata de una lista oficial de vulnerabilidades que están siendo explotadas **ahora mismo**.
- De cada vulnerabilidad, se adjunta su ID, el software o hardware afectado, una explicación breve de cuál es el problema, cuándo se añadió a la lista, etc.

## Seguridad de la información

### Definición

- Conjunto de medidas **preventivas y reactivas** de las org. y sistemas IT que permiten proteger la información buscando mantener la **confidencialidad, disponibilidad e integridad de datos**.
- Estas tres propiedades se suelen llamar **Triángulo CIA** (Confidentiality, Integrity, Availability).

### Triangulo CIA

- **Confidencialidad**:
  - Propiedad que impide la divulgación de info a individuos, entidades o procesos no autorizados.
  - Asegura el acceso a la información solo a las personas que tengan autorización.
- **Integridad**:
  - Propiedad que busca mantener los datos libres de modificaciones no autorizadas.
  - Es mantener con exactitud la información tal cual fue generada, sin ser manipulada ni alterada por personas o procesos no autorizados.
- **Disponibilidad**:
  - Característica de la info de encontrarse a disposición de quienes deben acceder a ella, ya sean personas, procesos o aplicaciones.
  - Es el acceso a la información y a los sistemas por personas autorizadas **en el momento que así lo requieran**.

## Software Libre

### Concepto

- El software libre es el que respeta la libertad de los usuarios y la comunidad.
- A grandes rasgos, significa que los usuarios tienen la libertad para ejecutar, copiar, distribuir, estudiar, modificar y mejorar el software.
- Libre apunta a la libertad, no al precio. Que un software sea libre no necesariamente significa que es gratuito.
- En inglés se lo conoce como free software, término que evitamos en español para no confundirlo con software gratis.

### Las 4 libertades

- Según GNU un programa es software libre si los usuarios tienen las cuatro libertades esenciales:
  - La libertad de ejecutar el programa para el propósito que sea (libertad 0).
  - La libertad de estudiar cómo funciona el programa vía acceso al código fuente, y cambiarlo para que haga lo que el usuario quiera (libertad 1).
  - La libertad de redistribuir copias del programa (libertad 2).
  - La libertad de distribuir copias de sus versiones modificadas a terceros (libertad 3).

## Licencias de Software

### Concepto

- Existen infinidad de licencias con las que se protege al software.
- Así como las hay para evitar que por ejemplo el Microsoft Office o una película sean copiados y distribuidos, hay licencias que impiden justo lo contrario, por ejemplo que una aplicación se cierre y se deje de distribuir por ejemplo su código fuente.
- En general se las suele clasificar como licencias privativas y licencias libres, aunque en el medio existen Freeware, ShareWare, Trial y Open Source.
- Hya licencias más y menos estrictas.

### Licencias más conocidas

- MIT / X Window System License.
- GPLv2, GPLv3, GPLv3 y sucesivas.
- BSD.
- Apache.
- PHP License.
- LGPL.

### Cuál elegir?

- Depende de varios factores:
  - En qué contexto se desarrolló el software: ¿en mi casa / en la universidad / en el trabajo?
  - En qué me basé para desarrollar el software, si use algo GPL no voy a poder cerrarlo... pero si use algo con copyright no voy a poder hacerlo GPL.

### Cómo proteger mi software con una licencia libre?

- Depende de la licencia.
- Por ejemplo en GNU:
  - El proceso involucra agregar dos elementos a cada fichero fuente de su programa:
  - Un aviso informativo del copyright (tal como «Copyright 1999 Terry Jones»),
  - Una autorización de copia, diciendo que el programa se distribuye bajo los términos de la General Public License de GNU (o la Lesser GPL).
- [Oficial](http://www.gnu.org/licenses/gpl-howto.html).
- [Más claro](http://producingoss.com/es/license-quickstart.html#license-quickstart-applying).

## Criptografía

### Definición

- Arte o ciencia de cifrar y descifrar info usando técnicas que hagan posible el intercambio de mensajes de forma segura de forma tal que sólo puedan ser leídos por las personas a quienes van dirigidos y nadie más.

### Encoding

- Consiste en convertir un texto (o datos) de un lenguaje o sistema de representación hacia otro.
- Es un proceso **reversible**: se puede volver a la forma original sin pérdida de información.
- No tiene como objetivo la seguridad, sino la compatibilidad, almacenamiento o transmisión de datos.
- Usa un algoritmo público y conocido. Por ejemplo:
  - Base64.
  - ASCII.
  - UTF-8.
  - URL encoding.
  - Morse.
  - Braile.
  - Etc..
- Cualquier persona que conozca el método puede decodificar los datos.
- **Encodear NO ES encriptar**.

#### Unicode

- Estándar de codificación de caracteres diseñado para facilitar el tratamiento informático, transmisión y visualización de textos de numerosos idiomas.
- El término Unicode proviene de los tres objetivos perseguidos:
  - Universalidad.
  - Uniformidad.
  - Unicidad.
- La versión 12.1 de Unicode contiene un repertoriode 137.994 caracteres
- Puede ser implementado por diferentes codificaciones de caracteres como UTF-8, UTF-16, UTF-32.

---

<h1 align="center">Clase 3 - 8 de abril, 2025</h1>

## Criptografía

### Concepto

- La criptografía es una ciencia que diseña funciones o dispositivos capaces de transformar mensajes legibles en mensajes cifrados de manera tal que esta transformación (cifrar) y su transformación inversa (descifrar) sólo pueden ser factibles con el conocimiento de una o más llaves.
- Cifrar consiste en convertir un mensaje legible a un dato sin sentido aparente (mensaje cifrado) usando una llave.
- El creador del mensaje cifrado comparte la técnica de descifrado y la llave solo con destinatarios previstos.
- Existen dos tipos de criptosistemas:
  - Sistemas de cifrado simétrico, también conocidos como sistemas de clave privada.
  - Sistemas de cifrado asimétrico, también conocidos como sistemas de clave pública.

### Criptografía simétrica

- El emisor:
  - **Genera** la clave compartida.
  - **Distribuye** la clave compartida.
  - El mensaje original es encriptado usando la clave compartida.
  - Se obtiene como resultado un **mensaje encriptado**.
  - Envía el mensaje encriptado al destinatario.
- El receptor:
  - Desencripta el mensaje usando el mismo sistema de cifrado y la misma clave compartida del emisor.
  - Se obtiene como resultado el **mensaje original**.
- Existen dos modos de operación:
  - **Cifrado en bloques**: Se usa para cifrar archivos.
  - **Cifrado de flujo**: Se usa para cosas en tiempo real.
- **Ventajas ✅**:
  - Gran velocidad de cifrado y descifrado.
  - No aumenta el tamaño del mensaje al cifrar.
- **Desventajas ❌**:
  - La seguridad depende de un secreto compartido entre emisor y receptor.
  - La administración de claves no es escalable, es decir si queremos comunicar el mensaje a muchos destinatarios, tendriamos que compartir la clave con cada uno de ellos uno por uno.
- Ejemplos:
  - 3DES.
  - RC5.
  - IDEA.
  - AES
  - Blowfish.

### Criptografía asimétrica

- Se usan dos claves, una pública y una privada:
  - La clave pública se puede compartir con cualquier persona.
  - La clave privada solo es conocida por el dueño y nadie más.
- Las claves están matemáticamente relacionadas entre sí.
- Ambas claves pueden ser usadas para encriptar y desencriptar, dependiendo del modo de operación utilizado.
- Este tipo de criptografía posee dos modos, modo encripción y modo autenticación.
  - En el modo **encripción**, el emisor encripta con clave la pública del receptor, y el receptor desencripta con su clave privada. Esto garantiza confidencialidad.
  - En el modo **autenticación**, el emisor encripta con su clave privada, y el receptor desencripta con la clave pública del emisor. Esto garantiza integridad y no repudio.
- **Ventajas ✅**:
  - No hace falta intercambiar claves secretas.
  - A través de sus dos modos se cubre gran parte de los requisitos de seguridad de la información.
- **Desventajas ❌**:
  - Requiere mayor potencia de cómputo para cifrar y descifrar que el método simétrico.
  - El mensaje cifrado es de mayor tamaño que el original.
- Ejemplos:
  - Diffie-Hellman.
  - RSA.
  - DSA.
  - ElGamal.
  - CCE.

### Resumen de tipos de criptografía

![Resumen de tipos de criptografía](https://i.imgur.com/KH6Rp9P.png)

### Funciones de hash

- Son funciones de transformación que toman un input de tamaño variable y retornan un string de longitud **fija**, conocido como “message digest”.
- Estas funciones son determinísticas: mismo input siempre dará el mismo hash de output.
- Son bastante rápidas de calcular.
- Es inviable obtener el mensaje original a partir del hash.
- Un pequeño cambio en el input cambia drasticamente el valor del hash.
- Se usan en:
  - Criptografía asimétrica.
  - Firma digital.
  - Almacenamiento de contraseñas.
- **Colisiones**:
  - Una colisión en hash ocurre cuando dos entradas diferentes a una función hash producen el mismo output (hash).
- **Problemas**:
  - Las debilidades en una función de hash están asociadas con la posibilidad de manipular las colisiones.
  - Lo rápidas que son estas funciones las hace vulnerables a ataques de fuerza bruta.
- Ejemplos:
  - MD5 (128 bits).
  - SHA-1 (160 bits).
  - SHA-2.
  - SHA-3.

## Esteganografía

### Definición

- Técnica para ocultar un mensaje secreto dentro de un mensaje ordinario y extraerlo en el destino para mantener la confidencialidad de los datos.
- Arte de ocultar un archivo de texto, imagen, video o audio dentro de otro archivo, llamado **portador**, de modo que no sea perceptible su existencia.
- El objetivo es ocultar la información lo suficientemente bien como para que los destinatarios involuntarios no sospechen que el medio esteganográfico contiene datos ocultos.
- Los medios portadores preferidos (por sus características) son archivos multimedia (imágenes, audio y vídeo).

### Tipos

- Hay dos tipos de esteganografía:
  - **Pura**: Se supone que la víctima (quien ve el mensaje) no conoce nada sobre el estego-algoritmo. Por lo tanto se usa seguridad basada en oscuridad.
  - **De clave secreta**: El estego-algoritmo se parametriza con una clave, que define como aplicar el algoritmo.

## Ofuscación

### Definición

- Acto intencional de hacer un cambio no destructivo, ya sea en el código fuente de un programa informático, en el código intermedio (bytecodes) o en el código máquina cuando el programa está en forma compilada o binaria.
- Es decir, se cambia el código manteniendo el funcionamiento original, para dificultar su entendimiento. De esta forma **se dificulta los intentos de ingeniería inversa y desensamblado que tienen la intención de obtener una forma de código fuente cercana a la forma original**.
- Ejemplo:

![Ejemplo de ofuscación](https://i.imgur.com/tnLp4vJ.png)

## PGP (Pretty Good Privacy)

### Definición

- PGP es un conjunto de programas creados por Phil Zimerman para proteger información. Es un **criptosistema híbrido** que usa criptografía de clave pública, criptografía simétrica y funciones de hash.
- Al convertirse en uno de los mecanismos más populares para utilizar criptografía, la IETF tomó como base su diseño para crear el estándar OpenPGP.
- Además de proteger los datos en tránsito también permite proteger los datos almacenados en discos, copias de seguridad, etc.

### PGP VS OpenPGP VS GNUPG

- **PGP**: Actualmente propiedad de Symantec.
- **OpenPGP**: Estándar aprobado por el IETF (RFC 4880) que describe cualquier mecanismo de cifrado que use procesos interoperables con PGP.
- **GnuPG**: Solución que sigue los estándares de OpenPGP desarrollada por la Free Software Fundation.

### Claves

- En PGP cada usuario genera un par de claves, una pública y otra privada.
  - La clave pública es la que se puede compartir.
  - La clave privada nunca debe ser compartida. Esta clave contendrá el header "PGP PRIVATE KEY BLOCK".
  - Cada clave desencripta un mensaje que fue encriptado con la otra.

### Fingerprint

- Las claves PGP tienen un fingerprint asociado, que es una versión corta de las mismas.
- Por ejemplo:
  - Long Key ID: D834 298F FEFB D9E2 (64 bits).
  - Short Key ID: FEFB D9E2 (32 bits).

### Certificado de revocación

- Una vez generado el par de claves, es recomendable generar un certificado de revocación que podrá ser utilizado en caso que la clave privada haya sido filtrada.
- Ante la presunción del leak de la clave, se debe subir el certificado de revocación a los servidores de claves para informar que la clave ya no es más válida.

### Servidores de claves

- Los servidores de claves son repositorios utilizados para **compartir las claves públicas**.
- Es importante remarcar que cualquiera puede generar y distribuir claves para cualquier nombre y dirección de correo.
- El servidor más conocido es [el que mantiene el MIT](https://keyserver.ubuntu.com/), pero todos se encuentran sincronizados.

### Encripción vs firma

- Cuando se encripta un mensaje o un archivo, aumenta el nivel de **confidencialidad**.
- Cuando se firma, se aumenta el nivel de **integridad y autenticidad**.
- Un mensaje puede ser cifrado y luego firmado o firmado y luego cifrado.

### Red de confianza

- Una red de confianza es un concepto usado para establecer qué tan confiable es un par de claves que se genera en un esquema descentralizado.

### Anillos de claves

- **Anillo de claves públicas**: Archivo en el que se guardan las claves públicas del usuario propietario y las claves públicas importadas.
- **Anillo de claves privadas**: archivos en el que se guardan la/s clave/s privada/s del usuario propietario.
- Si podemos confirmar la persona que utiliza una clave en particular, podemos firmar dicha clave con nuestra clave privada. Esto permitirá:
  - Certificar que dicha clave efectivamente pertenece a esa persona.
  - Evitar la manipulación de nuestro anillo de claves por parte de un tercero.
- Al igual que las claves públicas, las firmas realizadas a una clave también se pueden subir.
- Las reuniones donde se validan, intercambian y firman claves son conocidas como **PGP Parties**.

### Esquema de confianza

- La confianza es subjetiva.
- Yo puedo confiar en la clave de una persona, pero no confiar en **las claves en las que esa persona confía**.
- Se pueden establecer relaciones de confianza indirectas.

### Ventajas ✅

- Su fuerte radica en la facilidad para generar claves y gestionarlas, con un amplio campo de aplicación:
  - Comunicación entre individuos en correo electrónico.
  - Cifrado de archivos y mensajes.
- Existen versiones libres y comerciales que implementan PGP, para manejo de claves y operaciones de criptografía, las cuales están disponibles para gran variedad de plataformas.
- Está basado en algoritmos extensamente revisados y considerados ampliamente seguros (RSA, DSS y Diffie-Hellman; CAST-128, IDEA y 3DES; SHA-1).
- El software y la documentación están disponibles en Internet.
- Existen versiones comerciales y libres que implementan los servidores de clave PGP.
- No fue desarrollado por ningún gobierno ni organización de creación de estándares, lo cual lo hace atractivo.

### Desventajas ❌

- La gestión de claves en PGP se basa en la confianza mutua: "los amigos de tus amigos son mis amigos".
- En un sistema abierto en Internet como el comercio electrónico, esta situación y otras más que pueden darse en este sistema de gestión de claves de confianza mutua, resulta inaceptable.

### Aplicaciones

- Correo electrónico.
- Thunderbird.
- IPGMail para IOS.
- K-9 Mail para Android.
- Gmail mediante extensión para Google Chrome (FlowCrypt).
- Firma de código (GitHub).
- Cifrado de archivos / disco (gpg4win).

### Guía de uso básico

1. Generar el par de claves (pública y privada).
2. Configurar cliente de correo.
3. Resguardar la clave privada adecuadamente.
4. Intercambiar con el círculo de confianza la clave pública → PGP-parties.
5. Incorporar claves públicas de terceros a tu llavero → Fingerprint.
   1. einar@linti.unlp.edu.ar → Fingerprint **699B 5CD9 4C66 19BC DCE6 893D E4ED C070 3DB4 692E**.
   2. sandrazilla@gmail.com → Fingerprint **bb17 e159 5aad 556d 74e4 2086 9983 2da7 4b41 d3e3**.
   3. mcarbone@linti.unlp.edu.ar → Fingerprint **6FD4 2FA2 E23F 15E4 5019 0449 B0FC 335B C2C3 F158**.
   4. Forma grupo y enviar el mail con la conformación del grupo cifrado y firmado a las cuentas de correo de la cátedra.

[Más información](https://keyserver.ubuntu.com/).

### PGP y Triángulo CIA

- Si firmo un mail con mi clave privada, aseguro **integridad**:
  - El mensaje no se puede alterar ya que la firma no coincide y nadie lo puede escribir originalmente, excepto el dueño de la privada.
- Si encripto un mensaje con la clave pública del destinatario, aseguro **confidencialidad**:
  - Nadie puede leer el mensaje, excepto el dueño de la clave privada que se corresponde con la pública utilizada.
- Por ende, si realizo ambas cosas, aseguro **tanto integridad como confidencialidad**.
- Si en cada caso el destinatario pierde su clave privada, se pierde la **disponibilidad**.
- Si alguien se roba la clave privada del emisor, se pierde la **integridad**.
- Si alguien se roba la clave privada del destinatario, se pierde la **confidencialidad**.

---

<h1 align="center">Clase 4 - 15 de abril, 2025</h1>

## OWASP (Open Web Application Security Project)

### Definición

- OWASP es un proyecto conformado por una comunidad mundial libre y abierta que se enfoca en mejorar la seguridad del software.
- Busca ayudar a las organizaciones a desarrollar y mantener aplicaciones confiables.
- Posee su [página web](https://www.owasp.org/).

### Componentes de OWASP

- **OWASP Top Ten**:
  - Es un documento de concientización para desarrolladores y seguridad de aplicaciones web.
  - Riesgos de seguridad más críticos para las aplicaciones web.
  - Representa un amplio consenso sobre los riesgos de seguridad más críticos para las aplicaciones web.
  - Contiene 10 categorías, cada una con 5 secciones:
    - Riesgo (vectores de ataque, debilidades de seguridad, impacto tecnológico y del negocio).
    - La aplicación es vulnerable?
    - Cómo se previene.
    - Ejemplos de escenarios de ataques.
    - Referencias.
  - Cada categoría representa un riesgo de seguridad pero cada riesgo es genérico.
  - Por ejemplo **A3: Injection** representa cualquier tipo de inyección a una aplicación, pero existen muchísimas subcategorías de este riesgo (SQL injection, Command injection, Template injection, etc) que deben estudiarse de forma específica para obtener resultados.
  - Para estos casos deben usarse las referencias de la categoría que suelen ser muy útiles a la hora de estudiar el riesgo de la categoría de manera más específica.
- **OWASP Web Security Testing Guide**:
  - Controles de seguridad que se deben contemplar a la hora de realizar pentesting en aplicaciones web.
- **OWASP Cheat Sheet Series**:
  - Una colección concisa de información de alto valor sobre temas específicos de seguridad de aplicaciones.
  - Básicamente resúmenes sobre temáticas que complementan a los otros documentos.
- **OWASP Application Security Verification Standard**:
  - Ofrece una lista completa de requisitos, controles y pruebas de seguridad de aplicaciones web que puede utilizar para determinar el alcance, crear y verificar aplicaciones web y móviles seguras.
- **OWASP DefectDojo**:
  - Tracking de pentesting y reporte.
- **OWASP Zed Attack Proxy (ZAP)**:
  - Herramienta de pentesting tipo burp.
- **OWASP in SDLC**:
  - Ejemplo del uso de mucha de las herramientas de owasp en el SDLC.
- **OWASP API Top Ten**
- **OWASP Mobile Security**
- **OWASP Cloud-Native Application Security Top Ten**
- **OWASP Kubernetes Top Ten**
- **OWASP Docker Top Ten**
- **OWASP Top Ten Privacy Risks**
- **OWASP Attacks List**:
  - Enumeración de ataques a aplicaciones web.
- **OWASP Vulnerabilities**:
  - Enumeración de vulnerabilidades específicas.
- **OWASP Proactive Controls**:
  - Una lista de técnicas de seguridad que deben tenerse en cuenta para cada proyecto de desarrollo de software.
  - Están ordenados por orden de importancia, siendo el control número 1 el más importante.
  - Fue escrito por desarrolladores para ayudar a nuevos desarrolladores a asegurar la seguridad en el desarrollo de software.
- **OWASP Vulnerable Web Applications Directory**
- **OWASP Automated Threats to Web Applications**:
  - Enumeración de varios ataques automáticos a aplicaciones web.
  - También define un lenguaje estándar para referenciar a estos ataques.

### Evolución del OWASP Top Ten

- Se genera una nueva versión cada 3 o 4 años.
- CWE (Common Weakness Enumeration): Knowing the weaknesses that result in vulnerabilities means software developers, hardware designers, and security architects can eliminate them before deployment, when it is much easier and cheaper to do so.
- Historial:
  - Top Ten 2003.
  - Top Ten 2004.
  - Top Ten 2007.
  - Top Ten 2010.
  - Top Ten 2013.
  - Top Ten 2017.
  - Top Ten 2021 (actual)
  - Top Ten 2025 (se publicará en algun momento este año).
- Evolución del top ten de 2007 a 2017:

![Evolución del top ten de 2007 a 2017](https://i.imgur.com/PaasP8X.png)

- Entre el Top Ten 2007 y el de 2010 se cambió la metodología de selección: se empezó a centrar en riesgos y no en cantidad de vulnerabilidades:

![Cambio de metodología del Top Ten de 2007 a 2010](https://i.imgur.com/4F8x6bj.png)

- Evolución 2010 a 2013:

![2010 a 2013](https://i.imgur.com/8IwhEKM.png)

- Evolución 2013 a 2017:

![2013 a 2017](https://i.imgur.com/U88Pa6S.png)

- Evolución 2017 a 2021:
  - Hay tres nuevas categorías.
  - Cuatro categorías con cambios de nombre y alcance.
  - Alguna consolidación en el Top 10 de 2021
  - Cambiaron los nombres cuando ha sido necesario para centrarnos en la causa raíz en lugar del síntoma. Cambia la importancia de las CWE.

![2017 a 2021](https://i.imgur.com/nPcT0JX.png)

- Las 10 principales categorías fueron seleccionadas y priorizadas de acuerdo con estos datos de prevalencia, en combinación con estimaciones consensuadas de explotabilidad, detectabilidad e impacto.
- A partir de 2013 aparece la referencia directa a las CWE para reducir la complejidad de mapeo.
- En 2017 aparece la tasa de incidencia: se refiere al porcentaje de la población de aplicaciones que tiene al menos una instancia de un tipo de vulnerabilidad. No importa si fue algo puntual o sistémico.
- En 2017, categorías según la tasa de incidencia para determinar la probabilidad, y luego las clasificamos según la discusión del equipo basada en décadas de experiencia respecto a la Explotabilidad, la Detectabilidad (también probabilidad) y el Impacto técnico.
- Para 2021, queremos utilizar los datos de Explotabilidad e Impacto (técnico) si es posible.
- En 2021:
  - Ocho de las diez categorías a partir de los datos aportados por partners encuestados.
  - Y dos categorías a partir de la votación/encuesta de la comunidad del Top 10 a un alto nivel.
  - Se uso número de aplicaciones analizadas para un año determinado (a partir de 2017) y el número de aplicaciones con al menos una instancia de una CWE encontrada en las pruebas.

### Mitre

- Organización que con fondos del estado de EEUU trabaja en aspectos de seguridad informática.
- Administra el índice Common Vulnerabilities and Exposure (CVE), identificador usado mundialmente.

### Data Factors

- **CWEs mapeadas**: El número de CWEs asignadas a una categoría por el equipo del Top 10.
- **Tasa de incidencia**: Es el porcentaje de aplicaciones vulnerables a esa CWE de la población analizada por esa organización para ese año.
- **Cobertura (de pruebas)**: El porcentaje de aplicaciones que han sido testadas por todas las organizaciones para una determinada CWE.
- **Explotabilidad ponderada**: La sub-puntuación de explotabilidad de las puntuaciones CVSSv2 y CVSSv3 asignadas a las CVEs mapeadas a las CWEs, normalizados y colocados en una escala de 10 puntos.
- **Impacto ponderado**: La sub-puntuación de Impacto de las puntuaciones CVSSv2 y CVSSv3 asignadas a las CVEs mapeadas a las CWEs, normalizados y colocados en una escala de 10 puntos.
- **Total de ocurrencias**: Número total de aplicaciones en las que se han encontrado las CWEs asignados a una categoría.
- **Total de CVEs**: Número total de CVEs en la base de datos del NVD que fueron asignadas a las CWEs asignados a una categoría.

### Riesgos

- Un riesgo tecnólogico es la probabilidad de sufrir pérdidas por caídas o fallos en los sistemas informáticos o transmisión de datos, error desde programación u otros, siendo un componente del riesgo operativo.
- Los atacantes pueden potencialmente usar muchas diferentes rutas a través de la aplicación para hacer daño al negocio u organización.
  - Estas rutas representan un riesgo que puede, o no, ser lo suficientemente grave como para justificar la atención.
- A veces, estas rutas son triviales de encontrar y explotar pero a veces son extremadamente difíciles.
- De manera similar, el daño causado puede ir de ninguno hasta incluso sacarlo del negocio.
- Cada ruta es un riesgo separado.
- El riesgo "pérdida de control de acceso" se ha ido incrementando año a año, subiendo de rango en el Top Ten. Pasó de top 7 en 2007 a top 1 hoy en día.

## Docker

### Contenedores vs máquinas virtuales

- En el mundo de la virtualización y el desarrollo de software, existen dos enfoques principales:
  - Máquinas virtuales.
  - Contenedores.
- Los contenedores han surgido como una alternativa **ligera y eficiente** a las máquinas virtuales tradicionales.

![VMs vs Containers](https://i.imgur.com/Cpzbcbn.png)

### Máquinas virtuales

- Las máquinas virtuales son **entornos de computación completos** que se ejecutan sobre un hardware físico.
- Cada VM incluye un sistema operativo completo y recursos virtuales dedicados como CPU, RAM y almacenamiento.
- La virtualización completa del sistema operativo a través de un hipervisor permite la ejecución de múltiples sistemas operativos en un solo servidor.

### Contenedores

- Los contenedores son **entornos de ejecución ligeros y portátiles que comparten el kernel** del sistema operativo del host.
- Cada contenedor encapsula una aplicación y sus dependencias, pero no incluye un sistema operativo completo.
- Los contenedores proporcionan aislamiento a nivel de proceso y usan recursos de manera más eficiente que las VMs.
- Casos de uso:
  - **Desarrollo Ágil**: Permiten a los equipos de desarrollo crear, probar y desplegar aplicaciones de manera rápida y consistente.
  - **Entornos Aislados**: Las imágenes usadas por los contenedores ofrecen aislamiento de la aplicación y sus dependencias. Esto favorece prácticas de DevOps.
  - **Despliegue Escalable**: La escalabilidad horizontal de los contenedores facilita el despliegue de aplicaciones en entornos de nube y microservicios.

### Docker

- Plataforma de contenedores que simplifica el proceso de creación, distribución y ejecución de contenedores.
- Ha revolucionado la forma en que se empaqueta, distribuye y ejecuta las aplicaciones.
- Se compone de dos conceptos clave:
  - **Imágenes**.
  - **Contenedores**.

### Imágenes Docker

- Una imagen Docker es un **paquete ligero y autónomo** que contiene todo lo que se necesita para ejecutar una aplicación determinada:
  - Código.
  - Runtime.
  - Librerías.
  - Variables de entorno.
  - Configuraciones.
- Se crean a partir de un archivo especial llamado **dockerfile**:
  - Es un archivo de configuración que se utiliza para crear imágenes.
  - En ese archivo se especifica una serie de pasos para construir la imagen, es decir qué queremos que tenga, y qué comandos usar para instalar diversas herramientas.
- Estas imágenes se pueden guardar localmente o en repositorios compartidos como [DockerHub](https://hub.docker.com/). Esto permite que las mismas puedan ser reutilizadas fácilmente.

### Volúmenes

- No es una buena práctica guardar los datos persistentes dentro de un contenedor de Docker.
- Los volúmenes son espacios de almacenamiento **fuera** de los contenedores.
- Así podemos crear y borrar contenedores sin preocuparnos por que se borren los datos.
- Es un concepto análogo a las carpetas compartidas en VMs.
- También se pueden usar para compartir datos **entre contenedores**.

### Compose

- En ocasiones es necesario conectar contenedores entre si, por ejemplo: frontend, backend y db.
- Docker Compose es una herramienta que permite simplificar el uso de contenedores Docker cuando se necesita armar soluciones que agrupan varios contenedores.
- A partir de archivos YAML es mas sencillo crear contendores, conectarlos, habilitar puertos, volúmenes, etc.

---

<h1 align="center">Clase 5 - ? de ?, 2025</h1>

## ?

---

<h1 align="center">Clase 6 - ? de ?, 2025</h1>

## ?

---

<h1 align="center">Clase 7 - ? de ?, 2025</h1>

## ?

---

<h1 align="center">Clase 8 - ? de ?, 2025</h1>

## ?

---
