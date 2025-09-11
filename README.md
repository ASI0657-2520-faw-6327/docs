# <p align="center">Informe de Trabajo Final</p>

## <p align="center">Universidad Peruana de Ciencias Aplicadas</p>

<div align="center">
  <img src="./imgs/upc-logo.png" alt="Logo de UPC" />
</div>

<p align="center">Ingeniería de Software</p>
<p align="center">Fundamentos de Arquitectura de software - 6327</p>
<p align="center"><strong>Docente:</strong> Jorge Luis Delgado Vite</p>
<p align="center"><strong>Startup:</strong> TinkuyTech</p>
<p align="center"><strong>Producto:</strong> Ñango</p>

<p align="center"><strong>Team members:</strong></p>

| Nombre                            | Código     |
| --------------------------------- | ---------- |
| Gamarra Vega, Anderson Jose       | u202016154 |
| Nanfuñay Liza, Pedro Jesús        | u202215462 |
| Quijandria Araneda Vicente        | U201822697 |

<p align="center"><strong>Ciclo 2025-02</strong></p>


# Registro de versiones del informe

| Versión | Fecha | Autor | Descripción de Modificación |
| ------- | ----- | ----- | --------------------------- |
| TB1 | 06/09/2025 | TinkuyTech | Redación de los capítulos: <br> Capítulo I: Introducción <br> Capítulo II: Requirements  & Analysis <br> Capítulo III: Requirements Specification |

# Student Outcomes

### [Capítulo I: Introducción](#capítulo-i-introducción)

- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)


### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

