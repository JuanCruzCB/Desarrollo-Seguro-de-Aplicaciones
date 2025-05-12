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

<h1 align="center">Clase 5 - 22 de abril, 2025</h1>

## OWASP

### OWASP Risk Rating Metholodgy

- OWASP define a un riesgo como:

```
Riesgo = Probabilidad de que ocurra × Impacto en el negocio
```

- Los pasos son:
  - Identificar un riesgo.
  - Estimar la probabilidad de que ocurra.
  - Estimar el impacto que tendría si ocurre.
  - Determinar el grado de severidad del riesgo.
  - Decidir qué arreglar en base a los anteriores.
  - Customizar el modelo de risk rating.

#### Identificar un riesgo

- Suele ser el paso más difícil.
- Se debe:
  - Reunir información sobre los posibles **agentes** de amenaza.
  - Identificar vulnerabilidades que puedan ser explotados por esos agentes.
  - Estimar el impacto sobre el negocio si la amenaza se materializa.
- Se piensa en el peor caso posible.

#### Estimar la probabilidad de que ocurra.

- Una vez identificados los riesgos, se estima:
  - La prob. de que una vulnerabilidad en particular sea descubierta y explotada por uno o varios atacantes.
  - Se recomienda usar un cálculo cuantitativo
- OWASP usa una serie de factores para realizar la estimación de prob.
- Estos factores se asocian a dos conceptos: a él o los atacantes y a la vulnerabilidad.
- A cada factor se le asigna un valor 0..9.
  - A más bajo el valor, menor el impacto.
  - A más alto el valor, mayor el impacto.

#### Estimar el impacto que tendría si ocurre.

- Si la amenaza se materializa, se consideran dos tipos de impacto:
  - Técnico.
  - Sobre el negocio.
- Nuevamente se usan factores de 0..9.

#### Determinar el grado de severidad del riesgo.

- Para determinar la severidad se usa:
  - La probabilidad de ocurrencia de la amenaza.
  - El impacto generado sobre el negocio.
- El primer paso es seleccionar una de las opciones asociadas con cada factor a ingresar el número asociado en una tabla.
- Luego se toma el promedio de las puntuaciones para calcular la prob. general.

