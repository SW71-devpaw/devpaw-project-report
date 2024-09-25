# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management.
En esta sección del informe se detallan las decisiones y principios fundamentales que guiarán al equipo en la preservación de la coherencia y estabilidad del proyecto durante todo el proceso de desarrollo de la solución.

Este enfoque asegura que cada cambio, modificación o actualización del software se gestione de manera controlada y organizada, manteniendo la integridad del producto a lo largo de su evolución.
### 6.1.1. Software Development Environment Configuration.

**Configuración del Entorno de Desarrollo de Software**

En esta sección se incluyen los enlaces a las aplicaciones y productos de software desarrollados a lo largo del ciclo del proyecto, utilizando las herramientas y programas adecuados.

Con ese fin, se organizará en las siguientes secciones:

* Project Management
* Requirements Management
* Product UX/UI Design
* Software Development
* Software Testing
* Software Documentation

Asimismo, se clasificarán los elementos de estas secciones como rutas de referencia (para software basado en modelos Saas) o rutas de descarga (para productos que se ejecuten en las computadoras de los miembros del equipo) para cada uno de los productos de software.

**Project Management**

Esta disciplina se fundamenta en la administración de proyectos y busca principalmente la mejora de procesos y su entorno con el propósito de lograr los resultados esperados.

* Durante el ciclo digital del proyecto, se llevará a cabo la implementación de un producto de software basado en el modelo SaaS, el cual funcionará a través de un navegador web; no obstante, no se desarrollará una versión de la aplicación móvil correspondiente.

**Requirements Management:**

Este proceso se enfoca en asegurar que una organización documente, verifique y satisfaga las necesidades y expectativas de sus clientes, así como las de las partes interesadas internas o externas.

* **Pivotal Tracker:** Esta herramienta se describe como una plataforma que facilita la gestión de las historias de usuario, organizándolas en epopeyas y evaluando su importancia en el programa según su puntuación. Se utilizó debido a su capacidad para permitir que cada miembro del equipo comparta una vista en tiempo real de los avances en cada proyecto, contribuyendo con diferentes secciones o ajustando el flujo del proyecto.

**Product UX/UI Design**

Esta herramienta facilita la creación digital de modelos que se integran en la vida del consumidor. En este caso, estamos desarrollando un modelo de sitio web compatible tanto con computadoras como con dispositivos móviles.

Para lograrlo, utilizamos varias herramientas de diseño y colaboración, que incluyen:

