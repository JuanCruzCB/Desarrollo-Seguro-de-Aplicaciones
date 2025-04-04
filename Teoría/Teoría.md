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

## ?

---