![](https://i.imgur.com/NG7EqOn.png)
![](https://i.imgur.com/tX0u0II.png)

#### Decidir qué arreglar en base a los anteriores.

- Una vez hecho todo lo anterior, se tiene una lista pesada de arreglos para realizar.
- Sin embargo, no todo se puede arreglar debido a los costos.

#### Customizar el modelo de risk rating.

- Existen varias formas:
  - Agregando factores.
  - Personalizando las opciones.
  - Asignando peso a cada uno de los factores.

### CVSS

- La CVSS (Common Vulnerability Scoring System) provee una manera de capturar las características principales de una vulnerabilidad y producir un score numérico que refleja su severidad.
- Este score puede ser traducido a una representación cualitativa como **bajo - medio - alto - critico**, para ayudar a las organizaciones a analizar y priorizar su proceso de manejo de vulnerabilidades.
- [Calculadora](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?vector=AV:N/AC:H/PR:H/UI:R/S:U/C:N/I:N/A:H).

### FIRST

- FIRST (Forum of Incident Response and Security Teams) es una comunidad o foro mundial de los más importantes en cuestiones de ciberseguridad y gestión de incidentes.
- [Herramientas](https://www.first.org/cvss/calculator/4-0).

### Web Security Testing Guide

- WSTG (Web Security Testing Guide) se creó en 2013 como una guía que complementa al OWASP Top 10.
- Provee info específica y técnica sobre controles de seguridad que se deben contemplar a la hora de hacer pentesting en apps web.
- Además, se le suma un complemento llamado OWASP Web Application Penetration Checklist que ayuda a contabilizar y categorizar los controles de seguridad que se deben ejecutar según OWASP Top 10 y WTSG.
- Tiene como objetivo ayudar a entender el qué, por qué, cuándo, dónde y cómo testear apps web.
- Proporciona un marco de prueba completo, mucho más que una simple lista de verificación o prescripción de problemas que deben abordarse.
- Los lectores pueden usar este marco como plantilla para crear sus propios programas de testeo.
- WTSG describe en detalle tanto el marco de prueba general como las técnicas necesarias para implementar este marco en la práctica.

### Application Security Verification Standard

- ASVS (Application Security Verification Standard) es una lista de requisitos o pruebas de seguridad de apps que los arquitectos, devs, testers, profesionales de ciberseguridad e incluso los clientes pueden usar para definir qué significa una aplicación segura.
- La idea es que las personas involucradas se pongan de acuerdo y entiendan exactamente qué significa "seguro".
- Ofrece una lista completa de requisitos, controles y pruebas de seguridad de aplicaciones web que puede utilizar para determinar el alcance, crear y verificar aplicaciones web y móviles seguras.
- Permite a las organizaciones desarrollar y mantener aplicaciones más seguras; y también brinda a los proveedores de servicios de seguridad y proveedores un conjunto de controles bien documentado con el que pueden alinear sus requisitos y ofertas.
- La última versión, OWASP ASVS v4.0.2, se lanzó en octubre de 2020.
- Busca fijar un estándar para normalizar el nivel y el rigor con el que se hacen las verificaciones de seguridad sobre web apps.
- La idea general es que:
  - Se use como métrica para dar un valor de confianza a las apps.
  - Se use como guía para que los devs puedan construir controles de manera de satisfacer los requisitos de seguridad.
  - Se use durante adquisiciones proveyendo una base para especificar requerimientos de seguridad en los contratos.

#### Niveles

- El ASVS define tres niveles de verificación para la seguridad, con cada nivel incrementando su profundidad.
  - ASVS Nivel 1 es para todo el software.
  - ASVS Nivel 2 es para las aplicaciones conteniendo datos sensibles, los cuales requieren protección.
  - ASVS Nivel 3 es para las aplicaciones más críticas, aplicaciones realizando transacciones de alto valor, conteniendo datos médicos sensibles, o cualquier aplicación el cual requiera un alto nivel de confianza.
- Cada nivel contiene una lista de requerimientos para la seguridad.

### A01-2021: Pérdida de control de acceso

- Se trata de el mayor riesgo de seguridad en apps web (top 1).
- Significa que las restricciones sobre lo que los usuarios autenticados pueden hacer no se aplican de forma correcta.
- Por ende, los atacantes pueden explotar estos defectos para acceder, de forma **no autorizada**, a funcionalidades y/o datos, cuentas de otros usuarios, ver archivos sensibles, modificar datos, cambiar derechos de acceso y permisos, etc.
- Se trata de una violación del principio de **mínimo privilegio o denegación por defecto**, según el cual el acceso sólo debe ser permitido para capacidades, roles o usuarios particulares, y no para cualquier persona.
- Eludir las comprobaciones de control de acceso modificando la URL (alteración de parámetros o navegación forzada), el estado interno de la aplicación o la página HTML, o mediante el uso de una herramienta que modifique los pedidos a APIs.
- Permitir ver o editar la cuenta de otra persona, con tan solo conocer su ID (referencia directa insegura a objetos)
- Acceder a APIs con controles de acceso inexistentes para los métodos POST, PUT y DELETE.
- Elevación de privilegios:
  - Actuar como usuario sin haber iniciado sesión.
  - Actuar como administrador cuando se inició sesión como usuario regular.
- Manipulación de metadatos, como reutilizar o modificar un token de control de acceso JSON Web Token (JWT), una cookie o un campo oculto, manipulándolos para elevar privilegios o abusar de la invalidación de tokens JWT.
- Configuraciones incorrectas de CORS (uso compartido de recursos de origen cruzado) que permiten el acceso a APIs desde orígenes no autorizados o confiables.
- Forzar la navegación a páginas autenticadas siendo usuario no autenticado o a páginas privilegiadas siendo usuario regular.

### Control de acceso HTTP (CORS)

- Mecanismo que usa headers HTTP adicionales para permitir que un user agent obtenga permiso para acceder a recursos seleccionados desde un servidor, en un origen distinto.
- Un agente crea un HTTP request de **origen cruzado** cuando solicita un recurso desde un dominio distinto, un protocolo o un puerto diferente al del documento que lo generó.
- Por seguridad, los navegadores restringen los HTTP requests de origen cruzados iniciados dentro de un script.
- De forma simple, CORS es una regla que dice: Un sitio no puede obtener datos de otro sitio excepto que ese otro sitio lo permita.

### A01-2021: Ejemplos

#### 1

- Es importante tener mucho cuidado con los query args en las URLs.
- Un atacante puede modificar un parámetro en la URL para acceder a datos que deberían estar restringidos.
- El problema está en no verificar los datos de la URL antes de acceder a la base de datos.

```
pstmt.setString(1, request.getParameter("acct"));
ResultSet results = pstmt.executeQuery();
...

https://example.com/app/accountInfo?acct=notmyacct
```

#### 2

- Un atacante puede imaginarse nombres de URL de la página a las cuales no se puede acceder normalmente (clickeando) y simplemente escribirlas en la barra de navegación, y si no están protegidas podrá ganar acceso no autorizado.
- El problema está en no verificar qué host está accediendo a cada URL que tenemos (verificar que ese host tenga autorización).

### A01-2021: Referencia directa insegura a objetos

- Una **referencia directa a un objeto** ocurre cuando un dev expone una referencia a la implementación interna de un objeto (que puede ser un archivo, un directorio, un registro de DB, una clave, una URL o un parámetro de un formulario).
- Si no existe un control, un atacante puede manipular esta referencia para acceder a objetos sin autorización.
- Un atacante, como usuario autorizado en el sistema, simplemente modifica el valor de un parámetro que se refiere directamente a un objeto del sistema a otro objeto para el que el usuario no se encuentra autorizado.
- Las aplicaciones no siempre verifican que el usuario tiene autorización sobre el objetivo.

### C7: Aplicar controles de acceso

- El control de acceso (o autorización) es el proceso de otorgar o denegar solicitudes específicas de un usuario, programa o proceso.
- El control de acceso también implica el acto de otorgar y revocar estos privilegios.
- Hay varios tipos diferentes de diseño de control de acceso que se deben considerar:
  - DAC.
  - MAC.
  - RBAC.
  - ABAC.

#### DAC (Discretionary Access Control)

- El dueño o creador de un recurso tiene la autoridad de conceder o restringir acceso a ese recurso.
- Además, a los que tienen acceso, el dueño define cuales tipos de privilegios tienen y cuales no.

#### MAC (Mandatory Access Control)

- El acceso es controlado por una autoridad central basada en clasificaciones de seguridad (**etiquetas**) asignadas tanto a usuarios como a recursos.
- Las reglas se aplican en todo el sistema y no pueden ser anuladas por usuarios o propietarios.

#### RBAC (Role Based Access Control)

- Los permisos de acceso se asignan a **roles** en lugar de a usuarios individuales.
- Luego, los usuarios son asignados a los roles apropiados (ej. administrador, editor, visualizador), heredando los permisos asociados con dichos roles.

#### ABAC (Attribute Based Access Control)

- Las decisiones de acceso se toman evaluando **atributos** asociados con el usuario, el recurso al que se accede, la acción solicitada y, potencialmente, factores ambientales (como la hora del día o la ubicación).
- Las políticas usan estos atributos para determinar si se debe otorgar o no el acceso.

#### Principios

- **Diseñar el control de acceso a fondo**:
  - El control de acceso es una de las áreas principales del diseño de seguridad de aplicaciones que debe diseñarse minuciosamente desde el principio, especialmente cuando se abordan requisitos como el control de acceso de múltiples usuarios.
  - El diseño del control de acceso puede comenzar simple, pero a menudo puede convertirse en un control de seguridad complejo y con muchas funciones
  - Al evaluar la capacidad de control de acceso de los frameworks de software, asegúrese de que su funcionalidad de control de acceso permita la personalización para sus necesidades específicas de funciones de control de acceso.
- **Forzar que todas las solicitudes pasen por controles de control de acceso**:
  - Asegúrese de que todas las solicitudes pasen por algún tipo de capa de verificación de control de acceso.
  - Las tecnologías como los filtros Java u otros mecanismos de procesamiento automático de solicitudes son artefactos de programación ideales que ayudarán a garantizar que todas las solicitudes pasen por algún tipo de verificación de control de acceso.
- **Denegar por defecto**:
  - Principio de que si una solicitud no se permite específicamente, se rechaza.
  - Ejemplos:
    - El código de la aplicación puede generar un error o una excepción al procesar las solicitudes de control de acceso. En estos casos, siempre se debe negar el control de acceso.
  - Cuando un administrador crea un nuevo usuario o un usuario se registra para una nueva cuenta, esa cuenta debe tener un acceso mínimo o nulo de forma predeterminada hasta que se configure ese acceso.
  - Cuando se agrega una nueva función a una aplicación, se debe negar a todos los usuarios el uso de esa función hasta que esté configurada correctamente.
- **Principio de mínimo privilegio**:
  - Asegúrese de que a todos los usuarios, programas o procesos se les proporcione el mínimo acceso necesario posible.
  - Tenga cuidado con los sistemas que no proporcionan capacidades de configuración de control de acceso granular.
- **No codificar roles**:
  - Muchos marcos de aplicaciones tienen de forma predeterminada un control de acceso basado en roles.
  - Es común encontrar un código de aplicación que esté lleno de comprobaciones de esta naturaleza.
  - Ejemplo: `if (user.hasRole("ADMIN")) || (user.hasRole("MANAGER")) { deleteAccount(); }`.
  - La programación basada en roles de esta naturaleza es frágil.
  - Es fácil crear comprobaciones de roles incorrectas o faltantes en el código.
  - La programación basada en roles no permite la tenencia múltiple.
  - Se requerirán medidas extremas como bifurcar el código o verificaciones adicionales para cada cliente para permitir que los sistemas basados en roles tengan diferentes reglas para diferentes clientes.
  - Las bases de código grandes con muchas comprobaciones de control de acceso pueden ser difíciles de auditar o verificar la política general de control de acceso de la aplicación.
  - En su lugar, considere la siguiente metodología de programación de control de acceso: `if (user.hasAccess("DELETE_ACCOUNT")) { deleteAccount(); }`.
  - Las comprobaciones de control de acceso basadas en atributos o características de esta naturaleza son el punto de partida para construir sistemas de control de acceso bien diseñados y ricos en funciones.
  - Este tipo de programación también permite una mayor capacidad de personalización del control de acceso a lo largo del tiempo.
- **Registrar todos los eventos de control de acceso**:
  - Todas las fallas de control de acceso deben registrarse, ya que pueden indicar que un usuario malintencionado está investigando la aplicación en busca de vulnerabilidades.

---

<h1 align="center">Clase 6 - 29 de abril, 2025</h1>

## DDoS

### Concepto

- Un ataque DDoS (Distributed Denial of Service) busca sobrecargar un servicio online con tráfico malicioso desde múltiples fuentes coordinadas.
- Esto hace que ese servicio se vuelva inaccesible para los usuarios legítimos.
- La clave es la distribución del ataque, que hace dificil bloquear a las fuentes individuales.
- El objetivo es interrumpir la disponibilidad del servicio atacado.

### Tipos

- **Ataques volumétricos**: inundación de tráfico.
- **Ataques de protocolo**: explotan debilidades en la comunicación.
- **Ataques a la capa de aplicación**: dirigidos a funcionalidades específicas del software.

## A02-2021 - Fallas Criptográficas

### Concepto

- **Fallas Criptográficas** (anteriormente "Exposición de Datos Sensibles") es el segundo riesgo más crítico según OWASP. Se refiere a errores en el uso de criptografía que exponen información confidencial.
- **Descripción general:**
  - Implica fallos en la implementación, configuración o ausencia de criptografía.
  - Expone datos sensibles como credenciales, PII, historiales médicos o tarjetas de crédito.
  - Ha sido uno de los ataques con mayor impacto en los últimos años.
- **Errores comunes:**
  - No cifrar datos sensibles en reposo o en tránsito.
  - Usar algoritmos obsoletos o vulnerables (MD5, SHA-1, RC4).
  - Emplear criptografía propia (no probada ni auditada).
  - Usar algoritmos fuertes de manera incorrecta.
  - Hardcodear claves o almacenarlas sin protección.
- **Técnicas de ataque comunes:**
  - Robo de claves criptográficas.
  - Ataques Man-in-the-Middle (MITM).
  - Robo de datos en texto plano desde el cliente, el servidor o durante la transmisión.
  - Uso de bases de datos públicas de hashes y técnicas de cracking (por ejemplo, con GPU).
- **CWE asociados:**
  - CWE-259: Uso de contraseñas en el código fuente.
  - CWE-327: Algoritmo criptográfico inseguro.
  - CWE-331: Entropía insuficiente.
- **Consecuencias:**
  - Compromiso de datos que deberían estar protegidos.
  - Pérdida de confidencialidad y confianza.
  - Riesgos legales y regulatorios por exposición de información protegida.

### Como saber si la aplicación es vulnerable

- Es fundamental determinar las necesidades de protección de datos en tránsito y en almacenamiento.
- Contraseñas, tarjetas de crédito, registros médicos, info personal y datos sensibles del negocio requieren protección adicional.
- Ejemplos de ataques:
  - Si se envía información confidencial a través de Internet sin seguridad en las comunicaciones, un atacante en una conexión inalámbrica compartida podría ver y robar los datos de otro usuario.
  - Además, un atacante podría usar SQL Injection para robar contraseñas y otras credenciales de una base de datos de aplicaciones y exponer esa información al público.
- Se debe tener en cuenta la Ley 25.326 de Protección de Datos Personales.
  - Datos personales.
  - Datos sensibles.
- Para los datos sensibles hay que pensar en:
  - ¿Algunos de esos datos se guardan en plano? → ¿Considerando backups?
  - ¿Estos datos se transmiten como texto plano? ¿Ya sea Interna o externamente?
  - ¿Se usan algoritmos de cifrado viejos, débiles?
- Sobre el manejo de claves de cifrado:
  - ¿Cómo se generan?
  - ¿Cómo se administran?
  - ¿Se rotan?
  - ¿Como se recuperan contraseñas olvidadas?
  - ¿Ante un compromiso existe procediento de respuesta?

### Ejemplos de ataques

#### 1. Cifrado reversible vulnerable a SQL Injection

- Aunque los datos (como números de tarjeta) están cifrados en la base de datos, se descifran automáticamente al consultarlos.
- Si hay una vulnerabilidad de inyección SQL, un atacante puede acceder a los datos en texto plano.

#### 2. Falta o mal uso de TLS

- El sitio permite conexiones sin HTTPS o usa cifradores débiles.
- Un atacante puede interceptar la conexión (por ejemplo, en Wi-Fi pública), robar cookies de sesión y secuestrar la sesión del usuario, accediendo o modificando información privada.

#### 3. Contraseñas sin protección adecuada

- Se almacenan con hashes simples o sin salt.
- Si un atacante obtiene acceso (por ejemplo, mediante carga de archivos mal gestionada), puede usar diccionarios de hashes precalculados para revelar todas las contraseñas.

### Clasificación de los datos

- Es fundamental clasificar los datos en un sistema y determinar a **qué nivel de sensibilidad pertenece cada dato**.
- Luego, cada categoría de datos se puede asignar a las reglas de protección necesarias para cada nivel de sensibilidad.
- Por ejemplo:
  - La información de marketing público que no es confidencial puede clasificarse como **datos públicos** que se pueden colocar en el sitio web público.
  - Pero los números de tarjetas de crédito pueden clasificarse como datos de usuario privados que pueden necesitar ser encriptados mientras están almacenados o en tránsito.

### Cifrado de datos en tránsito

- Al transmitir datos confidenciales a través de cualquier red, se debe considerar la seguridad de las comunicaciones de extremo a extremo (o cifrado en tránsito) de algún tipo.
- **TLS** es el protocolo criptográfico más común para la seguridad de las comunicaciones.
  - Se usa en apps web, servicios web, apps mobile, etc para comunicarse a través de una red de forma segura.
  - TLS debe ser configurado correctamente antes de usarlo.
- El beneficio principal de la seguridad de la capa de transporte es la protección de los datos de la aplicación web contra la divulgación y modificación no autorizadas cuando se transmite entre clientes (navegadores web) y el servidor de aplicaciones web, y entre el servidor de aplicaciones web y el back-end y otros no basados en navegador.

### Cifrado en reposo

#### Concepto

- La primera regla fundamental de la gestión de datos sensibles es evitar almacenar éstos cuando sea posible: `lo que no tenés, no te lo pueden robar`.
- Cuando se deben almacenar datos sensibles, siempre se debe asegurar que estén **protegidos criptográficamente** para evitar su divulgación y modificación no autorizadas.
  - La criptografía es uno de los temas más avanzados de seguridad de la información, y uno cuya comprensión requiere gran educación y experiencia.
  - Es difícil hacerlo bien porque hay muchos enfoques para el cifrado, cada uno con sus ventajas y desventajas que los arquitectos y desarrolladores de soluciones web deben comprender a fondo.
  - Además, la **investigación seria en criptografía se basa típicamente en matemática avanzada y teoría de números**, lo que constituye una seria barrera de entrada.
  - En lugar de crear una capacidad criptográfica desde cero, se recomienda encarecidamente **usar soluciones abiertas y revisadas por pares**, como el proyecto Google Tink, Libsodium y la capacidad de almacenamiento seguro integrada en muchos frameworks de software y servicios en la nube.

#### Dispositivos móviles

- Las aplicaciones móviles corren un riesgo particular de fuga de datos porque los dispositivos móviles se pierden o son robados con regularidad, y contienen datos confidenciales.
- Como regla general, solo los datos mínimos requeridos deben almacenarse en el dispositivo móvil.
- Pero si debe almacenar datos confidenciales en un dispositivo móvil, entonces los datos confidenciales deben almacenarse dentro del directorio de almacenamiento de datos específico de cada sistema operativo móvil.
- En Android, será el almácen de claves de Android y en iOS será el llavero de iOS.

#### Manejo de secretos

- Las aplicaciones contienen numerosos "**secretos**" necesarios para las operaciones de seguridad.
- Estos incluyen:
  - Certificados.
  - Contraseñas de conexión SQL.
  - Credenciales de cuentas de servicios de terceros.
  - Contraseñas.
  - Claves SSH.
  - Claves de cifrado y más.
- **La divulgación o modificación no autorizada de estos secretos podría llevar a un compromiso total del sistema**.
- Al administrar los secretos de la aplicación, tenga en cuenta lo
  siguiente.
  - No almacene nunca secretos en código, archivos de configuración ni los pase a través de variables de entorno.
  - Guarde las claves y sus otros secretos de nivel de aplicación en una bóveda de secretos como **KeyWhiz** o el proyecto **Vault de Hashicorp** o **Amazon KMS** para proporcionar almacenamiento seguro y acceso a secretos de nivel de aplicación en tiempo de ejecución.

## TLS

### Concepto

- TLS = Transport Layer Security.
- Secure Socket Layer (SSL) fue el protocolo original que se usó para proporcionar cifrado para el tráfico HTTP, en forma de
  HTTPS.
- Hubo dos versiones de SSL publicadas: **las versiones 2 y 3 tienen serias debilidades criptográficas y ya no deberían usarse**.
- Por varias razones, la siguiente versión del protocolo (efectivamente SSL 3.1) se denominó Transport Layer Security (TLS) versión 1.0.
- Posteriormente se lanzaron las versiones 1.1, 1.2 y 1.3 de TLS.
- Los términos "SSL", "SSL / TLS" y "TLS" se usan indistintamente con frecuencia y, en muchos casos, se usa "SSL" cuando se hace referencia al protocolo TLS más moderno.

### Beneficios

- **Confidencialidad**: protección contra que un atacante lea el contenido del tráfico.
- **Integridad**: protección contra un atacante que modifica el tráfico.
- **Prevención de reproducción**: protección contra un atacante que reproduce solicitudes en el servidor.
- **Autenticación**: permite al cliente verificar que está conectado al servidor real (tenga en cuenta que la identidad del cliente no se verifica a menos que se usen certificados de cliente).

### Handshake

El handshake de TLS es un proceso que establece una conexión segura y encriptada entre un cliente y un servidor. Se compone de varios pasos:

1. **Client Hello**:
   1. El cliente inicia el protocolo de enlace enviando un mensaje de "saludo" al servidor.
   2. El mensaje incluirá qué versión de TLS admite el cliente, los conjuntos de cifrado admitidos y una cadena de bytes aleatorios conocida como "cliente aleatorio".
2. **Server Hello**:
   1. En respuesta al mensaje de saludo del cliente, el servidor envía un mensaje que contiene:
      1. El certificado SSL del servidor.
      2. El conjunto de cifrado elegido por el servidor.
      3. El "servidor aleatorio", otra cadena aleatoria de bytes que genera el servidor.
3. **Premaster secret**:
   1. El cliente envía una cadena aleatoria de bytes más, el "premaster secret".
   2. El secreto de premaster está encriptado con la clave pública y el servidor solo puede desencriptarlo con la clave privada (el cliente obtiene la clave pública del certificado SSL del servidor).
4. **Clave privada utilizada:**:
   1. El servidor descifra el secreto de premaster.
5. **Claves de sesión creadas**:
   1. Tanto el cliente como el servidor generan claves de sesión desde el cliente aleatorio, el servidor aleatorio y el secreto del premaster.
   2. Deberían llegar a los mismos resultados.
6. **El cliente está listo**:
   1. El cliente envía un mensaje "terminado" que está encriptado con una clave de sesión.
7. **El servidor está listo**:
   1. El servidor envía un mensaje "terminado" cifrado con una clave de sesión.
8. **Cifrado simétrico seguro logrado**:
   1. El protocolo de enlace se completa y la comunicación continúa utilizando las claves de sesión.

### Certificados

- Se debe usar claves fuertes y protegerlas.
- La clave privada usada para generar la clave de cifrado debe ser lo suficientemente fuerte para la vida útil de la clave privada y el certificado correspondiente.
- La mejor práctica actual es seleccionar un tamaño de clave >= 2048 bits.
- La clave privada también debe protegerse del acceso no autorizado mediante permisos del sistema de archivos y otros controles técnicos y administrativos.
- Se deben usar algoritmos de hash criptográficos potentes.
- Los certificados deben usar SHA-256 para el algoritmo hash, en lugar de los algoritmos MD5 y SHA-1 más antiguos.
  - Estos tienen una serie de debilidades criptográficas y los navegadores modernos no confían en ellos.

### Dominios

- El nombre de dominio del certificado debe coincidir con el nombre completo del servidor que presenta el certificado.
- Históricamente, esto se almacenaba en el atributo commonName (CN) del certificado.
- Sin embargo, las versiones modernas de Chrome ignoran el atributo CN y requieren que el Fully Qualified Domain Name esté en el atributo subjectAlternativeName (SAN).
- Por motivos de compatibilidad, los certificados deben tener el FQDN principal en la CN y la lista completa de FQDN en la SAN.
- Al crear el certificado, se debe tener en cuenta lo siguiente:
  - Considere si también debe incluirse el subdominio "www".
  - No incluya nombres de host no calificados.
  - No incluya direcciones IP.
  - No incluya nombres de dominio internos en certificados externos.
  - Si se puede acceder a un servidor mediante FQDN internos y externos, configúrelo con varios certificados.

### Dominios wildcard

- Los certificados wildcard pueden ser convenientes, sin embargo, violan el principio de mínimo privilegio, ya que un solo certificado es válido para todos los subdominios de un dominio (como `*.example.org`).

- Cuando varios sistemas comparten un certificado \*, aumenta la probabilidad de que la clave privada del certificado se vea comprometida, ya que la clave puede estar presente en varios sistemas.
- Además, el valor de esta clave aumenta significativamente, lo que la convierte en un objetivo más atractivo para atacantes.

### Autoridad de certificación (CA)

- Con el fin de ser de confianza para los usuarios, los certificados deberán ser firmados por una autoridad de certificados de confianza: **CA**.
- Para las aplicaciones orientadas a Internet, ésta debe ser una de las CA reconocidas y de confianza automática para los sistemas operativos y navegadores.
- LetsEncrypt CA proporciona certificados SSL validados de dominio gratuitos, en los que confían los principales navegadores.
- Para aplicaciones internas, se puede utilizar una CA interna.
- Esto significa que el FQDN del certificado no se expondrá (ni a una CA externa ni públicamente en las listas de transparencia de certificados).
- Sin embargo, el certificado solo será de confianza para los usuarios que hayan importado y hayan confiado en el certificado de CA interno que se usó para firmarlos.

### Aplicaciones

- Se recomienda usar TLS para todas las páginas.
- TLS debe usarse para **todas las páginas**, no solo para aquellas que se consideran confidenciales, como la página de inicio de sesión.
- Si hay páginas que no imponen el uso de TLS, estas podrían darle al atacante la oportunidad de sniffear información confidencial como tokens de sesión o inyectar JavaScript malicioso en las respuestas para llevar a cabo otros ataques contra el usuario.
- Para las aplicaciones de cara al público, puede ser apropiado hacer que el servidor web escuche las conexiones HTTP no cifradas en el puerto 80 y luego redirigirlas inmediatamente con una redirección permanente (HTTP 301) para brindar una mejor experiencia a los usuarios que escriben manualmente el nombre de dominio.
- Esto debería ser compatible con el encabezado HTTP Strict Transport Security (HSTS) para evitar que accedan al sitio a través de HTTP en el futuro.

### TLS y No TLS

- No mezclar contenido TLS y no TLS.
- Una página que está disponible a través de TLS no debe incluir ningún archivo de recursos (como JavaScript o CSS) que se carguen a través de HTTP no cifrado.
- Estos recursos no cifrados podrían permitir que un atacante sniffear las cookies de sesión o inyecte código malicioso en la página.
- Los navegadores modernos también bloquearán los intentos de cargar contenido a través de HTTP no cifrado en páginas seguras.

### Cookies "seguras"

- Todas las cookies deben estar marcadas con el atributo "secure", que indica al navegador que las envíe solo a través de conexiones HTTP cifradas, para evitar que sean rastreadas desde una conexión HTTP no cifrada.
- Esto es importante incluso si el sitio web no escucha en HTTP (puerto 80), ya que un atacante que realiza un ataque de Man In The Middle podría presentar un servidor web falsificado en el puerto 80 al usuario para robar su cookie.
- [Referencia](https://infosec.mozilla.org/guidelines/web_security#cookies).

### Caché de datos confidenciales

- Aunque TLS brinda protección de datos mientras están en tránsito, **no brinda ninguna protección para los datos una vez que han llegado al sistema solicitante**.
- Como tal, esta información puede almacenarse en la memoria caché del navegador del usuario, o por cualquier proxy intermedio que esté configurado para realizar el descifrado TLS.
- Cuando se devuelven datos confidenciales en las respuestas, se deben usar headers HTTP para indicar al navegador y a los servidores proxy que **no almacenen la información en caché**, a fin de evitar que se almacene o se devuelva a otros usuarios.
- Esto se puede lograr configurando los siguientes encabezados HTTP en la respuesta:
  - `Cache-Control: no-cache, no-store, must-revalidate`.
  - `Pragma: no-cache`.
  - `Expires: 0`.

### HSTS

#### Concepto

- HTTP Strict Transport Security (HSTS) es una mejora de seguridad opcional que es especificada por la aplicación web mediante el uso de un encabezado de respuesta.
- Una vez que un navegador compatible recibe este encabezado, ese navegador evitará que se envíen comunicaciones a través de HTTP al dominio especificado y, en su lugar, enviará todas las comunicaciones a través de HTTPS.

#### Amenazas

HSTS aborda las siguientes amenazas:

- Usuario ingresa a un sitio y está sujeto a un atacante Man In The Middle.
  - HSTS redirige automáticamente las solicitudes HTTP a HTTPS para el dominio de destino.
- La aplicación web que está destinada a ser puramente HTTPS contiene inadvertidamente enlaces HTTP o sirve contenido a través de HTTP.
  - HSTS redirige automáticamente las solicitudes HTTP a HTTPS para el dominio de destino.
- Un atacante MITM intenta interceptar el tráfico de un usuario víctima usando un certificado no válido y espera que el usuario acepte el certificado incorrecto.
  - HSTS no permite que un usuario anule el mensaje de certificado no válido.

---

<h1 align="center">Clase 7 - 6 de mayo, 2025</h1>

## TLS

### Let's Encrypt

- Autoridad de certificación que surgió en 2016 y proporciona certificados gratuitos para TLS a través de un proceso automatizado diseñado para eliminar el complejo proceso actual de creación manual, la validación, firma, instalación y renovación de los certificados de sitios web seguros.
- Es una espada de doble filo, ya que si bien tiene sus cosas positivas, le permitió a atacantes crear páginas falsas, réplicas de páginas legítimas, para estafar a la gente. Como estas páginas falsas usaban certificados, parecían legítimas.

### Homografía

- La homografía entre palabras es la circunstancia por la cual dos palabras de diferente significado coinciden en su escritura.
- Es un tipo de ataque.
- Básicamente, usan letras en el dominio (URL) que se ven casi idénticas a otras para engañar a la gente.

### SSLStrip

- Herramienta usada en ataques MITM para interceptar la comunicación entre un usuario y un servidor web.
- Su objetivo principal es degradar una conexión HTTPS segura a una conexión HTTP insegura.
- SSLStrip se sitúa entre el usuario y el sitio web.
- Cuando el navegador del usuario intenta establecer una conexión segura (HTTPS), la herramienta intercepta esta solicitud.
- Luego, establece una conexión HTTPS segura con el servidor web, pero presenta al navegador del usuario una conexión HTTP sin cifrar.
- Como resultado, toda la información sensible que el usuario introduce en el sitio web (contraseñas, datos de tarjetas de crédito, etc.) se transmite a través de una conexión HTTP insegura, permitiendo al atacante interceptarla con facilidad.
- El usuario, por su parte, puede no notar la diferencia, ya que el sitio web se ve y funciona de manera similar, aunque sin la protección del cifrado SSL/TLS.

### SSL Pinning

- Técnica de seguridad que busca prevenir ataques de MITM de una manera más robusta que la simple validación de certificados por parte de las Autoridades de Certificación (CAs).
- En lugar de confiar en cualquier certificado firmado por una CA de confianza, SSL Pinning "ancla" o "fija" un certificado específico o su clave pública dentro de la aplicación cliente (por ejemplo, una app móvil o un navegador web).
- Cuando la aplicación intenta establecer una conexión segura (HTTPS) con un servidor, no solo verifica que el certificado del servidor sea válido y esté firmado por una CA de confianza, sino que también compara el certificado presentado por el servidor (o su clave pública) con la copia "anclada" dentro de la aplicación.
- Si el certificado o la clave pública no coinciden exactamente con la información "anclada", la aplicación rechaza la conexión, incluso si el certificado del servidor es técnicamente válido.

### Frida

- Herramienta de dynamic instrumentation muy usada para bypassear mecanismos de seguridad en apps móviles, especialmente el SSL pinning.
- Permite:
  - Inyectar scripts (JavaScript) en procesos de apps en ejecución.
  - Interceptar funciones.
  - Modificar comportamientos en caliente.

### Certificate Transparency

- Estándar abierto publicado en 2013.
- Es un framework open source de monitorización y auditado de certificados digitales.
- Este ecosistema compuesto principalmente de logs, monitores y auditores, permite a cualquier interesado estar informado si se emite un nuevo certificado para un determinado dominio, ayudando así a **mitigar el uso de certificados fraudulentos emitidos sin el conocimiento del propietario del dominio para el que se emiten**.
- Además, esta tecnología permite realizar un seguimiento de la actividad de las autoridades certificadoras (CAs), de modo que puedan ser detectados rápidamente en el caso por ejemplo de que hayan sido comprometidas para emitir certificados fraudulentos.

## Almacenamiento de contraseñas

## AO3-2021 - Inyección

---

<h1 align="center">Clase 8 - 13 de mayo, 2025</h1>

## ?

---
