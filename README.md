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

- Creemos que los estudiantes podrán optimizar su tiempo y reducir costos de transporte si se implementa una funcionalidad que les permita coordinar viajes en grupo hacia la universidad a través de una plataforma que les conecte con otros estudiantes de su misma universidad. Sabremos que hemos tenido éxito cuando el 30% de los estudiantes utilicen regularmente la plataforma para coordinar viajes y que el 25% reporte una disminución en sus gastos de transporte mensual.

- Creemos que los estudiantes reducirán su huella de carbono y contribuirán a la sostenibilidad si proporcionamos una opción fácil de coordinar viajes en vehículos compartidos, disminuyendo el número de autos individuales en las rutas comunes hacia las universidades. Sabremos que hemos tenido éxito cuando el 20% de los estudiantes reporten que han preferido la opción de compartir vehículo por encima de usar transporte público o privado.

- Creemos que los estudiantes podrán mejorar la accesibilidad y seguridad en sus traslados si ofrecemos un sistema de calificación y seguimiento de viajes compartidos, lo que proporcionará mayor confianza y control. Sabremos que hemos tenido éxito cuando al menos el 15% de los usuarios reporten mayor confianza y comodidad al utilizar la plataforma, y que el 20% mencionen que el sistema de calificación ha mejorado su experiencia de viaje.

- Creemos que los estudiantes estarán más dispuestos a utilizar la plataforma si esta ofrece perfiles verificados y filtros de coincidencia por universidad o facultad. Sabremos que hemos tenido éxito cuando al menos el 60 % de los usuarios activen la verificación de identidad y el 70 % prefiera viajar con contactos verificados de su misma institución.

- Creemos que la adopción aumentará si se integra un sistema de notificaciones para viajes programados. Sabremos que hemos tenido éxito cuando el 80 % de los trayectos se confirmen con más de 6 horas de anticipación y se reduzca en un 30 % la tasa de cancelaciones de último minuto.

- Creemos que la plataforma será más atractiva si permite compartir gastos automáticamente mediante pagos digitales entre los pasajeros. Sabremos que hemos tenido éxito cuando al menos el 50 % de los viajes registrados utilicen el sistema de pago integrado y el 85 % de los usuarios lo califiquen como fácil y seguro.

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

### Estudiante pasajero
![Estudiante pasajero](imgs/as-is-estudiante.png)

### Estudiante conductor
![Estudiante conductor](imgs/as-is-estudiante-conductor.png)

### Familiar de estudiante
![Familiar de estudiante](imgs/as-is-familiar.png)


# Capítulo III: Requirements Specification

### 3.1. To-be Scenario Mapping

### Estudiante pasajero
![Estudiante pasajero](imgs/to-be-estudiante.png)

### Estudiante conductor
![Estudiante conductor](imgs/to-be-estudiante-conductor.png)

### Familiar de estudiante
![Familiar de estudiante](imgs/to-be-familiar.png)

### 3.2 User Stories

### 3.3 Impact Map

### 3.4. Product Backlog