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

![ GitFlow.png](https://i.postimg.cc/8z7qbV8y/Gitflow.png)

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

![activar-el-controlador-de-versiones-1.png](https://i.postimg.cc/wBv32MqC/activar-el-controlador-de-versiones-1.png)

Ahora se debe seleccionar el sistema de control a través de Git y, por último aceptar los cambios.

![activar-el-controlador-de-versiones-2.png](https://i.postimg.cc/hjQvFY7M/activar-el-controlador-de-versiones-2.png)

* **Aregar una cuenta de GitHub, siga estos pasos:**
  1. Diríjase a la sección de configuración en su aplicación.
  2. Dentro de la pestaña 'File', busque y seleccione la opción 'Settings'.
  3. En la configuración, busque la sección de version control.
  4. Agregue su cuenta de GitHub para obtener acceso a los repositorios.

![aregar-una-cuenta-de-GitHub-1.png](https://i.postimg.cc/hv9Gv7sd/aregar-una-cuenta-de-Git-Hub-1.png)

![aregar-una-cuenta-de-GitHub-2.png](https://i.postimg.cc/J0wnRQN8/aregar-una-cuenta-de-Git-Hub-2.png)

* **Configurar el nombre de usuario de Git:** Una vez que hayas establecido el sistema de control de versiones que se vinculará con tu IDE, deberás ingresar la cuenta que utilizarás. Para hacerlo, sigue estos pasos:
  1. Realiza un commit en tu proyecto. Durante este proceso, se te solicitará que ingreses tu nombre de usuario de Git.
  2. Después de haberlo añadido, todos los cambios se guardarán en el repositorio especificado en esa plataforma, siempre y cuando des la orden correspondiente.
  3. Para configurar tu nombre de usuario de Git, primero selecciona la opción 'commit' que se encuentra dentro de la pestaña 'Git'.

![configurar-el-nombre-de-usuario-de-Git-1.png](https://i.postimg.cc/HkLpDNq5/configurar-el-nombre-de-usuario-de-Git-1.png)


* **Guardar el progreso en GitHub:** Con todo configurado en WebStorm, ahora puedes subir tu código a GitHub sin problemas. Simplemente dirígete a la opción 'GitHub' que se encuentra en la pestaña 'Git' y comparte el proyecto.

![guardar-el-progreso-en-GitHub-1.png](https://i.postimg.cc/9fTKvtQZ/guardar-el-progreso-en-Git-Hub-1.png)

![guardar-el-progreso-en-GitHub-2.png](https://i.postimg.cc/LXpwRYJ7/guardar-el-progreso-en-Git-Hub-2.png)

* **Configurar la propiedad del repositorio en GitHub:** Ahora, solo necesitas configurar la ubicación del repositorio. El código ya debería estar guardado en GitHub, pero solo estará presente en tu propia cuenta. Para cambiar la propiedad y transferirla a la organización deseada, sigue estos pasos:
  1. Ingresa al repositorio creado en GitHub.
  2. Selecciona la pestaña 'settings'
  3. Dirigite al apartado de 'DangerZone'
  4. Luego da click en 'transfer'
  5. Finalmente elegimos el nuevo lugar para guardar el repositorio.

![configurar-la-propiedad-del-repositorio-en-GitHub-1.png](https://i.postimg.cc/Wzjv9Ymd/configurar-la-propiedad-del-repositorio-en-Git-Hub-1.png)

![configurar-la-propiedad-del-repositorio-en-GitHub-2.png](https://i.postimg.cc/DwDKVwdk/configurar-la-propiedad-del-repositorio-en-Git-Hub-2.png)

![configurar-la-propiedad-del-repositorio-en-GitHub-3.png](https://i.postimg.cc/cCmNP7TX/configurar-la-propiedad-del-repositorio-en-Git-Hub-3.png)

![configurar-la-propiedad-del-repositorio-en-GitHub-4.png](https://i.postimg.cc/SNS4C5N5/configurar-la-propiedad-del-repositorio-en-Git-Hub-4.png)


* **Configurar control remoto en Git:** Por último, dado que el repositorio ahora está bajo la propiedad de la empresa y depende de ella, es necesario acceder al control remoto del código. Para hacerlo, simplemente ingresa al repositorio creado y copia la URL del repositorio.

![configurar-control-remoto-en-Git-1.png](https://i.postimg.cc/1XZ9k3S5/configurar-control-remoto-en-Git-1.png)

Ahora, en el IDE, dirígete a la pestaña 'Git' y elige la opción 'Manage Remotes'.

![configurar-control-remoto-en-Git-2.png](https://i.postimg.cc/YqRpP7sM/configurar-control-remoto-en-Git-2.png)

Finalmente, como último paso, debes pegar el enlace copiado en el campo de dirección que solicita el IDE para el control remoto en Git.

![configurar-control-remoto-en-Git-3.png](https://i.postimg.cc/SNkSVRVg/configurar-control-remoto-en-Git-3.png)

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

**1. Configurar la rama que será usada para hacer deploy:**

![rama-landing-page.png](https://i.postimg.cc/wM3VdgQZ/rama-landing-page.png)

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


| |                                        |
|----------------------|---------------------------------------------------|
| Repository           | [PetTechh/Acceptance_test_Upet](https://github.com/PetTechh/Acceptance_test_Upet.git) |
| Branch               | main                                              |
| Commit Id            | 4772c601f85bda2ef0dd620088b406724bba6704        |
| Commit Message       | added acceptance tests                            |


#### 6.2.1.5. Execution Evidence for Sprint Review.
Para la entrega de este Sprint, se completó con éxito el despliegue de la Landing page y el Backend.

                                      LANDING PAGE

![landing-picture](https://i.postimg.cc/bJpCW7Mf/landing-picture1.png)
![landing-picture](https://i.postimg.cc/yYd5VzNV/landing-picture2.png)
![landing-picture](https://i.postimg.cc/vmRSLgtB/landing-picture3.png)
![landing-picture](https://i.postimg.cc/vmRSLgtB/landing-picture3.png)
![landing-picture](https://i.postimg.cc/BQXhrchb/landing-picture5.png)
![landing-picture](https://i.postimg.cc/pLjsTVMt/landing-picture6.png)
![landing-picture](https://i.postimg.cc/3rLSfbFz/landing-picture7.png)
![landing-picture](https://i.postimg.cc/zvMkz6dB/landing-picture8.png)


                                      BACKEND

![backend-picture](https://i.postimg.cc/sfSxwtzg/backend-picture1.png)
![backend-picture](https://i.postimg.cc/Mpspnw7d/backend-picture2.png)
![backend-picture](https://i.postimg.cc/SKJN8PVq/backend-picture3.png)
![backend-picture](https://i.postimg.cc/j5fx3JGF/backend-picture4.png)
![backend-picture](https://i.postimg.cc/d0pQ99SC/backend-picture5.png)


#### 6.2.1.6. Services Documentation Evidence for Sprint Review.
Se documentaron endpoints esenciales para UPet. Esto implicó detallar y especificar las rutas y funcionalidades de la API que permitirán la comunicación e intercambio de datos entre el frontend y el backend de la aplicación. Además de documentar estos endpoints cruciales, el equipo realizó confirmaciones (commits) en el repositorio del proyecto para registrar los cambios y avances realizados en el código fuente. A continuación, se muestra los endpoints documentados y los commits: 

| Endpoint                                        | Verbo HTTP | Parámetros        | Ejemplo de Llamada                           |
|-------------------------------------------------|------------|-------------------|----------------------------------------------|
| /api/v1/auth/sign-up                           | POST       | -                 | /api/v1/auth/sign-up                        |
| /api/v1/auth/sign-in                           | POST       | -                 | /api/v1/auth/sign-in                        |
| /api/v1/auth/current-user                      | GET        | -                 | /api/v1/auth/current-user                   |
| /api/v1/users                                  | GET        | -                 | /api/v1/users                               |
| /api/v1/veterinary_clinics                    | GET        | -                 | /api/v1/veterinary_clinics                 |
| /api/v1/veterinary_clinics                    | POST       | -                 | /api/v1/veterinary_clinics                 |
| /api/v1/pets/{petowner_id}                    | POST       | petowner_id       | /api/v1/pets/{petowner_id}                 |
| /api/v1/pets/{petowner_id}                    | GET        | petowner_id       | /api/v1/pets/{petowner_id}                 |
| /api/v1/pets                                    | GET        | -                 | /api/v1/pets                                |
| /api/v1/appointments                           | GET        | -                 | /api/v1/appointments                        |
| /api/v1/appointments                           | POST       | -                 | /api/v1/appointments                        |
| /api/v1/appointments/pet/{pet_id}             | GET        | pet_id            | /api/v1/appointments/pet/{pet_id}          |
| /api/v1/appointments/veterinarian/{veterinarian_id} | GET    | veterinarian_id   | /api/v1/appointments/veterinarian/{veterinarian_id} |
| /api/v1/notifications                          | GET        | -                 | /api/v1/notifications                       |
| /api/v1/notifications                          | POST       | -                 | /api/v1/notifications                       |
| /api/v1/notifications/petowner/{petowner_id} | GET        | petowner_id       | /api/v1/notifications/petowner/{petowner_id} |
| /api/v1/medical_historys                       | GET        | -                 | /api/v1/medical_historys                    |
| /api/v1/medical_historys                       | POST       | -                 | /api/v1/medical_historys                    |
| /api/v1/medical_historys/{medical_history_id}/diseases/ | GET | medical_history_id | /api/v1/medical_historys/{medical_history_id}/diseases/ |
| /api/v1/medical_historys/{medicalHistory_id}  | POST       | medicalHistory_id  | /api/v1/medical_historys/{medicalHistory_id} |
| /api/v1/medical_historys/{medical_history_id}/vaccinations/ | GET | medical_history_id | /api/v1/medical_historys/{medical_history_id}/vaccinations/ |
| /api/v1/medical_historys/{medicalHistoryId}   | PUT        | medicalHistory_id  | /api/v1/medical_historys/{medicalHistoryId} |
| /api/v1/users/petowner/{user_id}              | POST       | user_id           | /api/v1/users/petowner/{user_id}           |
| /api/v1/users/petowner                         | GET        | -                 | /api/v1/users/petowner                      |
| /api/v1/users/veterinarians/{user_id}         | POST       | user_id           | /api/v1/users/veterinarians/{user_id}      |
| /api/v1/users/veterinarians                    | GET        | -                 | /api/v1/users/veterinarians                 |
| /api/v1/diseases                               | GET        | -                 | /api/v1/diseases                            |
| /api/v1/diseases                               | POST       | -                 | /api/v1/diseases                            |
| /api/v1/vaccinations                           | GET        | -                 | /api/v1/vaccinations                        |
| /api/v1/vaccinations                           | POST       | -                 | /api/v1/vaccinations                        |



#### 6.2.1.7. Software Deployment Evidence for Sprint Review.
Se utilizó Github para el control de versiones y colaboración entre el equipo. En la organización, se creó un repositorio para cada producto, es decir, uno para la landing page, otro para el backend y uno para la aplicación móvil. Para el despliegue de la landing page se utilizó Github Pages.

**Landing Page desplegada:** https://pettechh.github.io/UPet-LandingPage/ <br>
**Backend desplegado** https://upetbackendapi.onrender.com/docs#/  



#### 6.2.1.8. Team Collaboration Insights during Sprint.
Durante el sprint 1, el equipo trabajo activamente en la implementación de la landing page, la aplicación móvil, el backend y el web application. La metodología que se empleó fue mediante Gitflow, gracias a ello, todos los miembros participaron simultáneamente.

                                      App Web

![contribution.png](https://i.postimg.cc/G2P0sJ0d/contribution.png)

                                      Mobile App

![alt text](https://i.postimg.cc/Znj1wbKQ/contribution-app-mobile.png)

                                      Backend
![alt text](https://i.postimg.cc/2jwRkwFx/contribution-backend.png)

                                      Report

![alt text](https://i.postimg.cc/kG70N698/contribution2.png)

### 6.2.2. Sprint 2

#### 6.2.2.1. Sprint Planning 2.

<table>
  <thead>
    <tr>
      <th style="text-align:center">Sprint #</th>
      <th style="text-align:center">Sprint 2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="2" ><strong>Sprint Planning Background</strong></td>
    </tr>
    <tr>
      <td style="text-align:center">Date</td>
      <td style="text-align:center">27-10-2024</td>
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
      <td style="text-align:center">Sprint 2 Review Summary</td>
      <td style="text-align:center"> Se realizó casi completamente la aplicación móvil e igualmente la aplicación web. Para el backend, se completó todos los endpoints. </td>
    </tr>
    <tr>
      <td style="text-align:center">Sprint 2 Retrospective Summary</td>
      <td style="text-align:center"> La comunicación del equipo se complementó mediante el grupo de Whatsapp y reuniones presenciales. Además, el equipo se mostró más proactivo. </td>
    </tr>
    <tr>
      <td colspan="2"><strong>Sprint Goal & User Stories</strong></td>
    </tr>
    <tr>
      <td style="text-align:center">Sprint 2 Goal</td>
      <td style="text-align:center"> Completar la aplicación móvil y web en un 90%. Wokwi y backend en un 100% </td>
    </tr>
    <tr>
      <td style="text-align:center">Sprint 2 Velocity</td>
      <td style="text-align:center">Se aceptaran 24 story points </td>
    </tr>
    <tr>
      <td style="text-align:center">Sum of Story Points</td>
      <td style="text-align:center">2 + 2 + 3 + 3 + 2 + 2 + 2 + 3 + 2 + 3 = 24 </td>
    </tr>
  </tbody>
</table>

#### 6.2.2.2. Sprint Backlog 2.


<table>
  <tr>
    <td> <strong>Sprint #</strong></td>
    <td   colspan="7"> <strong>Sprint 2</strong> </td>
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
    <td rowspan="2">US-006</td>
    <td rowspan="2">Subir foto de la mascota</td>
    <td>TA01</td>
    <td> Visualización </td>
    <td>Desarrollo de la interfaz con html css </td>
    <td>1</td>
    <td>Enzo Trujillo </td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>Lógica</td>
    <td> Desarrollar las conexiones con los servicios del backend</td>
    <td>1</td>
    <td>Enzo Trujillo </td>
    <td>Done</td>
  </tr>
   <!---------------------------------------------------------------------- -->
  <tr>
    <!--rowspan="number of rows for the tasks (2)" -->
    <td rowspan="2">US-007</td>
    <td rowspan="2">Ver listado de mis mascotas</td>
    <td>TA03</td>
   <td> Visualización </td>
    <td>Desarrollo de la interfaz con html css </td>
    <td>3</td>
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
    <td rowspan="2">US-010</td>
    <td rowspan="2">Agendar una cita</td>
    <td>TA05</td>
   <td> Visualización </td>
    <td>Desarrollo de la interfaz con html css </td>
    <td>5</td>
    <td>Enzo Trujillo </td>
    <td> Done</td>
  </tr>
  <tr>
    <td>TA06</td>
  <td>Lógica</td>
    <td> Desarrollar las conexiones con los servicios del backend</td>
    <td> 5</td>
    <td>Joseph Herrera </td>
    <td> Done </td>
  </tr>
 <!---------------------------------------------------------------------- -->
  <tr>
    <!--rowspan="number of rows for the tasks (2)" -->
    <td rowspan="2">US-012</td>
    <td rowspan="2">Acceso de la veterinaria a la información de la mascota</td>
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
    <td rowspan="2">US-014</td>
    <td rowspan="2">Ver historial de citas</td>
    <td>TA09</td>
   <td> Visualización </td>
    <td>Desarrollo de la interfaz con html css </td>
    <td>3</td>
    <td>Juliana Yauricasa </td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA10</td>
    <td>Lógica</td>
    <td> Desarrollar las conexiones con los servicios del backend</td>
    <td>3</td>
    <td>Daniel Valverde </td>
    <td> Done </td>
  </tr>
 <!---------------------------------------------------------------------- -->
  <tr>
    <!--rowspan="number of rows for the tasks (2)" -->
    <td rowspan="2">US-020</td>
    <td rowspan="2">Registrar vacunas</td>
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
    <td> Enzo Trujillo </td>
    <td> Done </td>
  </tr>
<!---------------------------------------------------------------------- -->
  <tr>
    <!--rowspan="number of rows for the tasks (2)" -->
    <td rowspan="2">US-021</td>
    <td rowspan="2">Registrar resultados</td>
    <td>TA09</td>
   <td> Visualización </td>
    <td>Desarrollo de la interfaz con html css </td>
    <td>2</td>
    <td>Enzo Trujillo </td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA10</td>
    <td>Lógica</td>
    <td> Desarrollar las conexiones con los servicios del backend</td>
    <td> 2</td>
    <td>Juliana Yauricasa </td>
    <td> Done </td>
  </tr>
<!---------------------------------------------------------------------- -->
  <tr>
    <!--rowspan="number of rows for the tasks (2)" -->
    <td rowspan="2">US-022</td>
    <td rowspan="2">Registrar cirugías</td>
    <td>TA09</td>
   <td> Visualización </td>
    <td>Desarrollo de la interfaz con html css </td>
    <td>2</td>
    <td>Joseph Herrera </td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA10</td>
    <td>Lógica</td>
    <td> Desarrollar las conexiones con los servicios del backend</td>
    <td> 2</td>
    <td> Joseph Herrera </td>
    <td> Done </td>
  </tr>
<!---------------------------------------------------------------------- -->
  <tr>
    <!--rowspan="number of rows for the tasks (2)" -->
    <td rowspan="2">US-023</td>
    <td rowspan="2">Registrar enfermedades</td>
    <td>TA09</td>
   <td> Visualización </td>
    <td>Desarrollo de la interfaz con html css </td>
    <td>2</td>
    <td>Randy </td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA10</td>
    <td>Lógica</td>
    <td> Desarrollar las conexiones con los servicios del backend</td>
    <td> 2</td>
    <td> Randy </td>
    <td> Done </td>
  </tr>
<!---------------------------------------------------------------------- -->
  <tr>
    <!--rowspan="number of rows for the tasks (2)" -->
    <td rowspan="2">US-024</td>
    <td rowspan="2">Visualizar resumen del historial médico</td>
    <td>TA09</td>
   <td> Visualización </td>
    <td>Desarrollo de la interfaz con html css </td>
    <td>4</td>
    <td> Juliana Yauricasa </td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA10</td>
    <td>Lógica</td>
    <td> Desarrollar las conexiones con los servicios del backend</td>
    <td> 4</td>
    <td> Juliana Yauricasa </td>
    <td> Done </td>
  </tr>
</table>

#### 6.2.2.3. Development Evidence for Sprint Review.

En la siguientes tablas se muestran el historial de commits realizados durante el Sprint 2 en el repositorio relacionado al proyecto del dispositivo embebido en wokwi y su primera versión. Además de los repositorios de la aplicación web y móvil.

**Wokwi**

| Repository                                   | Branch | Commit Id                                | Commit Message                             | Committed on (Date) |
|----------------------------------------------|--------|------------------------------------------|--------------------------------------------|---------------------|
| https://github.com/SW71-devpaw/wokwi-project | master | 64711adb48597cb59745930598cb5a60790f24d1 | inital commit                              | 27/10/2024          |
|                                              | master | e8d3b40c25a117679fd63b545da8305944bab4ac | feat: add libraries                        | 27/10/2024          |
|                                              | master | 55c174d2102b6cd994dbfa46d4afb3652f0512ee | feat: add Wi-Fi connection                 | 27/10/2024          |
|                                              | master | d93e66be2ee2d39c1a64b819c6a87f5623cecbae | feat: add temperature sensor configuration | 27/10/2024          |
|                                              | master | c10d0cb8808a00f6ac1b23d18ad291277d469ca8 | feat: add location configuration           | 27/10/2024          |

**Web application**

| Repository                                        | Branch            | Commit Id                                | Commit Message                               | Committed on (Date) |
|---------------------------------------------------|-------------------|------------------------------------------|----------------------------------------------|---------------------|
| https://github.com/SW71-devpaw/upet-frontend-web/ | main              | bd084ae7a64af51d5d9736f8ed7f63b6fd1caf59 | inital commit                                | 18/09/2024          |
|                                                   | feature/pet-owner-home-view              | 0fe1b1d3c18cce3d9284fc27d13bf6f6f636c41e | feat: section best specialists nearby were added                                         | 24/09/2024          |
|                                                   | feature/pet-owner-home-view              | 7d17018f6752fdd8efbb2ce793704a9e14e31063 | feat: banner was added                                         | 24/09/2024          |
|                                                   | feature/pet-owner-home-view              | 9c0014dacaa5940bd708d2a3b328506315623259 | feat: cards for pets and form for update or add pet were added                                         | 24/09/2024          |
|                                                   | feature/pet-owner-pets-view              | 65056dbc727b463387c80f9cdee909851a3ad903 | feat: profile for pets were added with all of the information about their medics histories                                         | 23/10/2024          |
|                                                   | feature/pet-owner-pets-view              | 6c352e1be111c13e90588e4f00d690c7fb603ecb | feat: badges from profile pet were updated                                         | 23/10/2024          |
|                                                   | feature/pet-owner-clinics-view              | 54bc869c715975e224b00ec0a861923e54b01411 | feat: forms for appointment and review were added                                         | 18/09/2024          |
|                                                   | feature/pet-owner-appointments              | cbc67dba309fcb3df44b9283ab9344f10434bff5 | feat: section appointments was added with its cards                                         | 31/10/2024          |
|                                                   | feature/pet-owner-appointments              | f76e6fc54ed7e492f2e5df1b1899cf0f8060b472 | feat: dialog for appointment details was added                                         | 31/10/2024          |
|                                                   | feature/auth              | 2c5c03deada44cd6b5a2e63cec98c8dcc019fcf1 | feat: add token and flow validation                                         | 29/10/2024          |
|                                                   | release/v1.0.0              | c251a5c31447f5bb61a05f122c379b523647cd40 | feat: configuration to deploy was changed                                         | 02/11/2024          |


**Mobile application**

| Repository                                        | Branch                  | Commit Id                                | Commit Message                                                            | Committed on (Date)  |
|---------------------------------------------------|-------------------------|------------------------------------------|---------------------------------------------------------------------------|----------------------|
| https://github.com/SW71-devpaw/MobileApp-Upet     | main                    | 749b1f2e0b5ae64d48cdb89e88cd95590bf6eb0f | first commit                                                              | 20/10/2024           |
|                                                   | feature/auth            | fa261d293e3ef7c03308c181935e6ce1fedba0e7 | feat(auth): implemented auth feature.                                     | 21/10/2024           |
|                                                   | feature/pet-owner       | 1f0795a5be578d79866190b0818d7f3bccb98db6 | feat(pet-owner): implemented pet owner feature.                           | 22/10/2024           |
|                                                   | feature/vet             | 490ebffd97f325d9b0a7e62edf3af0f30641ed77 | feat(vet): implemented vet feature.                                       | 22/10/2024           |
|                                                   | feature/pet             | 5386fc3a43eeb647a324f858053cef507138f99e | feat(pet): implemented pet feature.                                       | 23/10/2024           |
|                                                   | feature/vet-clinic      | d1cbcfd7eeeaf5a4bcf4873a16f867063187f2f9 | feat(vet-clinic): implemented vet clinic feature.                         | 23/10/2024           |
|                                                   | feature/appointment     | 7bc48b2fc7abb06a70ed399df10eb2bccea0e62c | feat(appointment): implemented appointment feature.                       | 23/10/2024           |
|                                                   | feature/medical-history | 4ea300a0bc8f4565f402789f6797de1fd7fc5cca | feat(medical-history): implemented medical history feature.               | 23/10/2024           |
|                                                   | feature/review          | ddc42b3e25ed6d7e47914aa43e0bcbd19c2bbc7a | feat(review): implemented review feature.                                 | 23/10/2024           |
|                                                   | feature/notification    | 4e14ba02dfef5e06792cbb1e59343a5f1c3a7692 | feat(notification): implemented notification feature.                     | 23/10/2024           |
|                                                   | feature/release         | aa25531795aa5b5d6072da35eeea022511e5f6ab | feat(release): implemented subscription feature and upgrade clinics view. | 27/10/2024           |
|                                                   | feature/release         | 7c7e64287d8161d0104711187b0505e8a3bec06e | feat(release): implemented tracked design and upgrade views.              | 28/10/2024           |
|                                                   | feature/release         | c34b33378cc04282b04861ec2226c49026637c5b | feat(release): fixed design and upgrade views.                            | 01/11/2024           |

#### 6.2.2.4. Testing Suite Evidence for Sprint Review.

| Repository                                               | Branch                  | Commit Id                                | Commit Message            | Committed on (Date)  |
|----------------------------------------------------------|-------------------------|------------------------------------------|---------------------------|----------------------|
| https://github.com/SW71-devpaw/Sprint2-AcceptanceTests-  | main                    | 03d8e9eaf8c0560f5b2770fed6133d3bb957d78b | initial commit            | 02/11/2024           |
|                                                          | testing                 | 4b92e38297fa14aee67df8f6ce858353c7349ceb | docs: added US006 feature | 02/11/2024           |
|                                                          | testing                 | 87469dee559b17d82fdc7cf1e9c91c36981a2e02 | docs: added US007 feature | 02/11/2024           |
|                                                          | testing                 | 3937c140ecfe513a94f7a83316d087ac90c0b73f | docs: added US010 feature | 02/11/2024           |
|                                                          | testing                 | b647af80078ac581448222f49f5aa32cd41ce098 | docs: added US012 feature | 02/11/2024           |
|                                                          | testing                 | 9556ec7119e062ced60c8167b103eadba5074c80 | docs: added US014 feature | 02/11/2024           |
|                                                          | testing                 | 42d22a1996d5803b2d3253f6c9890758ed8dcf3b | docs: added US020 feature | 02/11/2024           |
|                                                          | testing                 | 60d2f1967b76aabf137449e5c98379d307ce5fde | docs: added US021 feature | 02/11/2024           |
|                                                          | testing                 | 6e6c7c8a17b79bd55d89663fc578ec3d3d483415 | docs: added US022 feature | 02/11/2024           |
|                                                          | testing                 | c3c97392b087aabb9976f39eab290782275b194a | docs: added US023 feature | 02/11/2024           |
|                                                          | testing                 | 9d98dee0597393f71fbd3ad434ba7f61d62a58a8 | docs: added US024 feature | 02/11/2024           |

#### 6.2.2.5. Execution Evidence for Sprint Review.

A continuación se muestra la ejecución del proyecto relacionado a las aplicaciones web y móvil. Además, de el dispositivo embebido en Wokwi.

**Wokwi**

- Dispositivo ESP32 y sensor de temperatura

 ![Dispositivo Esp32](https://i.ibb.co/J7NPZWw/disp-sensor.png)

- Muestra de datos de temperatura y ubicación en la consola

![Datos en consola](https://i.ibb.co/LvYBjzh/captura-data-envio.png)

- Recepción de datos en los endpoints correspodientes

![endpoint temperatura](https://i.ibb.co/qrnYrWR/resp-200-temp.png)
![endpoint ubicación](https://i.ibb.co/nnvGVdn/resp-200-location.png)

**Web application**

<img src="https://i.postimg.cc/vZcJQkwh/image.png" alt="" height="500"/>
<img src="https://i.postimg.cc/3xXwZkWz/image.png" alt="" height="500"/>
<img src="https://i.postimg.cc/0yFLrn8s/image.png" alt="" height="500"/>

<img src="https://i.postimg.cc/g0LZdz0D/image.png" alt="" height="500"/>
<img src="https://i.postimg.cc/Znbn94JX/image.png" alt="" height="500"/>
<img src="https://i.postimg.cc/gJYmss1Z/image.png" alt="" height="500"/>
<img src="https://i.postimg.cc/kXkCzqk9/image.png" alt="" height="500"/>
<img src="https://i.postimg.cc/ZRCZXnKb/image.png" alt="" height="500"/>
<img src="https://i.postimg.cc/NfhYPght/image.png" alt="" height="500"/>
<img src="https://i.postimg.cc/HksN6KLH/image.png" alt="" height="500"/>
<img src="https://i.postimg.cc/ZKj7vcxQ/image.png" alt="" height="500"/>
<img src="https://i.postimg.cc/Y2z8T3ZS/image.png" alt="" height="500"/>
<img src="https://i.postimg.cc/ht60V3z2/image.png" alt="" height="500"/>
<img src="https://i.postimg.cc/GttB7d6G/image.png" alt="" height="500"/>
<img src="https://i.postimg.cc/Jn4t0Rrv/image.png" alt="" height="500"/>
<img src="" alt="" height="500"/>

**Mobile application**

<a href="https://ibb.co/zZZ8wYP"><img src="https://i.ibb.co/GRRsjLC/register.png" alt="register" height="400" border="0"></a>
<a href="https://ibb.co/2sjn3ZH"><img src="https://i.ibb.co/MGR2kBQ/login.png" alt="login" height="400" border="0"></a>
<a href="https://ibb.co/C78fPBc"><img src="https://i.ibb.co/QNQ4D9g/forgot-Password.png" alt="forgot-Password" height="400" border="0"></a>
<a href="https://ibb.co/BrSTTKM"><img src="https://i.ibb.co/jW133ZX/check-Email.png" alt="check-Email" height="400" border="0"></a>
<a href="https://ibb.co/FwS6TGQ"><img src="https://i.ibb.co/T8Vc3zQ/set-Password.png" alt="set-Password" height="400" border="0"></a>

<a href="https://ibb.co/wYKXVBp"><img src="https://i.ibb.co/4JjGzK4/home-Owner.png" alt="home-Owner" height="400" border="0"></a>
<a href="https://ibb.co/YPyDMKq"><img src="https://i.ibb.co/vVQsGrK/profile.png" alt="profile" height="400" border="0"></a>
<a href="https://ibb.co/JqkXcp0"><img src="https://i.ibb.co/YXjvNdY/addPet.png" alt="addPet" height="400" border="0"></a>
<a href="https://ibb.co/tQXq1r4"><img src="https://i.ibb.co/Xj87GRb/listPets.png" alt="listPets" height="400" border="0"></a>
<a href="https://ibb.co/T4BGLDw"><img src="https://i.ibb.co/jyvYR98/pet-Information.png" alt="pet-Information" height="400" border="0"></a>
<a href="https://ibb.co/x740TPj"><img src="https://i.ibb.co/pLm8FGz/editPet.png" alt="editPet" height="400" border="0"></a>
<a href="https://ibb.co/L1b0CVP"><img src="https://i.ibb.co/BBdfg0P/list-Clinic.png" alt="list-Clinic" height="400" border="0"></a>
<a href="https://ibb.co/VNf8DTp"><img src="https://i.ibb.co/GJzjkR3/cercanas-Clinics.png" alt="cercanas-Clinics" height="400" border="0"></a>
<a href="https://ibb.co/ZKHht3x"><img src="https://i.ibb.co/pZW3Ggd/clinic-Information.png" alt="clinic-Information" height="400" border="0"></a>
<a href="https://ibb.co/DWxkbvN"><img src="https://i.ibb.co/GpKkJ8X/vet-Information.png" alt="vet-Information" height="400" border="0"></a>
<a href="https://ibb.co/GdH3ngx"><img src="https://i.ibb.co/yN4BdLf/book-Appointment.png" alt="book-Appointment" height="400" border="0"></a>
<a href="https://ibb.co/NKT2qSJ"><img src="https://i.ibb.co/bXb5VJC/appointment-Pet-Detail.png" alt="appointment-Pet-Detail" height="400" border="0"></a>
<a href="https://ibb.co/gwVXB77"><img src="https://i.ibb.co/1K6pwnn/appointment-Registered.png" alt="appointment-Registered" height="400" border="0"></a>
<a href="https://ibb.co/4dXjb7D"><img src="https://i.ibb.co/3zj0x78/appointment-Detail.png" alt="appointment-Detail" height="400" border="0"></a>
<a href="https://ibb.co/JzKGC7z"><img src="https://i.ibb.co/NLsJ7jL/list-Appointments.png" alt="list-Appointments" height="400" border="0"></a>

<a href="https://ibb.co/Qf6PKcj"><img src="https://i.ibb.co/6m4HWZJ/homeVet.png" alt="homeVet" height="400" border="0"></a>
<a href="https://ibb.co/tYm8Bvf"><img src="https://i.ibb.co/ssmyjNS/vet-Profile.png" alt="vet-Profile" height="400" border="0"></a>
<a href="https://ibb.co/SmT95Lg"><img src="https://i.ibb.co/z2c0Qkg/generate-Password.png" alt="generate-Password" height="400" border="0"></a>
<a href="https://ibb.co/ZJ0sz5s"><img src="https://i.ibb.co/fSsRdfR/appointment-Detail-Vet.png" alt="appointment-Detail-Vet" height="400" border="0"></a>
<a href="https://ibb.co/yy2BPwf"><img src="https://i.ibb.co/tsRPK7m/add-Report.png" alt="add-Report" height="400" border="0"></a>
<a href="https://ibb.co/1RB0N89"><img src="https://i.ibb.co/sscg4yF/medical-Information.png" alt="medical-Information" height="400" border="0"></a>
<a href="https://ibb.co/s2j7vT1"><img src="https://i.ibb.co/t4BRM02/review.png" alt="review" height="400" border="0"></a>

#### 6.2.2.6. Services Documentation Evidence for Sprint Review.

Se documentaron endpoints esenciales para UPet. Esto implicó detallar y especificar las rutas y funcionalidades de la API que permitirán la comunicación e intercambio de datos entre el frontend y el backend de la aplicación web y móvil. Además de documentar estos endpoints, el equipo realizó confirmaciones (commits) en los repositorios del proyecto para registrar los cambios y avances realizados en el código fuente. A continuación, se muestra los endpoints documentados y los commits:

**Wokwi**

Repositorio Wokwi: https://github.com/SW71-devpaw/wokwi-project

<a href="https://ibb.co/TWhyLXC"><img src="https://i.ibb.co/kmcZ1nd/wokwi-Commits.png" alt="wokwi-Commits" border="0"></a>

**Web application**

Repositorio Web Application: https://github.com/SW71-devpaw/upet-frontend-web

<a href="https://ibb.co/HX9pyV1"><img src="https://i.ibb.co/PtVzyN3/web-Commits.png" alt="web-Commits" border="0"></a>
<a href="https://ibb.co/Z2TXqkG"><img src="https://i.ibb.co/QDmQy1p/web-Commits2.png" alt="web-Commits2" border="0"></a>
<a href="https://ibb.co/YdCsVZn"><img src="https://i.ibb.co/1XgW46y/web-Commits3.png" alt="web-Commits3" border="0"></a>
<a href="https://ibb.co/7XC4kMT"><img src="https://i.ibb.co/qdj5Jq4/web-Commits4.png" alt="web-Commits4" border="0"></a>
<a href="https://ibb.co/McwD5Y9"><img src="https://i.ibb.co/wSGNr9Y/web-Commits5.png" alt="web-Commits5" border="0"></a>
<a href="https://ibb.co/3SNKSYh"><img src="https://i.ibb.co/XFsHFkJ/web-Commits6.png" alt="web-Commits6" border="0"></a>

**Mobile application**

Repositorio Mobile Application: https://github.com/SW71-devpaw/MobileApp-Upet

<a href="https://ibb.co/dD1FqF1"><img src="https://i.ibb.co/bXqTZTq/mobile-Commits.png" alt="mobile-Commits" border="0"></a>
<a href="https://ibb.co/mNy5JJF"><img src="https://i.ibb.co/8YxgMM4/mobile-Commits2.png" alt="mobile-Commits2" border="0"></a>
<a href="https://ibb.co/vY9xFS8"><img src="https://i.ibb.co/SrSXjzp/mobile-Commits3.png" alt="mobile-Commits3" border="0"></a>

**Endpoint Documentados**

| Endpoint               | Verbo HTTP | Parámetros         | Ejemplo de Llamada                                            |
|------------------------|------------|--------------------|---------------------------------------------------------------|
| **Auth**               | POST       | -                  | `/api/v1/auth/sign-up`                                        |
|                        | POST       | -                  | `/api/v1/auth/sign-in`                                        |
| **Users**              | GET        | -                  | `/api/v1/users`                                               |
|                        | GET        | user_id            | `/api/v1/users/{user_id}`                                     |
|                        | PUT        | role_id            | `/api/v1/users/{role_id}`                                     |
| **Veterinary Clinics** | GET        | -                  | `/api/v1/veterinary_clinics`                                  |
|                        | POST       | -                  | `/api/v1/veterinary_clinics`                                  |
| **Pets**               | POST       | petowner_id        | `/api/v1/pets/{petowner_id}`                                  |
|                        | GET        | petowner_id        | `/api/v1/pets/{petowner_id}`                                  |
|                        | GET        | -                  | `/api/v1/pets`                                                |
| **Appointments**       | GET        | -                  | `/api/v1/appointments`                                        |
|                        | POST       | -                  | `/api/v1/appointments`                                        |
|                        | GET        | pet_id             | `/api/v1/appointments/pet/{pet_id}`                           |
|                        | GET        | veterinarian_id    | `/api/v1/appointments/veterinarian/{veterinarian_id}`         |
| **Notifications**      | GET        | -                  | `/api/v1/notifications`                                       |
|                        | POST       | -                  | `/api/v1/notifications`                                       |
|                        | GET        | petowner_id        | `/api/v1/notifications/petowner/{petowner_id}`                |
| **Medical Historys**   | GET        | -                  | `/api/v1/medical_historys`                                    |
|                        | POST       | -                  | `/api/v1/medical_historys`                                    |
|                        | GET        | medical_history_id | `/api/v1/medical_historys/{medical_history_id}/diseases/`     |
|                        | POST       | medicalHistory_id  | `/api/v1/medical_historys/{medicalHistory_id}`                |
|                        | GET        | medical_history_id | `/api/v1/medical_historys/{medical_history_id}/vaccinations/` |
|                        | PUT        | medicalHistory_id  | `/api/v1/medical_historys/{medicalHistoryId}`                 |
| **Pet Owners**         | POST       | user_id            | `/api/v1/users/petowner/{user_id}`                            |
|                        | GET        | -                  | `/api/v1/users/petowner`                                      |
| **Veterinarians**      | POST       | user_id            | `/api/v1/users/veterinarians/{user_id}`                       |
|                        | GET        | -                  | `/api/v1/users/veterinarians`                                 |
| **Diseases**           | GET        | -                  | `/api/v1/diseases`                                            |
|                        | POST       | -                  | `/api/v1/diseases`                                            |
| **Vaccinations**       | GET        | -                  | `/api/v1/vaccinations`                                        |
|                        | POST       | -                  | `/api/v1/vaccinations`                                        |
| **Reviews**            | GET        | -                  | `/api/v1/reviews`                                             |
|                        | POST       | -                  | `/api/v1/reviews`                                             |

#### 6.2.2.7. Software Deployment Evidence for Sprint Review.

El equipo aprovechó las capacidades de Github como sistema de control de versiones y plataforma de colaboración. Dentro de la organización en Github, se estableció un repositorio dedicado para cada uno de los productos desarrollados, es decir, un repositorio para la aplicación móvil, otro para la aplicación web, uno más para el Wokwi y un cuarto para el backend. Esta separación facilitó la gestión y el seguimiento del código fuente de manera organizada. En cuanto al despliegue del backend, se utilizó el servicio de Render y para la base de datos en MySQL esta desplegado en Railway, lo que permitió su publicación y acceso a los endpoints.

**Backend**

Backend desplegado: https://upetbackendapi.onrender.com/docs#/

<a href="https://ibb.co/c1XYdZC"><img src="https://i.ibb.co/0cVs36F/backend.png" alt="backend" border="0"></a>
<a href="https://ibb.co/h7LjBtv"><img src="https://i.ibb.co/yfd16bJ/backend1.png" alt="backend1" border="0"></a>
<a href="https://ibb.co/0JPzMhM"><img src="https://i.ibb.co/QmsxNrN/backend2.png" alt="backend2" border="0"></a>
<a href="https://ibb.co/HpgrqKF"><img src="https://i.ibb.co/LhpC10k/backend3.png" alt="backend3" border="0"></a>
<a href="https://ibb.co/tPY4c0h"><img src="https://i.ibb.co/WpB6Fr3/backend4.png" alt="backend4" border="0"></a>
<a href="https://ibb.co/pdFJNTM"><img src="https://i.ibb.co/1TW8BNP/backend5.png" alt="backend5" border="0"></a>

**Web Application**

Web Application desplegado: https://devpaw-upet.web.app/auth/login

<img src="https://i.postimg.cc/vZcJQkwh/image.png" alt="" height="500"/>
<img src="https://i.postimg.cc/0yFLrn8s/image.png" alt="" height="500"/>

#### 6.2.2.8. Team Collaboration Insights during Sprint.

En el transcurso del sprint 2, el equipo se enfocó en el desarrollo de la aplicación móvil desarrollada en Android Studio y la aplicación web desarrollada con Angular. Para coordinar el trabajo de manera eficiente, se implementó la metodología Gitflow, lo que permitió la participación simultánea de todos los miembros del equipo. Además, durante este período, se realizaron correcciones y mejoras al backend existente.

**Wokwi**

Repositorio Wokwi: https://github.com/SW71-devpaw/wokwi-project

<a href="https://ibb.co/tB0CR0x"><img src="https://i.ibb.co/nrXkpXn/wokwi-Network.png" alt="wokwi-Network" border="0"></a>
<a href="https://ibb.co/L5XQ2cL"><img src="https://i.ibb.co/M6x83tY/wokwi-Pulse.png" alt="wokwi-Pulse" border="0"></a>

**Web application**

Repositorio Web Application: https://github.com/SW71-devpaw/upet-frontend-web

<a href="https://ibb.co/4K8zpGN"><img src="https://i.ibb.co/gmSNJpg/web-Network.png" alt="web-Network" border="0"></a>
<a href="https://ibb.co/x3W0KRd"><img src="https://i.ibb.co/g6NpbBh/web-Network2.png" alt="web-Network2" border="0"></a>
<a href="https://ibb.co/DQhfj21"><img src="https://i.ibb.co/vkp4Mnc/webPulse.png" alt="webPulse" border="0"></a>

**Mobile application**

Repositorio Mobile Application: https://github.com/SW71-devpaw/MobileApp-Upet

<a href="https://ibb.co/mCLhS2z"><img src="https://i.ibb.co/Y7zfb1j/mobile-Network.png" alt="mobile-Network" border="0"></a>
<a href="https://ibb.co/kQmYhsG"><img src="https://i.ibb.co/V2wXvcL/mobile-Pulse.png" alt="mobile-Pulse" border="0"></a>

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

