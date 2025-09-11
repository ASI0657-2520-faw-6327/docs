# <p align="center">Informe de Trabajo Final</p>

## <p align="center">Universidad Peruana de Ciencias Aplicadas</p>

<div align="center">
  <img src="./imgsLogos/upc-logo.png" alt="Logo de UPC" />
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

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo

- **Anderson Jose Gamarra Vega:**

**Descripción:** <br>
Mi nombre es Anderson Jose Gamarra Vega, tengo 25 años , estudiante de Ingeniería de Software. Desde siempre he sentido una gran pasión por la tecnología, pero me decanto especialmente por el desarrollo de software, pues me fascina aprender nuevos lenguajes de programación, diseñar soluciones digitales y afrontar retos mediante código. Esta inclinación hacia el software fue lo que me motivó a elegir esta carrera, y actualmente estoy profundizando en áreas como backend, arquitectura de software, metodologías agile.

<img src="imgIntegrantes/anderson.jpg" alt="Anderson" title="Foto de Anderson" width="110"/>

<br>

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

En esta sección se detallan los segmentos de descripición de nuestra solución de software, sus características de valor y las estrategias de monetización.

**Product Name:**

Optamos por el nombre Ñango porque proviene de la palabra quechua “ñan”, que significa camino, y “go”, que remite a la acción de ir o avanzar. Esta combinación transmite la esencia de la aplicación: facilitar el desplazamiento de los estudiantes de manera segura, práctica y colaborativa. El nombre refleja cercanía con la cultura peruana y, al mismo tiempo, proyecta modernidad y dinamismo, valores que nuestra plataforma busca ofrecer a sus usuarios.

### 1.2.1 Antecedentes y problemática

En los últimos años, la situación del transporte en el Perú se ha visto marcada por altos niveles de inseguridad que afectan tanto a pasajeros como a conductores. Este contexto resulta especialmente delicado para los estudiantes universitarios, quienes suelen ser víctimas de robos y asaltos en los alrededores de sus centros de estudio. Asimismo, la presencia de transporte informal y la práctica de cobro de “cupos” a choferes limitan la disponibilidad de servicios confiables, generando incertidumbre y restringiendo la movilidad diaria.

Frente a esta realidad, surge la necesidad de una alternativa tecnológica que garantice un traslado más seguro y accesible para los estudiantes. Es en este escenario que se plantea ÑanGo, una plataforma de movilidad compartida enfocada en la comunidad universitaria, la cual busca conectar a estudiantes con vehículo propio con aquellos que requieren transporte. Con esta solución, se busca optimizar costos, reducir riesgos asociados a la inseguridad y generar confianza a través de perfiles verificados y medidas de protección.

Para analizar la problemática, se empleó la técnica de las 5 “W” y 2 “H”:

**WHAT – ¿Cuál es el problema?**
Los servicios de transporte actuales presentan deficiencias en términos de seguridad y confianza. Los estudiantes se enfrentan a delitos frecuentes como robos, asaltos y acoso, lo que genera un ambiente de vulnerabilidad. Existe una carencia de opciones que combinen economía y seguridad en los traslados hacia las universidades.

**WHEN – ¿Cuándo ocurre el problema?**
La problemática se presenta de forma cotidiana, sobre todo en horas punta, coincidiendo con los horarios de ingreso y salida de las universidades. Estos momentos de congestión son aprovechados por delincuentes en zonas cercanas a los centros educativos.

**WHERE – ¿Dónde surge el problema y dónde se usa el producto?**
El problema es más visible en las calles de Lima Metropolitana y otras ciudades universitarias donde predominan los taxis informales y la inseguridad. Los estudiantes podrán usar ÑanGo desde sus casas, universidades u otros espacios con conexión a internet, para coordinar viajes hacia sus centros de estudio y compartir rutas con compañeros de confianza.

**WHO – ¿Quiénes están involucrados?**
Los principales afectados son los estudiantes universitarios, aunque también se incluye a familiares que pueden actuar como choferes de confianza. Los usuarios de la plataforma serán tanto pasajeros que buscan un transporte seguro, como estudiantes que ofrecen sus vehículos para compartir gastos y mejorar la movilidad.

**WHY – ¿Por qué ocurre el problema?**
Las causas principales son la informalidad en el servicio de transporte, la falta de regulación eficiente y la limitada presencia de sistemas tecnológicos que garanticen la seguridad de los pasajeros. Además, los altos costos del transporte privado llevan a los estudiantes a optar por alternativas más riesgosas.

**HOW – ¿Cómo se utiliza la solución?**
ÑanGo será utilizada en situaciones de alta demanda de transporte, especialmente en horas punta. Los estudiantes coordinarán viajes compartidos, reducirán gastos al dividir costos y contarán con perfiles verificados que les brinden mayor confianza y seguridad en el servicio.

**HOW MUCH – Sustento estadístico**
De acuerdo con datos de la Policía Nacional del Perú y reportes del Ministerio del Interior, Lima Metropolitana registra elevados índices de robos y asaltos en el transporte público e informal. Estas cifras evidencian la urgencia de implementar soluciones seguras e innovadoras para la comunidad estudiantil, reforzando la necesidad de una plataforma como ÑanGo.
### 1.2.2 Lean UX Process.

#### 1.2.2.1. Lean UX Problem Statements

Nuestro servicio de movilidad compartida para estudiantes universitarios fue diseñado para garantizar un desplazamiento que garantice la seguridad, accesibilidad y economía de los estudiantes.

Hemos observado que el sistema de transporte público e informal actual no cumple con estos objetivos, lo que está causando altos niveles de inseguridad y sentimientos negativos como temor y estrés en los estudiantes universitarios, quienes se ven expuestos diariamente a robos, asaltos y extorsiones.

Actualmente, muchos estudiantes optan por alternativas riesgosas o costosas, lo que incrementa su exposición a la delincuencia, reduce su libertad de movilización y afecta negativamente su calidad de vida y rendimiento académico.

¿Cómo podríamos mejorar nuestro servicio de movilidad compartida para que los estudiantes universitarios tengan una solución efectiva para conectar con compañeros verificados y optimizar sus rutas diarias garantizando la confianza y la protección en sus desplazamientos?

#### 1.2.2.2. Lean UX Assumptions

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

### 3.3 Impact Map

### 3.4. Product Backlog