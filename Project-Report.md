# Reporte de Proyecto

<div align="center">

# **UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS**

<img src="Assets/UPCPng.png"/>

### **Facultad de Ingeniería - Carrera de Ingeniería de Software**

### **2025-1**

#### **Curso:**

### 1ASI0572 - Desarrollo de Soluciones IoT

#### **NRC:**

#### 2947

#### **Profesor:**

#### Angel Augusto Velasquez Nuñez

### **Informe de Trabajo Final**

#### Startup: **AquaSense Technologies**

#### Producto: **FeedGuard**

### **Integrantes del equipo**

</div>

<table align="center">
  <thead>
    <tr>
      <th>Código de Estudiante</th>
      <th>Apellidos y Nombres</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"></td>
      <td align="center">Eduardo Espinoza, Vittorio Marcelo</td>
    </tr>
    <tr>
      <td align="center"></td>
      <td align="center">Flores Avalos, Diego</td>
    </tr>
    <tr>
      <td align="center">U202121584</td>
      <td align="center">Martel Zevallos, Gabriel</td>
    </tr>
    <tr>
      <td align="center">U202018627</td>
      <td align="center">Garcia Rodriguez, Gabriel</td>
    </tr>
    <tr>
      <td align="center">201923994</td>
      <td align="center">Avellaneda Ramos, Carlo</td>
    </tr>
    <tr>
      <td align="center">20191E831</td>
      <td align="center">Rivas Sarango, David Alejandro</td>
    </tr>
  </tbody>
</table>

<br>

<div align="center">

### **Abril 2025**

</div>

---

## Registro de Versiones del Informe

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th>Versión</th>
    <th>Fecha</th>
    <th>Autor</th>
    <th>Descripción de modificación</th>
  </tr>
  <tr>
    <td>1.0.0</td>
    <td>18:04/2025</td>
    <td>Todos los miembros del grupo</td>
    <td>Se realizaron los capítulos I, II, III y  IV.</td>
  </tr>
</table>

## Project Report Collaboration Insights

## Contenido