- [2.1. Competidores](#21-competidores)
- [2.2. Entrevistas](#22-entrevistas)
- [2.3. Needfinding](#23-needfinding)
  - [2.3.1. User Personas](#231-user-personas)
  - [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)

### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)

- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

# Capítulo I: Introducción

## 1.1. Startup Profile

En esta sección se describen los detalles del problema que buscamos resolver.  
Se detalla el perfil de la startup, el mercado objetivo, y se presentan la misión y visión.  
Asimismo, se expone una visión atractiva del equipo, resaltando su potencial en función de las habilidades y capacidades de cada integrante.

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo

- **Anderson Jose Gamarra Vega:**

**Descripción:** <br>
Mi nombre es Anderson Jose Gamarra Vega, tengo 25 años , estudiante de Ingeniería de Software. Desde siempre he sentido una gran pasión por la tecnología, pero me decanto especialmente por el desarrollo de software, pues me fascina aprender nuevos lenguajes de programación, diseñar soluciones digitales y afrontar retos mediante código. Esta inclinación hacia el software fue lo que me motivó a elegir esta carrera, y actualmente estoy profundizando en áreas como backend, arquitectura de software, metodologías agile.

![AndersonGamarra-Image-Profile](imgs/anderson.jpg)


- **Pedro Jesús Nanfuñay Liza:**

**Descripción:** <br>
Mi nombre es Pedro Jesús Nanfuñay Liza, tengo 20 años y soy estudiante de la carrera de Ingeniería de Software. Me considero una persona creativa, responsable, perseverante y siempre dispuesto a trabajar en equipo. Tengo conocimientos en varios lenguajes de programación como C++, Java y Python; en el desarrollo web con frameworks Angular y Primevue, y en base de datos relacionales y no relacionales como SQL y MongoDB. Espero aportar de manera positiva al equipo y cumplir con los objetivos establecidos.

![PedroNanfuñay-Image-Profile](imgs/PedroNanfuñay-Image-Profile.jpg)

<br>

- **Vicente Quijandria Araneda:**

**Descripción:** <br>
Mi nombre es Vicente Quijandria Araneda, estudio la carrera de Ingeniería de Software en la UPC. Me gusta el fútbol, surf, buceo y la tecnología.
Tengo conocimientos en lenguajes de programación como Java y Python; en el desarrollo web con frameworks React y Angular, y en base de datos relacionales y no relacionales como SQL y MongoDB. Soy una persona que siempre busca aprender nuevos conocimientos que me lleven a convertirme en un gran profesional y así poder cumplir mis metas cada día.

![PedroNanfuñay-Image-Profile](imgs/vicente-quijandria.png)

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

### 1.2.2 Lean UX Process.

#### 1.2.2.1. Lean UX Problem Statements

Nuestro servicio de movilidad compartida para estudiantes universitarios fue diseñado para garantizar un desplazamiento que garantice la seguridad, accesibilidad y economía de los estudiantes.

Hemos observado que el sistema de transporte público e informal actual no cumple con estos objetivos, lo que está causando altos niveles de inseguridad y sentimientos negativos como temor y estrés en los estudiantes universitarios, quienes se ven expuestos diariamente a robos, asaltos y extorsiones.

Actualmente, muchos estudiantes optan por alternativas riesgosas o costosas, lo que incrementa su exposición a la delincuencia, reduce su libertad de movilización y afecta negativamente su calidad de vida y rendimiento académico.

¿Cómo podríamos mejorar nuestro servicio de movilidad compartida para que los estudiantes universitarios tengan una solución efectiva para conectar con compañeros verificados y optimizar sus rutas diarias garantizando la confianza y la protección en sus desplazamientos?

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions:**

1. Creemos que nuestros clientes necesitan una aplicación que les permita movilizarse de forma segura, confiable y económica, compartiendo viajes con otros estudiantes verificados.

2. Estas necesidades pueden cubrirse mediante una aplicación que integre validación de usuarios, rutas seguras, y un sistema de reparto de gastos entre pasajeros.

3. Nuestros clientes iniciales serán estudiantes universitarios que cuenten o no con vehículo propio, y que necesiten transportarse de manera segura.

4. El valor más importante que se espera de nuestro servicio es la seguridad durante los traslados, seguida de la accesibilidad económica y confianza entre usuarios.

5. Nuestros clientes también pueden obtener beneficios adicionales como la reducción de costos al compartir viajes, y mayor confianza y tranquilidad al trasladarse con compañeros verificados y seguimiento de su trayecto en tiempo real.

6. Planeamos adquirir la mayoría de nuestros usuarios mediante campañas en redes sociales y eventos académicos.

7. Nuestra competencia directa son los servicios de taxi tradicionales y aplicaciones de movilidad, pero estas no garantizan seguridad ni conexión exclusiva entre estudiantes.

8. Superaremos a la competencia ofreciendo una comunidad cerrada de usuarios verificados, opciones de viaje compartido y evaluación de rutas seguras.

9. El mayor riesgo de nuestro producto es la desconfianza inicial en el uso compartido del transporte con desconocidos.

10. Este riesgo será mitigado mediante perfiles verificados, calificaciones por viaje y soporte de emergencia en la aplicación.

11. La confianza en la plataforma aumentará con el tiempo gracias a la validación de usuarios y experiencias positivas.

12. La satisfacción del cliente también se podrá mejorar mediante la integración de un sistema de soporte.


**User Assumptions:**

1. **¿Quién es el usuario?** <br>
Estudiantes universitarios (como pasajeros o conductores) que necesitan trasladarse hacia sus instituciones educativas de forma segura y económica.

2. **¿Dónde encaja nuestro producto en su vida?** <br>
En su rutina diaria, cuando deben movilizarse a las clases universitarias, especialmente en horarios de alto riesgo.

3. **¿Qué problemas tiene nuestro producto y cómo se pueden resolver?** <br>
Al tratarse de un nuevo sistema, los usuarios podrían tener dudas sobre la seguridad y confiabilidad del servicio. Para resolverlo, se harán campañas informativas, se promoverán testimonios, y se establecerán protocolos de seguridad visibles desde el primer uso.

4. **¿Cuándo y cómo es usado nuestro producto?** <br>
ÑanGo será utilizado antes de clases para coordinar viajes, compartir rutas y gastos. La plataforma permitirá programar viajes con antelación y coordinar trayectos similares con compañeros.

5. **¿Qué características son importantes?** <br>
Verificación de identidad, calificación de usuarios, sistema de pago compartido, coordinar horarios de viajes y rutas seguras, y registro de detalle del trayecto.

6. **¿Cómo debe verse nuestro producto y cómo debe comportarse?** <br>
Debe tener una interfaz juvenil, amigable y confiable, con diseño intuitivo y botones de acción rápida. Debe responder con fluidez y ofrecer información clara sobre seguridad y confiabilidad del viaje.


**Features:**

- Visualización de rutas y horarios disponibles para facilitar la planificación de los viajes.

- Notificaciones instantáneas sobre llegada, cancelaciones o cambios.

- Sistema de verificación.

- Administración eficiente de vehículos.

- Chat interno entre usuarios verificados para coordinar viajes.

- Calificaciones y comentarios entre pasajeros y conductores.

- Historial de viajes y registro de gastos compartidos.

- Soporte técnico constante y actualizaciones de sistema para mejorar el rendimiento y la seguridad.

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos Objetivo

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

## 2.2. Entrevistas

## 2.3. Needfinding

### 2.3.1. User Persons

### 2.3.2. User Task Matrix

### 2.3.3 User Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-is Scenario Mapping

# Capítulo III: Requirements Specification

### 3.1. To-be Scenario Mapping

### 3.2 User Stories

| Epic ID | Título | Descripción |
| ------- | ------ | ----------- |
| EP01 | Registro de Usuario | Registro de usuarios en la plataforma |
| EP02 | Recuperación de Cuenta | Recuperación de cuenta de usuario |
| EP03 | Autenticación | Autenticación de cuenta para acceder a la plataforma |
| EP04 | Gestión de Perfil | Gestión de información de cuenta del usuario |
| EP05 | Comunicación | Funciones de comunicación entre usuarios |
| EP06 | Seguridad | Garantiza la seguridad del usuario y su información personal |
| EP07 | Verificación | Verificación de la cuenta mediante servicios externos |
| EP08 | Búsqueda de Viajes | Búsqueda de conductores disponibles en el momento |
| EP09 | Solicitud de Viaje | Solicita un viaje |
| EP10 | Calificación Post-Viaje | Calificación del usuario tras haber culminado un viaje |
| EP11 | Rutas de viaje en el mapa | Ruta más óptima a seguir |
| EP12 | Historial de Viajes | Acceso al historial de viajes realizados en la plataforma |
| EP13 | Planificación de Viajes | Planificación anticipada de viajes |
| EP14 | Publicación de Viajes | Publicación de viajes disponibles en el momento |
| EP15 | Gestión de Solicitudes de Viajes | Gestionar la disponibilidad e información del viaje |
| EP16 | Reputación | Calificación promedio obtenida |
| EP17 | Notificaciones | Alertas para mantenerse informado |
| EP18 | Historial y Finanzas | Historial de viajes y ganancias |


| Epic / User Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| -------------------- | ------ | ----------- | ----------------------- | ------------------------- |
| US01 | Registro de nueva cuenta | Como usuario nuevo no registrado, deseo poder crear una cuenta en la aplicación, para acceder a las funcionalidades exclusivas de ÑanGo. | Scenario 1: Registro con datos válidos <br> Dado que el usuario no está registrado, Y se encuentra en la pantalla de "registro", Cuando completa los campos requeridos [Nombres, Apellidos, Correo electrónico, Contraseña, Confirmar Contraseña] con datos válidos Y selecciona su perfil de usuario [Conductor o Pasajero], Y acepta los "términos y condiciones", Entonces el sistema crea la cuenta Y envía un link de verificación al correo. <br> <br> Scenario 2: Registro con datos inválidos o incompletos <br> Dado que el usuario está en la pantalla de "registro", Cuando deja campos obligatorios vacíos o introduce un correo inválido, Entonces el sistema muestra un mensaje de error Y no permite completar el registro hasta corregir los datos. | EP01 |
| US02 | Recuperación de contraseña | Como usuario que olvidó su contraseña, quiero recuperar el acceso a mi cuenta, para poder seguir usando la app. | Scenario 1: Solicitud de recuperación de contraseña <br> Dado que el usuario no recuerda su contraseña, Y accede a la opción "¿Olvidaste tu contraseña?", Cuando tu correo esta en el apartado de "iniciar sesion", Y es un electrónico registrado, Entonces el sistema envía un enlace para restablecer la contraseña. Cuando el Usuario abra el link podra ingresar a la recuperacion de cuenta, Y completa los campos requeridos Y le da click a guardar nueva contraseña, Entonces su contraseña es actualizada por el sistema. <br> <br> Scenario 2: Recuperación con correo no registrado <br> Dado que el usuario ha olvidado su contraseña, Y accede a la opción "¿Olvidaste tu contraseña?", Cuando introduce un correo no vinculado a ninguna cuenta, Entonces el sistema muestra un mensaje “Este correo no está registrado.” | EP02 |
| US03 | Inicio de sesión | Como usuario registrado, quiero iniciar sesión en la app, para acceder a mis funcionalidades personalizadas. | Scenario 1: Inicio de sesión exitoso <br> Dado que el usuario está registrado, Y se encuentra en la pantalla de "Iniciar Sesion", Cuando introduce su "correo" y "contraseña" válidos, Entonces el sistema lo autentica, Y lo redirige a su "pantalla principal". <br> <br> Scenario 2: Inicio de sesión fallido <br> Dado que el usuario está en la pantalla de login, Cuando introduce un correo o contraseña incorrectos, Entonces el sistema muestra un mensaje de error Y no permite iniciar sesión. <br> <br> Scenario 3: Inicio de sesión exitoso y guardado de inicio <br> Dado que el usuario está registrado, Y se encuentra en la pantalla de "Iniciar Sesión [Nueva contraseña, Confirmar Contraseña]", Cuando introduce su correo y contraseña válidos, Y marca la casilla Recuerdáme, Entonces el sistema lo autentica, Y genera un token de recordatorio único y seguro, Y almacena el token asociado al usuario en la base de datos, Y lo redirige a su "pantalla principal". | EP03 |
| US04 | Cierre de sesión | Como usuario autenticado, quiero cerrar sesión, para proteger el acceso a mi cuenta. | Scenario 1: Logout exitoso <br> Dado que el usuario está autenticado, Cuando selecciona su perfil, Y se despliega el menu cascada, Y selecciona la opción "Salir", Entonces el sistema cierra la sesión actual Y redirige al usuario a la pantalla de inicio. <br> <br> Scenario 2: Logout fallido por conexión <br> Dado que el usuario está autenticado, Cuando selecciona la opción "Cerrar sesión" y no hay conexión de red, Entonces el sistema muestra un mensaje de error Y no cierra la sesión hasta que se recupere la conexión. | EP03 |
| US05 | Edición de perfil | Como usuario autenticado, quiero poder editar mi perfil, para mantener mi información actualizada. | Scenario 1: Edición de campos personales <br> Dado que el usuario está autenticado, Y accede a la sección "Mi perfil", Y accede a la opcion "Editar", Cuando modifica los campos de "nombre, email, celular, Plan, o foto de perfil", Y guarda los cambios, Entonces el sistema actualiza su información correctamente. <br> <br> Scenario 2: Edición con datos inválidos <br> Dado que el usuario está autenticado, Y accede a la sección "Mi perfil", Y accede a la opcion "Editar", Cuando introduce caracteres inválidos en el campo "nombre", O intenta subir una imagen no permitida, Entonces el sistema muestra mensajes de validación Y no guarda los cambios hasta que se corrijan. | EP04 |
| US06 | Chat de comunicación | Como usuario, quiero comunicarme con otros mediante chat, para coordinar viajes y resolver dudas. | Scenario 1: Envío de mensaje en chat <br> Dado que el usuario está en una conversación activa, Cuando escribe un mensaje y pulsa "enviar", Entonces el mensaje se muestra en el chat Y es recibido por el otro usuario en tiempo real. <br> <br> Scenario 2: Fallo de red al enviar mensaje <br> Dado que el usuario está en una conversación activa, Y hay un problema de conexión a internet, Cuando intenta enviar un mensaje, Entonces el sistema muestra un mensaje “No se pudo enviar el mensaje. Intenta nuevamente.” | EP05 |
| US07 | Cambiar contraseña | Como usuario autenticado, quiero cambiar mi contraseña, para reforzar la seguridad de mi cuenta. | Scenario 1: Cambio exitoso de contraseña <br> Dado que el usuario está autenticado, Cuando selecciona su perfil, Y se despliega el menu cascada, Y selecciona la opción "Cambiar contraseña", Y cuando completa los campos de "contraseña" y "nueva contraseña", Y le da click al boton "Guardar nueva contraseña", Entonces el sistema lo lleva a la pagina "Cambiar contraseña", actualiza la "contraseña" Y muestra un mensaje de confirmación. <br> <br> Scenario 2: Contraseña actual incorrecta <br> Dado que el usuario accede a “Configuración > Seguridad”, Cuando introduce una contraseña actual incorrecta, Entonces el sistema muestra un mensaje de error Y no permite cambiar la contraseña. | EP06 |
| US08 | Verificación con correo institucional | Como estudiante, quiero verificar mi cuenta utilizando mi "DNI" y "Carnet Universitario", para tener acceso a las funcionalidades de la aplicación. | Scenario 1: Validacion con documentos válido <br> Dado que el estudiante está registrado, Y se encuentra en la pantalla de "Verificacion", Cuando da click en las opciones de subir documento en "DNI" y "Carnet Universitario", Y sube sus documentos validos, Entonces el sistema valida su cuenta. <br> Scenario 2: Validacion con documentos inválidos <br> Dado que el estudiante está registrado, Y se encuentra en la pantalla de "Verificacion", Cuando da click en las opciones de subir documento en "DNI" y "Carnet Universitario", Y sube documentos son invalidos, Entonces el sistema valida su cuenta. | EP07 |
| US09 | Búsqueda de viajes disponibles | Como estudiante sin vehículo, quiero buscar viajes disponibles, para poder unirme a ellos. | Scenario 1: Búsqueda de viajes según filtro <br> Dado que el estudiante está en la pantalla de cotizaciones, Cuando selecciona filtros como "fecha", "origen" y "destino", Entonces el sistema muestra una lista de viajes disponibles que coinciden con los filtros. <br> <br> Scenario 2: Sin resultados de búsqueda <br> Dado que el estudiante está en la pantalla de cotizaciones, Cuando no hay viajes disponibles para los filtros seleccionados, Entonces el sistema muestra un mensaje “No se encontraron viajes disponibles.” | EP08 |
| US10 | Solicitud de unirse a un viaje | Como estudiante, quiero solicitar unirme a un viaje disponible, para poder participar en el transporte compartido. | Scenario 1: Solicitud de unirse a un viaje disponible <br> Dado que el estudiante ha encontrado un viaje disponible, Cuando selecciona la opción “Unirse al viaje”, Y le aparece la ventana para reservar Y selecciona la opción en el apartado de "pago", Y selecciona la opción “Solicitar”, Entonces el sistema envía la solicitud al conductor. <br> <br> Scenario 2: Solicitud de unirse a un viaje lleno <br> Dado que el estudiante ha encontrado un viaje, Cuando intenta unirse a un viaje que ya está lleno, Entonces el sistema muestra el mensaje “Este viaje ya está completo.” | EP09 |
| US11 | Notificaciones en tiempo real | Como estudiante, quiero recibir notificaciones en tiempo real sobre el estado de mi solicitud de viaje, para estar informado de cualquier cambio. | Scenario 1: Notificación de aceptación de solicitud <br> Dado que el estudiante ha solicitado unirse a un viaje, Cuando el conductor acepta la solicitud, Entonces el sistema envía una notificación al estudiante con la confirmación. <br> <br> Scenario 2: Notificación de rechazo de solicitud <br> Dado que el estudiante ha solicitado unirse a un viaje, Cuando el conductor rechaza la solicitud, Entonces el sistema envía una notificación al estudiante con el mensaje “Solicitud rechazada.” | EP05 |
| US12 | Sistema de calificación post-viaje | Como estudiante, quiero calificar el viaje después de completarlo, para evaluar el servicio y ayudar a mejorar la calidad de los viajes. | Scenario 1: Calificación exitosa del viaje <br> Dado que el viaje ha finalizado, Cuando el estudiante accede a la sección de "calificación", Y selecciona una "calificación" y "comentarios", Entonces el sistema guarda la calificación y muestra un mensaje de confirmación. <br> <br> Scenario 2: Calificación incompleta <br> Dado que el estudiante ha finalizado el viaje, Cuando intenta calificar sin proporcionar "comentarios" o "calificación", Entonces el sistema muestra un mensaje “Por favor, proporciona una calificación para continuar.” | EP10 |
| US13 | Chat interno con Grupo | Como estudiante, quiero poder comunicarme con el conductor a través del chat interno una vez que mi solicitud de viaje haya sido aceptada. | Scenario 1: Enviar mensaje al conductor después de aceptación <br> Dado que el estudiante ha sido aceptado en un viaje, Cuando el estudiante envía un mensaje grupo, Entonces el mensaje aparece en el chat y es recibido por el grupo en tiempo real. <br> <br> Scenario 2: No poder enviar mensaje antes de aceptación <br> Dado que el estudiante no ha sido aceptado aún, Cuando intenta enviar un mensaje, Entonces el sistema muestra el mensaje “Esperando aceptación del conductor para iniciar el chat.” | EP05 |
| US14 | Ruta de mi viaje | Como estudiante, quiero poder ver la ruta del viaje, para saber dónde se encuentra el conductor. | Scenario 1: Visualización del mapa <br> Dado que el estudiante ha solicitado un viaje, Cuando accede al seguimiento del viaje, Entonces el sistema muestra la ruta en el mapa. <br> <br> Scenario 2: Sin señal <br> Dado que el estudiante está en un viaje activo, Cuando no puede obtener señal, Entonces el sistema muestra el mensaje “No se puede obtener la ruta y ubicacion.” | EP11 |
| US15 | Historial de viajes y gastos | Como estudiante, quiero consultar el historial de mis viajes y los gastos generados, para llevar un control de mis viajes y pagos. | Scenario 1: Ver historial completo de viajes <br> Dado que el estudiante está en la sección de "historial", Cuando selecciona la opción de "ver todos los viajes", Entonces el sistema muestra la lista de viajes realizados, con "fechas" y "detalles". <br> <br> Scenario 2: Ver historial con filtros de búsqueda <br> Dado que el estudiante está en la sección de "historial", Cuando aplica filtros como "fecha" o "tipo de viaje", Entonces el sistema muestra solo los viajes que coinciden con los criterios de búsqueda. | EP12 |
| US16 | Planificación de viajes recurrentes | Como estudiante, quiero poder programar viajes recurrentes, para no tener que buscar cada vez que necesite realizar el mismo trayecto. | Scenario 1: Crear un viaje recurrente <br> Dado que el estudiante está en la pantalla de "planificación", Cuando selecciona la opción de "planificar un viaje recurrente", Y establece las fechas y parámetros para el viaje, Entonces el sistema guarda el viaje como recurrente y muestra la próxima fecha. <br> <br> Scenario 2: No crear viaje recurrente sin fecha válida <br> Dado que el estudiante está en la pantalla de "planificación", Cuando no introduce una fecha válida para el viaje recurrente, Entonces el sistema muestra un mensaje de error “Fecha inválida, por favor ingrese una fecha correcta.” | EP13 |
| US17 | Registro como conductor | Como estudiante con vehículo, quiero registrarme como conductor para poder ofrecer viajes a otros estudiantes. | Scenario 1: Registro de conductor con datos válidos <br> Dado que el estudiante no está registrado como conductor, Y se encuentra en la pantalla de "registro" como conductor, Cuando introduce sus datos personales, datos del vehículo y licencia de conducir válidos, Y acepta los términos y condiciones, Entonces el sistema crea la cuenta de conductor Y envía un correo de verificación al estudiante. <br> <br> Scenario 2: Registro con datos inválidos <br> Dado que el estudiante está en la pantalla de "registro" como conductor, Cuando introduce datos del vehículo o licencia inválidos, Entonces el sistema muestra un mensaje de error Y no permite continuar con el registro. | EP01 |
| US18 | Verificación de licencia de conducir y datos del vehículo | Como conductor registrado, quiero que mis datos y licencia sean verificados, para asegurarme de que puedo ofrecer viajes de manera legal y segura. | Scenario 1: Verificación exitosa de licencia y vehículo <br> Dado que el conductor ha registrado su licencia y datos del vehículo, Cuando el sistema verifica que los datos son válidos, Entonces el sistema confirma la verificación y permite publicar viajes. <br> <br> Scenario 2: Verificación fallida de licencia o vehículo <br> Dado que el conductor ha registrado su licencia y datos del vehículo, Cuando el sistema detecta datos inválidos o incorrectos, Entonces el sistema muestra un mensaje de error Y solicita corrección de los datos. | EP07 |
| US19 | Publicación de viajes | Como conductor, quiero poder publicar mis viajes disponibles indicando la ruta, horarios, asientos disponibles y costo por pasajero, para que los estudiantes puedan unirse a ellos. | Scenario 1: Publicación de viaje con datos válidos <br> Dado que el conductor está en la pantalla de "publicación de viaje", Cuando introduce "la ruta", "horario", "asientos disponibles" y "costo por pasajero", Y publica el viaje, Entonces el sistema crea el viaje y lo muestra en la lista de viajes disponibles para los estudiantes. <br> <br> Scenario 2: Publicación de viaje con datos inválidos <br> Dado que el conductor está en la pantalla de "publicación de viaje", Cuando introduce datos incompletos o inválidos, Entonces el sistema muestra un mensaje de error Y no permite publicar el viaje. | EP13 |
| US20 | Gestión de solicitudes | Como conductor, quiero poder aceptar o rechazar solicitudes de pasajeros con perfiles verificados, para asegurarme de que los pasajeros sean confiables. | Scenario 1: Aceptar solicitud de pasajero <br> Dado que el conductor ha recibido una solicitud para unirse a su viaje, Cuando el conductor acepta la solicitud, Entonces el sistema confirma la aceptación al pasajero Y lo agrega a la lista de pasajeros del viaje. <br> <br> Scenario 2: Rechazar solicitud de pasajero <br> Dado que el conductor ha recibido una solicitud para unirse a su viaje, Cuando el conductor rechaza la solicitud, Entonces el sistema notifica al pasajero que la solicitud ha sido rechazada. <br> Scenario 3: Solicitud con perfil no verificado <br> Dado que el conductor ha recibido una solicitud de un pasajero con perfil no verificado, Cuando el conductor revisa el perfil, Entonces el sistema muestra el mensaje “Perfil no verificado” Y el conductor no puede aceptar la solicitud. | EP13 |
| US21 | Visualización de calificación | Como conductor, quiero ver la calificación promedio y los comentarios de pasajeros previos, para poder evaluar mi desempeño y mejorar el servicio. | Scenario 1: Visualización de calificación promedio <br> Dado que el conductor ha completado varios viajes, Cuando accede a la sección de "reputación", Entonces el sistema muestra la calificación promedio obtenida en todos los viajes. <br> <br> Scenario 2: Visualización de comentarios de pasajeros previos <br> Dado que el conductor ha completado varios viajes, Cuando accede a la sección de "reputación", Entonces el sistema muestra los "comentarios de los pasajeros" sobre los viajes anteriores. | EP16 |
| US22 | Chat interno con pasajeros | Como conductor, quiero comunicarme con los pasajeros a través del chat, para coordinar puntos de encuentro y cambios de última hora. | Scenario 1: Enviar mensaje a un pasajero <br> Dado que el conductor tiene un pasajero confirmado, Cuando escribe un mensaje en el chat, Entonces el mensaje es enviado y recibido por el pasajero en tiempo real. <br> <br> Scenario 2: No poder enviar mensaje antes de aceptación <br> Dado que el pasajero no ha sido aceptado en el viaje, Cuando el conductor intenta enviar un mensaje, Entonces el sistema muestra el mensaje “Esperando aceptación del pasajero.” | EP05 |
| US23 | Historial de viajes y ganancias | Como conductor, quiero ver el historial de viajes realizados y las ganancias generadas, para llevar un registro de mi actividad. | Scenario 1: Ver historial de viajes <br> Dado que el conductor ha completado varios viajes, Cuando el conductor accede a la sección de "historial" de viajes, Entonces el sistema muestra todos los viajes realizados y las ganancias generadas. <br> <br> Scenario 2: Sin historial de viajes <br> Dado que el conductor no ha realizado viajes, Cuando accede a la sección de "historial" de viajes, Entonces el sistema muestra el mensaje “No tienes viajes registrados.” | EP05 |
| US24 | Notificaciones de demanda | Como conductor, quiero recibir alertas sobre zonas y horarios con alta demanda de transporte, para poder ajustar mis viajes y atender la necesidad de los estudiantes. | Scenario 1: Recibir alerta de alta demanda <br> Dado que el conductor ha indicado disponibilidad en ciertos horarios, Cuando hay alta demanda en esa zona y horario, Entonces el sistema envía una notificación al conductor. <br> <br> Scenario 2: No recibir alerta sin disponibilidad <br> Dado que el conductor no tiene viajes programados, Cuando hay alta demanda en una zona, Entonces el sistema no envía ninguna alerta. | EP17 |
| US25 | Reporte de incidentes | Como estudiante, quiero reportar incidentes relacionados con conductores o pasajeros, para contribuir a la seguridad del sistema. | Scenario 1: Reportar un incidente <br> Dado que el familiar ha tenido una experiencia negativa, Cuando accede a la opción de reporte, Entonces puede seleccionar el motivo del incidente, describirlo y enviarlo al sistema. <br> <br> Scenario 2: Confirmación de envío <br> Dado que el familiar ha completado el reporte, Cuando lo envía, Entonces el sistema confirma que el incidente ha sido registrado correctamente. | EP06 |

### 3.3 Impact Map

### 3.4. Product Backlog