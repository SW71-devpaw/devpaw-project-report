# Capítulo III: Requirements Specification.

## 3.1. To-Be Scenario Mapping.

En esta sección, se presenta el To Be Scenario Mapping para cada segmento objetivo. Esta herramienta permite visualizar y definir el proceso mejorado. A través de este mapeo, se identificaron las áreas clave de mejora y se establecieron las acciones necesarias para optimizar el rendimiento y la eficiencia en cada segmento.

### Segmento 1: Veterinaria

![To-Be Scenario Mapping Veterinaria](https://i.postimg.cc/XN8vpc7L/To-be-Mapping-Veterinario.png)

### Segmento 2: Propietario de mascota

![To-Be Scenario Mapping PropietariodeMascota](https://i.postimg.cc/D0BfHFYH/To-be-Mapping-Propietariode-Mascota.png)

## 3.2. User Stories.

En esta sección, se presentan los requisitos definidos junto con el conjunto de User Stories y Epics para los requisitos identificados. Las User Stories permiten al equipo de desarrollo comprender las necesidades y expectativas de los usuarios finales, así como priorizar y planificar las funcionalidades del producto de manera efectiva. Asimismo, cada User Storie incluye sus Acceptance Criteria correspondientes.

<table>
      <thead>
            <tr>
                <th>Epic / Story ID</th>
                <th>Título</th>
                <th>Descripción</th>
                <th>Criterios de Aceptación</th>
                <th>Relacionado con (Epic ID)</th>
            </tr>
      </thead>
      <tbody>
            <tr>
                <td>EPIC-01</td>
                <td>Gestión de cuenta </td>
                <td>
                    <strong>Como</strong> usuario, 
                    <strong>quiero</strong> registrar, acceder y configurar mi cuenta 
                    <strong>para</strong> ingresar y utilizar las funcionalidades de la aplicación.
                </td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>EPIC-02</td>
                <td>Gestión de la información de la mascota</td>
                <td>
                    <strong>Como</strong> usuario registrado, 
                    <strong>quiero</strong> registrar, editar y compartir la información de mi mascota
                    <strong>para</strong> tener un control y seguimiento de mi mascota.
                </td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>EPIC-03</td>
                <td>Gestión de citas</td>
                <td>
                    <strong>Como</strong> usuario registrado, 
                    <strong>quiero</strong> agendar, reprogramar o cancelar citas
                    <strong>para</strong> manejar y organizar las citas de mi mascota.
                </td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>EPIC-04</td>
                <td>Notificaciones</td>
                <td>
                    <strong>Como</strong> usuario registrado, 
                    <strong>quiero</strong> activar y recibir notificaciones
                    <strong>para</strong> estar informado sobre las citas y recordatorios de mi mascota.
                </td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>EPIC-05</td>
                <td>Registro del Historial médico veterinario</td>
                <td>
                    <strong>Como</strong> usuario registrado, 
                    <strong>quiero</strong> registrar y visualizar el historial médico veterinario de mi mascota
                    <strong>para</strong> digitalizar y compartir la información con el veterinario.
                </td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>EPIC-06</td>
                <td>Gestión de la suscripción</td>
                <td>
                    <strong>Como</strong> usuario registrado, 
                    <strong>quiero</strong> suscribirme y gestionar mi plan de suscripción
                    <strong>para</strong> acceder a funcionalidades premium y beneficios exclusivos.
                </td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>EPIC-07</td>
                <td>Búsqueda de veterinarias en el mapa</td>
                <td>
                    <strong>Como</strong> usuario registrado, 
                    <strong>quiero</strong> buscar y visualizar veterinarias cercanas
                    <strong>para</strong> ubicar y contactar a un veterinario.
                </td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>EPIC-08</td>
                <td>Información de Veterinarias</td>
                <td>
                    <strong>Como</strong> usuario registrado, 
                    <strong>quiero</strong> visualizar información detallada de las veterinarias
                    <strong>para</strong> conocer los servicios y horarios de atención.
                </td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>EPIC-09</td>
                <td>Registro de veterinarias</td>
                <td>
                    <strong>Como</strong> usuario registrado, 
                    <strong>quiero</strong> registrar y editar información de la veterinaria
                    <strong>para</strong> actualizar y mantener actualizada la información.
                </td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>EPIC-10</td>
                <td>Backend API</td>
                <td>
                    <strong>Como</strong> usuario desarrollador, 
                    <strong>quiero</strong> implementar una API RESTful 
                    <strong>para</strong> gestionar la información de la aplicación.
                </td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>EPIC-11</td>
                <td>Acceso al sitio web estático</td>
                <td>
                    <strong>Como</strong> usuario visitante, 
                    <strong>quiero</strong> acceder al sitio web estático
                    <strong>para</strong> conocer la información de la aplicación.
                </td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>EPIC-12</td>
                <td>Gestión de dispositivos IoT</td>
                <td>
                    <strong>Como</strong> desarrollador, 
                    <strong>quiero</strong> implementar la gestión de dispositivos IoT
                    <strong>para</strong> integrar dispositivos IoT en la aplicación. 
                </td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <td>US-001</td>
                <td>Registro de cuenta</td>
                <!-- Descripción -->
                <td> 
                <strong>Como</strong> veterinario o propietario de una mascota
                <strong>quiero</strong> registrarme en la aplicación 
                <strong>para</strong> acceder a sus funcionalidades.
                </td>
                <!-- ---------- -->
                <!-- Criterios de Aceptación -->
                <td> 
                <h5>Escenario 01: Registro Exitoso</h5>
                <strong>Dado</strong> el usuario está en la pantalla de registro
                <strong>cuando</strong> complete los campos requeridos,
                <strong>Entonces</strong> la cuenta se crea exitosamente y se redirige a la pantalla de inicio de sesión. 
                <br>
                <h5>Escenario 02: Datos Incompletos en el Registro</h5>
                <strong>Dado</strong> el usuario está en la pantalla de registro,
                <strong>cuando</strong> intenta registrarse con datos incompletos,
                <strong>Entonces</strong> se muestra un mensaje de error y se le pide que complete los campos vacíos.
                <br>
                <h5>Escenario 03:  Correo Electrónico en Uso</h5>
                <strong>Dado</strong> el usuario está en la pantalla de registro,
                <strong>cuando</strong> intenta registrarse con un correo electrónico que está en uso,
                <strong>Entonces</strong> se muestra un mensaje de error que indica que el correo ya está registrado en la aplicación.
                </td>   
                <br>
                <!-- ---------- -->
                <td>EPIC-01</td>
            </tr>
            <tr>
                <td>US-002</td>
                <td>Iniciar Sesión</td>
                <td>
                    <strong>Como</strong> veterinario o propietario de una mascota 
                    <strong>quiero</strong> poder iniciar sesión en la aplicación utilizando mis credenciales 
                    <strong>para</strong> acceder a las funcionalidades y gestionar la información ingresada.
                </td>
                <td>
                    <h5>Escenario 01: Inicio de Sesión Exitoso</h5>
                    <strong>Dado</strong> el usuario está en la pantalla de inicio de sesión, 
                    <strong>cuando</strong> ingresa su correo electrónico y contraseña, 
                    <strong>Entonces</strong> accede exitosamente a su cuenta y se redirige a la pantalla de inicio.
                    <br>
                    <h5>Escenario 02: Datos Incorrectos en el Inicio de Sesión</h5>
                    <strong>Dado</strong> el usuario está en la pantalla de inicio de sesión, 
                    <strong>cuando</strong> ingresa un correo electrónico o una contraseña incorrecta, 
                    <strong>Entonces</strong> se muestra un mensaje de error indicando que el correo electrónico o la contraseña están incorrectos.
                    <br>
                    <h5>Escenario 03: Correo no Registrado en el Inicio de Sesión</h5>
                    <strong>Dado</strong> el usuario está en la pantalla de inicio de sesión, 
                    <strong>cuando</strong> intenta iniciar sesión con un correo que no está registrado, 
                    <strong>Entonces</strong> se muestra un mensaje de error indicando que el correo no está registrado.
                </td>
                <td>EPIC-01</td>
            </tr>
            <tr>
                <td>US-003</td>
                <td>Reestablecer Contraseña</td>
                <td>
                    <strong>Como</strong> veterinario o propietario de una mascota 
                    <strong>quiero</strong> tener la capacidad de restablecer mi contraseña en la aplicación 
                    <strong>para</strong> poder acceder de nuevo a mi cuenta y gestionar la información de manera segura.
                </td>
                <td>
                    <h5>Escenario 01: Solicitud de Recuperación de Contraseña Exitosa</h5>
                    <strong>Dado</strong> el usuario se encuentra en la pantalla de recuperación de contraseña, luego de dar clic a “¿olvidé contraseña?”, 
                    <strong>cuando</strong> ingresa su correo electrónico registrado y hace clic en “enviar”, 
                    <strong>Entonces</strong> se le envía un correo electrónico con un enlace para reestablecer su contraseña.
                    <br>
                    <h5>Escenario 02: Cambio de Contraseña Exitoso</h5>
                    <strong>Dado</strong> el usuario recibe el correo para reestablecer su contraseña, 
                    <strong>cuando</strong> hace clic en el enlace proporcionado, 
                    <strong>Entonces</strong> se le redirige a una página para crear una nueva contraseña.
                    <br>
                    <h5>Escenario 03: Correo Electrónico no Registrado para Recuperación de Contraseña</h5>
                    <strong>Dado</strong> el usuario se encuentra en la pantalla de recuperación de contraseña, luego de dar clic a “¿olvidé contraseña?”, 
                    <strong>cuando</strong> ingresa un correo electrónico no registrado y hace clic en “enviar”, 
                    <strong>Entonces</strong> se muestra un mensaje de error indicando que ingrese un correo registrado.
                </td>
                <td>EPIC-01</td>
            </tr>
            <tr>
                <td>US-004</td>
                    <td>Cerrar Sesión</td>
                    <td>
                        <strong>Como</strong> veterinario o propietario de una mascota 
                        <strong>quiero</strong> tener la capacidad de cerrar sesión en la aplicación 
                        <strong>para</strong> garantizar la seguridad de mi información y proteger mi privacidad.
                  </td>
                  <td>
                      <h5>Escenario 01: Cierre de Sesión Exitoso</h5>
                      <strong>Dado</strong> el usuario está autenticado en la aplicación, 
                      <strong>cuando</strong> selecciona la opción “Cerrar sesión” desde la pantalla de inicio, 
                      <strong>Entonces</strong> se cierra exitosamente la sesión del usuario y se redirige a la pantalla de inicio de sesión.
                  </td>
                  <td>EPIC-01</td>
            </tr>
            <tr>
                  <td>US-005</td>
                  <td>Registrar Mascota</td>
                  <td>
                      <strong>Como</strong> propietario de una mascota 
                      <strong>quiero</strong> crear un perfil para cada una de mis mascotas en la aplicación, ingresando su información básica 
                      <strong>para</strong> mantener un registro organizado de sus datos.
                  </td>
                  <td>
                      <h5>Escenario 01: Agregar una Nueva Mascota</h5>
                      <strong>Dado</strong> el propietario de mascota se encuentra en la página principal, 
                      <strong>cuando</strong> selecciona la opción de agregar una nueva mascota, 
                      <strong>Entonces</strong> se abre un formulario donde puede ingresar el nombre, la raza, la edad, el peso, entre otros datos importantes.
                      <br>
                      <h5>Escenario 02: Guardar Cambios de la Mascota</h5>
                      <strong>Dado</strong> el propietario de mascota ha ingresado la información en el formulario de la mascota, 
                      <strong>cuando</strong> guarda los cambios realizados, 
                      <strong>Entonces</strong> la información de la mascota se actualiza en el sistema y se muestra un mensaje de confirmación.
                      <br>
                      <h5>Escenario 03: Validación de Campos Obligatorios</h5>
                      <strong>Dado</strong> el propietario se encuentra en el formulario de información de la mascota, 
                      <strong>cuando</strong> intenta guardar los cambios sin completar todos los campos obligatorios, 
                      <strong>Entonces</strong> se muestra un mensaje de error que indica que debe llenar los campos requeridos.
                  </td>
                  <td>EPIC-02</td>
            </tr>
                        <tr>
                <td>US-006</td>
                <td>Subir foto de la mascota</td>
                <td>
                    <strong>Como</strong> propietario de mascota,
                    <strong>quiero</strong> poder subir una foto de mi mascota a la plataforma,
                    <strong>para</strong> poder personalizar su perfil y compartir su imagen con las veterinarias.
                </td>
                <td>
                    <h5>Escenario 01: Selección de Foto</h5>
                    <strong>Dado</strong> que estoy en la página de perfil de mi mascota,
                    <strong>cuando</strong> hago clic en el botón "Subir foto",
                    <strong>Entonces</strong> se abre un cuadro de diálogo para seleccionar la foto desde mi dispositivo.
                    <br>
                    <h5>Escenario 02: Confirmación de selección de foto</h5>
                    <strong>Dado</strong> que he seleccionado la foto de mi mascota,
                    <strong>cuando</strong> confirmo la selección,
                    <strong>Entonces</strong> la foto se carga correctamente en el perfil de la mascota y se muestra en la página.
                    <br>
                    <h5>Escenario 03: Manejar errores de carga de foto</h5>
                    <strong>Dado</strong> intento subir una foto que no cumple con los requisitos de formato o tamaño,
                    <strong>cuando</strong> selecciono la foto y trato de cargarla,
                    <strong>Entonces</strong> recibo un mensaje de error indicando los requisitos de formato o tamaño y no se permite la carga de la foto hasta que cumpla con estos criterios.
                </td>
                <td>EPIC-02</td>
            </tr>
            <tr>
                <td>US-007</td>
                <td>Ver listado de mis mascotas</td>
                <td>
                    <strong>Como</strong> propietario de una mascota,
                    <strong>quiero</strong> poder ver un listado de todas mis mascotas registradas en la aplicación,
                    <strong>para</strong> tener un acceso rápido a su información y gestionarlas de manera eficiente.
                </td>
                <td>
                    <h5>Escenario 01: Listado de mascotas</h5>
                    <strong>Dado</strong> el propietario de la mascota se encuentra en la pantalla inicial de la aplicación,
                    <strong>cuando</strong> navega a la sección de "Mis Mascotas",
                    <strong>Entonces</strong> se muestra un listado de todas sus mascotas registradas, incluyendo su nombre y foto.
                    <br>
                    <h5>Escenario 02: Usuario sin mascotas registradas</h5>
                    <strong>Dado</strong> el propietario de la mascota se encuentra en la pantalla inicial de la aplicación,
                    <strong>cuando</strong> el usuario intenta acceder al listado de sus mascotas, pero no tiene ninguna mascota registrada,
                    <strong>Entonces</strong> se muestra un mensaje de error indicando que no tiene mascotas registradas.
                    <br>
                    <h5>Escenario 03: Detalles de mascota seleccionada</h5>
                    <strong>Dado</strong> el propietario de la mascota se encuentra en la pantalla de “Mis mascotas”,
                    <strong>cuando</strong> selecciona una mascota del listado,
                    <strong>Entonces</strong> se muestra una pantalla con los detalles completos de la mascota, incluyendo su nombre, foto, especie, raza, edad, entre otros datos importantes.
                </td>
                <td>EPIC-02</td>
            </tr>
            <tr>
                <td>US-008</td>
                <td>Compartir información</td>
                <td>
                    <strong>Como</strong> propietario de una mascota,
                    <strong>quiero</strong> poder compartir información relevante sobre el perfil de mi mascota con veterinarios que no tienen acceso a la aplicación,
                    <strong>para</strong> facilitar el intercambio de información y garantizar la atención adecuada de mi mascota incluso fuera de la red de la aplicación.
                </td>
                <td>
                    <h5>Escenario 01: Selección de información de perfil para el PDF</h5>
                    <strong>Dado</strong> que el propietario está viendo el perfil de su mascota en la aplicación,
                    <strong>cuando</strong> selecciona la opción para generar un PDF,
                    <strong>Entonces</strong> se le presenta un formulario donde puede seleccionar la información que desea incluir en el PDF.
                    <br>
                    <h5>Escenario 02: Generación de PDF</h5>
                    <strong>Dado</strong> que el propietario de la mascota ha seleccionado la información deseada,
                    <strong>cuando</strong> confirma la generación del PDF,
                    <strong>Entonces</strong> la aplicación genera un archivo PDF bien formateado que contiene la información seleccionada.
                    <br>
                    <h5>Escenario 03: Descarga y compartición del PDF</h5>
                    <strong>Dado</strong> que el propietario de la mascota ha generado el PDF,
                    <strong>cuando</strong> selecciona la opción de “descargar perfil”,
                    <strong>Entonces</strong> el PDF se descarga en el dispositivo móvil del propietario.
                </td>
                <td>EPIC-02</td>
            </tr>
            <tr>
                <td>US-009</td>
                <td>Editar información de la mascota</td>
                <td>
                    <strong>Como</strong> propietario de una mascota,
                    <strong>quiero</strong> poder editar la información del perfil de mi mascota en la aplicación,
                    <strong>para</strong> mantener actualizada la información de mis mascotas.
                </td>
                <td>
                    <h5>Escenario 01: Acceso al perfil de la mascota para editar</h5>
                    <strong>Dado</strong> el usuario se encuentra en el perfil de la mascota que desea editar,
                    <strong>cuando</strong> selecciona la opción de actualizar información,
                    <strong>Entonces</strong> aparece el formulario de edición de perfil.
                    <br>
                    <h5>Escenario 02: Edición de la información de la mascota</h5>
                    <strong>Dado</strong> el propietario de la mascota se encuentra en el formulario,
                    <strong>cuando</strong> modifica la información de su mascota y selecciona la opción guardar,
                    <strong>Entonces</strong> se muestra un mensaje indicando que la información del perfil de la mascota ha sido actualizada correctamente.
                    <br>
                    <h5>Escenario 03: Validación de datos al editar</h5>
                    <strong>Dado</strong> que el propietario de la mascota se encuentra en el formulario de edición de perfil,
                    <strong>cuando</strong> intenta guardar cambios con un campo obligatorio sin completar,
                    <strong>Entonces</strong> se muestra un mensaje de error indicando que es necesario completar todos los campos obligatorios antes de guardar los cambios.
                </td>
                <td>EPIC-02</td>
            </tr>
            <tr>
                <td>US-010</td>
                <td>Agendar una cita</td>
                <td>
                    <strong>Como</strong> propietario de una mascota,
                    <strong>quiero</strong> poder agendar una cita en la clínica veterinaria a través de la aplicación,
                    <strong>para</strong> asegurar la atención médica oportuna para mi mascota.
                </td>
                <td>
                    <h5>Escenario 01: Elección del veterinario</h5>
                    <strong>Dado</strong> el propietario de la mascota se encuentra en el perfil de una clínica veterinaria,
                    <strong>cuando</strong> presiona la opción de agendar cita,
                    <strong>Entonces</strong> le muestra un formulario para elegir la fecha y hora.
                    <br>
                    <h5>Escenario 02: Agendar una cita con éxito</h5>
                    <strong>Dado</strong> el propietario de la mascota se encuentra en el formulario para agendar una cita,
                    <strong>cuando</strong> elige una fecha y hora disponibles, selecciona el tipo de servicio necesario para su mascota y confirma la cita,
                    <strong>Entonces</strong> la cita se agenda correctamente y se muestra un mensaje de confirmación.
                    <br>
                    <h5>Escenario 03: Selección de fecha y hora no disponible</h5>
                    <strong>Dado</strong> el propietario de una mascota se encuentra en la sección de citas,
                    <strong>cuando</strong> intenta agendar una cita en una fecha que no está disponible,
                    <strong>Entonces</strong> se muestra un mensaje indicando que no hay horarios disponibles en esa fecha y se le sugiere seleccionar una fecha alternativa.
                </td>
                <td>EPIC-03</td>
            </tr>
            <tr>
                <td>US-011</td>
                <td>Activar recordatorio</td>
                <td>
                    <strong>Como</strong> propietario de una mascota con una cita veterinaria programada,
                    <strong>quiero</strong> poder activar un recordatorio en la aplicación,
                    <strong>para</strong> recibir una notificación en la fecha y hora de la cita y asegurarme de no olvidarla.
                </td>
                <td>
                    <h5>Escenario 01: Recordatorio activado con éxito</h5>
                    <strong>Dado</strong> el usuario tiene una cita veterinaria programada y está en la pantalla de activación de recordatorio,
                    <strong>cuando</strong> activa el recordatorio seleccionando la opción correspondiente en la aplicación,
                    <strong>Entonces</strong> la aplicación programa el recordatorio y muestra una confirmación al usuario.
                    <br>
                    <h5>Escenario 02: Error al activar el recordatorio</h5>
                    <strong>Dado</strong> el usuario tiene una cita veterinaria programada y está en la pantalla de activación de recordatorio,
                    <strong>cuando</strong> intenta activar el recordatorio, pero la aplicación no puede programarlo debido a un error técnico,
                    <strong>Entonces</strong> la aplicación muestra un mensaje de error y sugiere al usuario intentarlo más tarde o contactar con soporte técnico.
                    <br>
                    <h5>Escenario 03: Fecha u hora incorrecta al activar el recordatorio</h5>
                    <strong>Dado</strong> el usuario tiene una cita veterinaria programada y está en la pantalla de activación de recordatorio,
                    <strong>cuando</strong> el usuario activa el recordatorio pero selecciona una fecha o hora incorrecta,
                    <strong>Entonces</strong> la aplicación muestra un mensaje indicando que la fecha u hora seleccionada no son válidas y solicita al usuario que corrija la configuración del recordatorio.
                </td>
                <td>EPIC-04</td>
            </tr>
            <tr>
                <td>US-012</td>
                <td>Acceso de la veterinaria a la información de la mascota</td>
                <td>
                    <strong>Como</strong> veterinario,
                    <strong>quiero</strong> poder acceder a la información completa de una mascota, incluyendo su historial médico, vacunas y tratamientos previos,
                    <strong>para</strong> brindar una atención adecuada durante una consulta veterinaria.
                </td>
                <td>
                    <h5>Escenario 01: Acceso exitoso a la información de la mascota</h5>
                    <strong>Dado</strong> el veterinario está en la consulta de la mascota y necesita acceder a su información,
                    <strong>cuando</strong> ingresa al perfil de la mascota en la aplicación,
                    <strong>Entonces</strong> la aplicación muestra la información completa de la mascota, incluyendo su historial médico, vacunas, tratamientos previos y cualquier otra información relevante.
                    <br>
                    <h5>Escenario 02: Error al acceder a la información de la mascota</h5>
                    <strong>Dado</strong> el veterinario está en la consulta de la mascota y necesita acceder a su información,
                    <strong>cuando</strong> intenta acceder a la información pero la aplicación no puede cargarla debido a un error técnico,
                    <strong>Entonces</strong> la aplicación muestra un mensaje de error y sugiere al veterinario intentarlo más tarde o contactar con soporte técnico.
                    <br>
                    <h5>Escenario 03: Información incompleta de la mascota</h5>
                    <strong>Dado</strong> el veterinario está en la consulta de la mascota y necesita acceder a su información,
                    <strong>cuando</strong> accede a la información de la mascota pero encuentra que algunos datos importantes están incompletos o faltantes,
                    <strong>Entonces</strong> la aplicación muestra una alerta al veterinario indicando que la información de la mascota está incompleta y sugiere completarla lo antes posible para garantizar una atención adecuada.
                </td>
                <td>EPIC-05</td>
            </tr>
            <tr>
                <td>US-013</td>
                <td>Cancelar o reprogramar cita</td>
                <td>
                    <strong>Como</strong> propietario de una mascota,
                    <strong>quiero</strong> poder cancelar o reprogramar una cita veterinaria previamente programada,
                    <strong>para</strong> poder gestionar mejor mi agenda y evitar problemas de horarios.
                </td>
                <td>
                    <h5>Escenario 01: Cancelación de cita exitosa</h5>
                    <strong>Dado</strong> el propietario está en la pantalla de detalles de la cita que desea cancelar,
                    <strong>cuando</strong> selecciona la opción de cancelar cita y confirma la cancelación,
                    <strong>Entonces</strong> la aplicación cancela la cita y muestra un mensaje de confirmación al propietario.
                    <br>
                    <h5>Escenario 02: Reprogramación de cita exitosa</h5>
                    <strong>Dado</strong> el propietario está en la pantalla de detalles de la cita que desea reprogramar,
                    <strong>cuando</strong> elige una nueva fecha y hora y confirma la reprogramación,
                    <strong>Entonces</strong> la aplicación actualiza la cita con la nueva fecha y hora y muestra un mensaje de confirmación.
                    <br>
                    <h5>Escenario 03: Error al cancelar o reprogramar cita</h5>
                    <strong>Dado</strong> el propietario está en la pantalla de detalles de la cita que desea cancelar o reprogramar,
                    <strong>cuando</strong> intenta cancelar o reprogramar la cita pero la aplicación no puede procesar la solicitud debido a un error técnico,
                    <strong>Entonces</strong> la aplicación muestra un mensaje de error y sugiere al propietario intentarlo más tarde o contactar con soporte técnico.
                </td>
                <td>EPIC-03</td>
            </tr>
            <tr>
                <td>US-014</td>
                <td>Ver historial de citas</td>
                <td>
                    <strong>Como</strong> propietario de una mascota,
                    <strong>quiero</strong> poder ver el historial completo de citas veterinarias de mi mascota, incluyendo fechas, horarios y propósito de la visita,
                    <strong>para</strong> tener un registro completo de la atención recibida.
                </td>
                <td>
                    <h5>Escenario 01: Consulta de historial de citas exitosa</h5>
                    <strong>Dado</strong> el propietario está en la pantalla de historial de citas de la mascota,
                    <strong>cuando</strong> selecciona la opción de ver historial de citas,
                    <strong>Entonces</strong> la aplicación muestra una lista completa de todas las citas veterinarias anteriores de la mascota, incluyendo fechas, horarios, propósito de la visita y cualquier otra información relevante.
                    <br>
                    <h5>Escenario 02: Sin citas anteriores registradas</h5>
                    <strong>Dado</strong> el propietario está en la pantalla de historial de citas de la mascota,
                    <strong>cuando</strong> no tiene citas anteriores registradas,
                    <strong>Entonces</strong> la aplicación muestra un mensaje indicando que no hay citas anteriores registradas para la mascota.
                    <br>
                    <h5>Escenario 03: Error al cargar historial de citas</h5>
                    <strong>Dado</strong> el propietario está en la pantalla de historial de citas de la mascota,
                    <strong>cuando</strong> la aplicación intenta cargar el historial de citas pero se produce un error técnico,
                    <strong>Entonces</strong> la aplicación muestra un mensaje de error y sugiere al propietario intentarlo más tarde o contactar con soporte técnico.
                </td>
                <td>EPIC-03</td>
            </tr>
            <tr>
                <td>US-015</td>
                <td>Ofertas de las veterinarias</td>
                <td>
                    <strong>Como</strong> propietario de mascota,
                    <strong>quiero</strong> poder recibir notificaciones sobre ofertas y promociones especiales de las veterinarias cercanas,
                    <strong>para</strong> poder aprovechar descuentos y beneficios adicionales en la atención de mi mascota.
                </td>
                <td>
                    <h5>Escenario 01: Recepción de oferta o promoción</h5>
                    <strong>Dado</strong> el propietario tiene la función de recibir notificaciones de ofertas activada,
                    <strong>cuando</strong> una veterinaria cercana publica una oferta o promoción en la aplicación,
                    <strong>Entonces</strong> la aplicación envía una notificación al propietario informando sobre la oferta o promoción.
                    <br>
                    <h5>Escenario 02: Configuración de preferencias de notificación</h5>
                    <strong>Dado</strong> el propietario tiene la función de recibir notificaciones de ofertas activada,
                    <strong>cuando</strong> desea configurar sus preferencias de notificación para recibir ofertas solo de ciertas veterinarias o en ciertos días,
                    <strong>Entonces</strong> la aplicación permite al propietario configurar sus preferencias según sus necesidades.
                    <br>
                    <h5>Escenario 03: No interés en recibir ofertas</h5>
                    <strong>Dado</strong> el propietario tiene la función de recibir notificaciones de ofertas activada,
                    <strong>cuando</strong> decide desactivar la función de recibir notificaciones de ofertas,
                    <strong>Entonces</strong> la aplicación deja de enviar notificaciones sobre ofertas y promociones al propietario.
                </td>
                <td>EPIC-06</td>
            </tr>
            <tr>
                <td>US-016</td>
                <td>Notificación de campañas veterinarias</td>
                <td>
                    <strong>Como</strong> propietario de mascota,
                    <strong>quiero</strong> poder recibir notificaciones sobre campañas veterinarias cercanas, como campañas de vacunación y desparasitación,
                    <strong>para</strong> mantener la salud de mi mascota al día.
                </td>
                <td>
                    <h5>Escenario 01: Recepción de notificación de campaña veterinaria</h5>
                    <strong>Dado</strong> el propietario tiene la función de recibir notificaciones de campañas veterinarias activada,
                    <strong>cuando</strong> una clínica veterinaria cercana realiza una campaña veterinaria,
                    <strong>Entonces</strong> la aplicación envía una notificación al propietario informando sobre la campaña, incluyendo detalles como la fecha, horario y servicios ofrecidos.
                    <br>
                    <h5>Escenario 02: Configuración de preferencias de notificación</h5>
                    <strong>Dado</strong> el propietario tiene la función de recibir notificaciones de campañas veterinarias activada,
                    <strong>cuando</strong> desea configurar sus preferencias para recibir información solo sobre campañas específicas,
                    <strong>Entonces</strong> la aplicación permite al propietario configurar sus preferencias según sus necesidades.
                    <br>
                    <h5>Escenario 03: No interés en recibir notificaciones de campañas veterinarias</h5>
                    <strong>Dado</strong> el propietario tiene la función de recibir notificaciones de campañas veterinarias activada,
                    <strong>cuando</strong> decide desactivar la función de recibir notificaciones de campañas,
                    <strong>Entonces</strong> la aplicación deja de enviar notificaciones sobre campañas veterinarias al propietario.
                </td>
                <td>EPIC-06</td>
            </tr>
            <tr>
                <td>US-017</td>
                <td>Confirmar cita</td>
                <td>
                    <strong>Como</strong> propietario de mascota,
                    <strong>quiero</strong> poder confirmar una cita veterinaria previamente agendada,
                    <strong>para</strong> asegurarme de que la cita está programada y evitar confusiones.
                </td>
                <td>
                    <h5>Escenario 01: Confirmación de cita exitosa</h5>
                    <strong>Dado</strong> el propietario recibe una notificación de recordatorio de la cita,
                    <strong>cuando</strong> selecciona la opción de confirmar cita en la notificación,
                    <strong>Entonces</strong> la aplicación registra la confirmación de la cita y muestra un mensaje de confirmación al propietario.
                    <br>
                    <h5>Escenario 02: Cancelación de cita después de confirmación</h5>
                    <strong>Dado</strong> el propietario ha confirmado la cita,
                    <strong>cuando</strong> decide cancelar la cita,
                    <strong>Entonces</strong> la aplicación cancela la cita y muestra un mensaje de confirmación al propietario.
                    <br>
                    <h5>Escenario 03: Error al confirmar cita</h5>
                    <strong>Dado</strong> el propietario recibe una notificación de recordatorio de la cita,
                    <strong>cuando</strong> intenta confirmar la cita pero la aplicación no puede procesar la solicitud debido a un error técnico,
                    <strong>Entonces</strong> la aplicación muestra un mensaje de error y sugiere al propietario intentarlo más tarde o contactar con soporte técnico.
                </td>
                <td>EPIC-04</td>
            </tr>
            <tr>
                <td>US-018</td>
                <td>Recordatorio de cita</td>
                <td>
                    <strong>Como</strong> propietario de mascota,
                    <strong>quiero</strong> recibir recordatorios de las citas veterinarias previamente agendadas,
                    <strong>para</strong> no olvidar la cita y organizarme mejor.
                </td>
                <td>
                    <h5>Escenario 01: Recepción de recordatorio de cita</h5>
                    <strong>Dado</strong> el propietario tiene la función de recibir recordatorios activada,
                    <strong>cuando</strong> se acerca la fecha y hora de la cita veterinaria,
                    <strong>Entonces</strong> la aplicación envía un recordatorio con la fecha, hora y lugar de la cita.
                    <br>
                    <h5>Escenario 02: Configuración de preferencias de recordatorio</h5>
                    <strong>Dado</strong> el propietario tiene la función de recibir recordatorios activada,
                    <strong>cuando</strong> desea configurar el tiempo antes de la cita en que desea recibir el recordatorio,
                    <strong>Entonces</strong> la aplicación permite al propietario configurar sus preferencias.
                    <br>
                    <h5>Escenario 03: No interés en recibir recordatorios de cita</h5>
                    <strong>Dado</strong> el propietario tiene la función de recibir recordatorios activada,
                    <strong>cuando</strong> decide desactivar la función de recibir recordatorios,
                    <strong>Entonces</strong> la aplicación deja de enviar recordatorios sobre citas al propietario.
                </td>
                <td>EPIC-04</td>
            </tr>
            <tr>
                <td>US-019</td>
                <td>Recordatorio de suscripción</td>
                <td>
                    <strong>Como</strong> propietario de mascota suscrito a un plan de servicios veterinarios,
                    <strong>quiero</strong> recibir recordatorios de mi suscripción, incluyendo fechas de renovación,
                    <strong>para</strong> gestionar mi plan de manera efectiva.
                </td>
                <td>
                    <h5>Escenario 01: Recepción de recordatorio de suscripción</h5>
                    <strong>Dado</strong> el propietario tiene la función de recibir recordatorios de suscripción activada,
                    <strong>cuando</strong> se acerca la fecha de renovación de la suscripción,
                    <strong>Entonces</strong> la aplicación envía un recordatorio con la fecha de renovación y detalles de los servicios incluidos.
                    <br>
                    <h5>Escenario 02: Configuración de preferencias de recordatorio</h5>
                    <strong>Dado</strong> el propietario tiene la función de recibir recordatorios de suscripción activada,
                    <strong>cuando</strong> desea configurar las preferencias del tiempo antes de la renovación en que desea recibir el recordatorio,
                    <strong>Entonces</strong> la aplicación permite al propietario configurar sus preferencias.
                    <br>
                    <h5>Escenario 03: No interés en recibir recordatorios de suscripción</h5>
                    <strong>Dado</strong> el propietario tiene la función de recibir recordatorios de suscripción activada,
                    <strong>cuando</strong> decide desactivar la función de recibir recordatorios,
                    <strong>Entonces</strong> la aplicación deja de enviar recordatorios sobre la suscripción al propietario.
                </td>
                <td>EPIC-06</td>
            </tr>
            <tr>
                <td>US-020</td>
                <td>Registrar vacunas</td>
                <td>
                    <strong>Como</strong> veterinario o personal autorizado,
                    <strong>quiero</strong> poder registrar las vacunas administradas a cada mascota,
                    <strong>para</strong> mantener un historial médico completo y actualizado.
                </td>
                <td>
                    <h5>Escenario 01: Registro de vacuna exitoso</h5>
                    <strong>Dado</strong> el usuario está autenticado como veterinario o personal autorizado,
                    <strong>cuando</strong> se administra una vacuna a una mascota,
                    <strong>Entonces</strong> se registra la vacuna en el historial médico de la mascota con los detalles correspondientes.
                    <br>
                    <h5>Escenario 02: Validación de datos de vacuna</h5>
                    <strong>Dado</strong> el usuario está autenticado como veterinario o personal autorizado,
                    <strong>cuando</strong> intenta registrar una vacuna pero faltan datos obligatorios,
                    <strong>Entonces</strong> la aplicación muestra un mensaje de error indicando los datos faltantes y no permite el registro hasta que se completen.
                    <br>
                    <h5>Escenario 03: Actualización de vacuna existente</h5>
                    <strong>Dado</strong> el usuario está autenticado como veterinario o personal autorizado,
                    <strong>cuando</strong> se necesita actualizar la información de una vacuna existente,
                    <strong>Entonces</strong> el usuario puede buscar la vacuna existente en el historial médico de la mascota y actualizar los datos.
                </td>
                <td>EPIC-05</td>
            </tr>
            <tr>
                <td>US-021</td>
                <td>Registrar resultados</td>
                <td>
                    <strong>Como</strong> veterinario o personal autorizado,
                    <strong>quiero</strong> poder registrar los resultados de análisis obtenidos de cada mascota,
                    <strong>para</strong> mantener un historial médico completo y actualizado.
                </td>
                <td>
                    <h5>Escenario 01: Registro de resultados exitoso</h5>
                    <strong>Dado</strong> el usuario está autenticado como veterinario o personal autorizado,
                    <strong>cuando</strong> se obtienen los resultados de análisis de una mascota,
                    <strong>Entonces</strong> el usuario registra los datos del resultado en el historial médico de la mascota.
                    <br>
                    <h5>Escenario 02: Validación de datos de resultados</h5>
                    <strong>Dado</strong> el usuario está autenticado como veterinario o personal autorizado,
                    <strong>cuando</strong> intenta registrar los resultados pero faltan datos obligatorios,
                    <strong>Entonces</strong> la aplicación muestra un mensaje de error indicando los datos faltantes.
                    <br>
                    <h5>Escenario 03: Adición de resultados al historial médico</h5>
                    <strong>Dado</strong> el usuario está autenticado como veterinario o personal autorizado,
                    <strong>cuando</strong> tiene los resultados registrados y quiere agregarlos al historial médico,
                    <strong>Entonces</strong> la aplicación muestra una opción de añadir el registro de resultados al historial médico del paciente.
                </td>
                <td>EPIC-05</td>
            </tr>
            <tr>
                <td>US-022</td>
                <td>Registrar cirugías</td>
                <td>
                    <strong>Como</strong> veterinario o personal autorizado,
                    <strong>quiero</strong> registrar un reporte de los resultados de cirugías realizadas en cada mascota,
                    <strong>para</strong> mantener un historial médico completo y actualizado.
                </td>
                <td>
                    <h5>Escenario 01: Registro de reporte quirúrgico exitoso</h5>
                    <strong>Dado</strong> el usuario está autenticado como veterinario o personal autorizado,
                    <strong>cuando</strong> se realiza una cirugía en una mascota,
                    <strong>Entonces</strong> el usuario registra los detalles de la cirugía en el historial médico de la mascota.
                    <br>
                    <h5>Escenario 02: Validación de datos del reporte</h5>
                    <strong>Dado</strong> el usuario está autenticado como veterinario o personal autorizado,
                    <strong>cuando</strong> intenta registrar los datos de la cirugía pero faltan datos obligatorios,
                    <strong>Entonces</strong> la aplicación muestra un mensaje de error indicando los datos faltantes.
                    <br>
                    <h5>Escenario 03: Adición de resultados de cirugía al historial médico</h5>
                    <strong>Dado</strong> el usuario está autenticado como veterinario o personal autorizado,
                    <strong>cuando</strong> tiene los resultados registrados de la cirugía y quiere agregarlos al historial médico,
                    <strong>Entonces</strong> la aplicación muestra una opción de añadir el registro al historial médico.
                </td>
                <td>EPIC-05</td>
            </tr>
            <tr>
                <td>US-023</td>
                <td>Registrar enfermedades</td>
                <td>
                    <strong>Como</strong> veterinario o personal autorizado,
                    <strong>quiero</strong> poder registrar las enfermedades diagnosticadas en cada mascota,
                    <strong>para</strong> mantener un historial médico completo y actualizado.
                </td>
                <td>
                    <h5>Escenario 01: Registro de diagnóstico exitoso</h5>
                    <strong>Dado</strong> el usuario está autenticado como veterinario o personal autorizado,
                    <strong>cuando</strong> se diagnostica una enfermedad en una mascota,
                    <strong>Entonces</strong> el usuario registra los detalles del diagnóstico en el historial médico de la mascota.
                    <br>
                    <h5>Escenario 02: Validación de datos de diagnóstico</h5>
                    <strong>Dado</strong> el usuario está autenticado como veterinario o personal autorizado,
                    <strong>cuando</strong> intenta registrar los datos del diagnóstico pero faltan datos obligatorios,
                    <strong>Entonces</strong> la aplicación muestra un mensaje de error indicando los datos faltantes.
                    <br>
                    <h5>Escenario 03: Adición de diagnóstico al historial médico</h5>
                    <strong>Dado</strong> el usuario está autenticado como veterinario o personal autorizado,
                    <strong>cuando</strong> tiene el diagnóstico y quiere agregarlo al historial médico,
                    <strong>Entonces</strong> la aplicación muestra una opción de añadir el diagnóstico al historial médico del paciente.
                </td>
                <td>EPIC-05</td>
            </tr>
            <tr>
                <td>US-024</td>
                <td>Visualizar resumen del historial médico</td>
                <td>
                    <strong>Como</strong> veterinario o personal autorizado,
                    <strong>quiero</strong> poder visualizar el resumen del historial médico de cada mascota,
                    <strong>para</strong> considerar sus antecedentes durante la atención de una consulta.
                </td>
                <td>
                    <h5>Escenario 01: Visualización del resumen del historial médico exitoso</h5>
                    <strong>Dado</strong> el usuario está autenticado como veterinario o personal autorizado,
                    <strong>cuando</strong> requiere el resumen del historial médico para atender a una mascota,
                    <strong>Entonces</strong> el sistema muestra la información relevante del historial médico de la mascota, como vacunas, cirugías y diagnósticos.
                    <br>
                    <h5>Escenario 02: Visualización del historial médico por fecha</h5>
                    <strong>Dado</strong> el usuario está autenticado como veterinario o personal autorizado,
                    <strong>cuando</strong> necesita ver el historial médico filtrado por fecha,
                    <strong>Entonces</strong> el sistema muestra el historial médico en el orden de fechas solicitado.
                    <br>
                    <h5>Escenario 03: Validación de fecha filtrada</h5>
                    <strong>Dado</strong> el usuario está autenticado como veterinario o personal autorizado,
                    <strong>cuando</strong> solicita ver el historial médico filtrado por una fecha inválida,
                    <strong>Entonces</strong> el sistema muestra un mensaje de error indicando que la fecha es incorrecta.
                </td>
                <td>EPIC-05</td>
            </tr>
            <tr>
                <td>US-025</td>
                <td>Ver planes disponibles de suscripción</td>
                <td>
                    <strong>Como</strong> propietario de mascota sin suscripción,
                    <strong>quiero</strong> poder visualizar los planes disponibles de suscripción,
                    <strong>para</strong> comparar y elegir el plan que mejor se ajuste a mis necesidades.
                </td>
                <td>
                    <h5>Escenario 01: Visualización de los planes de suscripción</h5>
                    <strong>Dado</strong> el usuario está en la versión gratuita de la aplicación,
                    <strong>cuando</strong> requiere la información de los planes disponibles,
                    <strong>Entonces</strong> el sistema muestra los beneficios y características de los planes.
                    <br>
                    <h5>Escenario 02: Acceso al detalle de un plan</h5>
                    <strong>Dado</strong> el usuario está interesado en un plan específico,
                    <strong>cuando</strong> selecciona la opción para ver los detalles,
                    <strong>Entonces</strong> el sistema muestra información detallada sobre los beneficios del plan seleccionado.
                    <br>
                    <h5>Escenario 03: Comparación de planes</h5>
                    <strong>Dado</strong> el usuario está revisando los planes de suscripción,
                    <strong>cuando</strong> desea comparar múltiples planes,
                    <strong>Entonces</strong> el sistema permite realizar una comparación lado a lado de las características de cada plan.
                </td>
                <td>EPIC-06</td>
            </tr>
            <tr>
                <td>US-026</td>
                <td>Suscribirse a un plan</td>
                <td>
                    <strong>Como</strong> propietario de mascota sin suscripción,
                    <strong>quiero</strong> poder suscribirme a los planes disponibles,
                    <strong>para</strong> obtener los beneficios de la versión de pago.
                </td>
                <td>
                    <h5>Escenario 01: Suscripción a un plan de pago exitoso</h5>
                    <strong>Dado</strong> el usuario está en la versión gratuita de la aplicación,
                    <strong>cuando</strong> selecciona un plan de pago y completa el proceso de pago,
                    <strong>Entonces</strong> el sistema confirma la suscripción y muestra los detalles del plan adquirido.
                    <br>
                    <h5>Escenario 02: Validación de los datos de pago</h5>
                    <strong>Dado</strong> el usuario está suscribiéndose a un plan,
                    <strong>cuando</strong> los datos de pago no son válidos o están incompletos,
                    <strong>Entonces</strong> el sistema muestra un mensaje de error indicando que los datos son incorrectos.
                    <br>
                    <h5>Escenario 03: Acceso a beneficios después del pago</h5>
                    <strong>Dado</strong> el usuario ha completado exitosamente el pago de un plan,
                    <strong>cuando</strong> accede a la aplicación nuevamente,
                    <strong>Entonces</strong> el sistema habilita las nuevas funcionalidades y beneficios del plan adquirido.
                </td>
                <td>EPIC-06</td>
            </tr>
            <tr>
                <td>US-027</td>
                <td>Cambiar de plan</td>
                <td>
                    <strong>Como</strong> propietario suscrito a un plan,
                    <strong>quiero</strong> poder cambiar mi plan de suscripción,
                    <strong>para</strong> acceder o limitar mis permisos a nuevas funcionalidades de la aplicación.
                </td>
                <td>
                    <h5>Escenario 01: Mejora de plan exitoso</h5>
                    <strong>Dado</strong> el usuario está suscrito a un plan básico,
                    <strong>cuando</strong> selecciona una opción para mejorar el plan y realiza el pago correspondiente,
                    <strong>Entonces</strong> el sistema actualiza su plan a uno con más beneficios.
                    <br>
                    <h5>Escenario 02: Desafiliación de plan actual</h5>
                    <strong>Dado</strong> el usuario está suscrito a un plan,
                    <strong>cuando</strong> selecciona la opción para bajar el plan o desafiliarse,
                    <strong>Entonces</strong> el sistema actualiza su suscripción y limita los permisos según el nuevo plan.
                    <br>
                    <h5>Escenario 03: Validación de los datos del formulario</h5>
                    <strong>Dado</strong> el usuario está cambiando su plan,
                    <strong>cuando</strong> no completa el formulario correctamente,
                    <strong>Entonces</strong> el sistema muestra un mensaje de error indicando los datos faltantes o incorrectos.
                </td>
                <td>EPIC-06</td>
            </tr>
            <tr>
                <td>US-028</td>
                <td>Historial de suscripciones</td>
                <td>
                    <strong>Como</strong> propietario autenticado,
                    <strong>quiero</strong> poder visualizar el historial de las suscripciones de mi cuenta,
                    <strong>para</strong> tener un recuento de los gastos realizados en la aplicación.
                </td>
                <td>
                    <h5>Escenario 01: Visualización del historial de suscripciones</h5>
                    <strong>Dado</strong> el usuario está autenticado en la aplicación,
                    <strong>cuando</strong> selecciona la opción de ver el historial de suscripciones,
                    <strong>Entonces</strong> la aplicación muestra un listado de todas las suscripciones anteriores con fechas y costos.
                    <br>
                    <h5>Escenario 02: Historial de suscripciones sin registro</h5>
                    <strong>Dado</strong> el usuario no tiene suscripciones previas,
                    <strong>cuando</strong> intenta acceder al historial de suscripciones,
                    <strong>Entonces</strong> el sistema muestra un mensaje indicando que no hay suscripciones registradas.
                    <br>
                    <h5>Escenario 03: Error al cargar historial de suscripciones</h5>
                    <strong>Dado</strong> el usuario intenta cargar el historial de suscripciones,
                    <strong>cuando</strong> ocurre un error técnico,
                    <strong>Entonces</strong> el sistema muestra un mensaje de error y sugiere intentarlo más tarde.
                </td>
                <td>EPIC-06</td>
            </tr>
            <tr>
                <td>US-029</td>
                <td>Cancelar plan</td>
                <td>
                    <strong>Como</strong> propietario suscrito a un plan,
                    <strong>quiero</strong> poder cancelar la versión de mi plan actual,
                    <strong>para</strong> limitar mis permisos y funcionalidades en la aplicación.
                </td>
                <td>
                    <h5>Escenario 01: Cancelación del plan actual</h5>
                    <strong>Dado</strong> el usuario está autenticado en la aplicación,
                    <strong>cuando</strong> selecciona la opción para cancelar su plan,
                    <strong>Entonces</strong> el sistema completa la desafiliación y el usuario vuelve a la versión gratuita.
                    <br>
                    <h5>Escenario 02: Validación de los datos del formulario</h5>
                    <strong>Dado</strong> el usuario intenta cancelar su plan,
                    <strong>cuando</strong> no completa correctamente el formulario,
                    <strong>Entonces</strong> el sistema muestra un mensaje de error indicando los datos incorrectos o faltantes.
                </td>
                <td>EPIC-06</td>
            </tr>
            <tr>
                <td>US-030</td>
                <td>Gestión de métodos de pago</td>
                <td>
                    <strong>Como</strong> propietario suscrito,
                    <strong>quiero</strong> gestionar mis métodos de pago,
                    <strong>para</strong> facilitar el proceso de transacciones en la aplicación.
                </td>
                <td>
                    <h5>Escenario 01: Pago con tarjeta exitoso</h5>
                    <strong>Dado</strong> el usuario está autenticado,
                    <strong>cuando</strong> añade una tarjeta como método de pago,
                    <strong>Entonces</strong> el sistema guarda los detalles de la tarjeta para futuras transacciones.
                    <br>
                    <h5>Escenario 02: Pago con PayPal exitoso</h5>
                    <strong>Dado</strong> el usuario está autenticado,
                    <strong>cuando</strong> añade PayPal como método de pago,
                    <strong>Entonces</strong> el sistema guarda los detalles de la cuenta PayPal para futuras transacciones.
                    <br>
                    <h5>Escenario 03: Validación de los datos del formulario</h5>
                    <strong>Dado</strong> el usuario está gestionando sus métodos de pago,
                    <strong>cuando</strong> no completa correctamente el formulario,
                    <strong>Entonces</strong> el sistema muestra un mensaje de error indicando los datos incorrectos o faltantes.
                </td>
                <td>EPIC-06</td>
            </tr>
            <tr>
                <td>US-031</td>
                <td>Actualizar método de pago</td>
                <td>
                    <strong>Como</strong> propietario suscrito,
                    <strong>quiero</strong> poder actualizar mi método de pago,
                    <strong>para</strong> garantizar que las transacciones futuras se procesen correctamente.
                </td>
                <td>
                    <h5>Escenario 01: Actualización de tarjeta de crédito</h5>
                    <strong>Dado</strong> que el usuario tiene un método de pago registrado,
                    <strong>cuando</strong> selecciona la opción para actualizar su tarjeta de crédito,
                    <strong>Entonces</strong> el sistema permite actualizar la información de la tarjeta.
                    <br>
                    <h5>Escenario 02: Actualización de PayPal</h5>
                    <strong>Dado</strong> que el usuario tiene su cuenta de PayPal registrada,
                    <strong>cuando</strong> selecciona la opción para actualizar sus detalles de PayPal,
                    <strong>Entonces</strong> el sistema permite actualizar dicha información.
                    <br>
                    <h5>Escenario 03: Validación de datos del nuevo método de pago</h5>
                    <strong>Dado</strong> que el usuario está intentando actualizar su método de pago,
                    <strong>cuando</strong> los datos ingresados son incorrectos o incompletos,
                    <strong>Entonces</strong> el sistema muestra un mensaje de error y no permite la actualización hasta que se corrijan los datos.
                </td>
                <td>EPIC-06</td>
            </tr>
            <tr>
                <td>US-032</td>
                <td>Eliminar método de pago</td>
                <td>
                    <strong>Como</strong> propietario suscrito,
                    <strong>quiero</strong> poder eliminar un método de pago,
                    <strong>para</strong> gestionar los métodos de pago que ya no uso.
                </td>
                <td>
                    <h5>Escenario 01: Eliminación de tarjeta de crédito exitosa</h5>
                    <strong>Dado</strong> que el usuario tiene una tarjeta de crédito registrada,
                    <strong>cuando</strong> selecciona la opción de eliminar la tarjeta,
                    <strong>Entonces</strong> el sistema elimina la tarjeta de su perfil de pago.
                    <br>
                    <h5>Escenario 02: Eliminación de PayPal exitosa</h5>
                    <strong>Dado</strong> que el usuario tiene su cuenta de PayPal registrada,
                    <strong>cuando</strong> selecciona la opción de eliminar la cuenta PayPal,
                    <strong>Entonces</strong> el sistema elimina los detalles de PayPal de su perfil de pago.
                    <br>
                    <h5>Escenario 03: Error al intentar eliminar un método de pago</h5>
                    <strong>Dado</strong> que el usuario intenta eliminar un método de pago,
                    <strong>cuando</strong> ocurre un error técnico durante la eliminación,
                    <strong>Entonces</strong> el sistema muestra un mensaje de error y no elimina el método hasta que el problema sea resuelto.
                </td>
                <td>EPIC-06</td>
            </tr>
            <tr>
                <td>US-033</td>
                <td>Enviar un mensaje a soporte</td>
                <td>
                    <strong>Como</strong> usuario de la aplicación,
                    <strong>quiero</strong> poder enviar un mensaje a soporte técnico,
                    <strong>para</strong> resolver problemas o consultas sobre el uso de la aplicación.
                </td>
                <td>
                    <h5>Escenario 01: Envío de mensaje a soporte exitoso</h5>
                    <strong>Dado</strong> que el usuario tiene una consulta o problema,
                    <strong>cuando</strong> ingresa a la sección de contacto y completa el formulario de mensaje,
                    <strong>Entonces</strong> el sistema envía el mensaje al equipo de soporte.
                    <br>
                    <h5>Escenario 02: Confirmación del envío de mensaje</h5>
                    <strong>Dado</strong> que el usuario ha enviado un mensaje a soporte,
                    <strong>cuando</strong> el mensaje es enviado con éxito,
                    <strong>Entonces</strong> el sistema muestra un mensaje de confirmación indicando que su solicitud fue recibida.
                    <br>
                    <h5>Escenario 03: Error al enviar mensaje a soporte</h5>
                    <strong>Dado</strong> que el usuario intenta enviar un mensaje a soporte,
                    <strong>cuando</strong> ocurre un error técnico durante el envío,
                    <strong>Entonces</strong> el sistema muestra un mensaje de error y sugiere intentar más tarde o contactar de otra manera.
                </td>
                <td>EPIC-11</td>
            </tr>
            <tr>
                <td>US-034</td>
                <td>Ver información del footer</td>
                <td>
                    <strong>Como</strong> visitante,
                    <strong>quiero</strong> poder acceder a los enlaces del footer,
                    <strong>para</strong> navegar rápidamente a secciones como redes sociales, noticias y contacto.
                </td>
                <td>
                    <h5>Escenario 01: Acceso a redes sociales desde el footer</h5>
                    <strong>Dado</strong> que el usuario está en la parte inferior de la página web,
                    <strong>cuando</strong> hace clic en los enlaces de redes sociales,
                    <strong>Entonces</strong> el sistema lo redirige a las cuentas oficiales de redes sociales.
                    <br>
                    <h5>Escenario 02: Visualización de contacto</h5>
                    <strong>Dado</strong> que el usuario está en la parte inferior de la página web,
                    <strong>cuando</strong> visualiza los contactos del equipo de UPet,
                    <strong>Entonces</strong> el sistema le muestra la dirección, telefono móvil y correo electrónico.
                    <br>
                    <h5>Escenario 03: Error al cargar información del footer</h5>
                    <strong>Dado</strong> que el usuario intenta acceder a un enlace del footer,
                    <strong>cuando</strong> ocurre un error técnico,
                    <strong>Entonces</strong> el sistema muestra un mensaje de error indicando que no se pudo cargar la página solicitada.
                </td>
                <td>EPIC-11</td>
            </tr>
            <tr>
                <td>US-035</td>
                <td>Revisar reseñas de la aplicación</td>
                <td>
                    <strong>Como</strong> visitante,
                    <strong>quiero</strong> poder ver las reseñas de la aplicación,
                    <strong>para</strong> conocer la experiencia de otros usuarios antes de descargarla o registrarme.
                </td>
                <td>
                    <h5>Escenario 01: Visualización de reseñas recientes</h5>
                    <strong>Dado</strong> que el usuario está en la sección de reseñas,
                    <strong>cuando</strong> desplaza hacia abajo en la página,
                    <strong>Entonces</strong> el sistema muestra un carrusel de reseñas recientes de otros usuarios.
                    <br>
                    <h5>Escenario 02: Error al cargar reseñas</h5>
                    <strong>Dado</strong> que el usuario intenta cargar las reseñas,
                    <strong>cuando</strong> ocurre un error técnico,
                    <strong>Entonces</strong> el sistema muestra un mensaje de error y sugiere intentar nuevamente más tarde.
                </td>
                <td>EPIC-11</td>
            </tr>
            <tr>
                <td>US-036</td>
                <td>Navegar en la página principal</td>
                <td>
                    <strong>Como</strong> visitante,
                    <strong>quiero</strong> acceder a la página principal del sitio web y ver un botón de Call to Action 
                    <strong>para</strong> descargar la aplicación o registrarme, para tener acceso rápido a la funcionalidad principal.
                </td>
                <td>
                    <h5>Escenario 01: Visualización de la página principal</h5>
                    <strong>Dado</strong> que el visitante está en la página de inicio,
                    <strong>cuando</strong> carga el sitio,
                    <strong>Entonces</strong> se visualiza un botón destacado de Call to Action con texto claro como "Descargar" en la parte superior derecha de la página.
                    <br>
                    <h5>Escenario 02: Redirección desde el botón</h5>
                    <strong>Dado</strong> que el visitante está en la página de inicio,
                    <strong>cuando</strong> hace clic en el boton "Descargar",
                    <strong>Entonces</strong> el sistema lo redirige a la sección de Download.
                    <br>
                    <h5>Escenario 03: Verificación del funcionamiento del botón en dispositivos móviles</h5>
                    <strong>Dado</strong> que el visitante está en la página de inicio desde un dispositivo móvil,
                    <strong>cuando</strong> hace clic en el boton "Descargar",
                    <strong>Entonces</strong> el sistema funciona correctamente y redirige a la sección adecuada.
                </td>
                <td>EPIC-11</td>
            </tr>
            <tr>
                <td>US-037</td>
                <td>Ver funcionalidades para propietarios de mascotas</td>
                <td>
                    <strong>Como</strong> visitante,
                    <strong>quiero</strong> ver las funcionalidades que ofrece la aplicación para los dueños de mascotas,
                    <strong>para</strong> saber cómo puedo usarla para cuidar de mi mascota.
                </td>
                <td>
                    <h5>Escenario 01: Visualización de funcionalidades</h5>
                    <strong>Dado</strong> que el visitante está en la página de funcionalidades para propietarios de mascotas,
                    <strong>cuando</strong> llega a esa sección,
                    <strong>Entonces</strong> puede ver una lista de las funcionalidades destacadas como agendar citas, registrar historial médico, recibir recordatorios, etc.
                    <br>
                    <h5>Escenario 02: Detalle de una funcionalidad</h5>
                    <strong>Dado</strong> que el visitante quiere saber más sobre una funcionalidad en particular,
                    <strong>cuando</strong> revisa una funcionalidad específica,
                    <strong>Entonces</strong> el sistema muestra una descripción detallada de esa funcionalidad.
                    <br>
                    <h5>Escenario 03: Error al cargar la lista de funcionalidades</h5>
                    <strong>Dado</strong> que el visitante está intentando ver las funcionalidades para propietarios de mascotas,
                    <strong>cuando</strong> ocurre un error técnico,
                    <strong>Entonces</strong> el sistema muestra un mensaje de error indicando que no se pueden cargar las funcionalidades.
                </td>
                <td>EPIC-11</td>
            </tr>
            <tr>
                <td>US-038</td>
                <td>Ver funcionalidades para veterinarias</td>
                <td>
                    <strong>Como</strong> visitante,
                    <strong>quiero</strong> ver las funcionalidades que ofrece la aplicación para veterinarias,
                    <strong>para</strong> conocer cómo puedo usarla en mi clínica veterinaria.
                </td>
                <td>
                    <h5>Escenario 01: Visualización de funcionalidades</h5>
                    <strong>Dado</strong> que el visitante está en la página de funcionalidades para veterinarias,
                    <strong>cuando</strong> llega a esa sección,
                    <strong>Entonces</strong> puede ver una lista de las funcionalidades para clínicas como agendar citas, llevar el historial médico de las mascotas, gestión de clientes, etc.
                    <br>
                    <h5>Escenario 02: Detalle de una funcionalidad</h5>
                    <strong>Dado</strong> que el visitante quiere saber más sobre una funcionalidad para veterinarias,
                    <strong>cuando</strong> revisa en una funcionalidad específica,
                    <strong>Entonces</strong> el sistema muestra una descripción detallada de esa funcionalidad.
                    <br>
                    <h5>Escenario 03: Error al cargar la lista de funcionalidades</h5>
                    <strong>Dado</strong> que el visitante está intentando ver las funcionalidades para veterinarias,
                    <strong>cuando</strong> ocurre un error técnico,
                    <strong>Entonces</strong> el sistema muestra un mensaje de error indicando que no se pueden cargar las funcionalidades.
                </td>
                <td>EPIC-11</td>
            </tr>
            <tr>
                <td>US-039</td>
                <td>Descargar la aplicación</td>
                <td>
                    <strong>Como</strong> visitante,
                    <strong>quiero</strong> poder descargar la aplicación desde el sitio web estático,
                    <strong>para</strong> instalarla en mi dispositivo y comenzar a usarla.
                </td>
                <td>
                    <h5>Escenario 01: Descarga desde Google Play</h5>
                    <strong>Dado</strong> que el visitante está en la sección de descarga de la página web,
                    <strong>cuando</strong> hace clic en el botón de descarga de Google Play,
                    <strong>Entonces</strong> el sistema lo redirige a la tienda Google Play para descargar la aplicación.
                    <br>
                    <h5>Escenario 02: Descarga desde App Store</h5>
                    <strong>Dado</strong> que el visitante está en la sección de descarga de la página web,
                    <strong>cuando</strong> hace clic en el botón de descarga de App Store,
                    <strong>Entonces</strong> el sistema lo redirige a la tienda App Store para descargar la aplicación.
                    <br>
                    <h5>Escenario 03: Error al intentar descargar la aplicación</h5>
                    <strong>Dado</strong> que el visitante está intentando descargar la aplicación,
                    <strong>cuando</strong> ocurre un error técnico,
                    <strong>Entonces</strong> el sistema muestra un mensaje de error indicando que no se puede completar la descarga.
                </td>
                <td>EPIC-11</td>
            </tr>
            <tr>
                <td>US-040</td>
                <td>Enviar un mensaje desde el sitio de web estático</td>
                <td>
                    <strong>Como</strong> visitante,
                    <strong>quiero</strong> poder enviar un mensaje al equipo de la aplicación desde la sección de contacto,
                    <strong>para</strong> resolver dudas o recibir más información sobre el servicio.
                </td>
                <td>
                    <h5>Escenario 01: Envío de mensaje exitoso</h5>
                    <strong>Dado</strong> que el visitante ha completado el formulario en la sección "Send us a message",
                    <strong>cuando</strong> hace clic en el botón de enviar,
                    <strong>Entonces</strong> el sistema envía el mensaje correctamente y muestra un mensaje de confirmación.
                    <br>
                    <h5>Escenario 02: Campos incompletos en el formulario</h5>
                    <strong>Dado</strong> que el visitante intenta enviar un mensaje,
                    <strong>cuando</strong> no ha completado todos los campos obligatorios del formulario,
                    <strong>Entonces</strong> el sistema muestra un mensaje de error indicando que debe completar todos los campos.
                    <br>
                    <h5>Escenario 03: Error al intentar enviar el mensaje</h5>
                    <strong>Dado</strong> que el visitante intenta enviar un mensaje desde la sección "Send us a message",
                    <strong>cuando</strong> ocurre un error técnico,
                    <strong>Entonces</strong> el sistema muestra un mensaje de error indicando que no se pudo enviar el mensaje y sugiere intentarlo más tarde.
                </td>
                <td>EPIC-11</td>
            </tr>
            <tr>
                <td>US-041</td>
                <td>Mostrar tu ubicación actual</td>
                <td>
                    <strong>Como</strong> propietario/a o autenticado y suscrito a un plan,
                    <strong>quiero</strong> poder visualizar mi ubicación
                    <strong>para</strong> buscar centros de atención cerca de mi ubicación.
                </td>
                <td>
                    <h5>Escenario 01: Mostrar ubicación actual del usuario con éxito</h5>
                    <strong>Dado</strong> el usuario está autenticado como propietario/a en la versión gratuita o suscrito en la aplicación
                    <strong>cuando</strong> selecciona la opción para mostrar su ubicación actual con el propósito de buscar centros
                    <strong>Entonces</strong> la aplicación accede a la ubicación actual del usuario y la muestra en el mapa de manera precisa.
                    <br>
                    <h5>Escenario 02: Imposibilidad de obtener la ubicación actual del usuario</h5>
                    <strong>Dado</strong> el usuario está autenticado como propietario/a en la versión gratuita o suscrito en la aplicación
                    <strong>cuando</strong> intenta acceder a la opción mostrar su ubicación actual
                    <strong>Y</strong> la aplicación intenta obtener la ubicación actual del usuario, pero hay una falla en el dispositivo o el usuario ha desactivado su gps
                    <strong>Entonces</strong> la aplicación muestra un mensaje de error indicando que no se pudo obtener la ubicación y sugiere que active la función de ubicación en su dispositivo.
                    <br>
                </td>
                <td>EPIC-07</td>
            </tr>
            <tr>
                <td>US-042</td>
                <td>Mostrar veterinarias cercanas</td>
                <td>
                    <strong>Como</strong> propietario/a o autenticado y suscrito a un plan,
                    <strong>quiero</strong> visualizar las veterinarias alrededor de mi zona,
                    <strong>para</strong> elegir una y atender a mi mascota
                </td>
                <td>
                    <h5>Escenario 01: Mostrar lista de veterinarias cercanas con éxito</h5>
                    <strong>Dado</strong> el usuario está autenticado, suscrito a un plan, tiene la ubicación activada en su dispositivo y hay veterinarias registradas en la zona del usuario.
                    <strong>cuando</strong> abre la aplicación y selecciona la opción “Mostrar veterinarias cercanas”
                    <strong>Entonces</strong> la aplicación muestra una lista de veterinarias cercanas a la ubicación del usuario.
                    <br>
                    <h5>Escenario 02: No se encuentran veterinarias cercanas</h5>
                    <strong>Dado</strong> el usuario está autenticado y suscrito a un plan, tiene la ubicación activada en su dispositivo y no hay veterinarias registradas en la zona del usuario.
                    <strong>cuando</strong> intenta acceder a la opción "Mostrar veterinarias cercanas”
                    <strong>Entonces</strong> la aplicación muestra un mensaje de error indicando que no encuentra veterinarias cercanas.
                    <br>
                </td>
                <td>EPIC-07</td>
            </tr>
            <tr>
                <td>US-043</td>
                <td>Ver las valoraciones y comentarios de la veterinaria</td>
                <td>
                    <strong>Como</strong> veterinario/a o personal autorizado de la clínica veterinaria, 
                    <strong>quiero</strong> poder visualizar las valoraciones y comentarios de mi veterinaria,
                    <strong>para</strong> mejorar en los aspectos negativos que pueda tener.
                </td>
                <td>
                    <h5>Escenario 01: Ver valoraciones y comentarios de la veterinaria con éxito</h5>
                    <strong>Dado</strong> el usuario está autenticado en la aplicación como veterinario/a o personal autorizado.
                    <strong>cuando</strong> accede a la sección de valoraciones y comentarios de la veterinaria en la aplicación
                    <strong>Entonces</strong> La aplicación muestra una lista de valoraciones y comentarios dejados por los clientes sobre la veterinaria.
                    <br>
                    <h5>Escenario 02: Comunicación directa con los clientes insatisfechos</h5>
                    <strong>Dado</strong> el usuario está autenticado en la aplicación como veterinario/a o personal autorizado.
                    <strong>cuando</strong> encuentra un comentario negativo sobre la veterinaria
                    <strong>Entonces</strong> la aplicación proporciona la opción de responder al comentario de forma que la veterinaria aborde directamente el problema para resolver que haya surgido.
                    <br>
                </td>
                <td>EPIC-07</td>
            </tr>
            <tr>
                <td>US-044</td>
                <td>Añadir valoraciones y comentarios</td>
                <td>
                    <strong>Como</strong> propietario/a de mascota autenticado y suscrito a un plan, 
                    <strong>quiero</strong> poder realizar comentarios y valoraciones,
                    <strong>para</strong> calificar la atención de cada centro de atención.
                </td>
                <td>
                    <h5>Escenario 01: Comentario añadido con éxito</h5>
                    <strong>Dado</strong> el usuario está autenticado como propietario/a en la versión gratuita o suscrito en la aplicación.
                    <strong>Cuando</strong> selecciona la opción para añadir una valoración y comentario sobre un centro de atención
                    <strong>Entonces</strong> la aplicación presenta un formulario donde el usuario puede ingresar su valoración en forma de puntuación y agregar un comentario opcionalmente.
                    <br>
                    <h5>Escenario 02: Intento de añadir valoración y comentario sin estar suscrito</h5>
                    <strong>Dado</strong> el usuario está autenticado como propietario/a pero no está suscrito a un plan.
                    <strong>Cuando</strong> intenta añadir una valoración acerca de una veterinaria
                    <strong>Entonces</strong> la aplicación detecta que el usuario no está suscrito a un plan y le muestra un mensaje de error indicando que esta función solo está disponible para usuarios suscritos.
                    <br>
                    <h5>Escenario 03: Edición de valoración y comentario existente</h5>
                    <strong>Dado</strong> el usuario está autenticado como propietario/a en la versión gratuita o suscrito en la aplicación.
                    <strong>Cuando</strong> desea editar una valoración o comentario que realizó anteriormente
                    <strong>Entonces</strong> la aplicación permite al usuario editar la valoración y/o comentario existente y guarda los cambios realizados.
                </td>
                <td>EPIC-08</td>
            </tr>
            <tr>
                <td>US-045</td>
                <td>Ver detalles de cada veterinaria</td>
                <td>
                    <strong>Como</strong> propietario/a o autenticado y suscrito a un plan, 
                    <strong>quiero</strong> poder visualizar la información de cada veterinaria,
                    <strong>para</strong> poder elegir con mayor eficacia la veterinaria acorde a mis necesidades.
                </td>
                <td>
                    <h5>Escenario 01: Visualización de detalles de veterinaria</h5>
                    <strong>Dado</strong> el usuario está autenticado como propietario/a en la versión gratuita o suscrito en la aplicación.
                    <strong>Cuando</strong> desea visualizar los detalles de una veterinaria específica
                    <strong>Entonces</strong> la aplicación muestra información detallada sobre la veterinaria seleccionada.
                    <br>
                    <h5>Escenario 02: Ver detalles de la veterinaria con filtros de búsqueda</h5>
                    <strong>Dado</strong> el usuario está autenticado como propietario/a en la versión gratuita o suscrito en la aplicación.
                    <strong>Cuando</strong> desea ver los detalles de una veterinaria, pero tiene preferencias específicas, como los servicios ofrecidos
                    <strong>Entonces</strong> la aplicación permite al usuario aplicar filtros de búsqueda para ver solo las veterinarias que cumplan con sus criterios específicos.
                </td>
                <td>EPIC-08</td>
            </tr>
            <tr>
                <td>US-046</td>
                <td>Ver reseñas y evaluación</td>
                <td>
                    <strong>Como</strong> propietario/a o autenticado y suscrito a un plan, 
                    <strong>quiero</strong> visualizar las reseñas de cada veterinaria,
                    <strong>para</strong> facilitar el proceso de selección de cada centro.
                </td>
                <td>
                    <h5>Escenario 01: Visualización de reseñas y evaluación</h5>
                    <strong>Dado</strong> el usuario está autenticado como propietario/a en la versión gratuita o suscrito en la aplicación.
                    <strong>Cuando</strong> desea visualizar las reseñas y evaluaciones de una veterinaria específica
                    <strong>Entonces</strong> la aplicación muestra una lista de reseñas y evaluaciones dejadas por otros usuarios sobre la veterinaria seleccionada.
                    <br>
                    <h5>Escenario 02: Ver reseñas y evaluaciones con filtros de búsqueda</h5>
                    <strong>Dado</strong> el usuario está autenticado como propietario/a en la versión gratuita o suscrito en la aplicación.
                    <strong>Cuando</strong> desea visualizar las reseñas y evaluaciones de una veterinaria, pero tiene preferencias específicas, como la búsqueda de reseñas positivas o negativas
                    <strong>Entonces</strong> la aplicación permite al usuario aplicar filtros de búsqueda para ver solo las reseñas que cumplan con sus criterios específicos, como la puntuación dada por otros usuarios.
                </td>
                <td>EPIC-08</td>
            </tr>
            <tr>
                <td>US-047</td>
                <td>Entrar al perfil de cada veterinaria</td>
                <td>
                    <strong>Como</strong> propietario/a o autenticado y suscrito a un plan, 
                    <strong>quiero</strong> visualizar información personal de cada veterinaria,
                    <strong>para</strong> poder informarme mejor acerca de cada veterinaria.
                </td>
                <td>
                    <h5>Escenario 01: Visualización de perfil de la veterinaria</h5>
                    <strong>Dado</strong> el usuario está autenticado como propietario/a en la versión gratuita o suscrito en la aplicación.
                    <strong>Cuando</strong> desea visualizar el perfil de cada veterinaria
                    <strong>Entonces</strong> la aplicación carga el perfil completo de la veterinaria, que incluye información detallada como el nombre, reseñas, servicios, dirección, horarios de atención, servicios ofrecidos.
                    <br>
                    <h5>Escenario 02: Ver información detallada de la veterinaria con filtros de búsqueda</h5>
                    <strong>Dado</strong> el usuario está autenticado como propietario/a en la versión gratuita o suscrito en la aplicación.
                    <strong>Cuando</strong> desea visualizar el perfil, pero tiene preferencias específicas, como buscar veterinarias con ciertas especialidades
                    <strong>Entonces</strong> la aplicación permite al usuario aplicar filtros de búsqueda para ver solo las veterinarias que cumplan con sus criterios específicos.
                </td>
                <td>EPIC-08</td>
            </tr>
            <tr>
                <td>US-048</td>
                <td>Añadir ubicación</td>
                <td>
                    <strong>Como</strong> veterinaria o personal autorizado de la clínica veterinaria, 
                    <strong>quiero</strong> añadir la ubicación de mi centro de atención,
                    <strong>para</strong> mostrar la ubicación actual de mi centro de atención.
                </td>
                <td>
                    <h5>Escenario 01: Registro de ubicación de veterinaria</h5>
                    <strong>Dado</strong> el usuario está autenticado en la aplicación como veterinario/a o personal autorizado.
                    <strong>Cuando</strong> se selecciona la opción añadir ubicación de la veterinaria.
                    <strong>Entonces</strong> la aplicación le mostrará el mapa para poder elegir la ubicación que desea guardar para su veterinaria.
                    <br>
                    <h5>Escenario 02: Intento de añadir ubicación sin autorización</h5>
                    <strong>Dado</strong> el usuario no está autenticado en la aplicación como veterinario/a o personal de la clínica.
                    <strong>Cuando</strong> intenta añadir la ubicación de un centro de atención
                    <strong>Entonces</strong> la aplicación detecta que el usuario no tiene los permisos adecuados y le muestra un mensaje de error indicando que esta función está disponible solo para personal autorizado.
                    <br>
                    <h5>Escenario 03: Actualización de ubicación existente</h5>
                    <strong>Dado</strong> el usuario está autenticado en la aplicación como veterinario/a o personal autorizado.
                    <strong>Cuando</strong> necesita actualizar la ubicación de su centro de atención debido a una reubicación 
                    <strong>Entonces</strong> la aplicación permite al usuario editar la ubicación existente del centro de atención y guarda los cambios realizados.
                </td>
                <td>EPIC-09</td>
            </tr>
            <tr>
                <td>US-049</td>
                <td>Añadir servicios ofrecidos</td>
                <td>
                    <strong>Como</strong> veterinaria o personal autorizado de la clínica veterinaria, 
                    <strong>quiero</strong> añadir la información de los servicios que ofrece mi veterinaria,
                    <strong>para</strong> informar a mis clientes que tipo de atención brindamos.
                </td>
                <td>
                    <h5>Escenario 01: Registro de la información de servicios</h5>
                    <strong>Dado</strong> el usuario está autenticado en la aplicación como veterinario/a o personal autorizado.
                    <strong>Cuando</strong> selecciona la opción para añadir información sobre los servicios ofrecidos por su veterinaria.
                    <strong>Entonces</strong> la aplicación proporciona un formulario donde el usuario puede ingresar la información detallada sobre sus servicios.
                    <br>
                    <h5>Escenario 02: Actualización de servicios existentes</h5>
                    <strong>Dado</strong> el usuario es una veterinaria o personal autorizado y ya no cuenta con una cuenta en la aplicación.
                    <strong>Cuando</strong> necesita actualizar información sobre los servicios ofrecidos debido a cambios en sus servicios 
                    <strong>Entonces</strong> la aplicación permite al usuario editar la información existente sobre los servicios ofrecidos y guardar los cambios realizados.
                </td>
                <td>EPIC-09</td>
            </tr>
            <tr>
                <td>US-050</td>
                <td>Añadir horarios de atención</td>
                <td>
                    <strong>Como</strong> veterinaria o personal autorizado de la clínica veterinaria, 
                    <strong>quiero</strong> poder añadir mis horarios de atención al usuario,
                    <strong>para</strong> evitar que mis clientes se acerquen en días no laborales de mi veterinaria.
                </td>
                <td>
                    <h5>Escenario 01: Registro de horarios de atención</h5>
                    <strong>Dado</strong> el usuario está autenticado en la aplicación como veterinario/a o personal autorizado.
                    <strong>Cuando</strong> se selecciona la opción de añadir horario de atención
                    <strong>Entonces</strong> la aplicación le mostrará un apartado para que pueda ingresar el horario que brindará.
                    <br>
                    <h5>Escenario 02: Confirmación de registro de horario</h5>
                    <strong>Dado</strong> el usuario es una veterinaria o personal autorizado y ya no cuenta con una cuenta en la aplicación.
                    <strong>Cuando</strong> ingresó su horario de atención
                    <strong>Entonces</strong> la aplicación muestra de confirmación del horario regulado listo para ser publicado.
                </td>
                <td>EPIC-09</td>
            </tr>
            <tr>
                <td>US-051</td>
                <td>Eliminar veterinaria</td>
                <td>
                    <strong>Como</strong> veterinaria o personal autorizado de la clínica veterinaria, 
                    <strong>quiero</strong> poder eliminar el centro veterinario en caso de cierre u otro motivo,
                    <strong>para</strong> mantener actualizada la base de datos de UPet y evitar confusiones.
                </td>
                <td>
                    <h5>Escenario 01: Eliminación exitosa de la veterinaria</h5>
                    <strong>Dado</strong> el usuario está autenticado en la aplicación como veterinario/a o personal autorizado.
                    <strong>Cuando</strong> se selecciona la opción de eliminar la veterinaria desde la configuración de la cuenta.
                    <strong>Entonces</strong> la aplicación elimina correctamente todos los datos relacionados con la veterinaria de la base de datos y muestra un mensaje de confirmación.
                    <br>
                    <h5>Escenario 02: Confirmación de la eliminación</h5>
                    <strong>Dado</strong> el usuario es una veterinaria o personal autorizado y ya no cuenta con una cuenta en la aplicación.
                    <strong>Cuando</strong> se intenta ingresar con las credenciales inexistentes.
                    <strong>Entonces</strong> la aplicación muestra un mensaje de cuenta y datos eliminados, cumpliendo con la regulación de protección de datos y privacidad.
                </td>
                <td>EPIC-09</td>
            </tr>
            <tr>
                <td>TS-001</td>
                <td>Endpoint Appointment</td>
                <td>
                    <strong>Como</strong> desarrollador front-end, 
                    <strong>quiero</strong> asegurarme de que el registro de historia médica funcione correctamente en la interfaz de usuario
                    <strong>para</strong> que los usuarios puedan ingresar la información de manera adecuada.
                </td>
                <td>
                    <h5>Escenario 01: Crear una nueva cita con éxito</h5>
                    <strong>Dado</strong> que el usuario tiene acceso a la API de gestión de citas y cuenta con los permisos necesarios para crear una cita.
                    <strong>Cuando</strong> el usuario envía una solicitud POST con los detalles de la nueva cita, incluyendo la fecha, hora, ID de la mascota y ID del veterinario.
                    <strong>Entonces</strong> el sistema procesa la solicitud y crea una nueva cita en la base de datos. El sistema responde con un código de estado 201 (Created) y devuelve los detalles de la cita recién creada en el cuerpo de la respuesta.
                    <br>
                    <h5>Escenario 02: Crear una nueva cita con formato de fecha y hora inválidos</h5>
                    <strong>Dado</strong> que el usuario tiene acceso a la API de gestión de citas.
                    <strong>Cuando</strong> el usuario envía una solicitud POST con detalles de cita que incluyen un formato de fecha y hora incorrecto.
                    <strong>Entonces</strong> el sistema devuelve un código de estado 400 (Bad Request) con un mensaje de error indicando que el formato de fecha y hora es inválido.
                    <br>
                    <h5>Escenario 03: Crear una nueva cita con ID de mascota inexistente</h5>
                    <strong>Dado</strong> que el usuario tiene acceso a la API de gestión de citas.
                    <strong>Cuando</strong> el usuario intenta crear una nueva cita con un ID de mascota que no existe en la base de datos.
                    <strong>Entonces</strong> el sistema devuelve un código de estado 404 (Not Found) con un mensaje de error indicando que la mascota no existe.
                </td>
                <td>EPIC-10</td>
            </tr>
            <tr>
                <td>TS-002</td>
                <td>Endpoint Medical History</td>
                <td>
                    <strong>Como</strong> desarrollador front-end, 
                    <strong>quiero</strong> acceder a un endpoint en el backend para gestionar el historial médico de las mascotas, incluyendo el registro de enfermedades y vacunaciones asociadas,
                    <strong>para</strong> permitir el manejo completo del historial médico desde la interfaz de usuario.
                </td>
                <td>
                    <h5>Escenario 01: Crear una nueva enfermedad</h5>
                    <strong>Dado</strong> acceso a la API de gestión del historial médico y permisos para crear enfermedades.
                    <strong>Cuando</strong> se envía una solicitud POST con los detalles de la nueva enfermedad.
                    <strong>Entonces</strong> el sistema crea la enfermedad y responde con un código 201 si es exitoso. Si la enfermedad ya existe, devuelve un código 400 con un mensaje de error.
                    <br>
                    <h5>Escenario 02: Asociar una enfermedad a un historial médico</h5>
                    <strong>Dado</strong> acceso a la API de gestión del historial médico y permisos para asociar enfermedades.
                    <strong>Cuando</strong> se envía una solicitud POST con los detalles de la asociación de enfermedad.
                    <strong>Entonces</strong> el sistema crea la asociación y responde con un código 201 si es exitoso. Si el historial médico o la enfermedad no existen, devuelve un código 404 con un mensaje de error.
                    <br>
                    <h5>Escenario 03: Crear una nueva vacuna</h5>
                    <strong>Dado</strong> acceso a la API de gestión del historial médico y permisos para crear vacunas.
                    <strong>Cuando</strong> se envía una solicitud POST a con los detalles de la nueva vacuna.
                    <strong>Entonces</strong> el sistema crea la vacuna y responde con un código 201 si es exitoso. Si la vacuna ya existe, devuelve un código 400 con un mensaje de error.
                </td>
                <td>EPIC-10</td>
            </tr>
            <tr>
                <td>TS-003</td>
                <td>Endpoint Notification</td>
                <td>
                    <strong>Como</strong> desarrollador front-end, 
                    <strong>quiero</strong> tener un endpoint para gestionar notificaciones de usuarios
                    <strong>para</strong> crear nuevas notificaciones y obtener las notificaciones existentes.
                </td>
                <td>
                    <h5>Escenario 01: Crear una nueva notificación</h5>
                    <strong>Dado</strong> acceso a la API de notificaciones.
                    <strong>Cuando</strong> se envía una solicitud POST con los detalles de la nueva notificación, incluyendo el ID del propietario de la mascota.
                    <strong>Entonces</strong> el sistema crea la notificación y responde con un código 201 si es exitoso. Si el propietario de la mascota no existe, devuelve un código 404 con un mensaje de error.
                    <br>
                    <h5>Escenario 02: Obtener todas las notificaciones</h5>
                    <strong>Dado</strong> acceso a la API de notificaciones.
                    <strong>Cuando</strong> se envía una solicitud GET.
                    <strong>Entonces</strong> el sistema devuelve una lista con todas las notificaciones existentes en el sistema. Responde con un código 200. Si no hay notificaciones disponibles, devuelve una lista vacía.
                    <br>
                    <h5>Escenario 03: Obtener notificaciones por ID de propietario de mascota</h5>
                    <strong>Dado</strong> acceso a la API de notificaciones.
                    <strong>Cuando</strong> se envía una solicitud GET con el ID del propietario de la mascota.
                    <strong>Entonces</strong> el sistema devuelve una lista con todas las notificaciones dirigidas al propietario de mascota especificado. Responde con un código 200. Si el propietario de mascota no existe o no tiene notificaciones, devuelve un código 404 con un mensaje de error.
                </td>
                <td>EPIC-10</td>
            </tr>
            <tr>
                <td>TS-004</td>
                <td>Endpoint Pet</td>
                <td>
                    <strong>Como</strong> desarrollador frontend, 
                    <strong>quiero</strong> poder integrar la funcionalidad de agregar y visualizar mascotas en la interfaz de usuario,
                    <strong>para</strong> permitir a los usuarios mantener un registro actualizado de sus mascotas desde la aplicación móvil.
                </td>
                <td>
                    <h5>Escenario 01: Crear una nueva mascota</h5>
                    <strong>Dado</strong> acceso a la API de mascotas.
                    <strong>Cuando</strong> se envía una solicitud POST con los detalles de la nueva mascota y el ID del propietario al que pertenece.
                    <strong>Entonces</strong> el sistema crea la mascota y responde con un código 201 si es exitoso. Si el propietario de la mascota no existe, devuelve un código 404.
                    <br>
                    <h5>Escenario 02: Obtener todas las mascotas</h5>
                    <strong>Dado</strong> acceso a la API de mascotas.
                    <strong>Cuando</strong> se envía una solicitud GET.
                    <strong>Entonces</strong> el sistema devuelve una lista con todas las mascotas existentes en el sistema. Responde con un código 200. Si no hay mascotas disponibles, devuelve una lista vacía.
                    <br>
                    <h5>Escenario 03: Obtener mascotas por ID de propietario</h5>
                    <strong>Dado</strong> acceso a la API de mascotas.
                    <strong>Cuando</strong> se envía una solicitud GET con el ID del propietario de la mascota.
                    <strong>Entonces</strong> el sistema devuelve una lista con todas las mascotas pertenecientes al propietario especificado. Responde con un código 200. Si el propietario de la mascota no existe o no tiene mascotas registradas, devuelve un código 404.
                </td>
                <td>EPIC-10</td>
            </tr>
            <tr>
                <td>TS-005</td>
                <td>Endpoint User</td>
                <td>
                    <strong>Como</strong> desarrollador frontend, 
                    <strong>quiero</strong> poder crear y obtener información sobre diferentes tipos de usuarios en la plataforma,
                    <strong>para</strong> gestionar eficazmente las cuentas de los usuarios desde la interfaz de usuario de la aplicación móvil.
                </td>
                <td>
                    <h5>Escenario 01: Crear un nuevo usuario</h5>
                    <strong>Dado</strong> un usuario desea registrarse en la plataforma.
                    <strong>Cuando</strong> envía una solicitud para crear un nuevo usuario mediante una solicitud POST con los detalles del usuario.
                    <strong>Entonces</strong> el sistema verifica la disponibilidad del correo electrónico y crea el nuevo usuario en la base de datos, devolviendo los detalles del usuario creado con un código de estado 201 (Created).
                    <br>
                    <h5>Escenario 02: Registrar un veterinario</h5>
                    <strong>Dado</strong> un veterinario desea registrarse en la plataforma.
                    <strong>Cuando</strong> envía una solicitud para registrar un veterinario mediante una solicitud POST con los detalles del veterinario y el ID de usuario.
                    <strong>Entonces</strong> el sistema verifica si el usuario existe y es apto para registrarse como veterinario, luego registra al veterinario en la base de datos y marca al usuario como registrado, devolviendo los detalles del veterinario registrado con un código de estado 201 (Created).
                    <br>
                    <h5>Escenario 03: Registrar un propietario de mascotas</h5>
                    <strong>Dado</strong> un propietario de mascotas desea registrarse en la plataforma.
                    <strong>Cuando</strong> envía una solicitud para registrar un propietario de mascotas mediante una solicitud POST con los detalles del propietario de mascotas y el ID de usuario.
                    <strong>Entonces</strong> el sistema verifica si el usuario existe y es apto para registrarse como propietario de mascotas, luego registra al propietario de mascotas en la base de datos y marca al usuario como registrado, devolviendo los detalles del propietario de mascotas registrado con un código de estado 201 (Created).
                </td>
                <td>EPIC-10</td>
            </tr>
            <tr>
                <td>TS-006</td>
                <td>Endpoint Veterinary Clinic</td>
                <td>
                    <strong>Como</strong> desarrollador frontend, 
                    <strong>quiero</strong> poder agregar nuevas clínicas veterinarias a la plataforma y ver una lista de todas las clínicas disponibles
                    <strong>para</strong> que los usuarios puedan encontrar fácilmente servicios veterinarios cercanos.
                </td>
                <td>
                    <h5>Escenario 01: Crear una nueva clínica veterinaria</h5>
                    <strong>Dado</strong> un usuario desea agregar una nueva clínica veterinaria a la plataforma.
                    <strong>Cuando</strong> envía una solicitud POST con los detalles de la nueva clínica veterinaria, incluyendo nombre, ubicación, servicios ofrecidos y horario de atención.
                    <strong>Entonces</strong> el sistema crea la nueva clínica veterinaria en la base de datos y devuelve los detalles de la clínica recién creada con un código de estado 201 (Created).
                    <br>
                    <h5>Escenario 02: Obtener todas las clínicas veterinarias</h5>
                    <strong>Dado</strong> un usuario desea ver todas las clínicas veterinarias disponibles en la plataforma.
                    <strong>Cuando</strong> envía una solicitud GET.
                    <strong>Entonces</strong> el sistema devuelve una lista de todas las clínicas veterinarias registradas en la plataforma con un código de estado 200 (OK).
                    <br>
                    <h5>Escenario 03: Filtrar clínicas veterinarias por ubicación o servicios</h5>
                    <strong>Dado</strong> un usuario desea encontrar clínicas veterinarias específicas por ubicación o servicios ofrecidos.
                    <strong>Cuando</strong> envía una solicitud GET con parámetros de consulta para filtrar por ubicación o servicios.
                    <strong>Entonces</strong> el sistema devuelve una lista de clínicas veterinarias que coinciden con los criterios de búsqueda con un código de estado 200 (OK). Si no se encuentran coincidencias, se devuelve una lista vacía.
                </td>
                <td>EPIC-10</td>
            </tr>
            <tr>
                <td>US-052</td>
                <td>Monitoreo de ubicación en tiempo real</td>
                <td>
                    <strong>Como</strong> propietario de mascota, 
                    <strong>quiero</strong> recibir la ubicación en tiempo real de mi mascota desde el collar con GPS,
                    <strong>para</strong> mantenerla localizada y poder actuar rápidamente en caso de pérdida o robo.
                </td>
                <td>
                    <h5>Escenario 1: Ubicación exitosa</h5>
                    <strong>Dado</strong> el collar está conectado y tiene señal GPS,
                    <strong>Cuando</strong> accedo a la opción de localización en la aplicación,
                    <strong>Entonces</strong> puedo ver la ubicación actual de mi mascota en el mapa en tiempo real, actualizada cada 30 segundos.
                    <br>
                    <h5>Escenario 2: Ubicación fuera de rango GPS</h5>
                    <strong>Dado</strong> el collar está fuera de la cobertura GPS,
                    <strong>Cuando</strong> intento ver la ubicación de la mascota,
                    <strong>Entonces</strong> recibo una notificación indicando que no se puede obtener la ubicación en este momento, con la última posición conocida del GPS.
                    <br>
                    <h5>Escenario 3: Desconexión del collar</h5>
                    <strong>Dado</strong> el collar se ha desconectado o apagado,
                    <strong>Cuando</strong> intento acceder a la ubicación,
                    <strong>Entonces</strong> la aplicación muestra un mensaje de error indicando que el dispositivo está desconectado, con opciones de solución como verificar la batería o la conexión.
                </td>
                <td>EPIC-02</td>
            </tr>
            <tr>
                <td>US-053</td>
                <td>Alertas de salud anormal</td>
                <td>
                    <strong>Como</strong> propietario de mascota o veterinaria,
                    <strong>quiero</strong> recibir una notificación si los signos vitales de mi mascota o paciente (ritmo cardiaco o temperatura) muestran valores anormales,
                    <strong>para</strong> poder actuar rápidamente en caso de emergencia.
                </td>
                <td>
                    <h5>Escenario 1: Ritmo cardiaco y temperatura normales</h5>
                    <strong>Dado</strong> el collar está monitoreando los signos vitales,
                    <strong>Cuando</strong> los valores están dentro de los rangos normales establecidos,
                    <strong>Entonces</strong> la aplicación no envía ninguna alerta y los datos se actualizan cada 5 minutos.
                    <br>
                    <h5>Escenario 2: Ritmo cardiaco elevado o baja temperatura</h5>
                    <strong>Dado</strong> el ritmo cardiaco supera 120 bpm o la temperatura es menor a 35°C,
                    <strong>Cuando</strong> se detecta un valor fuera del rango,
                    <strong>Entonces</strong> la aplicación envía una alerta al propietario y al veterinario con un reporte detallado de los signos vitales.
                    <br>
                    <h5>Escenario 3: Fallo en la lectura de los signos vitales</h5>
                    <strong>Dado</strong> el collar tiene problemas para medir el ritmo cardiaco o la temperatura,
                    <strong>Cuando</strong> se intenta hacer una lectura y el dispositivo falla,
                    <strong>Entonces</strong> la aplicación notifica al propietario sobre el fallo del dispositivo y sugiere revisar el collar.
                </td>
                <td>EPIC-02</td>
            </tr>
            <tr>
                <td>US-054</td>
                <td>Integración de datos del collar al historial médico</td>
                <td>
                    <strong>Como</strong> veterinario,
                    <strong>quiero</strong> acceder a los datos de salud (ritmo cardiaco y temperatura) registrados por el collar IoT,
                    <strong>para</strong> complementar el historial médico de la mascota y dar un mejor seguimiento a su salud.
                </td>
                <td>
                    <h5>Escenario 1: Integración exitosa de los datos</h5>
                    <strong>Dado</strong> el collar está conectado,
                    <strong>Cuando</strong> se registran los signos vitales (ritmo cardiaco y temperatura),
                    <strong>Entonces</strong> estos datos se almacenan automáticamente en el historial médico de la mascota con la fecha y hora correspondientes.
                    <br>
                    <h5>Escenario 2: Fallo en la sincronización de datos</h5>
                    <strong>Dado</strong> el collar tiene problemas para transmitir los datos,
                    <strong>Cuando</strong> se intenta sincronizar los signos vitales con el historial médico,
                    <strong>Entonces</strong> la aplicación muestra un mensaje de error indicando que los datos no pudieron ser sincronizados.
                    <br>
                    <h5>Escenario 3: Visualización de datos en el historial médico</h5>
                    <strong>Dado</strong> los datos han sido sincronizados,
                    <strong>Cuando</strong> el veterinario accede al historial médico de la mascota,
                    <strong>Entonces</strong> puede visualizar las métricas de salud del collar junto con otros datos clínicos, como vacunas y consultas previas.
                </td>
                <td>EPIC-02</td>
            </tr>
            <tr>
                <td>US-055</td>
                <td>Notificación de batería baja en el collar</td>
                <td>
                    <strong>Como</strong> propietario de mascota,
                    <strong>quiero</strong> recibir una notificación cuando la batería del collar esté baja,
                    <strong>para</strong> poder cargarlo a tiempo y no perder el seguimiento de mi mascota.
                </td>
                <td>
                    <h5>Escenario 1: Batería baja</h5>
                    <strong>Dado</strong> el collar tiene menos del 20% de batería,
                    <strong>Cuando</strong> se detecta este nivel,
                    <strong>Entonces</strong> recibo una notificación en la aplicación y un correo electrónico para cargar el dispositivo lo antes posible.
                    <br>
                    <h5>Escenario 2: Carga completada</h5>
                    <strong>Dado</strong> el collar está cargando,
                    <strong>Cuando</strong> se completa la carga,
                    <strong>Entonces</strong> recibo una notificación indicando que el dispositivo está listo para su uso y con un estimado de la duración de la batería.
                    <br>
                    <h5>Escenario 3: Fallo en la carga del dispositivo</h5>
                    <strong>Dado</strong> el collar tiene problemas para cargar,
                    <strong>Cuando</strong> se detecta un error en el proceso de carga,
                    <strong>Entonces</strong> recibo una notificación indicando que el collar no ha sido cargado correctamente y una recomendación para verificar el cargador o el puerto de carga.
                </td>
                <td>EPIC-04</td>
            </tr>
            <tr>
                <td>TS-007</td>
                <td>Implementación de la API de monitoreo de ubicación</td>
                <td>
                    <strong>Como</strong> desarrollador,
                    <strong>necesito</strong> crear una API RESTful para gestionar la comunicación entre la aplicación y el collar IoT,
                    <strong>para</strong> permitir la actualización y consulta de la ubicación GPS en tiempo real.
                </td>
                <td>
                    <h5>Escenario 1: Endpoint de consulta de ubicación</h5>
                    <strong>Dado</strong> el cliente desea obtener la ubicación de la mascota,
                    <strong>Cuando</strong> se envía una solicitud GET al endpoint /location/{petId},
                    <strong>Entonces</strong> la API responde con la ubicación actual de la mascota en formato JSON, incluyendo latitud, longitud, y hora de la última actualización.
                    <br>
                    <h5>Escenario 2: Error en la conexión con el dispositivo</h5>
                    <strong>Dado</strong> el dispositivo está desconectado o fuera de rango,
                    <strong>Cuando</strong> se envía una solicitud GET al endpoint /location/{petId},
                    <strong>Entonces</strong> la API devuelve un código de estado 503 (Service Unavailable) indicando la imposibilidad de obtener la ubicación en ese momento.
                    <br>
                    <h5>Escenario 3: Actualización de ubicación desde el collar IoT</h5>
                    <strong>Dado</strong> el dispositivo envía periódicamente la ubicación,
                    <strong>Cuando</strong> se recibe una solicitud POST desde el dispositivo IoT al endpoint /location/update,
                    <strong>Entonces</strong> la API actualiza la base de datos con la nueva ubicación y devuelve un código de estado 200 (OK).
                </td>
                <td>EPIC-12</td>
            </tr>
            <tr>
                <td>TS-008</td>
                <td>Integración de signos vitales en el historial médico</td>
                <td>
                    <strong>Como</strong> desarrollador,
                    <strong>necesito</strong> implementar una API que permita recibir los datos de los signos vitales desde el collar IoT y almacenarlos en el historial médico de la mascota,
                    <strong>para</strong> mantener un registro completo y actualizado de la salud de la mascota.
                </td>
                <td>
                    <h5>Escenario 1: Recepción de datos de signos vitales</h5>
                    <strong>Dado</strong> el collar envía los signos vitales de la mascota,
                    <strong>Cuando</strong> se realiza una solicitud POST al endpoint /health/update,
                    <strong>Entonces</strong> los datos de ritmo cardiaco y temperatura se almacenan en la base de datos con su respectivo timestamp.
                    <br>
                    <h5>Escenario 2: Fallo en la sincronización de datos</h5>
                    <strong>Dado</strong> los datos no se han recibido correctamente,
                    <strong>Cuando</strong> el dispositivo IoT envía una solicitud POST con un formato de datos incorrecto,
                    <strong>Entonces</strong> la API devuelve un código de estado 400 (Bad Request) y un mensaje de error describiendo el problema.
                    <br>
                    <h5>Escenario 3: Consulta de historial médico</h5>
                    <strong>Dado</strong> el veterinario desea consultar los signos vitales,
                    <strong>Cuando</strong> se envía una solicitud GET al endpoint /medical-history/{petId},
                    <strong>Entonces</strong> la API responde con un JSON que incluye los valores de ritmo cardiaco y temperatura registrados desde el collar IoT, junto con otros datos clínicos.
                </td>
                <td>EPIC-12</td>
            </tr>
      </tbody>
</table>

## 3.3. Impact Mapping.

En esta sección, se presenta el Impact Mapping para cada segmento objetivo. Esta técnica permite visualizar cómo las características del producto contribuyen a los objetivos de negocio y cómo se alinean con las necesidades de los usuarios.

### Segmento 1: Veterinaria

![Impact Mapping Veterinaria](https://i.postimg.cc/XqV7sXx9/Impact-mapping-Veterinaria.png)

### Segmento 2: Propietario de mascota

![Impact Mapping Propietario de mascota](https://i.postimg.cc/HLyxxqV8/Impact-mapping-Propietario.png)

## 3.4. Product Backlog.

Utilizamos la escala de Fibonacci para la estimación de los Story Points.

<table>
        <thead>
            <tr>
                <th>Orden</th>
                <th>User Story Id</th>
                <th>Título</th>
                <th>Descripción</th>
                <th>Story Points (1/2/3/5/8)</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>US-036</td>
                <td>Navegar en la página principal </td>
                <td>
                    <strong>Como</strong> visitante,
                    <strong>quiero</strong> acceder a la página principal del sitio web y ver un botón de Call to Action 
                    <strong>para</strong> descargar la aplicación o registrarme, para tener acceso rápido a la funcionalidad principal.
                </td>
                <td>1</td>
            </tr>
            <tr>
                <td>2</td>
                <td>US-039</td>
                <td>Descargar la aplicación</td>
                <td>
                    <strong>Como</strong> visitante,
                    <strong>quiero</strong> poder descargar la aplicación desde el sitio web estático,
                    <strong>para</strong> instalarla en mi dispositivo y comenzar a usarla.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>3</td>
                <td>US-037</td>
                <td>Ver funcionalidades para propietarios de mascotas</td>
                <td>
                    <strong>Como</strong> visitante,
                    <strong>quiero</strong> ver las funcionalidades que ofrece la aplicación para los dueños de mascotas,
                    <strong>para</strong> saber cómo puedo usarla para cuidar de mi mascota.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>4</td>
                <td>US-038</td>
                <td>Ver funcionalidades para veterinarias</td>
                <td>
                    <strong>Como</strong> visitante,
                    <strong>quiero</strong> ver las funcionalidades que ofrece la aplicación para veterinarias,
                    <strong>para</strong> conocer cómo puedo usarla en mi clínica veterinaria.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>5</td>
                <td>US-035</td>
                <td>Revisar reseñas de la aplicación</td>
                <td>
                    <strong>Como</strong> visitante,
                    <strong>quiero</strong> poder ver las reseñas de la aplicación,
                    <strong>para</strong> conocer la experiencia de otros usuarios antes de descargarla o registrarme.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>6</td>
                <td>US-034</td>
                <td>Ver información del footer</td>
                <td>
                    <strong>Como</strong> visitante,
                    <strong>quiero</strong> poder acceder a los enlaces del footer,
                    <strong>para</strong> navegar rápidamente a secciones como redes sociales, noticias y contacto.
                </td>
                <td>1</td>
            </tr>
            <tr>
                <td>7</td>
                <td>US-040</td>
                <td>Enviar un mensaje desde el sitio de web estático</td>
                <td>
                    <strong>Como</strong> visitante,
                    <strong>quiero</strong> poder enviar un mensaje al equipo de la aplicación desde la sección de contacto,
                    <strong>para</strong> resolver dudas o recibir más información sobre el servicio.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>8</td>
                <td>US-010</td>
                <td>Agendar una cita</td>
                <td>
                    <strong>Como</strong> propietario de una mascota,
                    <strong>quiero</strong> poder agendar una cita en la clínica veterinaria a través de la aplicación,
                    <strong>para</strong> asegurar la atención médica oportuna para mi mascota.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>9</td>
                <td>TS-001</td>
                <td>Endpoint Appointment</td>
                <td>
                    <strong>Como</strong> desarrollador front-end,
                    <strong>quiero</strong> asegurarme de que el registro de historia médica funcione correctamente en la interfaz de usuario,
                    <strong>para</strong> que los usuarios puedan ingresar la información de manera adecuada.
                </td>
                <td>5</td>
            </tr>
            <tr>
                <td>10</td>
                <td>US-005</td>
                <td>Registrar Mascota</td>
                <td>
                    <strong>Como</strong> propietario de una mascota,
                    <strong>quiero</strong> crear un perfil para cada una de mis mascotas en la aplicación, ingresando su información básica 
                    <strong>para</strong> mantener un registro organizado de sus datos.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>11</td>
                <td>TS-004</td>
                <td>Endpoint Pet</td>
                <td>
                    <strong>Como</strong> desarrollador frontend,
                    <strong>quiero</strong> poder integrar la funcionalidad de agregar y visualizar mascotas en la interfaz de usuario,
                    <strong>para</strong> permitir a los usuarios mantener un registro actualizado de sus mascotas desde la aplicación móvil.
                </td>
                <td>5</td>
            </tr>
            <tr>
                <td>12</td>
                <td>US-053</td>
                <td>Alertas de salud anormal</td>
                <td>
                    <strong>Como</strong> propietario de mascota o veterinaria,
                    <strong>quiero</strong> recibir una notificación si los signos vitales de mi mascota o paciente (ritmo cardiaco o temperatura) muestran valores anormales,
                    <strong>para</strong> poder actuar rápidamente en caso de emergencia.
                </td>
                <td>8</td>
            </tr>
            <tr>
                <td>13</td>
                <td>US-054</td>
                <td>Integración de datos del collar al historial médico</td>
                <td>
                    <strong>Como</strong> veterinario,
                    <strong>quiero</strong> acceder a los datos de salud (ritmo cardiaco y temperatura) registrados por el collar IoT,
                    <strong>para</strong> complementar el historial médico de la mascota y dar un mejor seguimiento a su salud.
                </td>
                <td>8</td>
            </tr>
            <tr>
                <td>14</td>
                <td>TS-008</td>
                <td>Integración de signos vitales en el historial médico</td>
                <td>
                    <strong>Como</strong> desarrollador,
                    <strong>quiero</strong> implementar una API que permita recibir los datos de los signos vitales desde el collar IoT y almacenarlos en el historial médico de la mascota,
                    <strong>para</strong> mantener un registro completo y actualizado de la salud de la mascota.
                </td>
                <td>13</td>
            </tr>
            <tr>
                <td>15</td>
                <td>TS-002</td>
                <td>Endpoint Medical History</td>
                <td>
                    <strong>Como</strong> desarrollador front-end,
                    <strong>quiero</strong> acceder a un endpoint en el backend para gestionar el historial médico de las mascotas, incluyendo el registro de enfermedades y vacunaciones asociadas,
                    <strong>para</strong> permitir el manejo completo del historial médico desde la interfaz de usuario.
                </td>
                <td>5</td>
            </tr>
            <tr>
                <td>16</td>
                <td>US-024</td>
                <td>Visualizar resumen del historial médico</td>
                <td>
                    <strong>Como</strong> veterinario o personal autorizado,
                    <strong>quiero</strong> poder visualizar el resumen del historial médico de cada mascota,
                    <strong>para</strong> considerar sus antecedentes durante la atención de una consulta.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>17</td>
                <td>TS-006</td>
                <td>Endpoint Veterinary Clinic</td>
                <td>
                    <strong>Como</strong> desarrollador frontend,
                    <strong>quiero</strong> poder agregar nuevas clínicas veterinarias a la plataforma y ver una lista de todas las clínicas disponibles,
                    <strong>para</strong> que los usuarios puedan encontrar fácilmente servicios veterinarios cercanos.
                </td>
                <td>5</td>
            </tr>
            <tr>
                <td>18</td>
                <td>US-052</td>
                <td>Monitoreo de ubicación en tiempo real</td>
                <td>
                    <strong>Como</strong> propietario de mascota,
                    <strong>quiero</strong> recibir la ubicación en tiempo real de mi mascota desde el collar con GPS,
                    <strong>para</strong> mantenerla localizada y poder actuar rápidamente en caso de pérdida o robo.
                </td>
                <td>5</td>
            </tr>
            <tr>
                <td>19</td>
                <td>TS-007</td>
                <td>Implementación de la API de monitoreo de ubicación</td>
                <td>
                    <strong>Como</strong> desarrollador,
                    <strong>quiero</strong> crear una API RESTful para gestionar la comunicación entre la aplicación y el collar IoT,
                    <strong>para</strong> permitir la actualización y consulta de la ubicación GPS en tiempo real.
                </td>
                <td>13</td>
            </tr>
            <tr>
                <td>20</td>
                <td>US-041</td>
                <td>Mostrar tu ubicación actual</td>
                <td>
                    <strong>Como</strong> propietario/a o autenticado y suscrito a un plan,
                    <strong>quiero</strong> poder visualizar mi ubicación,
                    <strong>para</strong> buscar centros de atención cerca de mi ubicación.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>21</td>
                <td>US-048</td>
                <td>Añadir ubicación</td>
                <td>
                    <strong>Como</strong> veterinaria o personal autorizado de la clínica veterinaria,
                    <strong>quiero</strong> añadir la ubicación de mi centro de atención,
                    <strong>para</strong> mostrar la ubicación actual de mi centro de atención.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>22</td>
                <td>US-042</td>
                <td>Mostrar veterinarias cercanas</td>
                <td>
                    <strong>Como</strong> propietario/a o autenticado y suscrito a un plan,
                    <strong>quiero</strong> visualizar las veterinarias alrededor de mi zona,
                    <strong>para</strong> elegir una y atender a mi mascota.
                </td>
                <td>5</td>
            </tr>
            <tr>
                <td>23</td>
                <td>TS-005</td>
                <td>Endpoint User</td>
                <td>
                    <strong>Como</strong> desarrollador frontend,
                    <strong>quiero</strong> poder crear y obtener información sobre diferentes tipos de usuarios en la plataforma,
                    <strong>para</strong> gestionar eficazmente las cuentas de los usuarios desde la interfaz de usuario de la aplicación móvil.
                </td>
                <td>5</td>
            </tr>
            <tr>
                <td>24</td>
                <td>US-049</td>
                <td>Añadir servicios ofrecidos</td>
                <td>
                    <strong>Como</strong> veterinaria o personal autorizado de la clínica veterinaria,
                    <strong>quiero</strong> añadir la información de los servicios que ofrece mi veterinaria,
                    <strong>para</strong> informar a mis clientes que tipo de atención brindamos.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>25</td>
                <td>US-050</td>
                <td>Añadir horarios de atención</td>
                <td>
                    <strong>Como</strong> veterinaria o personal autorizado de la clínica veterinaria,
                    <strong>quiero</strong> poder añadir mis horarios de atención al usuario,
                    <strong>para</strong> evitar que mis clientes se acerquen en días no laborales de mi veterinaria.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>26</td>
                <td>US-020</td>
                <td>Registrar vacunas</td>
                <td>
                    <strong>Como</strong> veterinario o personal autorizado,
                    <strong>quiero</strong> poder registrar las vacunas administradas a cada mascota,
                    <strong>para</strong> mantener un historial médico completo y actualizado.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>27</td>
                <td>US-021</td>
                <td>Registrar resultados</td>
                <td>
                    <strong>Como</strong> veterinario o personal autorizado,
                    <strong>quiero</strong> poder registrar los resultados de análisis obtenidos de cada mascota,
                    <strong>para</strong> mantener un historial médico completo y actualizado.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>28</td>
                <td>US-022</td>
                <td>Registrar cirugías</td>
                <td>
                    <strong>Como</strong> veterinario o personal autorizado,
                    <strong>quiero</strong> registrar un reporte de los resultados de cirugías realizadas en cada mascota,
                    <strong>para</strong> mantener un historial médico completo y actualizado.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>29</td>
                <td>US-023</td>
                <td>Registrar enfermedades</td>
                <td>
                    <strong>Como</strong> veterinario o personal autorizado,
                    <strong>quiero</strong> poder registrar las enfermedades diagnosticadas en cada mascota,
                    <strong>para</strong> mantener un historial médico completo y actualizado.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>30</td>
                <td>US-045</td>
                <td>Ver detalles de cada veterinaria</td>
                <td>
                    <strong>Como</strong> propietario/a o autenticado y suscrito a un plan,
                    <strong>quiero</strong> poder visualizar la información de cada veterinaria,
                    <strong>para</strong> poder elegir con mayor eficacia la veterinaria acorde a mis necesidades.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>31</td>
                <td>US-047</td>
                <td>Entrar al perfil de cada veterinaria</td>
                <td>
                    <strong>Como</strong> propietario/a o autenticado y suscrito a un plan,
                    <strong>quiero</strong> visualizar información personal de cada veterinaria,
                    <strong>para</strong> poder informarme mejor acerca de cada veterinaria.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>32</td>
                <td>US-051</td>
                <td>Eliminar veterinaria</td>
                <td>
                    <strong>Como</strong> veterinaria o personal autorizado de la clínica veterinaria,
                    <strong>quiero</strong> poder eliminar el centro veterinario en caso de cierre u otro motivo,
                    <strong>para</strong> mantener actualizada la base de datos de UPet y evitar confusiones.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>33</td>
                <td>US-017</td>
                <td>Confirmar cita</td>
                <td>
                    <strong>Como</strong> propietario de mascota,
                    <strong>quiero</strong> poder confirmar una cita veterinaria previamente agendada,
                    <strong>para</strong> asegurarme de que la cita está programada y evitar confusiones.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>34</td>
                <td>US-008</td>
                <td>Compartir información</td>
                <td>
                    <strong>Como</strong> propietario de una mascota,
                    <strong>quiero</strong> poder compartir información relevante sobre el perfil de mi mascota con veterinarios que no tienen acceso a la aplicación,
                    <strong>para</strong> facilitar el intercambio de información y garantizar la atención adecuada de mi mascota incluso fuera de la red de la aplicación.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>35</td>
                <td>US-012</td>
                <td>Acceso de la veterinaria a la información de la mascota</td>
                <td>
                    <strong>Como</strong> veterinario,
                    <strong>quiero</strong> poder acceder a la información completa de una mascota, incluyendo su historial médico, vacunas y tratamientos previos,
                    <strong>para</strong> brindar una atención adecuada durante una consulta veterinaria.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>36</td>
                <td>US-014</td>
                <td>Ver historial de citas</td>
                <td>
                    <strong>Como</strong> propietario de una mascota,
                    <strong>quiero</strong> poder ver el historial completo de citas veterinarias de mi mascota, incluyendo fechas, horarios y propósito de la visita,
                    <strong>para</strong> tener un registro completo de la atención recibida.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>37</td>
                <td>US-013</td>
                <td>Cancelar o reprogramar cita</td>
                <td>
                    <strong>Como</strong> propietario de una mascota,
                    <strong>quiero</strong> poder cancelar o reprogramar una cita veterinaria previamente programada,
                    <strong>para</strong> poder gestionar mejor mi agenda y evitar problemas de horarios.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>38</td>
                <td>US-006</td>
                <td>Subir foto de la mascota</td>
                <td>
                    <strong>Como</strong> propietario de mascota,
                    <strong>quiero</strong> poder subir una foto de mi mascota a la plataforma,
                    <strong>para</strong> poder personalizar su perfil y compartir su imagen con las veterinarias.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>39</td>
                <td>US-007</td>
                <td>Ver listado de mis mascotas</td>
                <td>
                    <strong>Como</strong> propietario de una mascota,
                    <strong>quiero</strong> poder ver un listado de todas mis mascotas registradas en la aplicación,
                    <strong>para</strong> tener un acceso rápido a su información y gestionarlas de manera eficiente.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>40</td>
                <td>US-009</td>
                <td>Editar información de la mascota</td>
                <td>
                    <strong>Como</strong> propietario de una mascota,
                    <strong>quiero</strong> poder editar la información del perfil de mi mascota en la aplicación,
                    <strong>para</strong> mantener actualizada la información de mis mascotas.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>41</td>
                <td>US-025</td>
                <td>Ver planes disponibles de suscripción</td>
                <td>
                    <strong>Como</strong> propietario de mascota sin suscripción,
                    <strong>quiero</strong> poder visualizar los planes disponibles de suscripción,
                    <strong>para</strong> comparar y elegir el plan que mejor se ajuste a mis necesidades.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>42</td>
                <td>US-026</td>
                <td>Suscribirse a un plan</td>
                <td>
                    <strong>Como</strong> propietario de mascota sin suscripción,
                    <strong>quiero</strong> poder suscribirme a los planes disponibles,
                    <strong>para</strong> obtener los beneficios de la versión de pago.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>43</td>
                <td>US-027</td>
                <td>Cambiar de plan</td>
                <td>
                    <strong>Como</strong> propietario suscrito a un plan,
                    <strong>quiero</strong> poder cambiar mi plan de suscripción,
                    <strong>para</strong> acceder o limitar mis permisos a nuevas funcionalidades de la aplicación.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>44</td>
                <td>US-029</td>
                <td>Cancelar plan</td>
                <td>
                    <strong>Como</strong> propietario suscrito a un plan,
                    <strong>quiero</strong> poder cancelar la versión de mi plan actual,
                    <strong>para</strong> limitar mis permisos y funcionalidades en la aplicación.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>45</td>
                <td>US-030</td>
                <td>Gestión de métodos de pago</td>
                <td>
                    <strong>Como</strong> propietario suscrito,
                    <strong>quiero</strong> gestionar mis métodos de pago,
                    <strong>para</strong> facilitar el proceso de transacciones en la aplicación.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>46</td>
                <td>US-031</td>
                <td>Actualizar método de pago</td>
                <td>
                    <strong>Como</strong> propietario suscrito,
                    <strong>quiero</strong> poder actualizar mi método de pago,
                    <strong>para</strong> garantizar que las transacciones futuras se procesen correctamente.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>47</td>
                <td>US-032</td>
                <td>Eliminar método de pago</td>
                <td>
                    <strong>Como</strong> propietario suscrito,
                    <strong>quiero</strong> poder eliminar un método de pago,
                    <strong>para</strong> gestionar los métodos de pago que ya no uso.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>48</td>
                <td>US-028</td>
                <td>Historial de suscripciones</td>
                <td>
                    <strong>Como</strong> propietario autenticado,
                    <strong>quiero</strong> poder visualizar el historial de las suscripciones de mi cuenta,
                    <strong>para</strong> tener un recuento de los gastos realizados en la aplicación.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>49</td>
                <td>US-043</td>
                <td>Ver las valoraciones y comentarios de la veterinaria</td>
                <td>
                    <strong>Como</strong> veterinario/a o personal autorizado de la clínica veterinaria,
                    <strong>quiero</strong> poder visualizar las valoraciones y comentarios de mi veterinaria,
                    <strong>para</strong> mejorar en los aspectos negativos que pueda tener.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>50</td>
                <td>US-046</td>
                <td>Ver reseñas y evaluación</td>
                <td>
                    <strong>Como</strong> propietario/a o autenticado y suscrito a un plan,
                    <strong>quiero</strong> visualizar las reseñas de cada veterinaria,
                    <strong>para</strong> facilitar el proceso de selección de cada centro.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>51</td>
                <td>US-044</td>
                <td>Añadir valoraciones y comentarios</td>
                <td>
                    <strong>Como</strong> propietario/a de mascota autenticado y suscrito a un plan,
                    <strong>quiero</strong> poder realizar comentarios y valoraciones,
                    <strong>para</strong> calificar la atención de cada centro de atención.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>52</td>
                <td>US-055</td>
                <td>Notificación de batería baja en el collar</td>
                <td>
                    <strong>Como</strong> propietario de mascota,
                    <strong>quiero</strong> recibir una notificación cuando la batería del collar esté baja,
                    <strong>para</strong> poder cargarlo a tiempo y no perder el seguimiento de mi mascota.
                </td>
                <td>5</td>
            </tr>
            <tr>
                <td>53</td>
                <td>US-018</td>
                <td>Recordatorio de cita</td>
                <td>
                    <strong>Como</strong> propietario de mascota,
                    <strong>quiero</strong> recibir recordatorios de las citas veterinarias previamente agendadas,
                    <strong>para</strong> no olvidar la cita y organizarme mejor.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>54</td>
                <td>US-019</td>
                <td>Recordatorio de suscripción</td>
                <td>
                    <strong>Como</strong> propietario de mascota suscrito a un plan de servicios veterinarios,
                    <strong>quiero</strong> recibir recordatorios de mi suscripción, incluyendo fechas de renovación,
                    <strong>para</strong> gestionar mi plan de manera efectiva.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>55</td>
                <td>US-011</td>
                <td>Activar recordatorio</td>
                <td>
                    <strong>Como</strong> propietario de una mascota con una cita veterinaria programada,
                    <strong>quiero</strong> poder activar un recordatorio en la aplicación,
                    <strong>para</strong> recibir una notificación en la fecha y hora de la cita y asegurarme de no olvidarla.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>56</td>
                <td>US-016</td>
                <td>Notificación de campañas veterinarias</td>
                <td>
                    <strong>Como</strong> propietario de mascota,
                    <strong>quiero</strong> poder recibir notificaciones sobre campañas veterinarias cercanas, como campañas de vacunación y desparasitación,
                    <strong>para</strong> mantener la salud de mi mascota al día.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>57</td>
                <td>US-015</td>
                <td>Ofertas de las veterinarias</td>
                <td>
                    <strong>Como</strong> propietario de mascota,
                    <strong>quiero</strong> poder recibir notificaciones sobre ofertas y promociones especiales de las veterinarias cercanas,
                    <strong>para</strong> poder aprovechar descuentos y beneficios adicionales en la atención de mi mascota.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>58</td>
                <td>TS-003</td>
                <td>Endpoint Notification</td>
                <td>
                    <strong>Como</strong> desarrollador front-end,
                    <strong>quiero</strong> tener un endpoint para gestionar notificaciones de usuarios,
                    <strong>para</strong> crear nuevas notificaciones y obtener las notificaciones existentes.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>59</td>
                <td>US-001</td>
                <td>Registro de cuenta</td>
                <td>
                    <strong>Como</strong> veterinario o propietario de una mascota,
                    <strong>quiero</strong> registrarme en la aplicación,
                    <strong>para</strong> acceder a sus funcionalidades.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>60</td>
                <td>US-002</td>
                <td>Iniciar Sesión</td>
                <td>
                    <strong>Como</strong> veterinario o propietario de una mascota,
                    <strong>quiero</strong> poder iniciar sesión en la aplicación utilizando mis credenciales,
                    <strong>para</strong> acceder a las funcionalidades y gestionar la información ingresada.
                </td>
                <td>2</td>
            </tr>
            <tr>
                <td>61</td>
                <td>US-003</td>
                <td>Reestablecer Contraseña</td>
                <td>
                    <strong>Como</strong> veterinario o propietario de una mascota,
                    <strong>quiero</strong> tener la capacidad de restablecer mi contraseña en la aplicación,
                    <strong>para</strong> poder acceder de nuevo a mi cuenta y gestionar la información de manera segura.
                </td>
                <td>3</td>
            </tr>
            <tr>
                <td>62</td>
                <td>US-004</td>
                <td>Cerrar Sesión</td>
                <td>
                    <strong>Como</strong> veterinario o propietario de una mascota,
                    <strong>quiero</strong> tener la capacidad de cerrar sesión en la aplicación,
                    <strong>para</strong> garantizar la seguridad de mi información y proteger mi privacidad.
                </td>
                <td>1</td>
            </tr>
            <tr>
                <td>63</td>
                <td>US-033</td>
                <td>Enviar un mensaje a soporte</td>
                <td>
                    <strong>Como</strong> usuario de la aplicación,
                    <strong>quiero</strong> poder enviar un mensaje a soporte técnico,
                    <strong>para</strong> resolver problemas o consultas sobre el uso de la aplicación.
                </td>
                <td>2</td>
            </tr>
        </tbody>
</table>

Imagen de Product Backlog en Pivotal Tracker:

![Pivotal_Tracker_UPet](https://i.postimg.cc/rmGwG5G8/pivotal-tracker-Pawture.png)

Enlace de Pivotal Tracker: https://www.pivotaltracker.com/n/projects/2677948
