# Reporte de Proyecto

<div align="center">

# **UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS**

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
      <td align="center">U202121584</td>
      <td align="center">Martel Zevallos, Gabriel</td>
    </tr>
    <tr>
      <td align="center">U202018627</td>
      <td align="center">Garcia Rodriguez, Gabriel</td>
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
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

## Project Report Collaboration Insights

## Contenido

### Tabla de contenidos

- [Reporte de Proyecto](#reporte-de-proyecto)
- [**UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS**](#universidad-peruana-de-ciencias-aplicadas)
  - [**Facultad de Ingeniería - Carrera de Ingeniería de Software**](#facultad-de-ingeniería---carrera-de-ingeniería-de-software)
  - [**2025-1**](#2025-1)
    - [**Curso:**](#curso)
  - [1ASI0572 - Desarrollo de Soluciones IoT](#1asi0572---desarrollo-de-soluciones-iot)
    - [**NRC:**](#nrc)
    - [2947](#2947)
    - [**Profesor:**](#profesor)
    - [Angel Augusto Velasquez Nuñez](#angel-augusto-velasquez-nuñez)
  - [**Informe de Trabajo Final**](#informe-de-trabajo-final)
    - [Startup: **AquaSense Technologies**](#startup-aquasense-technologies)
    - [Producto: **FeedGuard**](#producto-feedguard)
  - [**Integrantes del equipo**](#integrantes-del-equipo)
  - [**Abril 2025**](#abril-2025)
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
    - [3.2. User Stories](#32-user-stories)
    - [3.3. Impact Mapping](#33-impact-mapping)
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
    <i>TB1</i><br>
    Eduardo Espinoza, Vittorio Marcelo<br>
    <i>TB1</i><br>
    Flores Avalos, Diego<br>
    <i>TB1</i><br>
    Garcia Rodriguez, Gabriel Stefano<br>
    <i>TB1</i><br>
    MartelZevallos, Gabriel Aristoteles<br>
    <i>TB1</i><br>
    Rivas Sarango, David Alejandro<br>
    <i>TB1</i><br>
    </td>
    <td>Concluimos</td>
  </tr>
  <tr>
    <td><strong>Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.</strong></td>
    <td>
    Avellaneda Ramos, Carlos Edward<br>
    <i>TB1</i><br>
    Eduardo Espinoza, Vittorio Marcelo<br>
    <i>TB1</i><br>
    Flores Avalos, Diego<br>
    <i>TB1</i><br>
    Garcia Rodriguez, Gabriel Stefano<br>
    <i>TB1</i><br>
    MartelZevallos, Gabriel Aristoteles<br>
    <i>TB1</i><br>
    Rivas Sarango, David Alejandro<br>
    <i>TB1</i><br>
    </td>
    <td>Concluimos</td>
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
    <td>pongan su foto</td>
    <td>
    Avellaneda Ramos, Carlos Edward
    </td>
  </tr>
  <tr>
    <td><img src="Assets\VittorioEduardo.jpg" width="200"/></td>
    <td>
    Eduardo Espinoza, Vittorio Marcelo
    </td>
  </tr>
  
  <tr>
    <td><img src="Assets\diegoflorez.png" width="200"/></td>
    <td>
    Flores Avalos, Diego
    </td>
  </tr>
  <tr>
    <td><img src="Assets\GabrielGarcia.png" width="200"/></td>
    <td>
    Garcia Rodriguez, Gabriel Stefano
    </td>
  </tr>
  <tr>
    <td> <img src="./Assets/GabrielMartel.jpg" width="200"/></td>
    <td>
    MartelZevallos, Gabriel Aristoteles
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
> **💬 Enunciado:** Esta sección incluye dos secciones internas. La primera parte, Antecedentes y Problemática, consta del enunciado de problema, y una descripción de los puntos más importante que debe resolver la solución propuesta, así como objetivos y restricciones que delimiten el alcance del proyecto. La segunda parte, Lean UX Process, es resultado de la ejecución del Lean UX Process sobre el dominio del problema.
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

  <!-- Fila 1 -->
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

  <!-- Fila 2 -->
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

  <!-- Fila 3 -->
  <tr>
    <td colspan="4"><strong>Solutions</strong><br>
      - Sistema de sensores IoT<br>
      - Algoritmo de dosificación automática de alimento<br>
      - Interfaz móvil/web sencilla<br>
      - Alertas ambientales automatizadas<br>
      - Plataforma conectada a la nube con operación offline temporal
    </td>
  </tr>

  <!-- Fila 4 -->
  <tr>
    <td colspan="4"><strong>Hypotheses</strong><br>
      Creemos que la reducción del desperdicio de alimento será posible si los piscicultores obtienen alertas personalizadas y automatización del proceso de alimentación mediante sensores IoT integrados a una plataforma inteligente.
    </td>
  </tr>

  <!-- Fila 5 -->
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
  <!-- Fila 1: Título que ocupa las 7 columnas -->
  <tr>
    <th colspan="7">Competitive Analysis Landscape</th>
  </tr>

  <!-- Fila 2: Primera celda ocupa 2 columnas y 2 filas; las otras 5 son normales -->
  <tr>
    <td rowspan="2" colspan="2"><strong>¿Por qué llevar a cabo este análisis?</strong></td>
    <td colspan="5"><strong>Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</strong></td>
  </tr>

  <!-- Fila 3: solo 5 columnas, alineadas con las celdas superiores -->
  <tr>
    <td colspan="5"></td>
  </tr>

  <!-- Fila 4: primera celda ocupa 3 columnas, el resto son normales -->
  <tr>
    <td colspan="3"><strong>(En la cabecera colocar por cada competidor nombre y logo)</strong></td>
    <td style="width: 25%;">FeedGuard</td>
    <td style="width: 25%;">Aquarium Xiamoi</td>
    <td style="width: 25%;">FishFarmFeeder</td>
    <td style="width: 25%;">Aplians Fish</td>
  </tr>

  <!-- Perfil-->
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
  
  <!-- Perfil de Marketing-->
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

  <!-- Perfil de Producto-->
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

  <!-- Analisis SWOT-->
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
||Como primer entrevistado tenemos a Sebastian Pacheco, él es un piscicultor rural cuya granja se encuentra en Qulmana, Cañete. Cultiva tolapia roja y paco en menor escala. Nos menciona que posee un alimentador automático casero que armo con Arduino. Este alimenta a los peces 3 veces por día. Para el cálculo y registro de la alimentacion de los peces usa la herramienta Excel. Como indicadores paa saber si los peces estan comiendo bien califica la velocidad de consumoo, residuos en el fondo, reaccion cuando se aproxima a la granja de peces y la temperatura. Incluyendo el monitoreo de oxígeno y amonio constantemente. Actualmente posee una aplicación móvil que le avisa cuando baja el nivel de agua. Utiliza Whatsapp para ventas, Youtube para aprender y Drive para su registro. Él desearía que el sistema no falle o no avise sobre un evento. Estaría dispuesto a invertir entre 1500 y 2000 soles por una solución más completa.|

**Entrevista a piscicultores**
|**Nombre del entrevistado**|**Andre Bernaola**|
|:-|:-|
|Edad|24 años|
|Profesión|Psicicultor|
|Departamento|Lima, Peru|
||Andre Bernaola es un pisciultor rural que cría anguílas en agua salada. Menciona que no posee un control de la cantidad especifica de alimento que le brinda a su cultivo. Se les alimenta 2 veces durante un día. El desea saber cómo se puede verificar el nivel tanto de oxígeno y calidad del agua para poder proceder a un cambio y así las anguílas puedan prosperar en un buen ambiente. Utiliza Whatsapp para el contacto con proveedores y ventas. Esta muy interesado en usar una aplicación que lo ayuden con el monitoreo. El desearía que la aplicación posea monitoreo de oxígeno, cantidad de anguílas y datos que lo ayuden a mejorar su piscigranja. Estaría dispuesto a invertir 40 soles mensuales en una solución completa.|

**Entrevista a piscicultores**
|**Nombre del entrevistado**|**Alberto Martinez**|
|:-|:-|
|Edad|24 años|
|Profesión|Psicicultor|
|Departamento|Lima, Peru|
|| Alberto es un pisciultor experimentado que ya posee dispositivos de monitoreo para sus piscigranjas. Cría salmon en agua salada, carpas y tilapias. Con uno de sus dispositivos de Arduino, él ya puede saber la cantidad exacta de alimento que les va a proveer, con los demás registra el nivel de oxígeno, amonio y de residuos que perjudiquen a su cultivo; esto lo ayuda a decidir cuando hay un cambio de agua en sus piscigranjas. Utiliza Whatsapp e Instagram para el contacto con proveedores y para realizar sus ventas. Se encuentra interesado en usar una aplicación que reúna todas las características que sus dispositivos indican. El desearía que la aplicación posea una sección donde pueda colocar sus anotaciones. Estaría dispuesto a invertir 50 soles mensuales para una solución que reúna todas las características de sus ya existentes dispositivos Arduino. |


> **💬 Enunciado:**  Para cada segmento se requiere de 3 a 5 entrevistas. Para cada una de las entrevistas se debe indicar la información de nombres, apellidos, edad, distrito, un screenshot de un cuadro de video y el URL del video subido en Microsoft Stream (es un solo video editado para todas las entrevistas) incluyendo el timing donde inicia la entrevista y su duración. La entrevista debe ser registrada en video, que sirve de evidencia de entrevistas. Para cada entrevista debe redactarse en este informe un resumen, que explique de forma descriptiva las respuestas del entrevistado a las preguntas realizadas. Todas las características objetivas y subjetivas, incluyendo aspectos como personalidad, marcas e influencias, tecnología, canales de interacción, browser, dispositivos, etc. Deben estar incluidas como parte de los resúmenes para cada entrevista. Debe ser evidente que cada característica de los arquetipos que se construirán en base a esta información provienen de datos recolectados. Ver otras indicaciones importantes en el Anexo C. Indicaciones para secciones que incluyen Videos.

#### 2.2.3. Análisis de entrevistas

> **💬 Enunciado:** En esta sección se debe realizar un análisis por cada segmento objetivo, identificando con sustento estadístico (porcentajes) todas las características objetivas y subjetivas que representan los aspectos más comunes de cada segmento y que son necesarios para la construcción de los arquetipos. La fuente de información para este análisis proviene de las entrevistas registradas. Debe evidenciarse que cada característica tiene relación con las entrevistas registradas y los resúmenes realizados para las mismas.

### 2.3. Needfinding

El proceso de **Needfinding** tiene como propósito identificar las necesidades, expectativas, frustraciones y comportamientos de los usuarios vinculados al dominio de la solución. Esta etapa permite fundamentar decisiones de diseño centradas en el usuario, basadas en datos empíricos extraídos de entrevistas y observación contextual.<br>
A continuación, se detallan los principales artefactos elaborados en esta fase del proyecto.

#### 2.3.1. User Personas

Con base en el análisis de entrevistas realizadas a representantes de los segmentos objetivo, se han definido dos **User Personas** representativos del ecosistema productivo de la acuicultura semiindustrial.

- **Persona 1**, Juan
  <img src="Assets\UserPersonas\Juan, piscicultor rural.png"/>

- **Persona 2**, Bryan
  <img src="Assets\UserPersonas\Bryan, piscicultor técnico.png"/>

Estos arquetipos nos permiten modelar comportamientos, motivaciones y necesidades clave que serán consideradas a lo largo del diseño de la solución.

> **💬 Enunciado:** En esta sección se incluye la elaboración de las fichas de User Persona. La sección inicia con una introducción explicando la relación entre los artefactos a presentar y las principales características que se están tomando en cuenta del análisis de entrevistas y de la competencia. Se elabora una ficha de User Persona por cada segmento objetivo. Considere las mejores prácticas y todos los ítems necesarios para especificar un arquetipo. Utilice la herramienta indicada para este tipo de artefacto.

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

**Piscicultores técnicos**

<img src="Assets/miro_user_journey_map_tec.jpg"/>

#### 2.3.4. Empathy Mapping


### Empathy Map – Bryan Díaz

<img src="Assets\EmphatyMaps\BryanEmpathyMap.png"/>

**Piscicultores rurales**

<img src="Assets/miro_empathy1.jpg"/>

**Piscicultores técnicos**

<img src="Assets/miro_empathy2.jpg"/>

#### 2.3.5. As-is Scenario Mapping

En esta sección se presentan los _As-Is Scenario Mapping_ correspondientes a los dos User Personas definidos: **Juan Pérez** y **Bryan Díaz**. Estos mapas describen el escenario actual de los usuarios, sin la intervención de la solución FeedGuard, y permiten visualizar cómo experimentan su jornada operativa en relación a la alimentación y monitoreo en sistemas acuícolas semiindustriales.

**Piscicultores rurales**

|Phases|Preparación|Inspección visual|Alimentación|Registro|
|-|-|-|-|-|
|DOING|Se alista temprano y se dirige a los estanques.|Observa el color del agua y el comportamiento de los peces.|Abre manualmente los paquetes de comida y la reparte.|Anota en papel la cantidad de alimento usado y condiciones del estanque.|
|THINKING|“Hoy debo revisar todo antes que suba el sol.”|“Estará limpia el agua? Se ve un poco turbia.”|“Ojalá recuerde la cantidad exacta para cada estanque.”|“Todo esta en esta hoja, mejor no perderla.”|
|FEELING|Motivado por cuidar su producción.|Inseguro sobre la calidad del agua.|Estresado por la carga física.|Aliviado pero preocupado por olvidar o perder datos.|

**Piscicultores técnicos**

|Phases|Inicio del día|Monitoreo digital|Análisis de datos|Mantenimiento|
|-|-|-|-|-|
|DOING|Verifica funcionamiento de cada uno de los sensores.|Revisa parámetros de sensores: oxígeno, temperatura, etc.|Analiza datos históricos para planificar alimentación.|Registra datos en Excel a partir de lo arrojado en los sensores.|
|THINKING|“Voy a revisar los datos primero.”|“Estos valores están fuera del rango normal.”|“Podemos optimizar la alimentación.”|“Debo revisar este sensor que no envía datos.”|
|FEELING|Organizado y con control.|Alerta si algo no cuadra.|Proactivo y analítico.	|Frustrado si algo técnico falla.|

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

> **💬 Enunciado:** Esta sección permite que el equipo realice en base al análisis de la información
> obtenida en las investigaciones, la especificación de los requisitos de los productos
> digitales. La sección inicia con una introducción e incluye secciones internas para el
> To-Be Scenario Mapping, los User Stories, Impact Map y Product Backlog.

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

> **💬 Enunciado:** Requisitos definidos junto con el conjunto de User Stories y Epics para los requisitos
> identificados. Los User Stories incluyen Acceptance Criteria. En esta sección el
> equipo redacta una introducción y presenta un cuadro con la estructura especificada
> a continuación. Solo se elabora un cuadro para todo el conjunto de Epics/Stories.
> Debe dedicar una línea del cuadro a cada Epic / User Story. Es importante recordar que una User Story tiene varios criterios de aceptación. Los
> criterios de aceptación deben redactarse en tiempo presente, tercera persona, no
> hacer referencia a detalles de interfaz de usuario y deben ser comprobables. La
> estructura de criterios de aceptación debe seguir la estructura de Gherkin (GivenWhen-Then). Las únicas excepciones podrían ser reglas de negocio o restricciones
> que no dependan de condiciones.
> Debe también considerar User Stories para el sitio web estático (Landing Page),
> tomando como rol base visitante (o subconjuntos para cada segmento considerado
> cuando se requiera, como visitante del segmento XXXX) en la redacción de la
> descripción de la User Story. Recuerde que el sitio web estático tienen diversas secciones, con contenido dirigido a diversos segmentos, con características y
> comportamiento que permita su vínculo con la experiencia web.
> Adicionalmente, debe considerarse Technical Stories para los features de productos
> digitales que no tienen interacción directa con los usuarios finales, como por ejemplo
> los RESTful APIs. En ese caso, utilice el rol Developer en la redacción de la descripción
> de la User Story. Considere como Acceptance Criteria los posibles escenarios de
> interacción de request/response, siguiendo la estructura de Gherkin.

<table border="1" cellspacing="0" cellpadding="5" style="border-collapse: collapse; width: 100%;">
  <tr>
    <th>Epic / Story ID</th>
    <th>Título</th>
    <th>Descripción</th>
    <th>Criterios de<br>Aceptación</th>
    <th>Relacionado<br>con (Epic ID)</th>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
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

> **💬 Enunciado:** Los User Stories deben incluir su estimación y priorización en el Product Backlog.
> Debe utilizar la herramienta indicada para el Product Backlog. Adicionalmente debe
> elaborar en este documento una tabla con la siguiente estructura. Adicionalmente debe incluir una captura y una referencia de URL del enlace público
> para el product backlog en la herramienta indicada. Recuerde que en el Product
> Backlog, el orden lo determina el valor para el negocio. Elaborar un product backlog
> colocando al inicio User Stories ligados a la seguridad o autenticación, por ejemplo,
> se considera incorrecto. Considere que los User Stories relacionados con el sitio web
> estático (Landing Page) requieren considerarse desde el primer sprint.

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

> **💬 Enunciado:** En esta sección el equipo introduce y explica el proceso realizado para las decisiones de nivel estratégico aplicando Domain-Driven Design.<br> Bounded Contexts<br> `--En esta sección el equipo explica y evidencia el proceso para descomponer el sistema en subconjuntos con límites naturales o Bounded Contexts. Para ello debe aplicar las herramientas de EvenStorming y Bounded Context Canvas

#### 4.1.1. EventStorming

> **💬 Enunciado:** En esta sección el equipo explica y evidencia el proceso de EventStorming, con el fin de plantear una primera aproximación al modelado de nivel general para el dominio del problema, buscando a partir de ahí identificar el mayor nivel de detalle posible.
> Es recomendable que el equipo organice la sesión de EventStorming con una duración entre 1 – 2 horas, a fin de concentrar esfuerzos y no extender el proceso de forma innecesaria. La sección inicia con una introducción y explicación de las actividades realizadas en la sesión de EventStorming, e incluye capturas de lo elaborado en la herramienta indicada.

##### 4.1.1.1. Candidate Context Discovery

> **💬 Enunciado:** En esta sección el equipo, a partir del dominio modelado como EventStorm, explica y evidencia el proceso realizado para la sesión de Candidate Context Discovery, en la que se busca identificar los bounded contexts. Puede aplicar las técnicas de startwith-value (Identificar las partes core del dominio que tienen el mayor valor para el negocio), start-with-simple (Crear modelos simples, pero con propósito, descomponiendo el timeline en steps secuenciales), ó look-for-pivotal-events (Buscar eventos clave del negocio que indiquen cambios de estado entre diferentes partes del proceso de negocio). La sesión de Candidate Context Discovery no debería durar más de 2 horas. Utilice para el proceso la herramienta indicada. Complemente la explicación con capturas en imagen de los cambios progresivos del EventStorm.

##### 4.1.1.2. Domain Message Flows Modeling

> **💬 Enunciado:** En esta sección, el equipo explica y evidencia el proceso seguido para visualizar cómo deben colaborar los bounded contexts para resolver los casos que se presentan en el negocio para los usuarios del sistema. Para ello debe aplicar la técnica de visualización Domain Storytelling. Complemente la explicación con capturas en imágenes de los diagramas de Domain Storytelling elaborados.

##### 4.1.1.3. Bounded Context Canvases

> **💬 Enunciado:** En esta sección el equipo diseña sus candidate bounded contexts, detallando los criterios de diseño. El equipo debe ir seleccionando cada bounded context, por orden de importancia, para elaborar su Bounded Context Canvas. La elaboración del Bounded Context Canvas debe seguir un proceso iterativo con los pasos de Context Overview Definition, Business Rules Distillation & Ubiquitous Language Capture, Capability Analysis, Capability Layering (si aplica), Dependencies Capture, y Design Critique.

#### 4.1.2. Context Mapping

> **💬 Enunciado:** En esta sección el equipo explica y evidencia el proceso de elaboración de un conjunto de contexts maps (visualizaciones de las relaciones estructurales entre bounded contexts). Para ello el equipo revisa información recolectada y la utiliza para producir los diseños candidatos. Se recomienda en el proceso incluir preguntas como: “¿qué pasaría si movemos este capability a otro bounded context?”, “¿qué pasaría si descomponemos este capability y movemos uno de los sub-capabilities a otro bounded context?”, “¿qué pasaría si partimos el bounded context en múltiples
> bounded contexts?”, “¿qué pasaría si tomamos este capability de estos 3 contexts y lo usamos para formar un nuevo context?”, “¿qué pasaría si duplicamos una 16/41 V1.0 funcionalidad para romper la dependencia?”, “¿qué pasaría si creamos un shared service para reducir la duplicación entre múltiples bounded contexts?”, “¿qué pasaría si aislamos los core capabilities y movemos los otros a un context aparte?”. Debe finalizar este proceso discutiendo cada alternativa de context mapping a fin de llegar a la mejor aproximación. Es importante que el equipo considere los patrones de relaciones entre Bounded Contexts establecidos en Domain-Driven Design, como Anti-corruption Layer, Conformist, Customer/Supplier ó Shared Kernel.

#### 4.1.3. Software Architecture

> **💬 Enunciado:** En esta sección el equipo presenta y explica la representación, aplicando C4 Model y utilizando la herramienta indicada, de la Arquitectura de Software para la solución. Aquí se realiza una introducción y se incluye como secciones internas Software Architecture Context Level Diagram y Software Architecture Container Level Diagrams.

##### 4.1.3.1. System Landscape Diagram

##### 4.1.3.2. Context Level Diagrams

> **💬 Enunciado:** En esta sección el equipo realiza una introducción, presenta en imagen el context diagram, el cual debe mostrar el sistema como un recuadro en el centro, rodeado por sus usuarios y otros sistemas con los que interactúa. Utilice la herramienta indicada para la elaboración del diagrama. Se incluye en esta sección una explicación del diagrama.

![ContextDiagram](Assets/c4/diagrama-context-c4.png)

##### 4.1.3.3. Container Level Diagrams

> **💬 Enunciado:** En esta sección, el equipo realiza una introducción, presenta y explica el Container Diagram. Dicho diagrama debe mostrar los elementos de alto nivel de la arquitectura de software y cómo se distribuyen las responsabilidades entre ellos. Aquí se debe mostrar también las principales decisiones de tecnología y cómo los containers se comunican entre sí.

##### 4.1.3.4. Deployment Diagrams

### 4.2. Tactical-Level Domain-Driven Design

> **💬 Enunciado:** En este capítulo el equipo explica y presenta su propuesta para la perspectiva táctica del diseño de la solución de software. Aquí se incluye una sección interna por cada bounded context.

#### 4.2.X. Bounded Context: \<Bounded Context Name\>

> **💬 Enunciado:** En esta sección, el equipo presenta las clases identificadas y las detalla a manera de diccionario, explicando para cada una su nombre, propósito y la documentación de atributos y métodos considerados, junto con las relaciones entre ellas.

##### 4.2.X.1. Domain Layer

> **💬 Enunciado:** En esta capa el equipo explica por medio de qué clases representará el core de la aplicación y las reglas de negocio que pertenecen al dominio para el bounded context. Aquí el equipo presenta clases de categorías como Entities, Value Objects, Aggregates, Factories, Domain Services, o abstracciones representadas por interfaces como en el caso de Repositories.

##### 4.2.X.2. Interface Layer

> **💬 Enunciado:** En esta sección el equipo introduce, presenta y explica las clases que forman parte de Interface/Presentation Layer, como clases del tipo Controllers o Consumers.

##### 4.2.X.3. Application Layer

> **💬 Enunciado:** En esta sección el equipo explica a través de qué clases se maneja los flujos de procesos del negocio. En esta sección debe evidenciarse que se considera los 17/41 capabilities de la aplicación en relación al bounded context. Aquí debe considerarse clases del tipo Command Handlers e Event Handlers.

##### 4.2.X.4. Infrastructure Layer

> **💬 Enunciado:** En esta capa el equipo presenta aquellas clases que acceden a servicios externos como databases, messaging systems o email services. Es en esta capa que se ubica la implementación de Repositories para las interfaces definidas en Domain Layer. Algo similar ocurre con interfaces definidas para MessageBrokers.

##### 4.2.X.5. Component Level Diagrams

> **💬 Enunciado:** En esta sección, el equipo explica y presenta los Component Diagrams de C4 Model para cada uno de los Containers considerados para el bounded context. En estos diagramas el equipo busca reflejar la descomposición de cada Container para identificar los bloques estructurales principales y sus interacciones. Un Component Diagram debe mostrar cómo un container está conformado por components, qué son cada uno de dichos components, sus responsabilidades y los detalles de implementación/tecnología. Utilice la herramienta indicada para la elaboración del diagrama.

##### 4.2.X.6. Code Level Diagrams

> **💬 Enunciado:** En esta sección, el equipo presenta y explica los diagramas que presentan un mayor detalle sobre la implementación de componentes en el bounded context. Aquí se incluye como secciones internas Bounded Context Domain Layer Class Diagrams y Bounded Context Database Diagram.

###### 4.2.X.6.1. Domain Layer Class Diagrams

> **💬 Enunciado:** En esta sección el equipo presenta el Class Diagram de UML para las clases del Domain Layer en el bounded context. El nivel de detalle debe incluir además de las clases, interfaces, enumeraciones y sus relaciones, los miembros para cada clase, incluyendo atributos, métodos y el scope en cada caso (private, public, protected). Las relaciones deben incluir la calificación con nombres, la dirección (cuando aplica) y la multiplicidad. Utilice para la elaboración del diagrama la herramienta indicada.

###### 4.2.X.6.2. Database Design Diagram

> **💬 Enunciado:** En esta sección el equipo presenta y explica el Database Diagram que incluye los objetos de base de datos que permitirán la persistencia de información para los objetos del bounded context. Para el caso de un almacenamiento en base de datos relacional, aquí debe especificarse tablas, columnas, constraints (por ejemplo, primary, foreign key) y evidenciarse las relaciones en