### Tabla de contenidos

  - [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
  - [Project Report Collaboration Insights](#project-report-collaboration-insights)
  - [Contenido](#contenido)
    - [Tabla de contenidos](#tabla-de-contenidos)
  - [Student Outcome](#student-outcome)
  - [Capítulo I: Introducción](#capítulo-i-introducción)
    - [1.1. Startup Profile](#11-startup-profile)
      - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
      - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
      - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
      - [The 5 W’s and 2 H’s](#the-5-ws-and-2-hs)
    - [Descripción de la problemática](#descripción-de-la-problemática)
      - [1.2.2. Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
  - [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
    - [2.1. Competidores](#21-competidores)
      - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
      - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
    - [2.2. Entrevistas](#22-entrevistas)
      - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [🎯 Objetivo de la entrevista](#-objetivo-de-la-entrevista)
    - [📋 Guía de preguntas](#-guía-de-preguntas)
      - [1. Datos personales y productivos](#1-datos-personales-y-productivos)
      - [2. Proceso de alimentación actual](#2-proceso-de-alimentación-actual)
      - [3. Monitoreo ambiental y toma de decisiones](#3-monitoreo-ambiental-y-toma-de-decisiones)
      - [4. Tecnología, percepción y adopción](#4-tecnología-percepción-y-adopción)
    - [📝 Datos complementarios a recolectar](#-datos-complementarios-a-recolectar)
      - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
      - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas-1)
      - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
    - [2.3. Needfinding](#23-needfinding)
      - [2.3.1. User Personas](#231-user-personas)
      - [2.3.2. User Task Matrix](#232-user-task-matrix)
      - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
      - [2.3.4. Empathy Mapping](#234-empathy-mapping)
      - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
    - [2.4. Ubiquitous Language](#24-ubiquitous-language)
  - [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
    - [To-Be Scenario Mapping – Juan Pérez](#to-be-scenario-mapping--juan-pérez)
    - [To-Be Scenario Mapping – Bryan Díaz](#to-be-scenario-mapping--bryan-díaz)
    - [3.2. User Stories](#32-user-stories)
    - [3.3. Impact Mapping](#33-impact-mapping)
      - [Impact Mapping – Juan Pérez (Piscicultor rural, tradicional)](#impact-mapping--juan-pérez-piscicultor-rural-tradicional)
      - [Impact Mapping – Bryan Díaz (Piscicultor técnico, innovador)](#impact-mapping--bryan-díaz-piscicultor-técnico-innovador)
    - [3.4. Product Backlog](#34-product-backlog)
  - [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
    - [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
      - [4.1.1. EventStorming](#411-eventstorming)
        - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
        - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
        - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
      - [4.1.2. Context Mapping](#412-context-mapping)
      - [4.1.3. Software Architecture](#413-software-architecture)
        - [4.1.3.1. System Landscape Diagram](#4131-system-landscape-diagram)
        - [4.1.3.2. Context Level Diagrams](#4132-context-level-diagrams)
        - [4.1.3.3. Container Level Diagrams](#4133-container-level-diagrams)
        - [4.1.3.4. Deployment Diagrams](#4134-deployment-diagrams)
    - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
      - [4.2.X. Bounded Context: \<Bounded Context Name\>](#42x-bounded-context-bounded-context-name)
        - [4.2.X.1. Domain Layer](#42x1-domain-layer)
        - [4.2.X.2. Interface Layer](#42x2-interface-layer)
        - [4.2.X.3. Application Layer](#42x3-application-layer)
        - [4.2.X.4. Infrastructure Layer](#42x4-infrastructure-layer)
        - [4.2.X.5. Component Level Diagrams](#42x5-component-level-diagrams)
        - [4.2.X.6. Code Level Diagrams](#42x6-code-level-diagrams)
          - [4.2.X.6.1. Domain Layer Class Diagrams](#42x61-domain-layer-class-diagrams)
          - [4.2.X.6.2. Database Design Diagram](#42x62-database-design-diagram)
    - [Conclusiones](#conclusiones)
    - [Bibliografía](#bibliografia)

---

## Student Outcome

<table border="1" cellspacing="0" cellpadding="5" style="border-collapse: collapse; width: 100%;">
  <tr>
    <th>Criterio especifico</th>
    <th>Acciones realizadas</th>
    <th>Conclusiones</th>
  </tr>
  <tr>
    <td><strong>Trabaja en equipo para proporcionar liderazgo en forma conjunta</strong></td>
    <td>
    Avellaneda Ramos, Carlos Edward<br>
    <i>
    TB1:
    Trabajamos como equipo, liderando la dirección y aportando la ejecución técnica para modelar AquaSense.
    </i><br><br>
    Eduardo Espinoza, Vittorio Marcelo<br>
    <i>TB1: se realizo el Lean UX Problem Statements, Assumptions, Hypothesis Statements, Canvas y Segmentos objetivo</i><br>
    Flores Avalos, Diego<br>
    <i>TB1</i><br>
    Garcia Rodriguez, Gabriel Stefano<br>
    <i>TB1: se realizo el ubiquitous Languaje, To-Be Scenario Mapping, User Stories, Impact Mapping, Product Backlog</i><br>
    Martel Zevallos, Gabriel<br>
    <i>TB1: Colaboré con la elaboración de las preguntas que se le cuestionarian a los segmentos objetivo, también he aportado en el liderazgo para el EventStorming.</i><br>
    MartelZevallos, Gabriel Aristoteles<br>
    <i>TB1</i><br>
    Rivas Sarango, David Alejandro<br>
    <i>TB1:<i>Se realizó el capítulo 2, junto con la elaboración de las entrevistas.  Nos comunicamos eficientemte al comunicar nuestras ideas para el diseño de las entrevistas y así identificarlas falencias actuales que poseen los piscicultores.</i><br></i><br>
    </td>
    <td>TB1: La construcción de la solución se benefició con el intercambio constante de ideas entre los miembros del equipo. Cada miembro asumió responsabilidades específicas y contribuyó activamente en la toma de decisiones, fortaleciendo así el liderazgo distribuido dentro del grupo.</td>
  </tr>
  <tr>
    <td><strong>Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.</strong></td>
    <td>
    Avellaneda Ramos, Carlos Edward<br>
    <i>TB1: Creamos un entorno colaborativo y alcanzamos el objetivo de construir el modelo C4 mediante tareas planificadas y comunicación abierta.
    </i><br><br>
    Eduardo Espinoza, Vittorio Marcelo<br>
    <i>TB1: se realizo el Lean UX Problem Statements, Assumptions, Hypothesis Statements, Canvas y Segmentos objetivo</i><br>
    Flores Avalos, Diego<br>
    <i>TB1</i><br>
    Garcia Rodriguez, Gabriel Stefano<br>
    <i>TB1: se realizo el ubiquitous Languaje, To-Be Scenario Mapping, User Stories, Impact Mapping, Product Backlog</i><br>
    Martel Zevallos, Gabriel<br>
    <i>TB1: Colaboré con la elaboración de las preguntas que se le cuestionarian a los segmentos objetivo, también he aportado en el liderazgo para el EventStorming.</i><br>
    MartelZevallos, Gabriel Aristoteles<br>
    <i>TB1</i><br>
    Rivas Sarango, David Alejandro<br>
    <i>TB1: Para esta entrega realice el análisis de competidores y las entrevistas. Lo que me ayudó a comprender mejor la situación actual del usuario y así mejorar el Needfinding.</i><br>
    </td>
    <td> TB1: Concluimos que la incorporación de soluciones IoT es fundamental para el sector acuícola. Si se les ayuda a automatizar y que no requieran un sobre esfuerzo. Se centrarían más en la gestión y administración adecuada de su negocio.</td>
  </tr>
</table>

## Capítulo I: Introducción

En el contexto de los sistemas productivos modernos, la incorporación de tecnologías emergentes como el Internet de las Cosas (IoT, por sus siglas en inglés) representa una oportunidad clave para mejorar procesos tradicionales a través de la automatización, el monitoreo en tiempo real y la toma de decisiones basada en datos. Esta transformación digital, conocida como Industria 4.0, ha impactado positivamente múltiples sectores, incluyendo la agricultura, la manufactura, la logística y, más recientemente, la acuicultura.

La acuicultura, entendida como la cría controlada de organismos acuáticos en entornos artificiales o semi-naturales, se ha consolidado como una de las principales fuentes de proteína animal a nivel mundial. Sin embargo, a pesar de su crecimiento, enfrenta desafíos estructurales relacionados con la eficiencia de los recursos, la sostenibilidad ambiental y la precisión en los procesos operativos, especialmente en el manejo de la alimentación y la calidad del agua.

Este reporte documenta el ciclo de vida completo del desarrollo de una solución basada en IoT orientada a resolver una problemática concreta dentro del entorno acuícola. A través de la aplicación de metodologías ágiles, principios de diseño centrado en el usuario, y prácticas modernas de desarrollo de software, se busca diseñar e implementar una solución que no solo resuelva una necesidad real del sector, sino que también aproveche los beneficios de la conectividad y la automatización.

El contenido del informe abordará desde la identificación de la problemática, el análisis de los usuarios, la especificación de requerimientos y diseño de la arquitectura de software, hasta la implementación, validación y despliegue de la solución propuesta. Todo ello con el objetivo de mostrar cómo una propuesta tecnológica puede impactar positivamente la productividad y sostenibilidad de una actividad económica vital como lo es la acuicultura.

### 1.1. Startup Profile

#### 1.1.1. Descripción de la Startup

AquaSense Technologies es una startup tecnológica orientada al desarrollo de soluciones inteligentes para el sector acuícola. Su enfoque principal es mejorar la eficiencia y sostenibilidad de los procesos productivos en pisciculturas mediante el uso de tecnologías IoT, automatización y monitoreo ambiental en tiempo real. La empresa trabaja con un enfoque centrado en el usuario, combinando ingeniería, datos y experiencia en campo para resolver problemáticas clave en sistemas semiindustriales de crianza de peces.

- 🧭 **Visión**

  Convertirnos en referentes en la transformación digital de la acuicultura en Latinoamérica, mediante soluciones tecnológicas accesibles, eficientes y sostenibles que contribuyan al desarrollo de sistemas de producción más rentables y responsables con el medio ambiente.

- 🎯 **Misión**

  Diseñar e implementar soluciones inteligentes que integren IoT, automatización y análisis de datos en tiempo real para optimizar procesos clave en sistemas acuícolas, mejorando la productividad, la sostenibilidad y la calidad del producto final.

- 💡 **Propuesta de valor**

  - Soluciones tecnológicas adaptadas a las necesidades reales de productores acuícolas semiindustriales.
  - Automatización de procesos críticos como la alimentación y el monitoreo ambiental.
  - Mejora de la eficiencia operativa, reducción de desperdicios y optimización del uso de recursos.
  - Diseño centrado en el usuario y validación continua con datos reales del entorno.

- ⚙️ **Enfoque tecnológico**

  AquaSense Technologies desarrolla productos utilizando:

  - **Tecnologías IoT** para la sensorización y automatización.
  - **Sistemas embebidos** conectados con plataformas en la nube.
  - **Arquitecturas distribuidas** con Edge Computing y servicios RESTful.
  - **Software open-source** para garantizar adaptabilidad y sostenibilidad.

- 🤝 **Compromiso**

  Promovemos la integración entre tecnología y sostenibilidad en el sector acuícola. Nuestro compromiso es con la innovación responsable, la mejora continua y la colaboración interdisciplinaria, integrando conocimientos de ingeniería, biología acuática y experiencia del usuario.

- 🚀 **Primer producto**

  **FeedGuard**  
  Sistema inteligente de alimentación y monitoreo para acuicultura semiindustrial.<br>
  Automatiza la dosificación de alimento y toma decisiones en función de parámetros como el oxígeno disuelto y los compuestos nitrogenados del agua, mejorando la eficiencia productiva y el bienestar de los peces.

#### 1.1.2. Perfiles de integrantes del equipo

<table border="1" cellspacing="0" cellpadding="5" style="border-collapse: collapse; width: 100%;">
  <tr>
    <th>Foto</th>
    <th>Descripcion</th>
  </tr>
  <tr>
    <td><img src="Assets\CarlosAvellaneda.jpg" width="200"/></td>
    <td>
     Mi nombre es Carlos Avellaneda Ramos, estudiante de la carrera de ingeniería de software, en la UPC. Actualmente, manejo con soltura Java y TypeScript. Además, me divierto creando mods para juegos en Lua y también tengo experiencia con Python y C++.
    </td>
  </tr>
  <tr>
    <td><img src="Assets\VittorioEduardo.jpg" width="200"/></td>
    <td>
    Mi nombre es Vittorio Marcelo Eduardo Espinoza y soy alumno de la carrera de ingeniería de software en la UPC. Soy una persona persistente y honesta que trata realizar su trabajo de manera correcta, así como tengo conocimientos en programación como C++ y Java Spring.
    </td>
  </tr>
  <tr>
    <td><img src="Assets\diegoflorez.png" width="200"/></td>
    <td>
    Mi nombre es Diego Flores, tengo conocimientos de lenguajes de programación C++, Python, HTML y CSS. Frontend: Vue. Backend: Flask. Me interesa el área de desarrollo web y soy proactivo y me gusta trabajar en equipo.
    </td>
  </tr>
  <tr>
    <td><img src="Assets\GabrielGarcia.png" width="200"/></td>
    <td>
    Mi nombre es Garcia Rodriguez Gabriel Stefano, tengo conocimientos de lenguajes de programación c++, c#, python, html y css, Frontend: Html, CSS, Angular y Vue. Backend: C# .NET y Java Spring Boot.  Habilidades de liderazgo y contribución en equipo.
    </td>
  </tr>
  <tr>
    <td> <img src="./Assets/GabrielMartel.jpg" width="200"/></td>
    <td>
      Mi nombre es Gabriel Martel, tengo conocimientos de lenguajes de programación JavaScript, TypeScript, Python, HTML y CSS. Frontend: React. Me interesa el área de Data Science y cuento con habilidades de liderazgo y trabajo en equipo.
    </td>
  </tr>
  <tr>
    <td><img src="./Assets/rivas-foto.jpg" width="200"/></td>
    <td>
    Mi nombre es David Alejandro Rivas Sarango, actualmente estoy cursando la carrera de Ingeniería de Software en la UPC. Soy una persona honesta y responsable. Me interesa el área de Data Science, por esto estoy siguiendo cursos de capacitacion en SQL y Python.
    </td>
  </tr>
</table>

### 1.2. Solution Profile

#### 1.2.1. Antecedentes y problemática
#### The 5 W’s and 2 H’s

- **Who (¿Quiénes están involucrados?)**  
  Productores acuícolas, específicamente aquellos que operan sistemas semiindustriales de crianza de peces en estanques, piscinas o jaulas flotantes.  
  Técnicos encargados del monitoreo y mantenimiento de las condiciones del agua y de los procesos de alimentación.  
  Proveedores de alimento balanceado y servicios de mantenimiento de equipos.  
  Instituciones regulatorias o de supervisión ambiental.

- **What (¿Qué está ocurriendo?)**  
  Se presentan ineficiencias significativas en los procesos de alimentación y control de calidad del agua. Estas fallas operativas generan impactos negativos en el crecimiento de los peces, el uso de insumos y la rentabilidad general del sistema.

- **Where (¿Dónde ocurre?)**  
  En entornos de acuicultura semiindustrial, comúnmente en zonas rurales o periurbanas donde se instalan estanques o piscinas de crianza de peces como parte de sistemas de producción local o regional.

- **When (¿Cuándo ocurre?)**  
  De forma continua durante las fases activas del ciclo productivo de los peces, con especial incidencia durante los horarios de alimentación y monitoreo diario.

- **Why (¿Por qué ocurre?)**  
  La problemática surge por la ausencia de mecanismos automatizados y precisos que permitan controlar tanto la cantidad de alimento suministrado como el estado ambiental del agua. Las decisiones suelen basarse en la experiencia empírica del personal y no en datos en tiempo real.

- **How (¿Cómo ocurre?)**  
  A través de procesos manuales o semi-manuales que no siempre garantizan la regularidad ni la exactitud necesarias, lo que puede llevar a situaciones de sobrealimentación, subalimentación, o alimentación en condiciones desfavorables del agua.

- **How much (¿Cuánto impacta?)**  
  El impacto puede reflejarse en pérdidas económicas por mal aprovechamiento del alimento (hasta un 30% del alimento puede desperdiciarse), aumento del estrés en los peces, crecimiento lento, aparición de enfermedades, y deterioro de la calidad del agua que obliga a realizar tratamientos costosos o incluso pérdidas totales en algunos ciclos productivos.

---

### Descripción de la problemática

En los sistemas acuícolas semiindustriales, uno de los procesos más críticos y determinantes para el éxito del ciclo de producción es la alimentación. La alimentación adecuada no solo garantiza el crecimiento óptimo de los peces, sino que también influye directamente en la calidad del agua y en la salud general del cultivo. Sin embargo, a pesar de su importancia, la alimentación suele llevarse a cabo de manera manual o con mecanismos rudimentarios, lo que conlleva una serie de desafíos recurrentes.

En primer lugar, la alimentación manual depende de la experiencia del operario, lo que introduce una variabilidad significativa en términos de cantidad, frecuencia y oportunidad. Esto puede resultar en prácticas ineficientes como la sobrealimentación, que genera acumulación de residuos en el agua, o la subalimentación, que afecta el crecimiento de los peces. Ambas situaciones pueden tener consecuencias económicas severas para los productores.

Adicionalmente, la falta de integración entre el proceso de alimentación y las condiciones ambientales del agua representa otro factor de riesgo. Parámetros como el oxígeno disuelto o los niveles de compuestos nitrogenados (amonio, nitritos, nitratos) tienen un impacto directo en la fisiología de los peces. Alimentar en condiciones subóptimas no solo reduce la eficiencia de conversión alimenticia, sino que también incrementa el estrés y la vulnerabilidad a enfermedades.

A esto se suma la necesidad de optimizar el uso del tiempo y los recursos humanos en un contexto donde el acceso a personal capacitado es limitado y los márgenes de ganancia son estrechos. Las actividades repetitivas y rutinarias como la alimentación podrían ser automatizadas para liberar tiempo y reducir errores humanos.

Frente a esta problemática, se evidencia una clara oportunidad de mejora mediante el uso de tecnologías emergentes que permitan tomar decisiones más informadas, automatizar procesos clave y mejorar la sostenibilidad del sistema productivo.

#### 1.2.2. Lean UX Process

##### 1.2.2.1. Lean UX Problem Statements

**Domain:**
Acuicultura semiindustrial (crianza de peces en sistemas controlados, en zonas rurales o periurbanas).

**Customer Segments:**
Productores acuícolas semiindustriales, técnicos de campo, cooperativas pesqueras pequeñas, y eventualmente proveedores de tecnología para acuicultura.

**Pain Points:**

Alimentación ineficiente (sobre o subalimentación).

Falta de monitoreo continuo de calidad del agua.

Procesos manuales propensos a errores humanos.

Pérdida económica por desperdicio de alimento.

Crecimiento lento y enfermedades en los peces por malas prácticas.

**Gap:**
No existen soluciones integradas, accesibles y adaptables a entornos semiindustriales que automaticen la alimentación y el monitoreo ambiental en tiempo real.

**Visión / Strategy:**
Desarrollar un sistema inteligente que automatice la dosificación de alimento en función de parámetros ambientales del agua y del comportamiento de los peces, conectando sensores IoT con una plataforma de análisis de datos.

**Initial Segment:**
Piscicultores semiindustriales con entre 2 y 10 estanques operativos, localizados en zonas rurales con acceso a conectividad básica.

##### 1.2.2.2. Lean UX Assumptions

- Los productores acuícolas tienen acceso mínimo a conexión a internet o redes móviles.

- Están dispuestos a invertir en soluciones tecnológicas si estas aseguran ahorro en alimento y mejoran el crecimiento de los peces.

- La variabilidad en la alimentación está generando pérdidas económicas en más del 20% de los ciclos productivos.

- La introducción de una solución de fácil uso puede ser adoptada sin capacitación extensa si cuenta con interfaz intuitiva.

- Los parámetros más críticos para la alimentación son el oxígeno disuelto y los compuestos nitrogenados.

##### 1.2.2.3. Lean UX Hypothesis Statements

**Hipótesis general:**
Creemos que los productores acuícolas semiindustriales adoptarán un sistema de alimentación inteligente si este les permite ahorrar alimento, mejorar el crecimiento de los peces y reducir el trabajo manual.

**Hipótesis específicas:**

Si automatizamos la dosificación de alimento en función del oxígeno disuelto, entonces reduciremos el desperdicio de alimento en al menos un 20%.

Si mostramos alertas sobre condiciones críticas del agua en tiempo real, entonces los técnicos podrán tomar decisiones más informadas, reduciendo la mortalidad de peces.

Si ofrecemos una interfaz amigable basada en iconos y visualizaciones simples, entonces los usuarios podrán utilizar el sistema sin requerir capacitación formal.

Si el sistema demuestra beneficios medibles en el primer mes, entonces los usuarios recomendarán su uso a otros piscicultores locales.

##### 1.2.2.4. Lean UX Canvas

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th colspan="4">Lean UX Canvas</th>
  </tr>
  <tr>
    <td colspan="2"><strong>Business Problem</strong><br> 
      Los productores acuícolas semiindustriales enfrentan pérdidas económicas por sobrealimentación y deterioro del agua debido a prácticas manuales sin automatización.
    </td>
    <td colspan="2"><strong>Business Outcomes</strong><br>
      - Reducción de desperdicio de alimento (20%)<br>
      - Mejora en crecimiento y salud de los peces<br>
      - Reducción de tareas manuales<br>
      - Incremento en la rentabilidad por ciclo productivo
    </td>
  </tr>
  <tr>
    <td colspan="2"><strong>Users</strong><br>
      Piscicultores semiindustriales con entre 2 y 10 estanques, y técnicos de campo responsables del monitoreo y alimentación.
    </td>
    <td colspan="2"><strong>User Outcomes & Benefits</strong><br>
      - Reducción de trabajo manual<br>
      - Toma de decisiones basadas en datos<br>
      - Menor mortalidad<br>
      - Mayor tasa de conversión alimenticia
    </td>
  </tr>
  <tr>
    <td colspan="4"><strong>Solutions</strong><br>
      - Sistema de sensores IoT<br>
      - Algoritmo de dosificación automática de alimento<br>
      - Interfaz móvil/web sencilla<br>
      - Alertas ambientales automatizadas<br>
      - Plataforma conectada a la nube con operación offline temporal
    </td>
  </tr>
  <tr>
    <td colspan="4"><strong>Hypotheses</strong><br>
      Creemos que la reducción del desperdicio de alimento será posible si los piscicultores obtienen alertas personalizadas y automatización del proceso de alimentación mediante sensores IoT integrados a una plataforma inteligente.
    </td>
  </tr>
  <tr>
    <td colspan="2"><strong>What's the most important thing we need to learn first?</strong><br>
      ¿Los usuarios confiarán en la automatización para dosificar el alimento? <br>
      Riesgo: Si no confían, no usarán el sistema.
    </td>
    <td colspan="2"><strong>What's the least amount of work we need to do to learn the next most important thing?</strong><br>
      Probar un piloto funcional en un estanque real con sensores, dosificador y visualización básica para evaluar ahorro de alimento y aceptación del usuario.
    </td>
  </tr>
</table>

### 1.3. Segmentos objetivo

**Segmento 1: Productores acuícolas semiindustriales rurales**
Descripción:
Pequeños y medianos piscicultores que operan estanques de crianza de tilapia, trucha o gamitana en zonas rurales o periurbanas. Generalmente trabajan de forma independiente o en asociación, con entre 2 y 10 unidades de cultivo operativas.

Características demográficas y técnicas:

- Edad promedio de los productores: entre 35 y 55 años.
- Nivel educativo: secundaria completa o técnica agrícola.
- Acceso limitado a tecnologías digitales, pero creciente interés por innovaciones que mejoren la rentabilidad.
- Ubicación en zonas con conectividad móvil básica y limitado acceso a servicios técnicos continuos.
- Operación centrada en ciclos productivos de entre 5 y 8 meses.

**Segmento 2: Piscicultores técnicos innovadores**
Descripción:
Piscicultores jóvenes o de perfil técnico, con conocimientos básicos o intermedios en tecnologías digitales, automatización y sensores. Utilizan o experimentan con herramientas como Arduino, sensores ambientales y dispositivos móviles para monitoreo de sus estanques. Tienen altas expectativas en cuanto a eficiencia y tecnología.

Características demográficas y técnicas:

- Edad promedio: 25 a 40 años.
- Nivel educativo: técnico superior o universitario (áreas relacionadas a producción agropecuaria, ingeniería técnica o afines).
- Uso de dispositivos móviles y plataformas digitales.
- Interés activo en automatización, monitoreo en tiempo real y reducción de costos operativos.
- Buscan soluciones escalables y con soporte técnico constante.

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

#### 2.1.1. Análisis competitivo


<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th colspan="7">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td rowspan="2" colspan="2"><strong>¿Por qué llevar a cabo este análisis?</strong></td>
    <td colspan="5"><strong>Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</strong></td>
  </tr>
  <tr>
    <td colspan="5"></td>
  </tr>
  <tr>
    <td colspan="3"><strong>(En la cabecera colocar por cada competidor nombre y logo)</strong></td>
    <td style="width: 25%;">FeedGuard</td>
    <td style="width: 25%;">Aquarium Xiamoi</td>
    <td style="width: 25%;">FishFarmFeeder</td>
    <td style="width: 25%;">Aplians Fish</td>
  </tr>
  <tr>
    <td rowspan="2" colspan="1" style="writing-mode: vertical-rl; 
           transform: rotate(180deg); 
           text-align: center; 
           vertical-align: middle;"><strong>Perfil</strong></td>
    <td colspan="2"><strong>Overview</strong></td>
    <td><strong>Es una solución enfocada en la automatización del proceso de alimentación en las pesceras mediante sensores integrados.</strong></td>
    <td><strong>Acuario inteligente de Xiaomi dedicado a Smart Home, este dispositivo puede alimentar automáticamente a los peces, ofrece información sobre el estado del acuario</strong></td>
    <td><strong>Aplicación móvil que permite monitorizar en tiempo real los alimentadores instalados. Accesible tanto para IPhone como Android.</strong></td>
    <td><strong>Plataforma española que gestiona de manera continua el desempeño de la piscíola, disponible desde celular y pc.</strong></td>
  </tr>
  <tr>
    <td colspan="2"><strong>Ventaja competitiva ¿Qué valor ofrece a los clientes?</strong></td>
    <td>Automatización de alimentación y notificación de alerta basada en datos y con un diseño intuitivo</td>
    <td>Su principal ventaja radica en la integración tecnológica, siendo respaldado por la marca mundial Xiaomi. Ofrese una experiencia de usuario moderna para los poseedores de estanques hogareños.</td>
    <td>Su ventaja reside en la especialización y enfoque en la eficiencia y optimización de la alimentación en la industria acuícola.</td>
    <td>Centrado en la especialización de control de inventario y monitoreo de crecimiento, esta plataforma sigue todo el ciclo de vida desde la siembra hasta la cosecha y trazabilidad.</td>
  </tr>
  <tr>
    <td rowspan="2" colspan="1" style="writing-mode: vertical-rl; 
           transform: rotate(180deg); 
           text-align: center; 
           vertical-align: middle;"><strong>Perfil de Marketing</strong></td>
    <td colspan="2"><strong>Mercado objetivo</strong></td>
    <td><strong>Son los piscicultores con limitaciones tecnológicas que posean de 2 a 10 estanques que se ubican entre los 35 y 55 años de edad.</strong></td>
    <td><strong>Consumidores interesados en acuarios domésticos inteligentes.</strong></td>
    <td><strong>Productores agrícoles de pequeña a gran escala.</strong></td>
    <td><strong>Productores agrícoles que buscan digitalizar y optimizar la gestión de sus cultivos.</strong></td>
  </tr>
  <tr>
    <td colspan="2"><strong>Estrategias de marketing</strong></td>
    <td> Marketing educativo, alianzas estratégicas y flexibilidad en los costos.</td>
    <td>Poseen una línea de productos SmartHome que venden globalmente, no solo consolidándose como competidor en el mercado móvil.</td>
    <td>Marketing digital dirigido a la industria agrícola y en eventos del sector, incluyendo demostraciones del producto.</td>
    <td>Marketing online a través de su plataforma y redes sociales.</td>
  </tr>
  <tr>
    <td rowspan="3" colspan="1" style="writing-mode: vertical-rl; 
           transform: rotate(180deg); 
           text-align: center; 
           vertical-align: middle;"><strong>Perfil de Producto</strong></td>
    <td colspan="2"><strong>Productos & Servicios</strong></td>
    <td><strong>La funcionalidad principal viene de la mano con sensores IoT para monitorear oxígeno, temperatura y compuestos dañinos dentro de la pescera.</strong></td>
    <td><strong>Acuario inteligente con sistema de filtración integrado, iluminación LED, control de temperatura y oxígeno, conectividad WI-FI y aplicación móvil.</strong></td>
    <td><strong>Sistema de alimentación automática de peces en estanques y sistemas de acuicultura.</strong></td>
    <td><strong>Plataforma que maneja el desempeño agrícola incluso de manera local, incluye seguimiento del proceso productivo y reportes en línea.</strong></td>
  </tr>
  <tr>
    <td colspan="2"><strong>Precios & Costos</strong></td>
    <td>40 dólares por suscripción mensual.</td>
    <td>50 dólares por unidad</td>
    <td>55 dólares al mes</td>
    <td>80 dólares al mes por Centro piscícola / 25 dólares al mes por estanque</td>
  </tr>
  <tr>
    <td colspan="2"><strong>Canales de distribución (Web y/o Móvil)</strong></td>
    <td>Distribución tanto web como móvil.</td>
    <td>A través de su plataforma oficial o en tiendas online de terceros.</td>
    <td>Venta directa a través de su propia página web.</td>
    <td>Principalmente a través de su propia tienda online, luego se extiende a tiendasfísicas especializadas en acuarios.</td>
  </tr>
  <tr>
    <td rowspan="5" colspan="1" style="writing-mode: vertical-rl; 
           transform: rotate(180deg); 
           text-align: center; 
           vertical-align: middle;"><strong>Analisis SWOT</strong></td>
    <td colspan="6"><strong>Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</strong></td>
  </tr>
  <tr>
    <td colspan="2"><strong>Fortalezas</strong></td>
    <td><strong>No se posee necesidad de uso de red, implementación en granjas de estanques clave y colaboración estratégica con piscicultores de nicho.</strong></td>
    <td><strong>Integración de tecnología inteligente que se puede controlar por aplicación móvil, conectividad móvil, alimentación automática y monitoreo de ambiente.</strong></td>
    <td><strong>Solución especializada para la alimentación en acuicultura.</strong></td>
    <td><strong>Enfoque en la variedad y calidad de peces, conocimiento especilizado en el cuidado de peces.</strong></td>
  </tr>
  <tr>
    <td colspan="2"><strong>Debilidades</strong></td>
    <td>Dificultad inicial a adoptar una técnología con una curva de aprendizaje media para los piscicultores.</td>
    <td>Precio elevado</td>
    <td>Necesidad de capacitación, mercado objetivo limitado a la industria acuícola empresarial.</td>
    <td>Requiere una curva de aprendizaje elevada para el correcto manejo del producto.</td>
  </tr>
  <tr>
    <td colspan="2"><strong>Oportunidades</strong></td>
    <td>Crecimiento del sector acuícola en LATAM, enfoque en los que no poseen acceso a internet 24/7.</td>
    <td>Creciente interés en hogares inteligentes.</td>
    <td>Creciente demanda por productos del mar gestionables, posibilidad de incluir sensores.</td>
    <td>Creciente demanda por productos gestionables.</td>
  </tr>
  <tr>
    <td colspan="2"><strong>Amenazas</strong></td>
    <td>Competencia de soluciones genéricas IoT con monitoreo, variedad de características por parte de la competencia.</td>
    <td>Competencia con marcas de acuarios tradicionales y nuevos competidores de acuarios inteligentes.</td>
    <td>Costo elevado mensual respecto al mercado acuícola.</td>
    <td>Competencia de otras plataformas con mayor visibilidad.</td>
  </tr>
</table>

#### 2.1.2. Estrategias y tácticas frente a competidores

A partir del análisis competitivo realizado, se logró identificar las fortalezas, debilidades, oportunidades y amenzas destacadas en los competidores. A continuación, se brindará tanto estrategias como tácticas para alcanzar esta meta:

**Fortalezas de nuestros competidores:** 

- Integración de tecnología inteligente con una marga global por detrás.
- Solución especializada y eficiente para la alimentación.
- Acompaña en el ciclo de vida, incluyendo el control de inventario y monitoreo de crecimiento.

**Estrategias y tácticas a nuestras fortalezas:**

**Estrategias:**
- Consolidación de características: Se puede desarrollar tecnología que abarque en conjunto lo que ofrecen los competidores.
- Construcción de una comunidad: Se fomentaría una unión mediante una comunidad, los usuarios podrían acceder a contenido educativo que otros publican.
- Ampliar segmento objetivo: No limitarnos a negocios de piscicultura, sino a usuarios que inician en este ámbito.

**Tácticas:** 
- Crear foros de comunidad.
- Colaboración con tiendas online de cuidado de peces.
- Sistema de recompensas.

**Debilidades de nuestros competidores:** 

- Algunos pueden ser percibidos como caros debido a su costo excesivo mensual, llegando hasta los 80 dólares.
- Curva de aprendizaje pronunciada debido a su logística compleja.
  
**Estrategias y tácticas a nuestras debilidades:**
**Estrategias:** 

- Simplicidad: Ofrecer simplicidad y facilidad de uso para que la aplicación no posea una curva de aprendizaje pronunciada.
- Soporte: Ofrecer servicio al cliente
- Calidad-precio: Disminuir precio para acceder a la aplicación, distribuirlo entre las características que brinda.
- 
**Tácticas:**

- Crear tutoriales de uso y conceptos sobre la piscicultura
- Desarrollar alianzas con tiendas de mascotas locales
- Implementar sistema de suscripciones por características.

**Oportunidades de nuestros competidores:**

- Creciente interés en hogares inteligentes.
- Monitoreo avanzado y modificable que se le proporciona a los usuarios.
  
**Estrategias y tácticas a nuestras oportunidades:**
**Estrategias:** 

- Compra/venta de productos: Se pueden ofrecer productos como pesceras a nivel de usuarios especializados.
- Anticipación de tendencias y conceptos: Se puede identificar las nuevas tendencias y promoverlas en la plataforma.
  
**Tácticas:**

- Integrar asistentes de voz e IA.
- Establecer el producto físico como el más completo.
- Implementar nuevos sensores de monitoreo para el ambiente, no solo la pescera.

**Amenazas de nuestros competidores:**

- Competencia entre marcas de acuarios innovando en la tecnología, crecimiento de la IA, variedad de costos en el mercado.
- Competencia tanto online como en el mercado retail.
  
**Estrategias y tácticas a nuestras amenazas:**
**Estrategias:** 

- Adaptabilidad: Debemos ser capaces de ajustar la oferta, limitar lo esencial a la plataforma.
- Seguridad: Se debe incluir un sistema de seguridad eficiente.
- Disponibilidad: Debe utilizarse con normalidad sin resaltar defectos por parte del sistema.
  
**Tácticas:**
- Implementar un sistema de recompensa.
- Establecernos como la plataforma que monitorea todos los aspectos.

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

Con el objetivo de comprender las necesidades, frustraciones, comportamientos y expectativas de los usuarios objetivo del sistema FeedGuard, se diseñó una guía de entrevistas semiestructurada dirigida a **productores acuícolas semiindustriales**. Estas entrevistas permitirán construir perfiles de usuario (User Personas) representativos y definir con mayor claridad las funcionalidades de la solución IoT.

Las entrevistas se dividen en 4 bloques temáticos: **Datos personales y productivos**, **Proceso de alimentación actual**, **Monitoreo ambiental**, y **Tecnología y disposición al cambio**.

### 🎯 Objetivo de la entrevista

Recolectar información cualitativa sobre la operación acuícola, métodos actuales de alimentación, monitoreo ambiental, percepción de la tecnología y disposición a adoptar una solución automatizada como FeedGuard.

### 📋 Guía de preguntas

#### 1. Datos personales y productivos

- ¿Cuál es su nombre y edad?
- ¿Dónde está ubicada su piscigranja?
- ¿Qué especie cultiva (tilapia, trucha, gamitana, etc.)?
- ¿Cuántos estanques opera actualmente?
- ¿Desde hace cuánto tiempo se dedica a la acuicultura?
- ¿Cuántas personas trabajan en la operación?
- ¿Qué tipo de formación o experiencia tiene en este rubro?

#### 2. Proceso de alimentación actual

- ¿Cómo se realiza actualmente la alimentación de los peces?
- ¿Cuántas veces al día alimenta y en qué horarios?
- ¿Cómo decide la cantidad de alimento que les da?
- ¿Qué sucede si un día no puede alimentar en el horario previsto?
- ¿Ha tenido problemas de sobrealimentación o desperdicio?
- ¿Qué indicadores usa para saber si los peces están comiendo bien?

#### 3. Monitoreo ambiental y toma de decisiones

- ¿Monitorea parámetros del agua como oxígeno o amonio? ¿Con qué frecuencia?
- ¿Tiene sensores o lo hace de forma manual?
- ¿Alguna vez ha tenido pérdidas por mala calidad del agua?
- ¿Qué tan fácil o difícil es mantener el agua en condiciones óptimas?

#### 4. Tecnología, percepción y adopción

- ¿Ha usado alguna tecnología automatizada para alimentar?
- ¿Qué herramientas digitales utiliza en su trabajo? (Apps, redes, sensores, etc.)
- ¿Le interesaría automatizar el proceso de alimentación si esto le ahorra alimento y trabajo?
- ¿Qué necesitaría una herramienta tecnológica para que usted la use sin complicaciones?
- ¿Qué desconfianza tendría respecto a un sistema automatizado?
- ¿Cuánto estaría dispuesto a invertir en una solución que mejore su eficiencia?

---

### 📝 Datos complementarios a recolectar

Además de las respuestas a las preguntas, durante cada entrevista se deben registrar los siguientes datos del participante:

- **Género**: Masculino, femenino u otro.
- **Edad**: Número de años cumplidos.
- **Nivel educativo**: Primaria, secundaria, formación técnica o educación superior.
- **Tecnología que utiliza habitualmente**: Por ejemplo, celular, laptop, o ninguna herramienta digital.
- **Canales digitales que usa con frecuencia**: Como WhatsApp, Facebook u otras plataformas de comunicación.
- **Tiempo promedio dedicado diariamente al monitoreo de los estanques**: Expresado en horas por día.

#### 2.2.2. Registro de entrevistas

#### 2.2.2. Registro de entrevistas

**Entrevista a piscicultores**
|**Nombre del entrevistado**|**Sebastian Pacheco**|
|:-|:-|
|Edad|23 años|
|Profesión|Psicicultor|
|Departamento|Lima, Peru|
|Duración 00:0-8:43|Como primer entrevistado tenemos a Sebastian Pacheco, él es un piscicultor rural cuya granja se encuentra en Qulmana, Cañete. Cultiva tolapia roja y paco en menor escala. Nos menciona que posee un alimentador automático casero que armo con Arduino. Este alimenta a los peces 3 veces por día. Para el cálculo y registro de la alimentacion de los peces usa la herramienta Excel. Como indicadores paa saber si los peces estan comiendo bien califica la velocidad de consumoo, residuos en el fondo, reaccion cuando se aproxima a la granja de peces y la temperatura. Incluyendo el monitoreo de oxígeno y amonio constantemente. Actualmente posee una aplicación móvil que le avisa cuando baja el nivel de agua. Utiliza Whatsapp para ventas, Youtube para aprender y Drive para su registro. Él desearía que el sistema no falle o no avise sobre un evento. Estaría dispuesto a invertir entre 1500 y 2000 soles por una solución más completa.|

**Entrevista a piscicultores**
|**Nombre del entrevistado**|**Andre Bernaola**|
|:-|:-|
|Edad|24 años|
|Profesión|Psicicultor|
|Departamento|Lima, Peru|
|Duración 8:43-13:45|Andre Bernaola es un pisciultor rural que cría anguílas en agua salada. Menciona que no posee un control de la cantidad especifica de alimento que le brinda a su cultivo. Se les alimenta 2 veces durante un día. El desea saber cómo se puede verificar el nivel tanto de oxígeno y calidad del agua para poder proceder a un cambio y así las anguílas puedan prosperar en un buen ambiente. Utiliza Whatsapp para el contacto con proveedores y ventas. Esta muy interesado en usar una aplicación que lo ayuden con el monitoreo. El desearía que la aplicación posea monitoreo de oxígeno, cantidad de anguílas y datos que lo ayuden a mejorar su piscigranja. Estaría dispuesto a invertir 40 soles mensuales en una solución completa.|

**Entrevista a piscicultores**
|**Nombre del entrevistado**|**Alberto Martinez**|
|:-|:-|
|Edad|24 años|
|Profesión|Psicicultor|
|Departamento|Lima, Peru|
|Duración 13:45-17:55| Alberto es un pisciultor experimentado que ya posee dispositivos de monitoreo para sus piscigranjas. Cría salmon en agua salada, carpas y tilapias. Con uno de sus dispositivos de Arduino, él ya puede saber la cantidad exacta de alimento que les va a proveer, con los demás registra el nivel de oxígeno, amonio y de residuos que perjudiquen a su cultivo; esto lo ayuda a decidir cuando hay un cambio de agua en sus piscigranjas. Utiliza Whatsapp e Instagram para el contacto con proveedores y para realizar sus ventas. Se encuentra interesado en usar una aplicación que reúna todas las características que sus dispositivos indican. El desearía que la aplicación posea una sección donde pueda colocar sus anotaciones. Estaría dispuesto a invertir 50 soles mensuales para una solución que reúna todas las características de sus ya existentes dispositivos Arduino. |

**Entrevista a piscicultores**
|**Nombre del entrevistado**|**Rosa Nuñez**|
|:-|:-|
|Edad|24 años|
|Profesión|Psicicultor|
|Departamento|Lima, Peru|
|Duración 17:55-23:40| Rosa es una piscicultora cuya piscigranja se encuentra en Junín. Para sus cultivos de salmón, ella trabaja con dos personas para la administración de 3 estanques. Ella no posee experiencia previa puesto a que es un negocio familiar, alimenta a los peces dependiendo del tamaño del pez y a veces, no lo hace. Posee un dispensador automático para la alimentación, también para la salud del agua de los estanques utiliza un medido portátil. Hubieron ocasiones donde sus peces morían debido a falta de oxígeno. Cuando hace calor o llueve se complica el mantener una excelente calidad del agua. Utiliza Whatsapp para el contacto externo como ventas. Ella quisiera que hubiera una sección de notificaciones en la aplicación que utilize.|

**Entrevista a piscicultores**
|**Nombre del entrevistado**|**Sebastian Vargas**|
|:-|:-|
|Edad|26 años|
|Profesión|Psicicultor|
|Departamento|Lima, Peru|
|Duración 23:40- 29:22| Sebastian Vargas tiene 26 años, es un pisciultor experimentado que ya posee dispositivos de monitoreo para sus piscigranjas. Cría salmon en agua salada y carpas en 6 estanques. Se dedica al rubro hace 3 años, hay 3 personas que trabajan con él, su experiencia como tecnico apicultor le permitió entrar a la apicultura. Alimenta a sus peces 3 veces al día: 7am, 1 pm y 5:30pm. Para saber la cantidad de alimento utiliza una biomasa estimada, cuando no puede alimentar en el horaio previsto cuenta con un dispensador automático.A veces se le tapa la boquilla del dosificador, para saber el estado de los peces observa la velocidad de consumo y residuos en el estanque. Utiliza Whatsapp e Instagram para el contacto con proveedores y para realizar sus ventas. Se encuentra interesado en usar una aplicación que reúna todas las características que sus dispositivos indican. El desearía que la aplicación posea una sección donde pueda colocar sus anotaciones. Estaría dispuesto a invertir 50 soles mensuales para una solución que reúna todas las características de sus ya existentes dispositivos Arduino. |

**Entrevista a piscicultores**
|**Nombre del entrevistado**|**Bryan Palma**|
|:-|:-|
|Edad|25 años|
|Profesión|Psicicultor|
|Departamento|Lima, Peru|
|Duración 29:22-34:29| Bryan Palma es un pisciultor  de 25 años experimentado puesto que ya cuenta con dispositivos que lo ayudan en su pisigranja. Cría salmon en agua salada y tilapia roja en 3 estanques, cada uno con su dispensador y aireación. Con uno de sus dispositivos de Arduino, él ya puede saber la cantidad exacta de alimento que les va a proveer, con los demás registra el nivel de oxígeno, amonio y de residuos que perjudiquen a su cultivo; esto lo ayuda a decidir cuando hay un cambio de agua en sus piscigranjas. Utiliza Whatsapp para la relación con los proveedores, Facebook para ventas locales, Youtube para aprender y Drive para el registro de la producción. Se encuentra interesado en usar una aplicación que posea un dashboard con indicadores de alerta y conectividad estable. El desearía que la aplicación posea una sección donde pueda colocar sus anotaciones. Estaría dispuesto a invertir 65 soles mensuales para una solución que reúna todas las características de sus ya existentes dispositivos Arduino. |

#### 2.2.3. Análisis de entrevistas

**Piscicultor técnico**

El 100% de los piscicultores rurales indicaron que le gista la acuicultura y como es su principal fuente de ingresos. El 100% reconoció que la tecnología será clave para la automatización de procesos. Se presentó interés en conseguir una aplicación, con tal de que abarque todas las funcionalidades dentro del sistema  de monitoreo.

**Piscicultor rural**

Entre los piscicultres entrevistado, el 80% indica que los acuicultores rurales entrevistados mencionaron que le gusta relizar monitoreo. Solo 20% de los entrevistados ha utillizado sensores electrónicos para controlar parámetros físicos. A pesar de la carga, el 100% de los piscicultors expresó interés en la solución total. Que la herramienta incluya una función del registro y anotaciones para poder  tener control de los parámetros. Finalmente el 100% estaria dispuesto a invertir como mínimo 40 soles mensuales.

### 2.3. Needfinding

A continuación, se detallan los principales artefactos elaborados en esta fase del proyecto.

#### 2.3.1. User Personas

Con base en el análisis de entrevistas realizadas a representantes de los segmentos objetivo, se han definido dos **User Personas** representativos del ecosistema productivo de la acuicultura semiindustrial.

- **Persona 1**, Juan
  <img src="Assets\UserPersonas\Juan, piscicultor rural.png"/>

- **Persona 2**, Bryan
  <img src="Assets\UserPersonas\Bryan, piscicultor técnico.png"/>

Estos arquetipos nos permiten modelar comportamientos, motivaciones y necesidades clave que serán consideradas a lo largo del diseño de la solución.

#### 2.3.2. User Task Matrix

| Task Matrix                                                         | Piscicultores rural Frecuencia | Piscicultores rural Importancia | Piscicultores técnico Frecuencia | Piscicultores técnico Importancia |
|----------------------------------------------------------------|:------------------------:|:-----------------------:|:------------------------:|:-----------------------:|
| 1. Aumentar la eficiencia de su operación                      |           Alta           | Alta                    | Alta                     | Alta                    |
| 2. Monitorear niveles de la piscigranja                        |           Alta           | Alta                   | Alta                     | Media                   |
| 3. Reducir el desperdicio de recursos                          |           Alta           | Alta                   | Alta                     | Alta                    |
| 4. Anotar actividades y datos sobre su trabajo                 |           Media           | Alta                    | Alta                     | Alta                    |
| 5. Contar la cantidad de cultivos que posee                    |           Media           | Alta                    | Media                    | Media                   |
| 6. Monitorear el ciclo de vida del cultivo completo en la piscigranja|           Alta           | Alta                   | Alta                     | Alta                    |
| 7. Tomar decisiones en base a datos brindados                  |           Media           | Alta                    | Alta                    | Alta                   |
| 8. Estar alerta en caso de escasez o excedente de recursos     |           Alta           | Alta                    | Media                    | Alta                   |
| 9. Intentar automatizar el proceso                             |           Baja           | Media                    | Alta                    | Alta                   |


- **Juan** prioriza tareas manuales como la dosificación y supervisión visual, con poco uso de registros o análisis digital.
- **Bryan**, en cambio, tiene una visión más analítica: mide constantemente, registra sus datos y busca optimizar con base en evidencia técnica.

También se observa que **Bryan valora mucho la automatización y el uso de sensores**, mientras que **Juan necesita confianza y simplicidad** para adoptar nuevas herramientas.

**Piscicultores rurales**
Los piscicultores rurales priorizan la eficiencia operativa, el monitoreo constante de las  condiciones de la granja y la reducción de desperdicio de recursos. También se observa un alto valor otorgado a registrar actividades y datos. Aunque la automatización no esta entre su foco principal, muestra interés en la toma de decisiones a partir de datos.

**Piscicultores técnicos**

Los piscicultores técnicos, por otro lado, muestran un enfoque más avanzado y estratégico en la gestión de sus operaciones. Junto con la eficiencia, valoran altamente la automatización de procesos y el uso de datos para la toma de decisiones. Aunque el monitoreo constante sigue siendo frecuente, su importancia rapida más en los aspectos técnicos y analíticos. La anotación de datos son prácticas clave en este segmento.


#### 2.3.3. User Journey Mapping
Se construyeron los **User Journey Maps** (estado actual - *As-Is*) para cada User Persona. A continuación, se resumen las fases clave del proceso diario:

**Piscicultores rurales**

<img src="Assets/miro_user_journey_map_rural.jpg"/>

Link: https://miro.com/app/board/uXjVI-Kzxf8=/?share_link_id=977489618547

**Piscicultores técnicos**

<img src="Assets/miro_user_journey_map_tec.jpg"/>

Link: https://miro.com/app/board/uXjVI-Kzxf8=/?share_link_id=977489618547


#### 2.3.4. Empathy Mapping

**Piscicultores rurales**

<img src="Assets/miro_empathy1.jpg"/>

Link: https://miro.com/app/board/uXjVI-Kzxf8=/?share_link_id=977489618547


**Piscicultores técnicos**

<img src="Assets/miro_empathy2.jpg"/>

Link: https://miro.com/app/board/uXjVI-Kzxf8=/?share_link_id=977489618547

#### 2.3.5. As-is Scenario Mapping

En esta sección se presentan los _As-Is Scenario Mapping_ correspondientes a los dos User Personas definidos: **Juan Pérez** y **Bryan Díaz**. Estos mapas describen el escenario actual de los usuarios, sin la intervención de la solución FeedGuard, y permiten visualizar cómo experimentan su jornada operativa en relación a la alimentación y monitoreo en sistemas acuícolas semiindustriales.

**Piscicultores rurales**

<img src="Assets/miro_asis1.jpg"/>

Link: https://miro.com/app/board/uXjVI-Kzxf8=/?share_link_id=977489618547


**Piscicultores técnicos**

<img src="Assets/miro_asis2.jpg"/>

Link: https://miro.com/app/board/uXjVI-Kzxf8=/?share_link_id=977489618547


### 2.4. Ubiquitous Language

|Término (inglés)|Término (español)|Definición|
|-|-|-|
|Fish Farmer|Piscicultor|Persona responsable por la gestión de la piscigranja.|
|Fish Farm|Piscigranja|Instalación acuícola (natural o artificial) destinada a la crianza de organismos marinos.|
|Pond|Estanque|Donde se cultivan los organismos marinos.|
|Fish Stock|Cultivo de peces|Total de organismos marinos que estan siendo criados en un estanque.|
|Feeding time|Tiempo de alimentación|Momento determinado del día en el que se alimenta a los organismos marinos.|
|Feed distribution|Distribución de alimento|Acción de repartir el alimento para organismos marinos sobre el estanque.|
|Water Quality|Calidad del agua|Medición de las condiciones del agua, considerando oxígeno, pH, temperatura y químicos que afectan la salud de los peces.|
|Contamined water|Agua contaminada|Agua que no es adecuada para los peces debido a los desechos o químicos.|
|Oxygen level|Nivel de oxígeno|Cantidad de oxígeno disuelto en el agua.|
|Ammonia level|Nivel de amoniaco|Sistancia producida por los desechos de los peces que puede resultar tóxica en altas concentraciones.|
|Daily routine|Rutina diaria|Actividades realizadas o por realizar en un día en la piscigranja.|


## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping

En esta sección se presentan los **To-Be Scenario Mapping** elaborados para cada uno de los segmentos objetivo identificados: **Juan Pérez** (piscicultor rural, tradicional) y **Bryan Díaz** (piscicultor técnico, innovador).  
Cada mapa refleja cómo la solución FeedGuard transforma la experiencia diaria de los usuarios, detallando las fases principales de su jornada y describiendo, para cada una, lo que hacen (Doing), piensan (Thinking) y sienten (Feeling) con la incorporación de la tecnología.

El proceso de construcción de estos mapas incluyó sesiones de lluvia de ideas, revisión de los recorridos actuales (As-Is), identificación de fases clave y validación de los cambios esperados.  
A continuación, se presenta el To-Be Scenario Mapping para cada segmento objetivo, permitiendo comparar claramente la evolución respecto al escenario actual y evidenciar los beneficios de la solución propuesta.

### To-Be Scenario Mapping – Juan Pérez

<img src="Assets\To-BeMapping\Juan-ToBe.png">

### To-Be Scenario Mapping – Bryan Díaz

<img src="Assets\To-BeMapping\Bryan-ToBe.png"/>

### 3.2. User Stories

Los User Stories sirven para describir de manera más detallada las diferentes funciones de la aplicación, adaptándolas a las necesidades y prioridades de los usuarios. Estas historias también capturan el propósito de uso de las personas, brindando una comprensión más completa de cómo se relacionan con la aplicación y qué esperan lograr con ella.

**Epic Stories**
<table>
  <thead>
    <tr>
      <th>Epic / Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>EP01</td>
      <td>Landing Page</td>
      <td>
  <strong>Descripción:</strong> Como piscicultor, deseo que la landing page comunique claramente los beneficios de FeedGuard y cómo puede ayudarme a optimizar la alimentación y el monitoreo en mi piscigranja.<br><br>
  Como usuario interesado, deseo entender rápidamente cómo FeedGuard automatiza procesos críticos, reduce desperdicios y mejora la eficiencia en la acuicultura.<br><br>
  Como cliente potencial, deseo poder acceder fácilmente a información sobre las funcionalidades principales, casos de éxito y cómo comenzar a usar el sistema.<br><br>
  <strong>Technical Stories:</strong><br>
  - Como desarrollador, deseo implementar una landing page responsiva y optimizada para SEO, para atraer y convertir visitantes.<br>
  - Como desarrollador, deseo mostrar testimonios y casos de éxito en la landing page, para aumentar la confianza de los usuarios.<br>
  - Como desarrollador, deseo asegurar que la landing page cargue rápidamente y sea accesible desde cualquier dispositivo.
</td>
    </tr>
    <tr>
      <td>EP02</td>
      <td>Onboarding de Usuario y Configuración de Granja</td>
      <td>
        <strong>Descripción:</strong> Como nuevo usuario, deseo poder registrarme fácilmente en la plataforma FeedGuard y configurar la información básica de mi piscigranja (nombre, ubicación, número de estanques, especies de peces) para comenzar a utilizar el sistema.<br><br>
        Como técnico de campo, deseo poder agregar y configurar los dispositivos IoT (sensores, alimentadores) asociados a cada estanque para que la plataforma pueda recopilar datos y enviar comandos.<br><br>
        Como administrador, deseo tener herramientas para gestionar las cuentas de usuario y la información general de las piscigranjas.<br><br>
        <strong>Technical Stories:</strong><br>
        - Como desarrollador, deseo implementar un flujo de registro y login seguro para nuevos usuarios.<br>
        - Como desarrollador, deseo crear interfaces para la configuración de la información de la granja y los estanques.<br>
        - Como desarrollador, deseo implementar la lógica para asociar dispositivos IoT específicos a estanques.<br>
        - Como desarrollador, deseo asegurar la validación de la información ingresada por el usuario.
      </td>
    </tr>
    <tr>
      <td>EP03</td>
      <td>Monitoreo Ambiental en Tiempo Real</td>
      <td>
        <strong>Descripción:</strong> Como piscicultor, deseo poder visualizar en tiempo real los datos de los sensores ambientales de mis estanques (oxígeno disuelto, temperatura, pH, etc.) para estar informado de las condiciones del agua.<br><br>
        Como técnico de campo, deseo poder acceder a gráficos históricos de los parámetros ambientales para identificar tendencias y posibles problemas.<br><br>
        Como usuario, deseo recibir alertas automáticas cuando los parámetros ambientales se salgan de los rangos óptimos definidos para mis especies.<br><br>
        <strong>Technical Stories:</strong><br>
        - Como desarrollador, deseo implementar la recepción y almacenamiento de datos de los sensores IoT en tiempo real.<br>
        - Como desarrollador, deseo crear interfaces visuales (tableros, gráficos) para mostrar los datos ambientales en tiempo real e históricos.<br>
        - Como desarrollador, deseo implementar la lógica para la definición de reglas de alerta basadas en rangos de parámetros.<br>
        - Como desarrollador, deseo implementar el sistema de notificaciones (push, email) para enviar alertas a los usuarios.
      </td>
    </tr>
  </tbody>
</table>


<table border="1" cellspacing="0" cellpadding="5" style="border-collapse: collapse; width: 100%;">
  <tr>
    <th>Epic / Story ID</th>
    <th>Título</th>
    <th>Descripción</th>
    <th>Criterios de<br>Aceptación</th>
    <th>Relacionado<br>con (Epic ID)</th>
  </tr>
  <tr>
      <td>HU1</td>
      <td>Visualización de Servicios Destacados</td>
      <td>Como cliente, quiero ver los servicios legales más destacados en la landing page para entender rápidamente cómo la plataforma puede ayudarme a resolver mis problemas legales.</td>
      <td>
        <strong>Scenario 1:</strong> Visualización de Servicios Destacados<br>
        GIVEN un cliente potencial visitando la landing page<br>
        WHEN accede al sitio web<br>
        THEN se muestran los servicios legales más relevantes y populares en un formato atractivo, organizado por categorías para facilitar la navegación<br>
        AND puede hacer clic directamente en los servicios para obtener más información.<br><br>
        <strong>Scenario 2:</strong> No hay servicios destacados disponibles<br>
        GIVEN un cliente potencial accediendo a la landing page<br>
        WHEN no hay servicios destacados disponibles<br>
        THEN se muestra un mensaje indicando que los servicios se actualizarán pronto<br>
        AND se ofrece la opción de registrarse para recibir notificaciones sobre los nuevos servicios.
      </td>
      <td>EP01</td>
    </tr>
    <tr>
  <td>HU2</td>
  <td>Testimonios de Usuarios Satisfechos</td>
  <td>Como piscicultor, quiero leer testimonios de otros usuarios satisfechos en la landing page para sentirme más confiado al considerar la solución, lo que me ayudará a tomar una decisión informada.</td>
  <td>
    <strong>Scenario 1:</strong> Visualización de Testimonios<br>
    GIVEN un piscicultor potencial interesado en FeedGuard<br>
    WHEN navega por la landing page<br>
    THEN se muestra una sección con testimonios auténticos de usuarios satisfechos, ordenados por relevancia<br>
    AND puede filtrar los testimonios por tipo de piscigranja o beneficio obtenido.<br><br>
    <strong>Scenario 2:</strong> No hay testimonios disponibles<br>
    GIVEN un piscicultor potencial buscando opiniones en la landing page<br>
    WHEN no hay testimonios disponibles<br>
    THEN se muestra un mensaje indicando que pronto se publicarán nuevos testimonios<br>
    AND se invita al usuario a contactar con el equipo para más información.
  </td>
  <td>EP01</td>
</tr>
<tr>
  <td>HU3</td>
  <td>Acceso Rápido a Funcionalidades Clave</td>
  <td>Como piscicultor, quiero tener accesos rápidos a las funcionalidades principales desde la landing page para encontrar fácilmente lo que necesito, sin tener que hacer clics innecesarios.</td>
  <td>
    <strong>Scenario 1:</strong> Acceso Rápido desde la Landing Page<br>
    GIVEN un piscicultor potencial explorando el sitio web<br>
    WHEN llega a la landing page<br>
    THEN se muestran accesos directos claros a funcionalidades clave como registro, contacto y casos de éxito, con un diseño intuitivo y responsivo<br>
    AND puede realizar una acción en 3 clics o menos.<br><br>
    <strong>Scenario 2:</strong> No hay accesos rápidos disponibles<br>
    GIVEN un piscicultor potencial buscando funcionalidades clave<br>
    WHEN no se muestran accesos rápidos en la landing page<br>
    THEN el usuario puede navegar a través del menú principal para acceder a las funcionalidades deseadas<br>
    AND se le informa de los accesos disponibles en otras secciones.
  </td>
  <td>EP01</td>
</tr>
<tr>
  <td>HU4</td>
  <td>Información Clara y Concisa sobre FeedGuard</td>
  <td>Como piscicultor, quiero encontrar una descripción clara y concisa de FeedGuard en la landing page para entender de qué se trata la solución sin complicaciones.</td>
  <td>
    <strong>Scenario 1:</strong> Información sobre el Servicio<br>
    GIVEN un piscicultor potencial sin experiencia previa con FeedGuard<br>
    WHEN accede a la landing page<br>
    THEN se presenta una descripción clara y simple de los servicios y beneficios de FeedGuard<br>
    AND puede acceder a más información sin tener que navegar por varias páginas.<br><br>
    <strong>Scenario 2:</strong> No se muestra la información clara<br>
    GIVEN un piscicultor potencial buscando más información<br>
    WHEN la descripción no es clara o está incompleta<br>
    THEN el usuario puede contactar al equipo para obtener más detalles<br>
    AND se le ofrece una guía o página de preguntas frecuentes.
  </td>
  <td>EP01</td>
</tr>
<tr>
  <td>HU5</td>
  <td>Diseño Atractivo y Responsivo</td>
  <td>Como piscicultor, quiero que la landing page tenga un diseño atractivo y sea responsivo para una experiencia de usuario agradable desde cualquier dispositivo.</td>
  <td>
    <strong>Scenario 1:</strong> Diseño de la Landing Page<br>
    GIVEN un piscicultor potencial utilizando diferentes dispositivos<br>
    WHEN visita la landing page<br>
    THEN la página se adapta perfectamente al dispositivo, con un diseño atractivo que facilita la navegación<br>
    AND las principales funcionalidades son accesibles sin problemas desde móviles y tablets.<br><br>
    <strong>Scenario 2:</strong> Problemas de responsividad<br>
    GIVEN un piscicultor utilizando un dispositivo móvil<br>
    WHEN la página no se adapta correctamente a su pantalla<br>
    THEN el usuario puede informar del problema a través de un formulario de retroalimentación<br>
    AND se le ofrece una versión simplificada de la página para continuar su navegación.
  </td>
  <td>EP01</td>
</tr>
<tr>
  <td>HU06</td>
  <td>Registro Seguro de Usuario</td>
  <td>Como nuevo usuario, quiero registrarme en la plataforma con mi correo electrónico y contraseña de forma segura para poder acceder a las funcionalidades de FeedGuard.</td>
  <td>
    <strong>Scenario 1:</strong> Registro exitoso<br>
    GIVEN un nuevo usuario con un correo válido y una contraseña segura<br>
    WHEN completa el formulario de registro y lo envía<br>
    THEN su cuenta se crea correctamente y puede acceder a la plataforma.<br><br>
    <strong>Scenario 2:</strong> Registro fallido<br>
    GIVEN un usuario que ingresa datos inválidos (correo no válido o contraseña débil)<br>
    WHEN intenta registrarse<br>
    THEN el sistema muestra mensajes de error claros indicando cómo corregir los datos.
  </td>
  <td>EP02</td>
</tr>
<tr>
  <td>HU07</td>
  <td>Configuración Inicial de la Granja</td>
  <td>Como técnico de campo, quiero configurar los detalles de mi granja, incluyendo el nombre, ubicación y número de estanques para poder organizar mis dispositivos y datos.</td>
  <td>
    <strong>Scenario 1:</strong> Configuración completa<br>
    GIVEN un técnico que accede por primera vez a la plataforma<br>
    WHEN completa los datos de su granja y guarda la configuración<br>
    THEN los estanques quedan registrados y visibles en su tablero.<br><br>
    <strong>Scenario 2:</strong> Datos incompletos<br>
    GIVEN un técnico que omite campos obligatorios<br>
    WHEN intenta guardar<br>
    THEN el sistema le indica qué campos debe completar.
  </td>
  <td>EP02</td>
</tr>
<tr>
  <td>HU08</td>
  <td>Vinculación de Dispositivos IoT</td>
  <td>Como técnico, quiero vincular cada sensor y alimentador IoT específico a un estanque dentro de la plataforma para que los datos y las acciones se asocien correctamente.</td>
  <td>
    <strong>Scenario 1:</strong> Vinculación exitosa<br>
    GIVEN un técnico con dispositivos IoT previamente configurados<br>
    WHEN selecciona un estanque y asigna un dispositivo<br>
    THEN el dispositivo queda vinculado y comienza a transmitir datos.<br><br>
    <strong>Scenario 2:</strong> Error en vinculación<br>
    GIVEN un dispositivo que ya está vinculado a otro estanque<br>
    WHEN se intenta vincular de nuevo<br>
    THEN el sistema notifica que el dispositivo ya está en uso y no permite duplicación.
  </td>
  <td>EP02</td>
</tr>
<tr>
  <td>HU09</td>
  <td>Visualización de Parámetros en Tiempo Real</td>
  <td>Como piscicultor, quiero ver los valores actuales de oxígeno disuelto, temperatura y pH para cada uno de mis estanques en un panel principal para tener una visión general rápida de las condiciones.</td>
  <td>
    <strong>Scenario 1:</strong> Panel actualizado<br>
    GIVEN un piscicultor en su tablero principal<br>
    WHEN consulta el estado de sus estanques<br>
    THEN ve en tiempo real los valores actuales de los parámetros para cada estanque.<br><br>
    <strong>Scenario 2:</strong> Falta de datos<br>
    GIVEN una pérdida de conexión temporal con un sensor<br>
    WHEN intenta ver los valores<br>
    THEN el sistema indica que los datos están temporalmente no disponibles.
  </td>
  <td>EP03</td>
</tr>
<tr>
  <td>HU10</td>
  <td>Gráficos Históricos de Parámetros Ambientales</td>
  <td>Como técnico, quiero visualizar gráficos históricos de los parámetros ambientales durante las últimas 24 horas para identificar fluctuaciones o tendencias inusuales.</td>
  <td>
    <strong>Scenario 1:</strong> Análisis de datos<br>
    GIVEN un técnico en el módulo de monitoreo<br>
    WHEN selecciona un estanque<br>
    THEN puede ver gráficos con la evolución de temperatura, oxígeno y pH de las últimas 24 horas.<br><br>
    <strong>Scenario 2:</strong> Rangos anormales<br>
    GIVEN que existen variaciones inusuales en los datos<br>
    WHEN se visualizan los gráficos<br>
    THEN el sistema destaca automáticamente los valores fuera del rango normal.
  </td>
  <td>EP03</td>
</tr>
<tr>
  <td>HU11</td>
  <td>Alertas por Parámetros Fuera de Rango</td>
  <td>Como usuario, quiero definir rangos óptimos para cada parámetro ambiental por especie de pez y recibir una notificación si alguno de los valores se sale de ese rango para poder tomar medidas correctivas.</td>
  <td>
    <strong>Scenario 1:</strong> Configuración de alertas<br>
    GIVEN un usuario que ha ingresado los rangos óptimos por especie<br>
    WHEN un parámetro se desvía<br>
    THEN el sistema le envía una notificación instantánea.<br><br>
    <strong>Scenario 2:</strong> Personalización de rangos<br>
    GIVEN un usuario con múltiples especies<br>
    WHEN configura los rangos para cada estanque<br>
    THEN puede personalizar los umbrales según la especie presente.
  </td>
  <td>EP03</td>
</tr>
<tr>
  <td>HU12</td>
  <td>Recomendaciones de Alimentación Basadas en Tendencias Históricas</td>
  <td>Como piscicultor quiero recibir recomendaciones automáticas de dosificación de alimento basadas en el análisis de datos históricos de crecimiento y consumo Para optimizar la alimentación y maximizar la tasa de conversión alimenticia.</td>
  <td>
    <strong>Scenario 1:</strong>Mostrar recomendación diaria<br>
    GIVEN que tengo al menos 7 días de datos históricos en FeedGuard<br>
    WHEN entro en la sección de “Recomendaciones”<br>
    THEN el sistema muestra una sugerencia diaria de cantidad de alimento por estanque basada en patrones anteriores.<br><br>
    <strong>Scenario 2:</strong> Programar dosificación automática<br>
    GIVEN que acepto la recomendación<br>
    WHEN confirmo en el panel<br>
    THEN FeedGuard programa el dosificador para la siguiente alimentación automática.
  </td>
  <td>EP03</td>
</tr>
<tr>
  <td>HU13</td>
  <td>Mantenimiento Predictivo de Equipos IoT</td>
  <td>Como técnico de campo Quiero recibir alertas tempranas de posibles fallos o calibraciones necesarias en sensores y alimentadores Para programar mantenimiento antes de que ocurra una interrupción.</td>
  <td>
    <strong>Scenario 1:</strong>Alerta por deriva de sensor<br>
    GIVEN que un sensor muestra lecturas atípicas (deriva > 10% frente a su historial)<br>
    WHEN el sistema detecta la anomalía<br>
    THEN envía notificación al técnico con descripción del problema y sugerencia de calibración.<br><br>
    <strong>Scenario 2:</strong> Registro de mantenimiento completado<br>
    GIVEN que confirmo la intervención en el sistema<br>
    WHEN completo la reparación o calibración<br>
    THEN el estado del dispositivo vuelve a “Óptimo” y se registra la fecha de mantenimiento.
  </td>
  <td>EP02</td>
</tr>
<tr>
  <td>HU14</td>
  <td>Gestión Avanzada de Roles y Permisos</td>
  <td>Como administrador de FeedGuard Quiero asignar distintos roles (piscicultor, técnico, auditor) con permisos específicos sobre módulos de la plataforma Para controlar el acceso y asegurar la integridad de los datos.</td>
  <td>
    <strong>Scenario 1:</strong>Asignación granular de permisos<br>
    GIVEN que estoy en el módulo de “Usuarios”<br>
    WHEN creo o edito una cuenta<br>
    THEN puedo seleccionar uno de los roles predefinidos con permisos granulares en lectura de datos, configuración de alertas y generación de reporte.<br><br>
    <strong>Scenario 2:</strong> Acceso limitado para rol Auditor<br>
    GIVEN un usuario con rol “Auditor”<br>
    WHEN accede al tablero<br>
    THEN ve solamente reportes y métricas, sin acceso a configuración ni acciones de control.
  </td>
  <td>EP02</td>
</tr>
<tr>
  <td>HU15</td>
  <td>Exportación de Reportes para Análisis Externo</td>
  <td>Como piscicultor o técnico Quiero exportar mis datos de parámetros y alimentación en formatos CSV o PDF Para analizarlos con herramientas externas o compartirlos con consultores.</td>
  <td>
    <strong>Scenario 1:</strong>Exportación en CSV<br>
    GIVEN que estoy en la sección de “Reportes”<br>
    WHEN elijo un rango de fechas y el formato CSV<br>
    THEN el sistema genera y descarga el archivo con los datos correctamente delimitados y codificados en UTF-8.<br><br>
    <strong>Scenario 2:</strong>Exportación en PDF<br>
    GIVEN que selecciono formato PDF y rango de fechas<br>
    WHEN la descarga se completa<br>
    THEN el documento incluye encabezados con nombre de la granja, fecha de generación y leyendas de cada columna.
  </td>
  <td>EP03</td>
</tr>
<tr>
  <td>HU16</td>
  <td>Configuración de Alertas por Tendencias y Predicciones</td>
  <td>Como piscicultor semiindustrial Quiero definir alertas no solo por umbrales puntuales, sino también por cambios porcentuales y predicciones de riesgo Para anticiparme a variaciones críticas en la calidad del agua.</td>
  <td>
    <strong>Scenario 1:</strong>Alerta por variación porcentual<br>
    GIVEN que configuro una alerta del tipo “Aumento > 15% de amonio en 2 horas”<br>
    WHEN el sistema detecta esa variación<br>
    THEN envía notificación inmediata con historial de valores y gráfico de tendencia.<br><br>
    <strong>Scenario 2:</strong>Gestión de alertas resueltas<br>
    GIVEN la alerta se dispara<br>
    WHEN accedo a la sección de alertas<br>
    THEN puedo marcarla como “Resuelta” o “Ignorada” y agregar comentarios.
  </td>
  <td>EP03</td>
</tr>
</table>

### 3.3. Impact Mapping

En esta sección se presentan los **Impact Mapping** desarrollados para cada uno de los segmentos objetivo identificados: **Juan Pérez** (piscicultor rural, tradicional) y **Bryan Díaz** (piscicultor técnico, innovador).  
El Impact Mapping fue clave para alinear las funcionalidades de FeedGuard con los objetivos estratégicos del proyecto, permitiendo visualizar de manera clara cómo las acciones y cambios de comportamiento de cada usuario contribuyen al logro de los resultados esperados.

El proceso de construcción de estos mapas incluyó sesiones colaborativas de análisis, identificación de objetivos, actores, impactos y entregables clave, asegurando que cada funcionalidad propuesta responda a necesidades reales detectadas en la investigación.  

A continuación, se presentan los Impact Mapping para cada segmento objetivo, facilitando la comparación de los caminos de valor y el impacto esperado de la solución en cada perfil de usuario.

#### Impact Mapping – Juan Pérez (Piscicultor rural, tradicional)

<img src="Assets\impactMapping\im-juan.png">

#### Impact Mapping – Bryan Díaz (Piscicultor técnico, innovador)

<img src="Assets\impactMapping\im-bryan.png"/>

### 3.4. Product Backlog

<table border="1" cellspacing="0" cellpadding="5" style="border-collapse: collapse; width: 100%;">
  <tr>
    <th># Orden</th>
    <th>User Story Id</th>
    <th>Titulo</th>
    <th>Descripcion</th>
    <th>Story Points<br>(1/2/3/5/8)</th>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

## Capítulo IV: Solution Software Design

### 4.1. Strategic-Level Domain-Driven Design
#### 4.1.1. EventStorming
##### 4.1.1.1. Candidate Context Discovery

Durante la sesión de EventStorming realizada, se llevó a cabo un proceso de análisis para descubrir los **Bounded Contexts** naturales del sistema FeedGuard.  
Se utilizó la técnica **start-with-value**, priorizando aquellas partes del dominio que representan el mayor valor para el negocio, como la alimentación automática basada en parámetros ambientales críticos.


<img src="Assets\EventStorming\Untitled - Frame 2.jpg">

<img src="Assets\EventStorming\Untitled - Frame 3.jpg">

<img src="Assets\EventStorming\Untitled - Frame 5.jpg">




##### 4.1.1.2. Domain Message Flows Modeling

Posteriormente, se trabajó en la visualización de los **flujos de mensajes** entre los bounded contexts identificados.

Se identificaron los siguientes principales flujos de colaboración:

- **Monitoring Context** captura datos de sensores en tiempo real y notifica a:
  - **Alerting Context** si los valores exceden los límites críticos.
  - **Feeding Context** para ajustar dinámicamente el plan de alimentación basado en las condiciones del agua.

- **Alerting Context** genera alertas y las transmite hacia:
  - **User Interface Context**, que muestra la alerta al usuario final.

- **Farm Management Context** proporciona la configuración inicial (granja, estanques, especies) que utilizan los otros contextos como referencia operacional.

Estos flujos definen las dependencias y puntos de integración entre las partes del sistema, reforzando la independencia y el aislamiento de responsabilidades que busca Domain-Driven Design.


##### 4.1.1.3. Bounded Context Canvases
A continuación, se presenta el resumen de los **Bounded Context Canvases** elaborados para cada contexto identificado:

<img src="Assets\EventStorming\Untitled - Frame 6.jpg">

#### Monitoring Context

- **Propósito**:  
Capturar, procesar y almacenar datos ambientales críticos como oxígeno disuelto, temperatura y pH provenientes de sensores instalados en la piscigranja.

- **Responsabilidades**:
  - Recibir datos de sensores en intervalos configurables.
  - Verificar si los datos cumplen los parámetros esperados.
  - Actualizar los registros históricos de calidad del agua.
  - Disparar eventos hacia otros contextos en caso de condiciones anómalas.

- **Entidades principales**:
  - Sensor
  - Estanque
  - Datos de calidad de agua

#### Alerting Context

- **Propósito**:  
Detectar automáticamente condiciones ambientales críticas y generar notificaciones oportunas a los usuarios para tomar acciones correctivas.

- **Responsabilidades**:
  - Evaluar continuamente los datos ambientales recibidos.
  - Comparar con los umbrales configurados para cada especie de pez.
  - Generar y registrar alertas ambientales.
  - Notificar al usuario vía Mobile App o correo electrónico.

- **Entidades principales**:
  - Alerta
  - Notificación

#### Feeding Context

- **Propósito**:  
Gestionar la planificación y ejecución automática del proceso de alimentación, optimizando la cantidad de alimento suministrado según condiciones ambientales y configuraciones del usuario.

- **Responsabilidades**:
  - Permitir a los usuarios definir planes de alimentación.
  - Activar alimentadores automáticos en función de horarios y parámetros ambientales.
  - Adaptar dinámicamente las cantidades suministradas si las condiciones no son óptimas.

- **Entidades principales**:
  - Alimentador
  - Plan de alimentación
  - Evento de dosificación de alimento

#### Farm Management Context

- **Propósito**:  
Administrar los recursos físicos y organizativos de la piscigranja, como estanques, especies de peces y configuraciones generales.

- **Responsabilidades**:
  - Registrar nuevas granjas y estanques.
  - Configurar parámetros ambientales ideales por especie.
  - Asociar sensores y alimentadores a cada unidad de cultivo.
  - Mantener actualizada la información del usuario y la operación.

- **Entidades principales**:
  - Granja
  - Estanque
  - Usuario

#### User Interface Context

- **Propósito**:  
Presentar de forma clara, accesible y amigable toda la información crítica del sistema a los piscicultores y técnicos, facilitando la gestión de su operación desde dispositivos móviles o web.

- **Responsabilidades**:
  - Mostrar en tiempo real los valores de calidad del agua y estado de alimentación.
  - Mostrar alertas críticas de manera priorizada.
  - Permitir configurar parámetros de operación y alimentación.
  - Brindar acceso a históricos y reportes analíticos.

- **Entidades principales**:
  - Dashboard de monitoreo
  - Gestor de alertas

#### 4.1.2. Context Mapping


#### 4.1.3. Software Architecture


##### 4.1.3.1. System Landscape Diagram

##### 4.1.3.2. Context Level Diagrams

El diagrama de contexto de AquaSense Technologies ilustra la interacción entre su AquaSense Platform y las entidades externas que la rodean. Los principales actores (Personas) que interactúan con la plataforma son los Productores Acuícolas, quienes la utilizan para monitorear sus granjas, gestionar la alimentación y recibir alertas, y los Técnicos de Campo, que también interactúan para supervisar las operaciones y responder a las alertas.

La AquaSense Platform se comunica con varios Sistemas de Software Externos para enriquecer su funcionalidad. Obtiene datos meteorológicos del Weather Service y datos de calidad del agua (si utilizan sensores de terceros) del Water Quality Sensor Cloud. La conectividad para los dispositivos IoT se proporciona a través de la Cellular Network. En el futuro, podría haber una integración con un Fish Feed Management System de proveedores o de los propios productores.

En esencia, la AquaSense Platform se sitúa como un sistema central que ayuda a los productores acuícolas a optimizar sus operaciones al integrar datos del entorno, automatizar procesos clave y proporcionar información valiosa a través de una interfaz de usuario accesible.
![ContextDiagram](Assets/c4/context-diagram.png)

##### 4.1.3.3. Container Level Diagrams

El diagrama de contenedores de la **AquaSense Platform** desglosa la arquitectura interna del sistema. El contenedor central es la **AquaSense Platform**, que alberga varios contenedores clave:

* La **Mobile App** proporciona la interfaz de usuario principal para los productores y técnicos.
* La **API Application** actúa como la puerta de enlace central, gestionando la comunicación entre la Mobile App y los bounded contexts.
* Varios **Bounded Contexts** organizan la lógica de negocio en dominios específicos:
  * **Feeding Bounded Context** gestiona la alimentación automatizada.
  * **Monitoring Bounded Context** maneja la ingesta y el procesamiento de datos de sensores.
  * **Farm Management Bounded Context** almacena la información de las granjas, usuarios y configuraciones.
  * **Alerting Bounded Context** gestiona las reglas y el envío de notificaciones.
  * **User Interface Bounded Context** maneja la presentación de la interfaz de usuario.
* El **Data Analytics Service** procesa los datos para generar insights.
* Los **IoT Devices** son los sensores y actuadores desplegados en las granjas.
* La **Relational Database** almacena todos los datos persistentes del sistema.

Estos contenedores interactúan entre sí para proporcionar las funcionalidades de la plataforma, desde la recopilación de datos de los IoT Devices hasta la presentación de información y el control de la alimentación a través de la Mobile App, todo orquestado por la API Application y la lógica de negocio encapsulada en los Bounded Contexts.
![ContextDiagram](Assets/c4/containers-diagram.png)

##### 4.1.3.4. Deployment Diagrams

## Alerting Bounded Context
![ContextDiagram](Assets/c4/BC1.png)
## Farm Management Bounded Context
![ContextDiagram](Assets/c4/BC2.png)
## Feeding Bounded Context
![ContextDiagram](Assets/c4/BC3.png)
##  Monitoring Bounded Context
![ContextDiagram](Assets/c4/BC4.png)
## User Interface Bounded Context
![ContextDiagram](Assets/c4/BC5.png)

### link de structurizr

https://structurizr.com/share/101696/0bfbd598-12c4-4206-aeea-2a33a2379713


### 4.2. Tactical-Level Domain-Driven Design


#### 4.2.X. Bounded Context: \<Bounded Context Name\>


##### 4.2.X.1. Domain Layer


##### 4.2.X.2. Interface Layer


##### 4.2.X.3. Application Layer


##### 4.2.X.4. Infrastructure Layer


##### 4.2.X.5. Component Level Diagrams


##### 4.2.X.6. Code Level Diagrams


###### 4.2.X.6.1. Domain Layer Class Diagrams


###### 4.2.X.6.2. Database Design Diagram