**1\. Uxpressia:** Uxpressia es una plataforma en línea especializada en el mapeo de la trayectoria del cliente. Nos ayuda a crear mapas de impacto y perfiles de usuario, como User Personas, Empathy Maps y Journey Maps. Puedes encontrar más información sobre Uxpressia en [este enlace](https://uxpressia.com/).

**2\. MIRO:** MIRO es una pizarra digital colaborativa en línea que se adapta a diversas actividades colaborativas, como investigación, ideación, creación de lluvias de ideas y mapas mentales. Es una herramienta versátil que facilita el trabajo en equipo. Descubre más sobre MIRO en [su sitio web](https://miro.com/app/dashboard/).

**3\. Figma:** Figma es una herramienta de prototipado web y un editor de gráficos vectoriales. A diferencia de otras herramientas, Figma se ejecuta en línea, lo que permite crear modelos que funcionan tanto en navegadores web como en navegadores móviles. Puedes explorar Figma en [este enlace](https://www.figma.com/design/).

**4\. Lucid Chart:** Esta es una aplicación de diagramación en línea que permite a los usuarios colaborar y trabajar juntos en tiempo real para crear una variedad de diseños, incluidos diagramas UML, mapas mentales, prototipos de software y otros tipos de diagramas. Puedes conocer más acerca de Lucid Chart en [este enlace](https://www.lucidchart.com/pages/es).

**5\. Overflow:** Overflow es una herramienta de diagramación que ofrece la posibilidad de colaborar en tiempo real. Utilizamos esta herramienta para crear diagramas de Userflows. Si deseas obtener más información sobre Overflow, visita [su sitio web](https://userflow.com/app/).

Estas herramientas nos ayudan a dar vida a nuestros diseños digitales y a garantizar que nuestros productos sean accesibles y atractivos en diferentes plataformas.

**Software Development:**

El desarrollo de software es una metodología aplicada en la creación de productos de software. Esta metodología se utiliza para establecer un proceso que guía el desarrollo del software, y cada uno de sus pasos describe un enfoque específico para las distintas actividades que ocurren durante el proceso.

Aquí te presentamos algunas herramientas y tecnologías clave que utilizaremos en el proyecto:

**1\. GitHub:** GitHub es una plataforma de repositorio comunitario que se utiliza para almacenar y gestionar los avances de proyectos realizados por grupos de personas. Puedes acceder al repositorio del proyecto en [este enlace](https://github.com/sw53-metasoft).

**2\. Webstorm:** Webstorm es un entorno de desarrollo de JetBrains, una empresa especializada en software, orientado al desarrollo web en JavaScript. Esta herramienta proporciona facilidades para probar sitios web en navegadores como Google Chrome. En nuestro proyecto, utilizaremos webstorm para trabajar con lenguajes como HTML, CSS y JavaScript. Obtén más información sobre WebStorm [aquí](https://www.jetbrains.com/webstorm/).

**3\. HTML:** HTML es un lenguaje de marcado que se utiliza en el desarrollo de sitios web para crear hipertextos y enlazar a otros documentos. Este lenguaje proporciona herramientas para diseñar sitios web y se puede combinar eficazmente con CSS y JavaScript. En nuestro proyecto, utilizaremos HTML para implementar la documentación de la página web. Obtén más información sobre la edición de archivos HTML en WebStorm [aquí](https://www.jetbrains.com/help/idea/editing-html-files.html).

**4\. CSS:** CSS es un lenguaje de diseño destinado al entorno web, que posibilita la mejora de la interfaz de usuario previamente diseñada al añadir elementos como colores y tamaños, entre otros. Además, es posible crear un estilo en CSS y compartirlo en el sitio web creado en HTML. Este lenguaje será empleado en la implementación del diseño de nuestra plataforma web. Puedes obtener más información sobre CSS en [enlace](https://www.jetbrains.com/help/idea/style-sheets.html).

**5\. JavaScript:** Es un lenguaje de programación que es interpretado por otros programas. Funciona bajo el paradigma de programación orientada a objetos (POO), utilizando prototipos en lugar de clases para la implementación. Este lenguaje permite crear dinámicas para los usuarios a través de la lógica de programación y será utilizado en la creación de las interacciones dinámicas en la plataforma web. Puedes encontrar más detalles sobre JavaScript en [enlace](https://www.jetbrains.com/help/idea/javascript-specific-guidelines.html).

Estas herramientas y tecnologías desempeñarán un papel fundamental en la creación exitosa de nuestro producto de software.

**Software Testing:**

Se trata de la acción de evaluar los elementos y el funcionamiento del software sometido a prueba mediante procesos de validación y verificación.

**Lenguaje Gherkin:** Este lenguaje, conocido como DSL (Lenguaje Específico de Dominio), está diseñado específicamente para abordar problemas particulares. Además de poder ser interpretado en código, permite agregar historias de usuario del programa junto con sus componentes correspondientes, como Característica, Escenario, Ejemplo, Esquema de Escenario, Dado, Cuando, Entonces y Y.

**Software Documentation**

Se refiere a textos escritos o ilustraciones que acompañan al software de computadora o están integrados en su código fuente. Esta documentación tiene como objetivo explicar cómo funciona el software o cómo utilizarlo.

### 6.1.2. Source Code Management.

A continuación se describe la gestión del código fuente, también conocida por las siglas SCM (Source Code Management). Su función principal es rastrear los cambios que realizará el equipo durante el desarrollo de su proyecto en el repositorio de código fuente. Se utilizará como un sistema de control de versiones que le permitirá realizar un seguimiento de los cambios realizados por miembros o desarrolladores individuales del proyecto. Además, es importante tener en cuenta que usaremos GitHub como nuestro sistema de control de versiones.

* **URL de la organización:** SW71-devpaw - https://github.com/SW71-devpaw 

* **URL del repositorio de la Landing Page:** SW71-devpaw - 

* **URL del repositorio del Front-End:** SW71-devpaw - https://github.com/SW71-devpaw/upet-frontend-web

* **URL del repositorio del Reporte:** SW71-devpaw - https://github.com/SW71-devpaw/devpaw-project-report


**GitFlow**

GitFlow es un modelo alternativo para la creación de ramas en Git que se ha convertido en una herramienta esencial para muchos desarrolladores en los últimos años. Este flujo de trabajo de control de versiones, desarrollado y popularizado por Vicent Driessen, desempeña un papel crucial en la gestión de las versiones de un código, facilitando la creación ordenada de nuevas características (Features) y correcciones de problemas urgentes (Hotfixes).

![ GitFlow.png](/assets/img/chapter-vi/Gitflow.png)

Como se mencionó previamente, GitFlow opera con ramas o "branches". A continuación, se detallan las ramas que se utilizarán en el flujo de trabajo de nuestro proyecto.

* **Main Branches:**
  * **Main:** Esta es la rama principal desde la cual se ramifican todas las demás. Contendrá la versión más reciente junto con las versiones anteriores creadas por los desarrolladores. Aquí se mantendrá el historial oficial de las versiones publicadas.
  * **Develop:** Esta rama puede ser creada a partir de la rama principal (Main) y contendrá todas las características (Features) estables. A través de esta rama, el equipo podrá integrar las funcionalidades de manera efectiva.

* **Support Branches**
  A diferencia de las ramas principales, estas ramas secundarias tienen una vida útil limitada, ya que se eliminan al fusionarse con sus ramas primarias.
  * **Feature:**
    * Se ramifica de: develop
    * Debe fusionarse de nuevo en: develop
    * Se utilizan para desarrollar las nuevas funciones que se integrarán en la próxima versión. Es importante destacar que esta rama existe únicamente mientras está en proceso de desarrollo. Sin embargo, una vez que el desarrollador haya completado esa función, se fusionará nuevamente con la rama "develop".

* **Convenciones para nombrar los Features:**
  * **Feture Branch:** feature/name
    **Example:**
    1. feature/welcome
    2. feature/about
    3. feture/myfeture
  * **Conventional Commits**
    El commit debe seguir la siguiente estructura:
    **\<type> [optional scope]: \<description>**
    **[optional body]**
    **[optional footer(s)]**
    * **Type:**
      **1\. feat:** Cuando se agrega un nuevo feature.
      **2\. fix:** cuando corriges un error.
      **3\. build:** cuando afectan los componentes de compilación como la herramienta de compilación, las dependencias o la version del proyecto.
      **4\. chore:** modificaciones privadas del código.
      **5\. docs:** commits que afectan solo a la documentación.
      **6\. refractor:** commits que reescriben o reestructura el código, pero no cambia el comportamiento.
      **7\. perf:** commits especiales que mejoran el rendimiento.
      **8\. style:** commits que no afectan el programa. (espacios en blanco, formato, puntos o comas faltantes).
      **9\. test:** commits que agregan pruebas.
    * **Scope**
      Ofrece información contextual adicional. Aunque es opcional, es beneficioso incluirlo para proporcionar a los desarrolladores una descripción más detallada del commit.
      **\<description>**
      Es una parte obligatoria del formato de los commits. Siempre debemos usar lenguaje en modo imperativo y evitar escribir en mayúsculas
      **[optional body]**
      El cuerpo es opcional y, cuando se utiliza, debe explicar la motivación detrás del cambio y contrastarlo con el comportamiento anterior. Es ideal para mencionar identificadores de problemas y sus relaciones.
      **[optional footer(s)]**
      Esta sección es opcional y puede incluir información sobre cambios significativos. Puede hacer referencia al problema por su identificación y, en esta sección, se incluyen los cambios importantes precedidos por "BREAKING CHANGES:" seguido de uno o dos saltos de línea.
      **Ejemplos:**
      1. feat(welcome): add welcome section
      2. build(release): bump version to 1.0.0
      3. style: remove empty line
      4. feat(sign up): add the button to sign up
      5. feat!: email the costumer when product is shipped
      6. feat: remove ticket list endpoint
         refers to JIRA-1337
         BREAKING CHANGES: ticket enpoints no longer supports list all entites.

Como se mencionó previamente, la gestión de nuestro código fuente se llevará a cabo mediante GitHub. El IDE utilizado en este caso, WebStorm, debe estar vinculado directamente al repositorio creado por nuestra empresa MIRAI. De esta manera, cada commit realizado por un miembro del equipo se subirá automáticamente y se cargará en el GitHub de la organización. Las instrucciones para completar con éxito este proceso de emparejamiento se detallan a continuación:

* **Activar el controlador de versiones del IDE**
  Dado que utilizaremos GitHub para gestionar nuestro código, la opción que debe estar habilitada o seleccionada es aquella que indique que el sistema de control se realizará mediante Git. Para hacer esto, siga los siguientes pasos:
  1. Diríjase a la pestaña "VCS" en WebStorm.
  2. Luego, seleccione la opción "Enable Version Control Integration".

![activar-el-controlador-de-versiones-1.png](/assets/img/chapter-vi/activar-el-controlador-de-versiones-1.png)

Ahora se debe seleccionar el sistema de control a través de Git y, por último aceptar los cambios.

![activar-el-controlador-de-versiones-2.png](/assets/img/chapter-vi/activar-el-controlador-de-versiones-2.png)

* **Aregar una cuenta de GitHub, siga estos pasos:**
  1. Diríjase a la sección de configuración en su aplicación.
  2. Dentro de la pestaña 'File', busque y seleccione la opción 'Settings'.
  3. En la configuración, busque la sección de version control.
  4. Agregue su cuenta de GitHub para obtener acceso a los repositorios.

![aregar-una-cuenta-de-GitHub-1.png](/assets/img/chapter-vi/aregar-una-cuenta-de-GitHub-1.png)

![aregar-una-cuenta-de-GitHub-2.png](/assets/img/chapter-vi/aregar-una-cuenta-de-GitHub-2.png)

* **Configurar el nombre de usuario de Git:** Una vez que hayas establecido el sistema de control de versiones que se vinculará con tu IDE, deberás ingresar la cuenta que utilizarás. Para hacerlo, sigue estos pasos:
  1. Realiza un commit en tu proyecto. Durante este proceso, se te solicitará que ingreses tu nombre de usuario de Git.
  2. Después de haberlo añadido, todos los cambios se guardarán en el repositorio especificado en esa plataforma, siempre y cuando des la orden correspondiente.
  3. Para configurar tu nombre de usuario de Git, primero selecciona la opción 'commit' que se encuentra dentro de la pestaña 'Git'.

![configurar-el-nombre-de-usuario-de-Git-1.png](/assets/img/chapter-vi/configurar-el-nombre-de-usuario-de-Git-1.png)


* **Guardar el progreso en GitHub:** Con todo configurado en WebStorm, ahora puedes subir tu código a GitHub sin problemas. Simplemente dirígete a la opción 'GitHub' que se encuentra en la pestaña 'Git' y comparte el proyecto.

![guardar-el-progreso-en-GitHub-1.png](/assets/img/chapter-vi/guardar-el-progreso-en-GitHub-1.png)

![guardar-el-progreso-en-GitHub-2.png](/assets/img/chapter-vi/guardar-el-progreso-en-GitHub-2.png)

* **Configurar la propiedad del repositorio en GitHub:** Ahora, solo necesitas configurar la ubicación del repositorio. El código ya debería estar guardado en GitHub, pero solo estará presente en tu propia cuenta. Para cambiar la propiedad y transferirla a la organización deseada, sigue estos pasos:
  1. Ingresa al repositorio creado en GitHub.
  2. Selecciona la pestaña 'settings'
  3. Dirigite al apartado de 'DangerZone'
  4. Luego da click en 'transfer'
  5. Finalmente elegimos el nuevo lugar para guardar el repositorio.

![configurar-la-propiedad-del-repositorio-en-GitHub-1.png](/assets/img/chapter-vi/configurar-la-propiedad-del-repositorio-en-GitHub-1.png)

![configurar-la-propiedad-del-repositorio-en-GitHub-2.png](/assets/img/chapter-vi/configurar-la-propiedad-del-repositorio-en-GitHub-2.png)

![configurar-la-propiedad-del-repositorio-en-GitHub-3.png](/assets/img/chapter-vi/configurar-la-propiedad-del-repositorio-en-GitHub-3.png)

![configurar-la-propiedad-del-repositorio-en-GitHub-4.png](/assets/img/chapter-vi/configurar-la-propiedad-del-repositorio-en-GitHub-4.png)


* **Configurar control remoto en Git:** Por último, dado que el repositorio ahora está bajo la propiedad de la empresa y depende de ella, es necesario acceder al control remoto del código. Para hacerlo, simplemente ingresa al repositorio creado y copia la URL del repositorio.

![configurar-control-remoto-en-Git-1.png](/assets/img/chapter-vi/configurar-control-remoto-en-Git-1.png)

Ahora, en el IDE, dirígete a la pestaña 'Git' y elige la opción 'Manage Remotes'.

![configurar-control-remoto-en-Git-2.png](/assets/img/chapter-vi/configurar-control-remoto-en-Git-2.png)

Finalmente, como último paso, debes pegar el enlace copiado en el campo de dirección que solicita el IDE para el control remoto en Git.

![configurar-control-remoto-en-Git-3.png](/assets/img/chapter-vi/configurar-control-remoto-en-Git-3.png)

Si has seguido correctamente todos los pasos y directrices mencionados, entonces has completado la configuración con éxito. Ahora, solo necesitas realizar un commit y los cambios que hayas efectuado se guardarán en el repositorio de GitHub, ya sea que hayas realizado modificaciones en el código, creado nuevas ramas u otras acciones.


### 6.1.3. Source Code Style Guide & Conventions.

En esta sección, se presentarán las pautas, convenciones, estilos y principios que se aplicarán a cada uno de los lenguajes utilizados en la creación de nuestra aplicación. La observancia de este conjunto de directrices reviste una importancia fundamental, ya que tiene el propósito de mantener la calidad estructural del software, mejorar la legibilidad del código fuente y simplificar el mantenimiento del mismo.

Dado que en este proyecto se emplearán varios lenguajes, como HTML, CSS, JavaScript, Python y TypeScript para el desarrollo de la plataforma web, así como Gherkin para el proceso de pruebas del programa, a continuación, se detallarán y describirán las reglas y recomendaciones generales que se tendrán en cuenta al utilizarlos.

**Nomenclatura General**

Para los nombres de variables, objetos, elementos y funciones que se utilicen en el proyecto, se emplearán términos en inglés que estén relacionados con lo que representan. No se utilizarán mayúsculas en estos nombres, ya que, de acuerdo con W3Schools (sin fecha), la combinación de mayúsculas y minúsculas puede dificultar la legibilidad del código. En su lugar, se optará por utilizar exclusivamente letras minúsculas, lo que contribuirá a una mayor claridad en el código.

Ejemplos de nomenclatura estándar, siguiendo las recomendaciones de Google (s.f.):

```
.gallery {}
.video {}
.login {}
```

Estas pautas de nomenclatura ayudarán a mantener una coherencia en el código y facilitarán su comprensión.

**Sangría**

Cuando se trabaje con HTML, CSS y/o JavaScript, se aplicará un espaciado de dos espacios antes de cada línea que se encuentre dentro de un bloque. Según W3Schools (sin fecha), no se recomienda el uso de la tecla "Tabulación". A continuación, se muestra un ejemplo de la sangría estándar en HTML siguiendo las directrices de W3Schools (s.f.):

``` html
<!DOCTYPE html>
<html>
  <head>
    <title>Título del Documento</title>
  </head>
  <body>
    <h1>Encabezado Principal</h1>
    <p>Este es un párrafo dentro del cuerpo del documento.</p>
  </body>
</html>
```

Este estilo de sangría proporciona una estructura clara y organizada al código, lo que facilita su lectura y mantenimiento.

Ejemplo de formato estándar de sangría en CSS, conforme a las recomendaciones de W3Schools (s.f):

``` CSS
html {
  background: #fff; /* Fondo blanco */
  color: #404;     /* Color de texto gris */
}
```

Ejemplo de nomenclatura estándar de la sangría en JavaScript según W3School (s.f.):

``` JavaScript
function toCelsius(fahrenheit) {
  return (5 / 9) * (fahrenheit - 32);
}
```

**Especificaciones generales**

A continuación, detallaremos las reglas específicas necesarias para comprender el código de nuestra aplicación en cada lenguaje.

**HTML:**

HTML, acrónimo de HyperText Markup Language en inglés, es un lenguaje de marcado que se utiliza para definir la estructura de una página web. También incluye funcionalidades que permiten controlar el comportamiento de diferentes elementos del contenido de la página, como cambiar el tamaño del texto o aplicar formato cursiva, entre otros. En nuestro proyecto, emplearemos HTML5, y a continuación, se presentan las características y directrices que debemos seguir para utilizar este lenguaje de la siguiente manera:

* **Declare Document Type**
  La declaración del tipo de documento debe realizarse en la primera línea del código. Según las recomendaciones de Google (s.f.), se prefiere la sintaxis de HTML5 para todos los documentos HTML. Para declararla, simplemente copia lo siguiente:

``` html
<!DOCTYPE html>
```

* **Blank Lines**
  Cada vez que comiences un nuevo bloque, lista o tabla de gran longitud, es recomendable dejar una línea en blanco después del elemento anterior para mejorar la legibilidad y la presentación del código, de acuerdo con las pautas de W3Schools (s.f.):

``` html
<!DOCTYPE html>
<html>
<head>
<title>Animales Exóticos</title>
</head>
<body>
<h1>Lemur de Madagascar</h1>
<p>El lémur de Madagascar es un primate endémico de la isla de Madagascar en el Océano Índico.</p>

<h1>Pangolín</h1>
<p>El pangolín es un mamífero cubierto de escamas que se encuentra en regiones de África y Asia.</p>

<h1>Ocelote</h1>
<p>El ocelote es un felino salvaje que habita en América del Sur y Central, conocido por su pelaje moteado.</p>
</body>
</html>
```

Esta práctica de dejar una línea en blanco mejora la estructura y legibilidad del código HTML.

* **Quote attribute Values**
  Para los valores de los atributos, es común utilizar comillas dobles alrededor de ellos, aunque esta característica no sea obligatoria. Según W3Schools (sin fecha), esto mejora la legibilidad del código y es una práctica común entre los desarrolladores. Aquí tienes un ejemplo:

``` html
<table class="striped">
```

Este enfoque de usar comillas dobles alrededor de los valores de los atributos es ampliamente aceptado y recomendado en la comunidad de desarrollo web.

* **Never Skip the \<title> Element**
  El elemento `<title>` permite que las páginas aparezcan en la lista de resultados al realizar búsquedas en un navegador web. Además, este elemento es responsable de proporcionar el nombre de la página cuando se agrega a marcadores o favoritos. A continuación, se muestra un ejemplo de su uso:

``` html
<title>Guía de Estilo HTML y Convenciones de Codificación</title>
```

Este elemento es esencial para mejorar la identificación y accesibilidad de una página web.

* **HTML Line-Wrapping**
  A pesar de que en un documento HTML no exista un límite estricto en la cantidad de palabras por línea, no se recomienda generar líneas de código excesivamente largas. De hecho, hacerlo dificulta la legibilidad del código. Para continuar en la siguiente línea, se deben utilizar al menos cuatro espacios para distinguir elementos secundarios. Aquí tienes un ejemplo basado en las recomendaciones de Google (sin fecha):

``` html
<button mat-icon-button color='primary' class="menu-button"
(click)="openMenu()">
<mat-icon>menu</mat-icon>
</button>
```

Este estilo de formateo ayuda a mantener un código más legible y facilita la identificación de los elementos y su jerarquía en la estructura del documento HTML.

**CSS:**

CSS, conocido por sus siglas en inglés, Cascading Style Sheets (Hojas de Estilo en Cascada), es un lenguaje que se enfoca en definir y mejorar la presentación de un documento basado en HTML. A continuación, se presentan las directrices que debemos seguir al utilizar CSS:

* **Shorthand Properties**
  Se recomienda utilizar abreviaturas de propiedades y declarar los campos de los elementos en la menor cantidad de líneas posible, según las pautas de Google (sin fecha). Esto aumenta la eficiencia del código y lo hace más legible. Además, se debe evitar agregar unidades después del valor cero. Aquí tienes un ejemplo:

``` css
border-top: 0;
font: 100%/1.6 palatino, georgia, serif;
padding: 0 1em 0;
```

Siguiendo estas recomendaciones, se puede lograr un código CSS más conciso y fácil de entender.

* **Declaration Stops**
  Es importante incluir un punto y coma al final de cada declaración en CSS, al igual que en la mayoría de los lenguajes de programación. Siguiendo las pautas de Google (sin fecha), esta práctica contribuye a mantener la coherencia en el código. A continuación, se muestra un ejemplo:

``` css
html {
  background: #fff;
  color: #404;
}
```

El uso consistente de puntos y comas al final de las declaraciones CSS ayuda a prevenir errores y mejora la claridad del código.

* **Property Name Stops**
  Es necesario incluir un espacio entre los dos puntos que siguen al nombre de una propiedad y el valor correspondiente. Siempre se debe colocar un solo espacio después de los dos puntos, pero no antes. A continuación, se muestra un ejemplo siguiendo esta convención estándar de Google (s.f):

``` css
html {
  background: #fff;
  color: #404;
}
```

Mantener esta consistencia en la colocación de espacios ayuda a que el código CSS sea más legible y fácil de entender.

* **Declaration Block Separation**
  Es esencial utilizar un espacio separador después del nombre de un selector de elemento y antes de la llave que inicia un bloque de declaración CSS. Además, la llave de apertura del bloque debe estar en la misma línea que el selector. Aquí tienes un ejemplo siguiendo esta convención estándar de Google (sin fecha):

``` css
html {
  background: #fff;
  color: #404;
}
```

El cumplimiento de estas directrices ayuda a mantener la consistencia y la legibilidad en el código CSS.

* **CSS quotation Marks**
  No se deben utilizar comillas dobles (`"`) en el código CSS; en su lugar, se permiten y deben emplearse comillas simples (`'`) únicamente para selectores de atributos y valores de propiedades.
  Ejemplo conforme a las pautas estándar de Google (sin fecha):

``` css
html {
  font-family: 'open sans', arial, sans-serif;
}
```

Este ejemplo demuestra el uso de comillas simples para encerrar el valor del atributo `font-family` en CSS, lo cual es una práctica común y aceptada.

**JavaScript**

JavaScript es un lenguaje de programación que permite especificar de manera precisa las acciones que debe realizar el navegador web, incluyendo el orden de ejecución de tareas y la frecuencia con la que se deben llevar a cabo. A continuación, se presentan las pautas para el uso de JavaScript en nuestro proyecto:

* **Spaces around operators**
  Es importante añadir espacios alrededor de cada operador matemático y comas que se utilicen en el código JavaScript. A continuación, se muestra un ejemplo siguiendo la convención estándar de W3Schools (sin fecha):

``` javascript
let x = y + z;
const myArray = ['Volvo', 'Saab', 'Fiat'];
```

El uso consistente de espacios alrededor de operadores y comas mejora la legibilidad del código JavaScript.

* **Simple Statement's End**
  Es fundamental que una instrucción simple finalice con un punto y coma, tal como es el caso en muchos otros lenguajes de programación. A continuación, se muestra un ejemplo que cumple con la convención estándar de W3Schools (sin fecha):

``` javascript
let x = v + 7;
const myArray = ['Volvo', 'Saab', 'Fiat'];
```

El uso de punto y coma al final de cada instrucción ayuda a garantizar la estructura correcta del código JavaScript y a evitar posibles errores.

* **Beginning and End of Function**
  Un bloque de función debe incluir una llave al final de la primera línea, de modo que el cierre de la función esté en la última línea, sin necesidad de un punto y coma. Este mismo principio se aplica a las estructuras condicionales y los bucles. A continuación, se muestra un ejemplo que cumple con la convención estándar de W3Schools (sin fecha):

``` javascript
function toCelsius(fahrenheit) {
  return (5 / 9) * (fahrenheit - 32);
}
```

En este ejemplo, la función `toCelsius` está formateada de acuerdo con estas pautas, con la llave de apertura en la misma línea que la declaración de la función y la llave de cierre en la última línea. Esto ayuda a mantener la estructura y la legibilidad del código JavaScript.

* **Object Rules**
  Para la creación de un objeto, al igual que en una función, se comienza con una llave al final de la primera línea. Sin embargo, en este caso, la llave de cierre debe ir seguida de un punto y coma. Para definir las propiedades del objeto, se utilizan dos puntos y un espacio para separar el nombre de la propiedad de su valor. Si el valor es un string, se debe encerrar entre comillas dobles. A continuación, se muestra un ejemplo siguiendo la convención estándar de W3Schools (sin fecha):

``` javascript
const person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
};
```

En este ejemplo, el objeto `person` está formateado de acuerdo con estas pautas, lo que mejora la legibilidad y la estructura del código JavaScript.

**Gherking:**

Gherkin es un Lenguaje Específico de Dominio (DSL por sus siglas en inglés) que se utiliza para resolver problemas específicos mediante la generación de casos de prueba que validan una característica en diversos escenarios. Gherkin incluye varios elementos, entre los cuales los más conocidos y utilizados son Feature, Scenario, Example, Given, When y Then. A continuación, se presentan las pautas que debemos seguir al utilizar Gherkin en nuestro código:

* **Discernible Given-When-Then Blocks**
  Es importante aplicar sangría a los elementos que representan los pasos a seguir en un escenario. En el caso de "And", se debe aplicar una sangría adicional. Siguiendo la recomendación de Keiblinger (2021), este enfoque ayuda a identificar rápidamente las partes que componen un escenario. A continuación, se muestra un ejemplo:

``` gherkin
Scenario: Ingreso de requisitos con claridad
  Given que en el formulario de ingreso de oferta laboral
  When escribo claramente los requisitos
  Then se mostrará el mensaje
  And mi oferta solo aparecerá a quienes cumplan con estos
  And se habilita la opción
```

En este ejemplo, se ha aplicado la sangría de manera adecuada para resaltar los pasos del escenario, y se ha utilizado una sangría adicional para los pasos que comienzan con "And". Esto mejora la legibilidad y la comprensión de los escenarios escritos en Gherkin.

* **Step with Tables**
  Conforme a la recomendación de Keiblinger (2021), cuando sea necesario introducir valores en partes del escenario, se debe emplear una tabla o crear un formulario que refleje esa parte del escenario. Antes de esta representación, se deben colocar dos puntos. Aquí tienes un ejemplo:

``` gherkin
Then se mostrará el mensaje:
  | Mensaje |
  | Se completaron los requisitos adecuadamente |
```

Este enfoque permite una representación clara y estructurada de los valores relacionados con una parte específica del escenario.

* **Reducing Noise**
  Para evitar la acumulación de demasiadas líneas de código en un escenario, es recomendable incluir valores por defecto dentro de los pasos para campos que no sean muy relevantes para ese escenario en particular. Los valores "estándar" que se coloquen deben estar entre comillas simples. Siguiendo el consejo de Keiblinger (2021), esta práctica contribuye significativamente a la reducción del tamaño del código. A continuación, se muestra un ejemplo:

``` gherkin
When escribo claramente los requisitos 'dominio en C'
```

En este ejemplo, se ha incluido un valor por defecto ('dominio en C') entre comillas simples dentro del paso para representar un campo que no es esencial en ese escenario. Esto ayuda a mantener el escenario más conciso y legible.

* **Scenarios Separator**
  Para separar dos escenarios, se debe insertar un salto de línea y, según la sugerencia de Keiblinger (2021), si es posible, agregar una línea de comentario para facilitar la visualización de estos. De esta manera, se identifica rápidamente el inicio y el fin de un escenario. A continuación, se presenta un ejemplo:

``` gherkin
Scenario: Ingreso de requisitos con claridad
Given que en el formulario de ingreso de oferta laboral
When escribo claramente los requisitos
Then se mostrará el mensaje
And mi oferta solo aparecerá a quienes cumplan con estos
And se habilita la opción

# --------------------------

Scenario: Otro escenario
Given que en otro contexto
When ocurre algo diferente
Then se muestra otro resultado
```

En este ejemplo, se ha agregado un salto de línea entre los dos escenarios y se ha incluido una línea de comentario como separador para mejorar la visualización y la identificación de cada escenario.

**Typescript**

JavaScript es uno de los lenguajes más populares y ha experimentado un rápido avance y mejora en los últimos años. A continuación, se presentan las pautas para utilizar JavaScript en nuestro proyecto:

En TypeScript, se recomienda que las variables se declaren en minúsculas y se especifique el tipo de dato utilizando dos puntos después del nombre de la variable. Aquí tienes ejemplos de cómo declarar y asignar valores a variables en TypeScript:

``` typescript
// Definición e inicialización separadas
let edad: number;
edad = 20;

// Definición e inicialización en la misma línea.
let edadAitor: number = 18;
```

Además, en TypeScript, se siguen las mismas convenciones que se utilizan en JavaScript.

### 6.1.4. Software Deployment Configuration.

Para desplegar la Landing Page desde GitHubPages hay que seguir los siguientes pasos:

**1. Seleccionar la sección pages:**

![pages-landing-page.png](/assets/img/chapter-vi/pages-landing-page.png)


**1. Configurar la rama que será usada para hacer deploy:**

![rama-landing-page.png](/assets/img/chapter-vi/rama-landing-page.png)

## 6.2. Landing Page, Services & Applications Implementation.

### 6.2.1. Sprint 1
En la fase inicial de nuestro proyecto, nos propusimos llevar a cabo la implementación de la primera vesión del diseño de nuestra Landing Page, Web Application y Backend services
utilizando WebStorm y Visual Studio Code como entornos de desarrollo. Esto implica que al concluir el Sprint 1, se habrán completado las tareas y objetivos establecidos para esta etapa inicial del proyecto.
#### 6.2.1.1. Sprint Planning 1.
En el Sprint Planning 1, se llevó a cabo una sesión de planificación para la elaboración de la primera versión de las soluciones 
de Upet. Se dividieron las secciones a programar entre los integrantes, además se determinó el plazo de entrega de estas tareas.

<table>
  <thead>
    <tr>
      <th style="text-align:center">Sprint #</th>
      <th style="text-align:center">Sprint 1</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="2" ><strong>Sprint Planning Background</strong></td>
    </tr>
    <tr>
      <td style="text-align:center">Date</td>
      <td style="text-align:center">13-09-2024</td>
    </tr>
    <tr>
      <td style="text-align:center">Time</td>
      <td style="text-align:center">08:00 pm</td>
    </tr>
    <tr>
      <td style="text-align:center">Location</td>
      <td style="text-align:center">Google Meet</td>
    </tr>
    <tr>
      <td style="text-align:center">Prepared By</td>
      <td style="text-align:center">Enzo Trujillo</td>
    </tr>
    <tr>
      <td style="text-align:center">Attendees</td>
      <td style="text-align:center">
      Enzo Trujillo, Randy, Juliana Yauricasa, Joseph Herrera y Daniel Valverde
      </td>
    </tr>
    <tr>
      <td colspan="2"><strong>Sprint Goal & User Stories</strong></td>
    </tr>
    <tr>
      <td style="text-align:center">Sprint 1 Goal</td>
      <td style="text-align:center"> Implementar la primera versión  de la Landing Page, Web Application y Backend services </td>
    </tr>
    <tr>
      <td style="text-align:center">Sprint 1 Velocity</td>
      <td style="text-align:center">38</td>
    </tr>
    <tr>
      <td style="text-align:center">Sum of Story Points</td>
      <td style="text-align:center">38</td>
    </tr>
  </tbody>
</table>

#### 6.2.1.2. Sprint Backlog 1.

<table>
  <tr>
    <td> <strong>Sprint #</strong></td>
    <td   colspan="7"> <strong>Sprint 1</strong> </td>
  </tr>
   <tr>
    <td   colspan="2"> <strong>User Story</strong></td>
    <td   colspan="6"> <strong>Work-item/Task</strong></td>
  </tr>
  <tr>
    <td  > <strong>ID</strong> </td>
    <td  > <strong>Title</strong></td>
    <td  > <strong>ID</strong> </td>
    <td  > <strong>Title</strong></td>
    <td  > <strong>Description</strong></td>
    <td  > <strong>Estimation (Hours)</strong></td>
    <td  > <strong>Assigned To</strong></td>
    <td  > <strong> Status (To-do/In-Process/To-Review/Done) </strong></td>
  </tr>
  <!---------------------------------------------------------------------- -->
  <tr>
    <!--rowspan="number of rows for the tasks (2)" -->
    <td rowspan="2">US001</td>
    <td rowspan="2">Registro de cuenta</td>
    <td>TA01</td>
    <td> Visualización </td>
    <td>Desarrollo de la interfaz con html css </td>
    <td>2</td>
    <td>Enzo Trujillo </td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>Lógica</td>
    <td> Desarrollar las conexiones con los servicios del backend</td>
    <td>2</td>
    <td>Enzo Trujillo </td>
    <td>Done</td>
  </tr>
   <!---------------------------------------------------------------------- -->
  <tr>
    <!--rowspan="number of rows for the tasks (2)" -->
    <td rowspan="2">US002</td>
    <td rowspan="2">Iniciar Sesión</td>
    <td>TA03</td>
   <td> Visualización </td>
    <td>Desarrollo de la interfaz con html css </td>
    <td>2</td>
    <td>Randy  </td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA04</td>
     <td>Lógica</td>
    <td> Desarrollar las conexiones con los servicios del backend</td>
    <td> 3</td>
    <td>Joseph Herrera </td>
    <td> Done  </td>
  </tr>
 <!---------------------------------------------------------------------- -->
  <tr>
    <!--rowspan="number of rows for the tasks (2)" -->
    <td rowspan="2">US005</td>
    <td rowspan="2">Registrar Mascota</td>
    <td>TA05</td>
   <td> Visualización </td>
    <td>Desarrollo de la interfaz con html css </td>
    <td>2</td>
    <td>Enzo Trujillo </td>
    <td> Done</td>
  </tr>
  <tr>
    <td>TA06</td>
  <td>Lógica</td>
    <td> Desarrollar las conexiones con los servicios del backend</td>
    <td> 3</td>
    <td>Joseph Herrera </td>
    <td> Done </td>
  </tr>
 <!---------------------------------------------------------------------- -->
  <tr>
    <!--rowspan="number of rows for the tasks (2)" -->
    <td rowspan="2">US009</td>
    <td rowspan="2">Editar información de la mascota</td>
    <td>TA07</td>
    <td> Visualización </td>
    <td>Desarrollo de la interfaz con html css </td>
    <td>2</td>
    <td>Joseph Herrera </td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA08</td>
    <td>Lógica</td>
    <td> Desarrollar las conexiones con los servicios del backend</td>
    <td> 2</td>
    <td>Juliana Yauricasa </td>
    <td> Done </td>
  </tr>
 <!---------------------------------------------------------------------- -->
  <tr>
    <!--rowspan="number of rows for the tasks (2)" -->
    <td rowspan="2">US024</td>
    <td rowspan="2">Visualizar resumen del historial médico</td>
    <td>TA09</td>
   <td> Visualización </td>
    <td>Desarrollo de la interfaz con html css </td>
    <td>2</td>
    <td>Juliana Yauricasa </td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA10</td>
    <td>Lógica</td>
    <td> Desarrollar las conexiones con los servicios del backend</td>
    <td> 2</td>
    <td>Daniel Valverde </td>
    <td> Done </td>
  </tr>
 <!---------------------------------------------------------------------- -->
  <tr>
    <!--rowspan="number of rows for the tasks (2)" -->
    <td rowspan="2">US007</td>
    <td rowspan="2">Ver listado de mis mascotas</td>
    <td>TA11</td>
   <td> Visualización </td>
    <td>Desarrollo de la interfaz con html css </td>
    <td>1</td>
    <td>Daniel Valverde </td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA12</td>
    <td>Lógica</td>
    <td> Desarrollar las conexiones con los servicios del backend</td>
    <td> 2</td>
    <td> Daniel Valverde </td>
    <td> Done </td>
  </tr>
</table>


#### 6.2.1.3. Development Evidence for Sprint Review.

| Repository                                        | Branch            | Commit Id                                | Commit Message                               | Committed on (Date) |
|---------------------------------------------------|-------------------|------------------------------------------|----------------------------------------------|---------------------|
| https://github.com/SW71-devpaw/upet-frontend-web/ | main              | bd084ae7a64af51d5d9736f8ed7f63b6fd1caf59 | inital commit                                | 18/09/2024          |
|                                                   | main              | 6c352e1be111c13e90588e4f00d690c7fb603ecb | init                                         | 18/09/2024          |
|                                                   | feature/home-view | 9c0014dacaa5940bd708d2a3b328506315623259 | feat: cards for pets and form for update pet | 24/09/2024          |
|                                                   | feature/home-view | 7d17018f6752fdd8efbb2ce793704a9e14e31063 | feat: banner was added                       | 24/09/2024          |
|                                                   | feature/home-view | 0fe1b1d3c18cce3d9284fc27d13bf6f6f636c41e | feat: section best specialist nearby added   | 24/09/2024          |
|                                                   | feature/care-view | 91b536f519bb1deae888ef8c13e7ead7d33eac3f | feat(care): add structure of care pet view   | 25/09/2024          |
|                                                   | feature/care-view | 208952d45fe0caf90028dd6ac11c2bcdfff4bf09 | feat(care): add list of dates                | 25/09/2024          |
|                                                   | feature/care-view | d2b7a21a1ef02e784ef7689fb2e689312ad490e3 | feat(care): add table of history records     | 25/09/2024          |

#### 6.2.1.4. Testing Suite Evidence for Sprint Review.

| Repository     | Branch             | Commit Id | Commit Message | Committed on (Date) |
|----------------|--------------------|-----------|----------------|---------------------|
| repositoryname | feature/loremipsum | 14ca4e3   | ---            | 20/08/2024          |
|                |                    |           |                |                     |
|                |                    |           |                |                     |
|                |                    |           |                |                     |
|                |                    |           |                |                     |
|                |                    |           |                |                     |
|                |                    |           |                |                     |

#### 6.2.1.5. Execution Evidence for Sprint Review.

#### 6.2.1.6. Services Documentation Evidence for Sprint Review.

#### 6.2.1.7. Software Deployment Evidence for Sprint Review.

#### 6.2.1.8. Team Collaboration Insights during Sprint.

## 6.3. Validation Interviews.

### 6.3.1. Diseño de Entrevistas.

### 6.3.2. Registro de Entrevistas.

Entrevista Segmento 1

<table>
        <thead>
            <tr>
                <th>Entrevistado 1</th>
                <th>Nombre Entrevistado</th>
            </tr>
            <tr>
                <th>Entrevistador</th>
                <th>Nombre Entrevistador</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Edad</td>
                <td>edad del entrevistado </td>
            </tr>
            <tr>
                <td>Distrito</td>
                <td>distrito del entrevistado</td>
            </tr>
            <tr>
                <td><img src="" alt="Foto de la entrevista"></td>
                <td><strong>Resumen:</strong><br>
                    Resumen de la entrevista aquí
                </td>
            </tr>
            <tr>
                <td>Timing de la entrevista</td>
                <td> 0:00 </td>
            </tr>
            <tr>
                <td>URL de la entrevista</td>
                <td>https://shorturl.at/acGL6</td>
            </tr>
        </tbody>
</table>

Entrevista Segmento 2

<table>
        <thead>
            <tr>
                <th>Entrevistado 1</th>
                <th>Nombre Entrevistado</th>
            </tr>
            <tr>
                <th>Entrevistador</th>
                <th>Nombre Entrevistador</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Edad</td>
                <td>edad del entrevistado </td>
            </tr>
            <tr>
                <td>Distrito</td>
                <td>distrito del entrevistado</td>
            </tr>
            <tr>
                <td><img src="" alt="Foto de la entrevista"></td>
                <td><strong>Resumen:</strong><br>
                    Resumen de la entrevista aquí
                </td>
            </tr>
            <tr>
                <td>Timing de la entrevista</td>
                <td> 0:00 </td>
            </tr>
            <tr>
                <td>URL de la entrevista</td>
                <td>https://shorturl.at/acGL6</td>
            </tr>
        </tbody>
</table>

### 6.3.3. Evaluaciones según heurísticas.

**UX Heuristics & Principles Evaluation**

**Usability – Inclusive Design – Information Architecture**

CARRERA : Ingeniería de Software

CURSO : Desarrollo de Soluciones IOT 

SECCIÓN : SW71

PROFESOR : Marco Antonio León Baca

AUDITOR : startup name

CLIENTE(S) : Grupo X

SITE o APP A EVALUAR: product

TAREAS A EVALUAR:
El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:
* Landing Page
    * i. Descripción de las características de la aplicación
    * ii. Accesibilidad de los botones call to action
    ...
* Web Application
    * i. Diseño responsive para toda la aplicación
    ...
* Another Platform
    * i. ...
    ...
  
### ESCALA DE SEVERIDAD:
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad

| Nivel | Descripción                                                                                                                                                                                     |
|-------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | Problema superficial: puede ser fácilmente superador por el usuario ó ocurre con muy poco frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.                   |
| 2     | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente release. |
| 3     | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta.                                 |
| 4     | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.                               |


#### TABLA DE RESUMEN - platform

| # | Problema                                                                    | Escala de severidad | Heurística/Principio violada(o)           |
|---|-----------------------------------------------------------------------------|---------------------|-------------------------------------------|
| 1 | description                                                                 | 0                   | problem                                   |
| 2 | description                                                                 | 0                   | problem                                   |
| 3 | description                                                                 | 0                   | problem                                   |


**DESCRIPCIÓN DE PROBLEMAS:**

**PROBLEMA #1:** Nombre del problema

**Severidad:** X

**Heurística violada:** xxxxxxxxxxxx

**Problema:**
Descripción del problema identificado.

![evidencia del problema]()

**Recomendación:**
Descripción de la recomendación para solucionar el problema.

## 6.4. Video About-the-Product.

### **Conclusiones**

#### Conclusiones y recomendaciones.

#### Video About-the-Team.

### **Bibliografía**

### **Anexos**

<table>
        <thead>
            <tr>
                <th>Sección</th>
                <th>Características del video</th>
                <th>Sobre el contenido</th>
                <th>Integración y entrega</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Needfinding Interviews</td>
                <td>Cantidad de videos: 1 <br> 
                  Nomenclatura: nomenclatura correspondiente <br>
                  Formato: .mp4 <br>
                  Duración: 00:00:00 min </td>
                <td>Consolida todas las entrevistas realizadas</td>
                <td>Link: link aqui
                  Captura: <br>
                  <img src="" alt="" width="350"/>
                </td>
            </tr>
            <tr>
                <td>Another video</td>
                <td>Cantidad de videos: 1 <br> 
                  Nomenclatura: nomenclatura correspondiente <br>
                  Formato: .mp4 <br>
                  Duración: 00:00:00 min </td>
                <td>Consolida todas las entrevistas realizadas</td>
                <td>Link: link aqui
                  Captura: <br>
                  <img src="" alt="" width="350"/>
                </td>
            </tr>
        </tbody>
</table>
