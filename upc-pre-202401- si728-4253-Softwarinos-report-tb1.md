# Softwarinos - Report

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="LogoUPC">
</p>

# Universdiad Peruana de Ciencias Aplicadas

# INGENIERÍA DE SOFTWARE

### Ciclo: 7

## CURSO: Arquitecturas De Software Emergentes | SECCIÓN 4253

Profesor: De Los Rios Fernandez, Christian Luis

# Proyecto de curso

## Informe de Trabajo Final

#### StartUp: Softwarinos

#### Producto: Detekto

### Integrantes:

| Integrantes                            | Codigo     |
| -------------------------------------- | ---------- |
| Ampudia Flores, Jose Carlos Isaac      | u202112936 |
| De La Piedra Quintanilla, Erwin Miquel | U202112179 |
| Elsner De La Torre Ugarte              | u202111654 |
| Gutierrez Zumaeta, Manuel Alonso       | U202112353 |

#### Ciclo 2025-10

##### Abril, 2025

---

# Registro de Versiones del informe

| Versión | Fecha | Autor | Descripción de modificación |
| ------- | ----- | ----- | --------------------------- |
| 0.1     |       |       |                             |
| 0.2     |       |       |                             |
| 0.3     |       |       |                             |
| 0.4     |       |       |                             |
| 0.5     |       |       |                             |

# Project Report Collaboration Insights

Para el desarrollo del proyecto, se ha utilizado la plataforma de GitHub para el control correcto de versiones y la colaboración de los integrantes del equipo. A continuación se presenta el link directo a la organización del equipo:

**Link de organización Softwarinos:**  
[https://github.com/Emergentes-Softwarinos](https://github.com/Emergentes-Softwarinos)

## TB1

Para la entrega de la TB1 se realizó una reunión donde se asignaron las responsabilidades a cada integrante del equipo. A continuación se muestra la siguiente tabla con los detalles:

| Integrante          | Responsabilidad                                                                                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| José Ampudia        | Desarrollo del diseño de las entrevistas, registro de entrevistas, Análisis de entrevistas, Needfinding, User Personas, User Task Matrix, Empathy Mapping, As-Is Scenario Mapping, Ubiquitous Language, To-Be Scenario Mapping y User Stories                                                                                                                                                                        |
| Manuel Gutierrez    | Desarrollo de Solution Profile, Antecedentes y problemática, Lean UX Process, Lean UX Problem Statements, Lean UX Assumptions, Lean UX Hypothesis Statements, Lean UX Canvas, Segmentos objetivos, Competidores, Análisis competitivo, Estrategias y tácticas frente a competidorees y Registro de entrevistas                                                                                                       |
| Miquel De la Piedra | Desarrollo del Impact Mapping, Product Backlog, Strategic-Level Attribute-Driven Design, Design Purpose, Attribute-Driven Design Inputs, Primary Functionality (Primary User Stories), Quality attribute Scenarios, Constraints, Architectural Drivers Backlog, Architectural Design Decisions y Quality Attribute Scenario Refinements y Registro de entrevistas                                                    |
| Julio De la Torre   | Desarrollo de Strategic-Level Domain-Driven Design, EventStorming, Candidate Context Discovery, Domain Message Flows Modeling, Bounded Context Canvases, Context Mapping y Software Architecture, Software Architecture System Landscape Diagram, Software Architecture Context Level Diagrams, Software Architecture Container Level Diagrams y Software Architecture Deployment Diagrams y Registro de entrevistas |

Durante la elaboración de las aplicaciones, tanto web como mobile, se realizaron _commits_ respectivos con el fin de mantener el orden y un control de versiones eficiente.

Para tener mejor precisión en los integrantes del equipo, a continuación presentamos los usuarios de GitHub de los integrantes:

- José Ampudia (@IsaacAmp24)
- Manuel Gutierrez (@ManuGZ)
- Miquel De la Piedra (@MiquelDlp)
- Julio De la Torre (@JulioElsnerDLTU)

A continuación se presentan las capturas del repositorio de GitHub donde se realizaron los avances correspondientes.

# Tabla de contenidos
- [Student Outcome](#student-outcome)

[Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

[Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. Empathy Mapping](#233-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)

[Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)

[Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)
  - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [4.1.1. Design Purpose](#411-design-purpose)
    - [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
      - [4.1.2.1. Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)
      - [4.1.2.2. Quality attribute Scenarios](#4122-quality-attribute-scenarios)
      - [4.1.2.3. Constraints](#4123-constraints)
    - [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)
    - [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)
    - [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
  - [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
    - [4.2.1. EventStorming](#421-eventstorming)
    - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
    - [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)
    - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)
    - [4.2.5. Context Mapping](#425-context-mapping)
  - [4.3. Software Architecture](#43-software-architecture)
    - [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
    - [4.3.2. Software Architecture Context Level Diagrams](#432-software-architecture-context-level-diagrams)
    - [4.3.3. Software Architecture Container Level Diagrams](#433-software-architecture-container-level-diagrams)
    - [4.3.4. Software Architecture Deployment Diagrams](#434-software-architecture-deployment-diagrams)

### Capítulo V: Tactical-Level Software Design

- [5.X. Bounded Context: Nombre del Contexto](#5x-bounded-context-nombre-del-contexto)
  - [5.X.1. Domain Layer](#5x1-domain-layer)
  - [5.X.2. Interface Layer](#5x2-interface-layer)
  - [5.X.3. Application Layer](#5x3-application-layer)
  - [5.X.4. Infrastructure Layer](#5x4-infrastructure-layer)
  - [5.X.6. Bounded Context Software Architecture Component Level Diagrams](#5x6-bounded-context-software-architecture-component-level-diagrams)
  - [5.X.7. Bounded Context Software Architecture Code Level Diagrams](#5x7-bounded-context-software-architecture-code-level-diagrams)
    - [5.X.7.1. Domain Layer Class Diagrams](#5x71-domain-layer-class-diagrams)
    - [5.X.7.2. Database Design Diagram](#5x72-database-design-diagram)

### Capítulo VI: Solution UX Design

- [6.1. Style Guidelines](#61-style-guidelines)
  - [6.1.1. General Style Guidelines](#611-general-style-guidelines)
  - [6.1.2. Web, Mobile & Devices Style Guidelines](#612-web-mobile--devices-style-guidelines)
- [6.2. Information Architecture](#62-information-architecture)
  - [6.2.2. Labeling Systems](#622-labeling-systems)
  - [6.2.3. Searching Systems](#623-searching-systems)
  - [6.2.4. SEO Tags and Meta Tags](#624-seo-tags-and-meta-tags)
  - [6.2.5. Navigation Systems](#625-navigation-systems)
- [6.3. Landing Page UI Design](#63-landing-page-ui-design)
  - [6.3.1. Landing Page Wireframe](#631-landing-page-wireframe)
  - [6.3.2. Landing Page Mock-up](#632-landing-page-mock-up)
- [6.4. Applications UX/UI Design](#64-applications-uxui-design)
  - [6.4.1. Applications Wireframes](#641-applications-wireframes)
  - [6.4.2. Applications Wireflow Diagrams](#642-applications-wireflow-diagrams)
  - [6.4.3. Applications Mock-ups](#643-applications-mock-ups)
  - [6.4.4. Applications User Flow Diagrams](#644-applications-user-flow-diagrams)
- [6.5. Applications Prototyping](#65-applications-prototyping)

### Capítulo VII: Product Implementation, Validation & Deployment

- [7.1. Software Configuration Management](#71-software-configuration-management)
  - [7.1.1. Development Environment Configuration](#711-development-environment-configuration)
  - [7.1.2. Source Code Management](#712-source-code-management)
  - [7.1.3. Code Style Guide & Conventions](#713-code-style-guide--conventions)
  - [7.1.4. Deployment Configuration](#714-deployment-configuration)
- [7.2. Solution Implementation](#72-solution-implementation)
  - [7.2.X. Sprint n](#72x-sprint-n)
    - [7.2.X.1. Sprint Planning](#72x1-sprint-planning)
    - [7.2.X.2. Sprint Backlog](#72x2-sprint-backlog)
    - [7.2.X.3. Development Evidence](#72x3-development-evidence)
    - [7.2.X.4. Testing Suite Evidence](#72x4-testing-suite-evidence)
    - [7.2.X.5. Execution Evidence](#72x5-execution-evidence)
    - [7.2.X.6. Services Documentation](#72x6-services-documentation)
    - [7.2.X.7. Deployment Evidence](#72x7-deployment-evidence)
    - [7.2.X.8. Team Collaboration Insights](#72x8-team-collaboration-insights)
- [7.3. Validation Interviews](#73-validation-interviews)
  - [7.3.1. Diseño de Entrevistas](#731-diseño-de-entrevistas)
  - [7.3.2. Registro de Entrevistas](#732-registro-de-entrevistas)
  - [7.3.3. Evaluaciones según heurísticas](#733-evaluaciones-según-heurísticas)
- [7.4. Video About-the-Product](#74-video-about-the-product)

### Conclusiones

- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

### Video About-the-Team

- [Video del equipo](#video-del-equipo)

### Bibliografía

- [Referencias](#referencias)

### Anexos

- [Anexos](#anexos)

# Student Outcome

ABET – EAC - Student Outcome 3: Capacidad de comunicarse efectivamente con un
rango de audiencias.

<table>
  <thead>
    <tr>
      <th>Criterio específico</th>
      <th>Acciones realizadas</th>
      <th>Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Comunica oralmente con efectividad a diferentes rangos de audiencia</strong></td>
      <td>
        <strong>José Ampudia</strong><br />
        <strong>TB1</strong><br />
        Participó activamente en entrevistas con usuarios para la recopilación de información clave sobre necesidades reales. Durante estas sesiones, empleó un lenguaje claro y empático para asegurar la comprensión del propósito del proyecto, facilitando así una retroalimentación útil y precisa.
        <br /><br />
        <strong>Manuel Gutierrez</strong><br />
        <strong>TB1</strong><br />
        Comunicó de manera clara la problemática y el enfoque estratégico del proyecto durante las entrevistas con usuarios y discusiones del equipo, asegurando que todos comprendieran la visión general del producto. Además, facilitó sesiones explicativas sobre la propuesta de valor frente a competidores.
        <br /><br />
        <strong>Miquel De la Piedra</strong><br />
        <strong>TB1</strong><br />
        Explicó el propósito y funcionamiento del Impact Mapping a su equipo, así como las decisiones de diseño arquitectónico a nivel estratégico, asegurando que todos los miembros comprendieran la relación entre funcionalidades y metas del proyecto.
        <br /><br />
        <strong>Julio De la Torre</strong><br />
        <strong>TB1</strong><br />
        Facilitó el entendimiento de conceptos técnicos complejos como el EventStorming, Candidate Context Discovery y la arquitectura del sistema mediante presentaciones orales y debates dentro del equipo, adaptando el lenguaje técnico según el nivel de conocimiento de la audiencia.
      </td>
      <td>
        Las habilidades de comunicación oral del equipo permitieron un entendimiento claro y compartido del proyecto tanto a nivel técnico como no técnico, mejorando la colaboración con usuarios y entre los miembros del equipo.
      </td>
    </tr>
    <tr>
      <td><strong>Comunica por escrito con efectividad a diferentes rangos de audiencia</strong></td>
      <td>
        <strong>José Ampudia</strong><br />
        <strong>TB1</strong><br />
        Redactó documentos como el análisis de entrevistas, User Personas, y escenarios As-Is/To-Be de forma estructurada y clara, facilitando la comprensión por parte del equipo y stakeholders del contexto del usuario y sus necesidades.
        <br /><br />
        <strong>Manuel Gutierrez</strong><br />
        <strong>TB1</strong><br />
        Elaboró entregables como el Lean UX Canvas, Problem Statements y el análisis competitivo con una redacción precisa y orientada a la toma de decisiones estratégicas. Su documentación fue esencial para definir la propuesta de valor del proyecto.
        <br /><br />
        <strong>Miquel De la Piedra</strong><br />
        <strong>TB1</strong><br />
        Documentó el diseño arquitectónico a través del Attribute-Driven Design y Backlog técnico, asegurando claridad en los lineamientos técnicos para los futuros desarrolladores y partes interesadas.
        <br /><br />
        <strong>Julio De la Torre</strong><br />
        <strong>TB1</strong><br />
        Generó documentación técnica detallada sobre los componentes de la arquitectura del sistema, diagramas y mapeos de contexto, facilitando así la comprensión integral del sistema por parte de audiencias tanto técnicas como no técnicas.
      </td>
      <td>
        La calidad de los entregables escritos permitió transmitir efectivamente tanto el enfoque de usuario como las decisiones técnicas, mejorando la comunicación y coordinación entre todos los actores involucrados.
      </td>
    </tr>
  </tbody>
</table>
<br><br>

# Capítulo I: Introducción

## 1.1. Startup Profile

En esta sección presentaremos la descripción del startup y los perfiles de los miembros del team.

### 1.1.1. Descripción de la Startup

En Softwarinos, estamos desarrollando una solución con respecto al reconocimiento de objetos a través de una aplicación móvil, para facilitar la búsqueda de productos y la venta de estos mismos por parte de vendedores, además de un seguimiento de estas ventas y proyecciones de parte del administrador.

**Misión**: Crear una aplicación móvil que reconozca objetos de forma rápida y precisa, para ayudar a los vendedores a encontrar y vender productos fácilmente, y permitir a los administradores llevar un mejor control de las ventas y hacer proyecciones para su negocio.

**Visión**: Convertirnos en una empresa destacada en soluciones tecnológicas para el comercio, facilitando el trabajo de vendedores y administradores a través de herramientas inteligentes que mejoran la gestión y el crecimiento de sus negocios.

### 1.1.2. Perfiles de integrantes del equipo

| Foto                                                              | Nombre y Descripción                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ----------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Foto Manuel](assets/CAP1/FotoManuel.png)                        | **Nombre:** Manuel Alonso Gutierrez Zumaeta<br>**Código:** u202112353<br>**Descripción:** Soy Manuel Gutierrez, estudiante de la carrera de Ingeniería de Software, tengo 20 años. Tengo experiencia en el desarrollo de aplicaciones web, tanto frontend como backend, programación móvil en Flutter. Me considero una persona responsable y que se propone hacer un buen trabajo.                                                                                                                                        |
| ![Foto Julio](ruta/a/la/foto)                                     | **Nombre:** Julio Elsner De La Torre Ugarte<br>**Código:** u202111654<br>**Descripción:** Estudiante de Ingeniería de software, tengo 21 años. Cuento con experiencia en desarrollo de aplicaciones Web Full Stack (Front, Back-end) y bases de datos. Me considero una persona indagadora y que hace las cosas con una idea plasmada antes de realizarla.                                                                                                                                                                 |
| ![Foto Miquel](ruta/a/la/foto)                                    | **Nombre:** Erwin Miquel De la Piedra Quintanilla<br>**Código:** u202112179<br>**Descripción:** Soy Miquel De la Piedra, tengo 21 años, estudiante de la carrera de Ingeniería de Software. Poseo conocimientos relacionados a la programación en C++, Python, HTML y CSS. Además poseo experiencia con el manejo de bases de datos. Considero que estos conocimientos ayudarán a la realización de este trabajo, además de mejorar nuestros métodos de organización y trabajo en equipo.                                  |
| ![Foto José](./assets/CAP1/Perfil-Integrantes/rostro-Jocais.jpeg) | **Nombre:** José Carlos Isaac Ampudia Flores<br>**Código:** u202112936<br>**Descripción:** Soy estudiante de Ingeniería de Software, con sólida formación en desarrollo Backend utilizando frameworks como Spring Boot. También cuento con conocimientos en el desarrollo Frontend, trabajando con herramientas como Angular. Me caracterizo por mi capacidad para trabajar bajo presión, así como por mi enfoque organizado y metódico, lo que me permite adaptarme correctamente a los desafíos del entorno tecnológico. |

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

- **What (¿Qué?)**  
 El problema principal es la dificultad que enfrentan ferreterías y comercios de productos físicos para identificar, buscar y gestionar herramientas y materiales de forma rápida y precisa. Los sistemas actuales no están adaptados al sector y requieren conocimientos técnicos o procesos manuales lentos.

- **When (¿Cuándo?)**  
  Este problema ocurre diariamente en el momento de la atención al cliente, la búsqueda de productos en almacén, la actualización del inventario y el registro de ventas. Es especialmente crítico durante horas de alta demanda o cuando se requiere atención eficiente.

- **Where (¿Dónde?)**  
  Sucede en ferreterías, depósitos, puntos de venta físicos y almacenes, donde los empleados necesitan reconocer y registrar productos con rapidez, y los administradores requieren visibilidad clara sobre el movimiento de stock y ventas.

- **Who (¿Quién?)**  
  Afecta principalmente a los vendedores que deben identificar productos de forma rápida, a los clientes que experimentan demoras, y a los administradores que necesitan gestionar inventario y ventas sin sistemas complejos.

- **Why (¿Por qué?)**  
  Porque los sistemas actuales como Shopify, Zoho CRM o TradeGecko están diseñados para otros tipos de negocios, no cuentan con funciones de reconocimiento visual, y son demasiado generales o complejos para el día a día de una ferretería tradicional.

- **How (¿Cómo?)**  
  El problema se intenta resolver actualmente con métodos manuales (catálogos impresos, búsqueda visual, listas), aplicaciones genéricas o incluso sin ningún sistema, lo que lleva a errores, pérdida de tiempo y falta de control.

- **How much (¿Cuánto?)**  
  El impacto puede medirse en tiempo perdido (minutos por venta), errores en inventario, insatisfacción del cliente, y pérdida de ventas por no poder identificar o encontrar un producto a tiempo. A nivel económico, esto representa una baja en la eficiencia operativa y en la competitividad del negocio.

### 1.2.2 Lean UX Process.

#### 1.2.2.1. Lean UX Problem Statements.
El estado actual de la gestión de productos en las ferreterías está centrado principalmente en métodos tradicionales, como catálogos físicos y búsqueda manual, lo que resulta en tiempos de espera largos, ineficiencia en la atención al cliente y una gestión de inventario poco precisa. Lo que los sistemas existentes no logran abordar es la integración efectiva de tecnología para agilizar la identificación de productos, mejorar la precisión en el registro de ventas e inventario, y optimizar el seguimiento de las operaciones comerciales.

Nuestro producto, Detekto, resolverá esta brecha mediante el desarrollo de una solución móvil innovadora que utiliza reconocimiento visual a través de la cámara del dispositivo. Nos enfocaremos en proporcionar una plataforma que permita a los vendedores identificar productos rápidamente, registrar ventas, acceder a informes de inventario en tiempo real y obtener reportes automatizados. Además, simplificaremos la gestión del inventario y mejoraremos la comunicación entre vendedores y administradores, todo desde una interfaz sencilla y fácil de usar.

Nuestro enfoque inicial será dirigirnos a ferreterías y pequeños comercios especializados en herramientas y materiales, proporcionando una solución tecnológica accesible que optimice sus procesos. Sabremos que hemos tenido éxito cuando veamos una disminución significativa en los tiempos de atención al cliente, una mejora en la precisión del inventario y una mayor satisfacción tanto de empleados como de clientes, resultando en un aumento en las ventas y eficiencia operativa.

#### 1.2.2.2. Lean UX Assumptions.
- **Business Assumptions**

Los vendedores y administradores de ferreterías necesitan una herramienta rápida y sencilla para identificar productos y gestionar inventarios.

Detekto solucionará esto mediante una app móvil con reconocimiento visual, facilitando la identificación de productos y la gestión de ventas e inventarios.

El modelo de negocio se basará en suscripciones mensuales para ferreterías, con opciones premium como reportes avanzados.

La principal competencia son plataformas generales como Shopify y Zoho CRM, que no están especializadas en ferreterías.

Nos diferenciamos al ofrecer una solución sencilla y enfocada, con reconocimiento visual que ahorra tiempo y mejora la eficiencia operativa.

- **User Assumptions**

  - **¿Quién es el usuario?**  
    Vendedores de ferretería, encargados de mostrador, y administradores de pequeñas y medianas ferreterías.

  - **¿Dónde encaja nuestro producto en su trabajo o vida?**  
    Detekto se utilizará en el punto de venta o durante la organización de inventario, como una herramienta rápida para identificar productos y facilitar su registro, venta o seguimiento.

  - **¿Qué problema tiene nuestro producto? ¿Cómo se resuelve?**  
    El usuario necesita identificar productos sin perder tiempo revisando catálogos físicos o digitales. El reconocimiento visual automatizado reduce este tiempo, mejora la precisión y acelera la atención al cliente.

  - **¿Cuándo y cómo es usado nuestro producto?**  
    Detekto se usa durante el horario laboral en ferreterías, a través de dispositivos móviles (principalmente smartphones) al momento de interactuar con clientes o gestionar productos en bodega.

  - **¿Qué características son importantes?**  
    Reconocimiento visual rápido y preciso, facilidad para registrar ventas, reportes automáticos, historial de productos buscados y acceso desde el celular sin depender de otros sistemas externos.

  - **¿Cómo debe verse nuestro producto y comportarse?**  
    Debe tener una interfaz limpia, visual e intuitiva, con navegación simple, botones grandes y flujos cortos. Debe ser confiable, ágil y estar optimizada para ambientes de trabajo (ruido, poco tiempo, poca conectividad).

- **User Benefits**

  - **Identificación instantánea de productos:**  
    El usuario puede reconocer herramientas y materiales en segundos sin buscar manualmente.

  - **Optimización de ventas y atención al cliente:**  
    Se reduce el tiempo de atención, mejorando la experiencia del cliente y la eficiencia del vendedor.

  - **Gestión simplificada para administradores:**  
    Los responsables pueden monitorear ventas y productos más vendidos desde un panel claro.

  - **Reducción de errores:**  
    Se evita registrar productos incorrectos gracias al reconocimiento visual automatizado.

  - **Adopción sencilla:**  
    La app no requiere conocimientos técnicos avanzados, lo que permite una adopción rápida incluso por usuarios con baja familiaridad digital.

#### 1.2.2.3. Lean UX Hypothesis Statements.
- **Creemos que** la experiencia del vendedor mejorará si se ofrece reconocimiento automático de herramientas mediante la cámara del móvil.**Sabremos que hemos tenido éxito, cuando** el tiempo promedio de identificación de productos disminuya en un 50% durante el primer mes de uso.

- **Creemos que** los administradores podrán tomar mejores decisiones si se les proporciona un panel con reportes automáticos de ventas e inventario.**Sabremos que hemos tenido éxito, cuando** el 70% de los administradores usen el panel semanalmente y reporten una mejora en la gestión del stock en los primeros tres meses.

- **Creemos que** los usuarios adoptarán más rápidamente la app si la interfaz es simple, visual e intuitiva. **Sabremos que hemos tenido éxito, cuando** al menos el 80% de los nuevos usuarios completen su primera venta con ayuda de Detekto en menos de 10 minutos, durante el primer uso.

- **Creemos que** Detekto tendrá una mayor aceptación que soluciones genéricas si se enfoca únicamente en ferreterías. **Sabremos que hemos tenido éxito, cuando** al menos el 60% de los usuarios prefieren Detekto sobre otros sistemas después de un mes de uso, según encuestas de satisfacción.

#### 1.2.2.4. Lean UX Canvas.
<img src="assets/CAP1/LeanUXCanvas.png" alt="LeanUxCanvas">

## 1.3. Segmentos objetivo.

El estado actual de la gestión de productos en las ferreterías está centrado principalmente en métodos tradicionales, como catálogos físicos y búsqueda manual, lo que resulta en tiempos de espera largos, ineficiencia en la atención al cliente y una gestión de inventario poco precisa. Lo que los sistemas existentes no logran abordar es la integración efectiva de tecnología para agilizar la identificación de productos, mejorar la precisión en el registro de ventas e inventario, y optimizar el seguimiento de las operaciones comerciales.

Nuestro producto, Detekto, resolverá esta brecha mediante el desarrollo de una solución móvil innovadora que utiliza reconocimiento visual a través de la cámara del dispositivo. Nos enfocaremos en proporcionar una plataforma que permita a los vendedores identificar productos rápidamente, registrar ventas, acceder a informes de inventario en tiempo real y obtener reportes automatizados. Además, simplificaremos la gestión del inventario y mejoraremos la comunicación entre vendedores y administradores, todo desde una interfaz sencilla y fácil de usar.

Nuestro enfoque inicial será dirigirnos a ferreterías y pequeños comercios especializados en herramientas y materiales, proporcionando una solución tecnológica accesible que optimice sus procesos. Sabremos que hemos tenido éxito cuando veamos una disminución significativa en los tiempos de atención al cliente, una mejora en la precisión del inventario y una mayor satisfacción tanto de empleados como de clientes, resultando en un aumento en las ventas y eficiencia operativa.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores.

### 2.1.1. Análisis competitivo.

<table><tr><th colspan="6" valign="top">Competitive Analysis Landscape</th></tr>
<tr><td colspan="1" valign="top">¿Por qué llevar a cabo este análisis?</td><td colspan="5" valign="top">El objetivo de este análisis es identificar las características de los competidores y encontrar maneras de diferenciarnos.</td></tr>
<tr><td colspan="2" rowspan="2" valign="top">Startup y Competidores</td><td colspan="1" valign="top">Detekto</td><td colspan="1" valign="top">TradeGecko</td><td colspan="1" valign="top">Zoho CRM</td><td colspan="1" valign="top">Shopify</td></tr>
<tr><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td><td colspan="1" valign="top"></td></tr>
<tr><td rowspan="2" valign="top">Perfil</td><td valign="top">Overview</td>
<td valign="top">App móvil centrada en reconocimiento de herramientas de ferretería mediante cámara. Enfocada en facilitar búsqueda, venta y seguimiento de producto.</td>
<td valign="top">Plataforma de gestión de inventario para pequeñas empresas. Adquirido por QuickBooks.</td>
<td valign="top">CRM completo con automatización de ventas y análisis, enfocado en todo tipo de industria.</td>
<td valign="top">Plataforma de ecommerce para crear y gestionar tiendas online con herramientas integradas de ventas.</td></tr>
<tr><td valign="top">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
<td valign="top">Reconocimiento de productos en tiempo real con IA + enfoque específico en ferreterías. Integración con ventas y control.</td>
<td valign="top">Gestión de inventario multi-canal con buena interfaz, pero sin reconocimiento visual.</td>
<td valign="top">Gran capacidad de personalización y automatización, pero no especializado.</td>
<td valign="top">Alto poder de personalización en ecommerce, pero más generalista, sin reconocimiento visual.</td></tr>
<tr><td rowspan="2" valign="top">Perfil de Marketing</td><td valign="top">Mercado objetivo</td>
<td valign="top">Ferreterías, vendedores de productos físicos, administradores de puntos de venta.</td>
<td valign="top">PYMES con múltiples canales de venta.</td>
<td valign="top">Empresas medianas y grandes con procesos de ventas complejos.</td>
<td valign="top">Emprendedores, pymes y empresas que venden en línea.</td></tr>
<tr><td valign="top">Estrategias de marketing</td>
<td valign="top">Enfoque en contenido visual (demostraciones), alianzas con ferreterías, participación en ferias del sector.</td>
<td valign="top">Marketing B2B digital, webinars, presencia en comunidades de comercio electrónico.</td>
<td valign="top">Publicidad online, inbound marketing, fuerza de ventas directa.</td>
<td valign="top">Marketing digital masivo, influencers, SEO, redes sociales.</td></tr>
<tr><td rowspan="3" valign="top">Perfil de producto</td><td valign="top">Productos & Servicios</td>
<td valign="top">Reconocimiento de objetos, gestión de ventas, seguimiento de stock, reportes para administradores.</td>
<td valign="top">Gestión de inventario, pedidos, reportes, integración con ecommerce.</td>
<td valign="top">CRM, automatización de marketing, analíticas, gestión de clientes.</td>
<td valign="top">Tienda online, pagos, envíos, herramientas de marketing y reportes.</td></tr>
<tr><td valign="top">Precios & Costos</td>
<td valign="top">Modelo freemium con funcionalidades avanzadas por suscripción mensual (propuesta).</td>
<td valign="top">Planes desde $39/mes a más de $200, dependiendo de la funcionalidad.</td>
<td valign="top">Planes desde $14/mes, escalables por necesidades.</td>
<td valign="top">Desde $39/mes hasta planes empresariales. Costos adicionales por plugins.</td></tr>
<tr><td valign="top">Canales de distribución (Web y/o Móvil)</td>
<td valign="top">App móvil (iOS/Android), versión web en desarrollo (futuro).</td>
<td valign="top">Web app, sin versión móvil independiente.</td>
<td valign="top">Web app y apps móviles.</td>
<td valign="top">Web app y apps móviles.</td></tr>
<tr><td rowspan="4" valign="top">Análisis SWOT</td><td valign="top">Fortalezas</td>
<td valign="top">Enfoque especializado en ferreterías. Reconocimiento visual innovador. Facilidad de uso.</td>
<td valign="top">Sólido en inventario multi-canal. Buena integración con QuickBooks.</td>
<td valign="top">Potente CRM con automatizaciones. Altamente configurable.</td>
<td valign="top">Ecosistema completo de ecommerce. Alto reconocimiento de marca.</td></tr>
<tr><td valign="top">Debilidades</td>
<td valign="top">Producto nuevo, aún en fase inicial. Menor reconocimiento de marca.</td>
<td valign="top">No incluye funciones de reconocimiento visual. Puede ser complejo para nuevos usuarios.</td>
<td valign="top">No es específico para el sector ferretería. Curva de aprendizaje.</td>
<td valign="top">Competencia feroz, enfoque generalista. Costos ocultos con apps externas.</td></tr>
<tr><td valign="top">Oportunidades</td>
<td valign="top">Asociaciones con proveedores de ferretería. Escalabilidad con inteligencia artificial.</td>
<td valign="top">Integrarse con nuevas plataformas de ecommerce.</td>
<td valign="top">Expandirse en sectores nicho como retail técnico.</td>
<td valign="top">Aumentar integraciones con IA y automatización visual.</td></tr>
<tr><td valign="top">Amenazas</td>
<td valign="top">Entrada de grandes plataformas al nicho. Adopción tecnológica baja en ciertos mercados.</td>
<td valign="top">Dependencia de QuickBooks. Competencia creciente.</td>
<td valign="top">Saturación del mercado CRM. Nuevos players con IA.</td>
<td valign="top">Altos costos de operación. Competencia con marketplaces como Amazon.</td></tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores.

Detekto puede diferenciarse en el mercado ofreciendo una solución móvil especializada en el reconocimiento de herramientas y productos de ferretería mediante inteligencia artificial, un enfoque único frente a competidores más generalistas como TradeGecko, Zoho CRM y Shopify. Al centrarse en un mercado específico como el de las ferreterías y comercios de productos físicos, Detekto puede desarrollar funcionalidades para vendedores y administradores, como la identificación instantánea de productos, seguimiento de inventario y reportes automatizados de ventas.

A diferencia de plataformas como Shopify, que están orientadas a la creación de tiendas online generales, Detekto puede destacar por su simplicidad de uso, velocidad en el reconocimiento de objetos y utilidad directa en puntos de venta físicos. Frente a Zoho CRM, que apunta a la gestión de relaciones con clientes de múltiples industrias, Detekto puede posicionarse como una herramienta operativa y directa, que no requiere grandes configuraciones ni curvas de aprendizaje complejas.

Además, el desarrollo de capacidades avanzadas basadas en visión por computadora y el uso de datos para generar proyecciones y sugerencias de ventas permitirá que Detekto evolucione hacia una plataforma inteligente, útil tanto para vendedores como para administradores. Esta tecnología, poco explotada en el sector ferretero, representa una ventaja competitiva significativa.

Para enfrentar a TradeGecko, que ofrece sólidas funciones de gestión de inventario pero sin reconocimiento visual, Detekto puede aprovechar su facilidad de uso desde dispositivos móviles y su interfaz adaptada al trabajo en campo o mostrador. También puede incluir integraciones simples con sistemas contables o puntos de venta, cerrando así el ciclo completo de atención comercial.

Una estrategia de marketing centrada en demostrar el funcionamiento en tiempo real de la app, mediante videos y casos de éxito, junto a alianzas con cadenas de ferreterías, distribuidores de herramientas y cámaras de comercio local, puede permitir a Detekto ganar visibilidad y confianza. Además, capacitar a los usuarios con contenido sencillo y práctico ayudará a reducir barreras tecnológicas en sectores menos digitalizados.


## 2.2. Entrevistas.

### 2.2.1. Diseño de entrevistas.


Se han planteado varias interrogantes dirigidas a nuestro público objetivo, con el fin de recolectar información que nos proporcionen requisitos, lo que fortalecerá para el desarrollo de nuestra solución.

- Segmento 1: Vendedor

  - Preguntas generales (Vendedor):

    - ¿Cuál es tu nombre y edad?
    - ¿En qué distrito vives actualmente?
    - ¿Cuál es tu estado civil y con quién vives?
    - ¿Cuál es tu ocupación actual y cuántos años llevas trabajando como vendedor?
    - ¿Con qué frecuencia usas el celular o dispositivos móviles en tu trabajo?

  - Preguntas sobre necesidades (Vendedor)

    - ¿Cómo sueles buscar un producto en la tienda actualmente?
    - ¿Qué haces cuando un cliente no sabe el nombre de lo que necesita, pero lo describe o muestra una imagen?
    - ¿Cómo verificas si hay stock de un producto?
    - ¿Te sientes cómodo usando tecnología como apps móviles para trabajar? ¿Por qué?

  - Preguntas para profundizar (Vendedor)

    - ¿Te ha pasado que pierdes una venta por no encontrar rápido el producto?
    - ¿Usas alguna aplicación o sistema digital actualmente en tu trabajo? ¿Cuál?
    - ¿Qué tipo de celular usas? (marca/modelo)
    - ¿Qué tan frecuentemente accedes a redes sociales o apps desde el celular?
    - ¿Qué esperas de una app que te ayude en tu trabajo como vendedor?
    - ¿Qué es lo que más te frustra de tu día a día en el trabajo?

- Segmento 2: Administrador

  - Preguntas generales (Administrador):

    - ¿Cuál es su nombre y edad?
    - ¿Dónde vive actualmente?
    - ¿Cuál es su ocupación dentro del negocio? ¿Desde cuándo ocupa ese cargo?
    - ¿Qué nivel educativo tiene?
    - ¿Con qué frecuencia utiliza una computadora en su trabajo?

  - Preguntas sobre necesidades (Administrador)

    - ¿Cómo realiza actualmente el seguimiento de productos y stock en la tienda?
    - ¿Qué tipo de información le gustaría ver respecto a las ventas que realizan los vendedores?
    - ¿Cómo hace proyecciones o predicciones de ingresos o ganancias?
    - ¿Usa alguna herramienta digital (Excel, sistema contable, etc.) para la gestión del negocio?
    - ¿Qué tan cómodo se siente usando plataformas web o dashboards de datos?

  - Preguntas para profundizar (Administrador)

    - ¿Qué tipo de decisiones toma a partir de la información de ventas?
    - ¿Con qué frecuencia revisa el rendimiento de los vendedores?
    - ¿Qué tipo de reportes o gráficos le gustaría ver en una plataforma web?
    - ¿Qué le frustra más al momento de hacer seguimiento o gestión del negocio?
    - ¿Cuáles son sus objetivos principales como administrador de la tienda?

### 2.2.2. Registro de entrevistas.

**Entrevistas realizadas a Vendedores (Segmento 1):**

| **Entrevista 1** | **Carlos Raul** |
| --- | --- |
| **Edad** | 23 |
| **Ocupación** | Vendedor en una ferretería |
| **Distrito** | Villa El Salvador  |
| **Fecha** | 23/04/2025 |
| <img src="./assets/CAP2/entrevistas/segmento1_entrevista1.png"/> | Carlos, un joven vendedor de 23 años que trabaja en una ferretería desde hace casi dos años, compartió su experiencia diaria atendiendo clientes. Actualmente, realiza búsquedas de productos de forma manual, lo que le toma tiempo, especialmente cuando el cliente no conoce el nombre del artículo. En esos casos, Carlos intenta adivinar a partir de fotos o descripciones, lo que muchas veces genera demoras o incluso pérdida de ventas. Destacó que una de sus principales frustraciones es no encontrar rápidamente los productos o confirmar su disponibilidad, ya que no cuentan con un sistema digital de stock. Carlos usa con frecuencia su celular durante el trabajo y se siente cómodo con la tecnología, por lo que considera muy útil una app con reconocimiento de objetos mediante cámara. Espera que esta herramienta le permita identificar productos rápidamente, verificar su precio, stock y ubicación dentro de la tienda para mejorar su atención y eficiencia.|
| **URL de la grabación**  | [Ver grabación](Link-de-la-entrevista-completa)  |
| **Timming** | 0:05 - 21:06 |



| **Entrevista 2** | **Roberto Carranza** |
| --- | --- |
| **Edad** | 25 |
| **Ocupación** | Vendedor de ferretería |
| **Distrito** | Jesús María |
| **Fecha** | 24/02/2025 |
| <img src="./assets/CAP2/entrevistas/segmento1_entrevista2.png"/> | Roberto es un joven vendedor en una ferretería. Actualmente, en su trabajo utilizan un software antiguo para buscar stock y precios, lo cual resulta lento y ha ocasionado pérdida de ventas. Una de sus principales frustraciones es cuando los clientes traen una muestra sin saber el nombre del producto; él tiene que adivinar el nombre y la marca, ya que el sistema solo muestra resultados si se ingresan exactamente esos datos. Roberto considera que una aplicación que reconozca los productos a partir de una muestra y muestre diferentes marcas con precios y stock disponibles le facilitaría mucho el proceso de venta. |
| **URL de la grabación** | [Ver grabación](#) |
| **Timming** | 0:03 - 16:13 |








**Entrevistas realizadas a Administradores (Segmento 2):**

| **Entrevista 4** | **Luna Doly** |
| --- | --- |
| **Edad** | 30 |
| **Ocupación** | Administradora de una ferretería |
| **Distrito** | Jesús María, Lima |
| **Fecha** | 23/04/2025 |
| <img src="./assets/CAP2/entrevistas/segmento2_entrevista1.png"/> | La entrevista se realizó con Luna, administradora de una ferretería en Lima con más de 7 años de experiencia en el cargo. Actualmente gestiona el negocio utilizando principalmente Excel y realiza el seguimiento del stock y las ventas de forma manual. Está interesada en contar con una plataforma web sencilla que le permita visualizar el rendimiento de los vendedores, los productos más vendidos y hacer proyecciones de ganancias. Aunque se siente cómoda usando computadoras, prefiere herramientas simples y visuales. Sus principales frustraciones incluyen la falta de información actualizada y errores en los registros. Como administradora, su objetivo es optimizar la gestión del negocio, crecer y mejorar la organización interna con ayuda de herramientas digitales. |
| **URL de la grabación** | [Ver grabación](#) |
| **Timming** | 0:03 - 16:13 |



### 2.2.3. Análisis de entrevistas.

En base a las entrevistas realizadas, se ha llegado a la conclusión de 1 análisis para cada segmento objetivo.

**Segmento 1: Vendedor**


**Segmento 2: Administrador**


## 2.3. Needfinding.

### 2.3.1. User Personas.

A continuación se presentan los perfiles de nuestros segmentos objetivos, tales como los Vendedores, y los Administradores de las ferreterías, esta información es primordial para entender las necesidades específicas y diseñar una herramienta que facilite la detección de objetos de ferretería y de esta manera aumentar sus ventas.

- Segmento 1: Vendedor:

![UP-Vendedor](./assets/CAP2/User-Personas/UP_Vendedor_Juan%20Fernando.png)

- Segmento 2: Administrador:

![UP-Administrador](./assets/CAP2/User-Personas/UP_Administradora_Alexandra.png)

### 2.3.2. User Task Matrix.

En esta sección se detallan las tareas principales de los segmentos objetivos, en este caso, los vendedores y administradores de ferreterías, así como su frecuencia e importancia.

<table border="1">
  <tr>
    <th rowspan="2">Tareas</th>
    <th colspan="2">Vendedores</th>
    <th colspan="2">Administradores</th>
  </tr>
  <tr>
    <th>Frecuencia</th>
    <th>Importancia</th>
    <th>Frecuencia</th>
    <th>Importancia</th>
  </tr>
  <tr>
    <td>Buscar productos en el almacén o tienda</td>
    <td>Diario</td>
    <td>Alta</td>
    <td>Quincenal</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Identificar productos a partir de imágenes o descripciones</td>
    <td>Diario</td>
    <td>Alta</td>
    <td>Rara vez</td>
    <td>Baja</td>
  </tr>
  <tr>
    <td>Consultar stock</td>
    <td>Diario</td>
    <td>Alta</td>
    <td>Semanal</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Reservar productos para un cliente</td>
    <td>Varias veces por semana</td>
    <td>Alta</td>
    <td>Ocasional</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Registrar ventas o informar sobre ventas realizadas</td>
    <td>Diario</td>
    <td>Alta</td>
    <td>Semanal</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Hacer seguimiento a ventas realizadas</td>
    <td>Rara vez</td>
    <td>Media</td>
    <td>Semanal</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Analizar productos más vendidos</td>
    <td>Rara vez</td>
    <td>Media</td>
    <td>Semanal</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Hacer proyecciones de ingresos</td>
    <td>-</td>
    <td>-</td>
    <td>Quincenal</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Interactuar con tecnología</td>
    <td>Diario</td>
    <td>Media</td>
    <td>Diario</td>
    <td>Alta</td>
  </tr>
</table>

Las tareas que realizan en una empresa de ferretería son bastante similares a cualquier empresa de ventas, lo cual nos permite identificar las principales necesidades de nuestro público objetivo. A través de este análisis se pudo entender que, el vendedor realiza principalmente tareas operativas con una frecuencia diaria, relacionadas con la atención al cliente y búsqueda de productos. Por otro lado, la administradora desempeña un rol más estratégico y analítico, con tareas menos frecuentes pero de alta importancia, enfocadas a la supervisión de las ventas. Se destaca que ambos segmentos interactúan con herramientas digitales, aunque el enfoque y los propósitos son distintos.

### 2.3.3. Empathy Mapping.

Mediante este gráfico se evidencia las percepciones y sentimientos de los usuarios al interactuar con nuestra solución, este análisis nos permite conocer sobre sus desafíos que ellos poseen, y diseñar una propuesta más adecuada y centrada a sus requisitos.

- Segmento 1 - Vendedor:

![Empathy Map Vendedor](./assets/CAP2/Empathy-Mapping/EmpathyMapping_Vendedor_Juan%20Fernando.png)

- Segmento 2 - Administrador:

![Empathy Map Administrador](./assets/CAP2/Empathy-Mapping/EmpathyMapping_Administrador_Alexandra.png)

### 2.3.4. As-is Scenario Mapping.

En esta sección, se describen los procesos cotidianos, antes de la implementación de nuestra solución, esto nos permite identificar desafíos que sufren nuestro segmento objetivo, y a través de estos, encontrar oportunidades de mejora para mejorar el reconocimiento de objetos y mejorar las ventas en el sector ferretero.

- Segmento 1 - Vendedor:

![As-is Scenario Mapping Vendedor](./assets/CAP2/As-Is-Scenario-Mapping/As-Is%20Vendedor.png)

- Segmento 2 - Administrador:

![As-is Scenario Mapping Administrador](./assets/CAP2/As-Is-Scenario-Mapping/As-Is%20Administrador.png)

## 2.4. Ubiquitous Language.

En esta sección, se definen términos clave para el dominio del negocio, basándose en el enfoque de Ubiquitous Language propuesto por Eric Evans en Domain-Driven Design. Estas definiciones buscan asegurar una comunicación clara y efectiva entre los miembros del equipo, alineando el vocabulario técnico con las necesidades del proyecto.

- **Product (Producto)**: Herramienta o material físico que se encuentra en venta dentro de la ferretería.

- **Stock (Stock/Inventario)**: Cantidad disponible de cada producto en el almacén o tienda.

- **Sale (Venta)**: Transacción realizada entre un vendedor y un cliente por uno o más productos.

- **Seller (Vendedor)**: Persona encargada de atender al cliente, identificar los productos y concretar las ventas.

- **Administrator (Administrador)**: Persona responsable de supervisar el negocio, controlar las ventas y monitorear el inventario.

- **Recognition (Reconocimiento visual)**: Proceso por el cual la app identifica un producto mediante la cámara del celular.

- **Reservation (Reserva)**: Acción de apartar un producto para un cliente hasta que se concrete su compra.

- **Report (Reporte)**: Documento o visualización con datos organizados sobre ventas, productos o inventario.

- **Projection (Proyección)**: Estimación de ventas o ingresos futuros basada en el análisis de datos pasados.

- **Unavailable Product (Producto no disponible):** Producto que no se encuentra en stock al momento de la búsqueda.

- **Best Seller (Producto más vendido)**: Producto que ha tenido mayor número de ventas en un período determinado.

- **Break in Stock (Quiebre de stock)**: Situación en la que se agota un producto y no se cuenta con reposición inmediata.

- **Storefront (Mostrador)**: Zona de atención al cliente donde el vendedor interactúa directamente y realiza las ventas.

- **Warehouse (Almacén)**: Espacio físico donde se guardan los productos no exhibidos.

- **Shift (Turno)**: Período asignado de trabajo para los vendedores en el día.

- **Sales Summary (Resumen de ventas)**: Informe breve que muestra el total de ventas realizadas en un día o período específico.

- **Restock (Reabastecimiento)**: Acción de reponer productos que se han agotado en el inventario.

- **Visual Search (Búsqueda visual)**: Método para encontrar un producto a través de una imagen o la cámara, en lugar de una búsqueda por nombre.

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.
En esta sección, se visualiza el rendimiento esperado de la solución propuesta después de su implementación, se presentarán los flujos de trabajo, las interacciones y las mejoras con respecto al estado actual, resaltando cómo la aplicación propuesta resolverá problemas y optimizará los procesos existentes.

**Segmento 1: Vendedor:**

![To-be-Vendedor](./assets/capitulo-3/To-Be%20Vendedor.png)

**Segmento 2: Administrador:**

![To-be-Administrador](./assets/capitulo-3/To-Be%20Administrador.png)

## 3.2. User Stories.
En esta sección, se presentan las User Stories que rescatan las necesidades principales de nuestros usuarios finales, tanto vendedores como los administradores. Esto nos ayuda a definir y a priorizar funcionalidades críticas para asegurar que la aplicación cumpla con las expectativas del usuario.

<table align="center">
  <thead align="center">
    <tr>
      <th>Epic/User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relación (EPIC ID)</th>
    </tr>
  </thead>
  <tbody  align="center">
   <tr>
      <td>EP-01</td>
      <td>Gestión de cuenta</td>
      <td  align="justify">Como usuario, quiero gestionar mi cuenta, incluyendo la creación de mi perfil y configuración de preferencias y personalizar mi perfil.</td>
      <td  align="justify">
      -
      </td>
      <td>
         -
      </td>
    </tr>
    <tr>
      <td>EP-02</td>
      <td>Gestión de productos mediante escaneo visual</td>
      <td  align="justify">Como vendedor, quiero usar la cámara para reconocer productos, verificar stock, hacer reservas y revisar escaneos recientes, para agilizar mis tareas.</td>
      <td  align="justify">
      -
      </td>
      <td>
        -
      </td>
    </tr>
    <tr>
      <td>EP-03</td>
      <td>Monitoreo de vendedores en tiempo real</td>
      <td  align="justify">Como administrador, quiero visualizar en tiempo real la ubicación de los vendedores y su actividad para supervisar mejor su desempeño y tomar decisiones oportunas.</td>
      <td  align="justify">
        -
      </td>
      <td>
         -
      </td>
    </tr>
    <tr>
      <td>EP-04</td>
      <td>Control de asistencia de vendedores</td>
      <td  align="justify">Como administrador quiero tener un registro del horario de entrada y salida laboral de los vendedores</td>
      <td  align="justify">
        -
      </td>
      <td>
         -
      </td>
    </tr>
    <tr>
</tr>
    <tr>
      <td>HU-01</td>
      <td>Registrar cuenta</td>
      <td align="justify">Como usuario, quiero crear una cuenta para poder acceder a la aplicación.</td>
      <td  align="justify">
        <strong>Escenario 1: Proceso de registro</strong><br>
        Dado que el usuario desea crear una cuenta, cuando complete el formulario de registro en la aplicación, entonces la cuenta deberá ser creada y el usuario recibirá una confirmación.<br>
        <strong>Escenario 2: Verificación de cuenta</strong><br>
        Dado que el usuario ha registrado una cuenta, cuando la cuenta se cree,entonces el usuario deberá verificar su correo electrónico para activar la cuenta y acceder a la aplicación.</td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>HU-02</td>
      <td>Iniciar sesión</td>
      <td align="justify">Como usuario, quiero ingresar a mi cuenta para utilizar la aplicación.</td>
      <td  align="justify">
        <strong>Escenario 1: Acceso a la cuenta</strong><br>
        DadoDado que el usuario desea ingresar a la aplicación, cuando ingrese sus credenciales correctas, entonces deberá tener acceso a su cuenta y a todas las funcionalidades.<br>
        <strong>Escenario 2: Mensaje de error.</strong><br>
        Dado que el usuario ha ingresado credenciales incorrectas, cuando intente iniciar sesión, entonces deberá recibir un mensaje de error y la opción de intentar nuevamente.
      </td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>HU-03</td>
      <td>Cerrar sesión</td>
      <td align="justify">Como usuario quiero cerrar mi sesión para mantener mis datos seguros.</td>
      <td  align="justify">
        <strong>Escenario 1: Cierre de sesión</strong><br>
        Dado que el usuario desea cerrar su sesión, cuando seleccione la opción de cerrar sesión en la aplicación,entonces su sesión deberá finalizar y será redirigido a la pantalla de inicio.<br>
        <strong>Escenario 2: Confirmación de cierre.</strong><br>
        Dado que el usuario ha cerrado su sesión, cuando el proceso se complete, entonces deberá recibir una confirmación de que ha cerrado sesión exitosamente.
      </td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>HU-04</td>
      <td>Recuperar contraseña</td>
      <td align="justify">Como usuario, quiero recuperar mi contraseña en caso de olvidarla para poder acceder a mi cuenta.</td>
      <td  align="justify">
        <strong>Escenario 1: Solicitar recuperación.</strong><br>
        Dado que el usuario ha olvidado su contraseña, cuando seleccione la opción de recuperación de contraseña o proporcione su dirección de correo electrónico, entonces recibirá un enlace para restablecer la contraseña.<br>
        <strong>Escenario 2: Restablecer contraseña.</strong><br>
        Dado que el usuario ha recibido el enlace de recuperación, cuando siga el enlace y complete el formulario de restablecimiento de contraseña,entonces la contraseña deberá actualizarse y el usuario recibirá una confirmación de que la contraseña ha sido cambiada exitosamente.</td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>HU-05</td>
      <td>Escanear productos con la cámara</td>
      <td align="justify">Como vendedor, quiero identificar productos escaneándolos con la cámara para ahorrar tiempo.</td>
      <td  align="justify">
        <strong>Escenario 1: Producto reconocido correctamente</strong><br>
        Dado que el vendedor desea reconocer un producto, cuando lo escanee correctamente, entonces el sistema deberá mostrar su nombre, imagen, stock y precio.<br>
        <strong>Escenario 2: Producto no reconocido</strong><br>
        Dado que el vendedor desea reconocer un producto, cuando el sistema no lo identifique, entonces deberá mostrar un mensaje de error y sugerir búsqueda manual.
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>HU-06</td>
      <td>Verificar disponibilidad en stock</td>
      <td align="justify">Como vendedor, quiero conocer el stock de un producto escaneado para saber si puedo venderlo.</td>
      <td  align="justify">
        <strong>Escenario 1: Mostrar stock actualizado.</strong><br>
        Dado que el vendedor desea verificar disponibilidad, cuando el sistema muestre el producto, entonces deberá indicar su cantidad en stock.<br>
        <strong>Escenario 2: Considerar reservas activas.</strong><br>
        Dado que el vendedor desea información en tiempo real, cuando consulte el stock, entonces este deberá estar actualizado y reflejar reservas activas.
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>HU-07</td>
      <td>Reservar producto escaneado</td>
      <td align="justify">Como vendedor, quiero reservar productos para asegurar que estén disponibles para el cliente.</td>
      <td  align="justify">
        <strong>Escenario 1: Crear reserva temporal</strong><br>
        Dado que el vendedor desea reservar un producto, cuando lo seleccione, entonces el sistema deberá marcarlo como reservado.<br>
        <strong>Escenario 2: Liberar producto no vendido</strong><br>
        Dado que el vendedor desea mantener la reserva por un tiempo, cuando no se concrete la venta, entonces el producto deberá liberarse automáticamente.</td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>HU-08</td>
      <td>Ver historial de escaneos recientes.</td>
      <td align="justify">Como vendedor, quiero ver los últimos productos escaneados para acceder a ellos sin repetir el proceso.</td>
      <td  align="justify">
        <strong>Escenario 1: Acceso al historial visual.</strong><br>
        Dado que el vendedor desea revisar productos anteriores, cuando acceda al historial, entonces deberá ver los últimos 10 escaneos con nombre e imagen.<br>
        <strong>Escenario 2: Acceso rápido a escaneo previo.</strong><br>
        Dado que el vendedor desea rapidez, cuando seleccione un producto del historial, entonces deberá cargarse directamente su información.
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>HU-09</td>
      <td>Registrar una venta</td>
      <td align="justify">Como vendedor, quiero registrar una venta para llevar un control de las transacciones realizadas.</td>
      <td  align="justify">
        <strong>Escenario 1: Registro exitoso de venta</strong><br>
        Dado que el usuario desea recibir notificaciones de riego, cuando el sistema complete un riego, entonces enviará una notificación con detalles sobre el riego realizado.<br>
        <strong>Escenario 2: Validación antes del registro</strong><br>
        Dado que el vendedor desea registrar una venta, cuando el stock sea insuficiente o el producto no esté validado, entonces el sistema deberá impedir el registro y mostrar un mensaje.
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>HU-10</td>
      <td>Generar recibo de venta</td>
      <td align="justify">Como vendedor, quiero generar un recibo luego de registrar una venta para entregarlo al cliente como comprobante.</td>
      <td  align="justify">
        <strong>Escenario 1: Emisión automática del recibo</strong><br>
        Dado que el vendedor ha registrado una venta, cuando el proceso finalice, entonces el sistema deberá generar un recibo con resumen de productos, precios y total.<br>
        <strong>Escenario 2: Visualizar o reenviar recibo</strong><br>
        Dado que el vendedor desea compartir el recibo, cuando lo seleccione, entonces deberá poder visualizarlo, descargarlo o enviarlo por correo/WhatsApp.
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>HU-11</td>
      <td>Cancelar venta registrada recientemente</td>
      <td align="justify">Como vendedor, quiero cancelar una venta reciente en caso de error, para corregir información sin afectar el inventario.</td>
      <td  align="justify">
        <strong>Escenario 1: Cancelación dentro de límite de tiempo</strong><br>
        Dado que el vendedor desea cancelar una venta, cuando lo haga dentro de los 5 minutos posteriores al registro, entonces el sistema deberá anularla y actualizar el stock.<br>
        <strong>Escenario 2: Restricción tras tiempo límite</strong><br>
        Dado que el vendedor desea cancelar una venta pasada, cuando haya excedido el tiempo permitido, entonces el sistema deberá bloquear la acción y sugerir contacto con el administrador.
      </td>
      <td>EP-02</td>
    </tr>
     <tr>
      <td>HU-12</td>
      <td>Revisar ventas realizadas</td>
      <td align="justify">Como administrador, quiero revisar el historial de ventas realizadas por los vendedores para supervisar el rendimiento y tomar decisiones basadas en datos.</td>
      <td align="justify">
        <strong>Escenario 1: Consulta de ventas por fecha o vendedor.</strong><br>
        Dado que el administrador desea revisar el historial de ventas, cuando seleccione un rango de fechas o un vendedor específico, entonces el sistema deberá mostrar una lista con las ventas registradas, incluyendo fecha, productos y montos.<br>
        <strong>Escenario 2: Acceso a detalles de cada venta</strong><br>
        Dado que el administrador desea analizar información específica, cuando seleccione una venta de la lista, entonces deberá poder ver el detalle completo: productos vendidos, cantidades, método de pago y total.
        </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>HU-13</td>
      <td>Ver ubicación de vendedores activos</td>
      <td align="justify">Como administrador, quiero ver en el mapa la ubicación de los vendedores en tiempo real para supervisar sus rutas.</td>
      <td align="justify">
        <strong>Escenario 1: Seguimiento en vivo</strong><br>
        Dado que el administrador desea supervisar al equipo, cuando abra el panel de seguimiento, entonces el sistema deberá mostrar los vendedores con su última posición.<br>
        <strong>Escenario 2: Actualización continua</strong><br>
        Dado que el administrador desea ver rutas actuales, cuando el vendedor cambie de ubicación, entonces el sistema deberá actualizar automáticamente el mapa.
      </td>
      <td>EP-03</td>
    </tr>
    <tr>
      <td>HU-14</td>
      <td>Recibir alertas por inactividad o desvíos.</td>
      <td align="justify">Como administrador, quiero recibir alertas si un vendedor se detiene por mucho tiempo o se desvía de su ruta para poder actuar rápidamente.</td>
      <td  align="justify">
        <strong>Escenario 1: Notificación por inactividad prolongada</strong><br>
        Dado que el administrador desea detectar problemas, cuando un vendedor no se mueva por más de 20 minutos, entonces el sistema deberá emitir una alerta.<br>
        <strong>Escenario 2: Desvío de zona asignada</strong><br>
        Dado que el administrador desea asegurar el cumplimiento de zonas, cuando un vendedor salga del área establecida, entonces el sistema deberá notificar al administrador.
      </td>
      <td>EP-03</td>
    </tr>
    <tr>
      <td>HU-15</td>
      <td>Consultar historial de rutas por fecha</td>
      <td align="justify">Como administrador, quiero consultar la ruta que siguió un vendedor en un día específico para analizar su productividad.</td>
      <td  align="justify">
        <strong>Escenario 1: Selección de fecha y vendedor</strong><br>
        Dado que el administrador desea revisar rutas pasadas, cuando seleccione una fecha y vendedor, entonces el sistema deberá mostrar el trayecto registrado.<br>
        <strong>Escenario 2: Detalles de movimiento</strong><br>
        Dado que el administrador desea analizar el comportamiento, cuando revise la ruta, entonces deberá ver puntos de inicio, paradas, tiempo total y distancia recorrida.
      </td>
      <td>EP-03</td>
    </tr>
    <tr>
      <td>HU-16</td>
      <td>Registro de Entrada</td>
      <td align="justify">Como vendedor, quiero registrar mi hora de entrada al trabajo para que se contabilice mi asistencia diaria.</td>
      <td  align="justify">
        <strong>Escenario 1: Visualizar opción de marcar entrada</strong><br>
        Dado que el vendedor inicia su jornada laboral,cuando acceda a la sección de asistencia,entonces deberá ver un botón para marcar su entrada.<br>
        <strong>Escenario 2: Registrar la entrada correctamente</strong><br>
        Dado que el vendedor presione "Marcar entrada", cuando se confirme el registro, entonces se deberá almacenar la fecha y hora exacta del ingreso.
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
  <td>HU-17</td>
  <td>Registro de Salida</td>
  <td align="justify">Como vendedor, quiero registrar mi hora de salida para completar mi jornada laboral.</td>
  <td align="justify">
    <strong>Escenario 1: Opción habilitada tras marcar entrada</strong><br>
    Dado que el vendedor ya marcó su entrada, cuando entre nuevamente a la sección de asistencia, entonces deberá ver habilitado el botón de "Marcar salida".<br>
    <strong>Escenario 2: Registrar salida correctamente</strong><br>
    Dado que el vendedor presione "Marcar salida", cuando se confirme el registro, entonces se deberá almacenar la hora de salida y calcular el tiempo trabajado.
  </td>
  <td>EP-04</td>
</tr>
<tr>
      <td>HU-18</td>
      <td>Consultar Historial de Asistencia</td>
      <td align="justify">Como administrador, quiero consultar el historial de asistencia de los vendedores para hacer seguimiento de su cumplimiento.</td>
      <td  align="justify">
        <strong>Escenario 1: Visualizar historial por vendedor</strong><br>
        Dado que el administrador accede al historial, cuando seleccione un vendedor y un rango de fechas, entonces el sistema deberá mostrar los registros de entrada y salida correspondientes.<br>
        <strong>Escenario 2: Exportar historial</strong><br>
        Dado que el administrador ha generado una vista del historial, cuando seleccione "Exportar", entonces el sistema deberá permitir descargar el reporte en PDF o Excel.
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>HU-19</td>
      <td>Recordatorio de Marcación</td>
      <td align="justify">Como vendedor, quiero recibir una notificación si no he marcado entrada para no olvidar registrar mi asistencia.</td>
      <td  align="justify">
        <strong>Escenario 1: Envío de recordatorio automático</strong><br>
        Dado que es un día laboral y no se ha registrado entrada hasta las 10:00 a.m., cuando el sistema detecte esta condición, entonces enviará una notificación push al dispositivo del vendedor.<br>
        <strong>Escenario 2: No enviar en días no laborales</strong><br>
        Dado que el día está marcado como no laborable en el sistema, cuando no haya registro de entrada, entonces no se deberá enviar ninguna notificación.
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>HU-20</td>
      <td>Generar Reporte Mensual</td>
      <td align="justify">Como administrador, quiero generar un reporte mensual de asistencia para evaluar el rendimiento del personal.</td>
      <td  align="justify">
        <strong>Escenario 1: Seleccionar mes y empleado</strong><br>
        Dado que el administrador accede al módulo de reportes, cuando seleccione un mes y un vendedor, entonces deberá visualizar el resumen de asistencia.<br>
        <strong>Escenario 2: Descargar reporte</strong><br>
        Dado que el administrador visualiza el resumen mensual, cuando presione "Descargar", entonces el reporte deberá generarse en formato PDF o Excel.
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>HU-21</td>
      <td>Visualización de reportes diarios de ventas</td>
      <td align="justify">Como administrador, quiero ver un reporte de ventas diario para poder revisar el desempeño de las ventas del día y tomar decisiones sobre el stock.</td>
      <td  align="justify">
        <strong>Escenario 1: Reporte de ventas diarias</strong><br>
        Dado que el administrador ha llegado al final del día, cuando accede al dashboard de reportes, entonces podrá ver un reporte detallado de las ventas del día.<br>
        <strong>Escenario 2: Datos de ventas filtrados</strong><br>
        Dado que el administrador tiene el reporte de ventas diarias, cuando filtra las ventas por categoría o nombre, entonces podrá ver un reporte detallado de las ventas del día.
      </td>
      <td>EP-05</td>
    </tr>
    <tr>
      <td>HU-22</td>
      <td>Visualización sobre sugerencias sobre compras</td>
      <td align="justify">Como administrador, quiero recibir sugerencias de compras basadas en los reportes de ventas para tomar decisiones precisas.</td>
      <td  align="justify">
        <strong>Escenario 1: Sugerencia sobre compras</strong><br>
        Dado que el administrador está visualizando el reporte de ventas, cuando hace clic en un producto específico en el reporte, entonces el sistema mostrará una sugerencia automática sobre el restock del producto.<br>
        <strong>Escenario 2: Proyección de compras futuras</strong><br>
        Dado que el administrador está revisando el reporte de ventas, cuando de clic en “Proyecciones de compras futuras”, entonces el sistema mostrará una proyección basada en las ventas pasadas.
      </td>
      <td>EP-05</td>
    </tr>
    <tr>
      <td>HU-23</td>
      <td>Visualizaciones de proyecciones mensuales o en un rango</td>
      <td align="justify">Como administrador, quiero ver proyecciones mensuales de ventas y stock para poder planificar compras a largo plazo</td>
      <td  align="justify">
        <strong>Escenario 1: Proyecciones mensuales de ventas.</strong><br>
        Dado que el administrador desea planificar compras, cuando accede al panel de proyecciones mensuales, entonces el sistema mostrará una proyección de ventas para los próximos 30 días o un rango basado en datos históricos de ventas.<br>
        <strong>Escenario 2: Proyecciones del stock</strong><br>
        Dado que el administrador desea gestionar el stock, cuando visualiza las proyecciones de ventas, entonces, el sistema calculará y mostrará el stock necesario para cubrir las proyecciones de ventas del mes siguiente.
      </td>
      <td>EP-05</td>
    </tr>
    <tr>
      <td>HU-24</td>
      <td>Exportar reportes a formatos descargables</td>
      <td align="justify">Como administrador, quiero exportar los reportes generados en formatos como PDF o Excel para poder analizarlos fuera de la aplicación.</td>
      <td  align="justify">
        <strong>Escenario 1: Exportación en formato PDF.</strong><br>
        Dado que el administrador está viendo un reporte en la aplicación, cuando de clic al botón “Exportar en PDF”, entonces el sistema generará y descarga el reporte en formato PDF.<br>
        <strong>Escenario 2: Error al exportar en PDF</strong><br>
        Dado que el administrador está observando el reporte en la aplicación y se va el internet o sucede un error externo, cuando de clic a “Exportar en PDF”, entonces la aplicación mostrará un error “Error al exportar PDF”
      </td>
      <td>EP-05</td>
    </tr>
    <tr>
      <td>TS-01</td>
      <td>Desarrollar API para el registro del usuario</td>
      <td align="justify">Como Developer, quiero desarrollar una API RESTful que permita a los usuarios registrar sus cuentas en la aplicación.</td>
      <td  align="justify">
        <strong>Escenario 1: Solicitar creación de cuenta</strong><br>
        Dado que el usuario proporciona su nombre, correo electrónico y contraseña en el formulario de registro, cuando la API recibe la solicitud de registro, entonces debe almacenar los datos en la base de datos y devolver un código de respuesta HTTP 201 (Creado), junto con un mensaje de éxito.<br>
        <strong>Escenario 2: Error en la creación de cuenta</strong><br>
        Dado que el usuario proporciona datos incompletos o inválidos, cuando la API recibe la solicitud, entonces debe devolver un código de respuesta HTTP 400 (Bad Request), con un mensaje que indique los errores de validación (por ejemplo, "El correo electrónico ya está registrado").
      </td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>TS-02</td>
      <td>Desarrollar API para autenticación de usuario</td>
      <td align="justify">Como Developer, quiero crear una API RESTful que valide las credenciales de los usuarios (correo electrónico y contraseña) para generar un token de autenticación y permitir el acceso a la aplicación.</td>
      <td  align="justify">
        <strong>Escenario 1: Inicio de sesión exitoso.</strong><br>
        Dado que el usuario proporciona credenciales válidas (correo y contraseña), cuando la API recibe la solicitud de inicio de sesión, entonces debe devolver un código de respuesta HTTP 200, junto con el token de autenticación JWT.<br>
        <strong>Escenario 2: Error en inicio de sesión</strong><br>
        Dado que el usuario ingresa credenciales incorrectas, cuando la API recibe la solicitud de inicio de sesión, entonces debe devolver un código de respuesta HTTP 401 (Unauthorized), con un mensaje "Credenciales incorrectas".
      </td>
      <td>EP-01</td>
    </tr>
    <tr>
      <td>TS-03</td>
      <td>Desarrollar API para escanear productos</td>
      <td align="justify">Como Developer, quiero crear una API RESTful que reciba la imagen escaneada de un producto, lo procese y devuelva información relevante como el nombre, precio y stock del producto.</td>
      <td  align="justify">
        <strong>Escenario 1: Escaneo exitoso</strong><br>
        Dado que el vendedor escanea el producto desde la camara de su smartphone, cuando la API recibe la solicitud con el código de barras, entonces debe devolver un código de respuesta HTTP 200, con los datos del producto: nombre, precio, stock disponible.<br>
        <strong>Escenario 2: Escaneo fallido</strong><br>
        Dado que el el vendedor escanea el producto desde la camara de su smartphone, cuando la API no encuentra el producto en la base de datos, entonces debe devolver un código de respuesta HTTP 404 (Not Found), con un mensaje "Producto no encontrado".
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>TS-04</td>
      <td>Desarrollar API para registrar una venta</td>
      <td align="justify">Como Developer, quiero crear una API RESTful que registre una venta, incluyendo los productos vendidos, cantidades, precios y el total de la transacción.</td>
      <td  align="justify">
        <strong>Escenario 1: Registro de venta exitoso</strong><br>
        Dado que el vendedor proporciona los productos vendidos, sus cantidades y precios, cuando la API recibe la solicitud, entonces debe almacenar los datos de la venta en la base de datos y devolver un código de respuesta HTTP 201 (Creado), junto con los detalles de la venta (productos, cantidades, monto total).<br>
        <strong>Escenario 2: Error en registro de venta debido a stock insuficiente</strong><br>
        Dado que el stock de algún producto es insuficiente, cuando la API recibe la solicitud de venta, entonces debe devolver un código de respuesta HTTP 400 (Bad Request), con el mensaje "Stock insuficiente para el producto [nombre del producto]".
      </td>
      <td>EP-02</td>
    </tr>
    <tr>
      <td>TS-05</td>
      <td>Desarrollar API para generar reportes de ventas</td>
      <td align="justify">Como Developer, quiero desarrollar una API RESTful que permita generar reportes de ventas, filtrados por fecha, vendedor, o categoría de productos, y devolver los datos en formato JSON.</td>
      <td  align="justify">
        <strong>Escenario 1: Solicitar reporte de ventas filtrado</strong><br>
        Dado que el administrador selecciona un rango de fechas y un vendedor, cuando la API recibe la solicitud, entonces debe devolver un código de respuesta HTTP 200, con un listado de ventas que incluyan productos, cantidades, fechas y montos totales.<br>
        <strong>Escenario 2: Error al generar reporte</strong><br>
        Dado que el rango de fechas o los filtros proporcionados son inválidos, cuando la API procesa la solicitud, entonces debe devolver un código de respuesta HTTP 400, con el mensaje "Rango de fechas inválido".
      </td>
      <td>EP-05</td>
    </tr>
    <tr>
      <td>TS-06</td>
      <td>Desarrollar API para exportación de reportes</td>
      <td align="justify">Como Developer, quiero crear una API RESTful que permita exportar los reportes generados en formatos como PDF o Excel, para que el administrador pueda descargarlos.</td>
      <td  align="justify">
        <strong>Escenario 1: Exportación en formato PDF</strong><br>
        Dado que el administrador ha generado un reporte de ventas, cuando selecciona la opción de exportar en formato PDF, entonces la API debe generar el archivo PDF y devolverlo para su descarga con un código de respuesta HTTP 200.<br>
        <strong>Escenario 2: Error al exportar reporte</strong><br>
        Dado que ocurre un problema técnico (por ejemplo, conexión a internet caída), cuando la API intenta generar el reporte, entonces debe devolver un código de respuesta HTTP 500 (Internal Server Error), con el mensaje "Error al exportar reporte".
      </td>
      <td>EP-05</td>
    </tr>
    <tr>
      <td>TS-07</td>
      <td>Desarrollar API para geolocalización de vendedores</td>
      <td align="justify">Como Developer, quiero crear una API RESTful que reciba las coordenadas de los vendedores y las registre en la base de datos para que el administrador pueda ver las ubicaciones en tiempo real.</td>
      <td  align="justify">
        <strong>Escenario 1: Enviar ubicación del vendedor</strong><br>
        Dado que el vendedor envía su ubicación actual (latitud y longitud), cuando la API recibe la solicitud, entonces debe actualizar la base de datos con la nueva ubicación y devolver un código de respuesta HTTP 200.<br>
        <strong>Escenario 2: Error al enviar ubicación</strong><br>
        Dado que la ubicación enviada es inválida o está fuera de un rango permitido, cuando la API procesa la solicitud, entonces debe devolver un código de respuesta HTTP 400, con el mensaje "Ubicación inválida".
      </td>
      <td>EP-03</td>
    </tr>
    <tr>
      <td>TS-08</td>
      <td>API para registrar entrada de asistencia</td>
      <td align="justify">Como Developer, quiero desarrollar un endpoint que permita registrar la hora de entrada de un vendedor, para que el sistema almacene correctamente su inicio de jornada
</td>
      <td  align="justify">
        <strong>Escenario 1: Registrar entrada por primera vez en el día</strong><br>
        Dado que el vendedor ha iniciado sesión y no ha registrado entrada en la fecha actual, Cuando realiza un POST a <code> /api/asistencia/entrada</code> con su ID, Entonces el sistema debe guardar la fecha y hora actuales como hora de entrada
  Y retornar un mensaje de confirmación<br>
        <strong>Escenario 2: Intentar registrar entrada más de una vez</strong><br>
        Dado que el vendedor ya ha registrado su entrada en la fecha actual, cuando realiza un nuevo POST a <code>/api/asistencia/entrada</code> Entonces el sistema debe retornar un mensaje de error indicando que la entrada ya fue registrada
      </td>
      <td>EP-04</td>
    </tr>
    <tr>
      <td>TS-09</td>
      <td>API para registrar salida de asistencia</td>
      <td align="justify">Como Developer, quiero desarrollar un endpoint que registre la hora de salida del vendedor, para que se calcule automáticamente su tiempo trabajado.</td>
      <td  align="justify">
        <strong>Escenario 1: Registrar salida correctamente</strong><br>
        Dado que el vendedor ya registró su entrada en la fecha actual y aún no ha registrado su salida, Cuando realiza un POST a <code>/api/asistencia/salida</code> con su ID Entonces el sistema debe guardar la hora actual como salida.<br>
        <strong>Escenario 2: Intentar registrar salida sin haber registrado entrada</strong><br>
        Dado que el vendedor no ha registrado su entrada en la fecha actual, Cuando realiza un POST a <code>/api/asistencia/salida</code> Entonces el sistema debe retornar un mensaje de error indicando que no se puede registrar la salida sin una entrada previa.<br>
        <strong>Escenario 3: Intentar registrar salida más de una vez</strong><br>
         Dado que el vendedor ya ha registrado su salida en la fecha actual, Cuando realiza otro POST a <code>/api/asistencia/salida</code> Entonces el sistema debe retornar un mensaje de error indicando que la salida ya fue registrada.
      </td>
      <td>EP-04</td>
    </tr>
  </tbody>
</table>

## 3.3. Impact Mapping.
- Vendedor

<img src="assets/capitulo-3/Impact map 1.png" alt="Impact map 1" width="900"/>

- Administrador

<img src="assets/capitulo-3/Impact map 2.png" alt="Impact map 2" width="900"/>

## 3.4. Product Backlog.

| Orden | User Story ID | Título | Descripción | Story Points |
|:-----:|:-------------:|:------:|:-----------:|:------------:|
| 1 | HU-01 | Registrar cuenta | Como usuario, quiero crear una cuenta para poder acceder a la aplicación. | 2 |
| 2 | HU-02 | Iniciar sesión | Como usuario, quiero ingresar a mi cuenta para utilizar la aplicación. | 1 |
| 3 | HU-05 | Escanear productos con la cámara | Como vendedor, quiero identificar productos escaneándolos con la cámara para ahorrar tiempo. | 5 |
| 4 | HU-06 | Verificar disponibilidad en stock | Como vendedor, quiero conocer el stock de un producto escaneado para saber si puedo venderlo. | 3 |
| 5 | HU-07 | Reservar producto escaneado | Como vendedor, quiero reservar productos para asegurar su disponibilidad. | 3 |
| 6 | HU-08 | Ver historial de escaneos recientes | Como vendedor, quiero ver los últimos productos escaneados para agilizar consultas. | 2 |
| 7 | HU-09 | Registrar una venta | Como vendedor, quiero registrar una venta para llevar control de las transacciones. | 5 |
| 8 | HU-10 | Generar recibo de venta | Como vendedor, quiero generar un recibo luego de registrar una venta para el cliente. | 3 |
| 9 | HU-11 | Cancelar venta registrada recientemente | Como vendedor, quiero cancelar una venta reciente en caso de error. | 3 |
| 10 | HU-16 | Registro de Entrada | Como vendedor, quiero registrar mi hora de entrada al trabajo. | 2 |
| 11 | HU-17 | Registro de Salida | Como vendedor, quiero registrar mi hora de salida para completar la jornada. | 2 |
| 12 | HU-19 | Recordatorio de Marcación | Como vendedor, quiero recibir una notificación si olvido marcar entrada. | 2 |
| 13 | HU-03 | Cerrar sesión | Como usuario, quiero cerrar sesión para mantener mis datos seguros. | 1 |
| 14 | HU-04 | Recuperar Contraseña | Como usuario, quiero recuperar mi contraseña si la olvido. | 2 |
| 15 | HU-12 | Revisar ventas realizadas | Como administrador, quiero revisar ventas realizadas por los vendedores. | 5 |
| 16 | HU-21 | Visualización de reportes diarios de ventas | Como administrador, quiero ver reportes diarios de ventas para gestionar stock. | 5 |
| 17 | HU-22 | Visualización sobre sugerencias de compras | Como administrador, quiero recibir sugerencias automáticas de compras. | 3 |
| 18 | HU-23 | Visualización de proyecciones mensuales o rango | Como administrador, quiero ver proyecciones de ventas y stock. | 3 |
| 19 | HU-24 | Exportar reportes a formatos descargables | Como administrador, quiero exportar los reportes en PDF o Excel. | 2 |
| 20 | HU-13 | Ver ubicación de vendedores activos | Como administrador, quiero ver en el mapa la ubicación de vendedores. | 5 |
| 21 | HU-14 | Recibir alertas por inactividad o desvíos | Como administrador, quiero recibir alertas si un vendedor está inactivo o desviado. | 5 |
| 22 | HU-15 | Consultar historial de rutas por fecha | Como administrador, quiero consultar rutas seguidas por los vendedores. | 3 |
| 23 | HU-18 | Consultar Historial de Asistencia | Como administrador, quiero consultar el historial de asistencia de vendedores. | 3 |
| 24 | HU-20 | Generar Reporte Mensual | Como administrador, quiero generar un reporte mensual de asistencia. | 2 |
| 25 | TS-01 | Desarrollar API para registro de usuario | Como Developer, quiero desarrollar una API que permita registrar cuentas de usuario. | 3 |
| 26 | TS-02 | Desarrollar API para autenticación de usuario | Como Developer, quiero crear una API que valide credenciales y genere token de autenticación. | 3 |
| 27 | TS-03 | Desarrollar API para escanear productos | Como Developer, quiero crear una API que reciba imagen o código de barras y devuelva información del producto. | 5 |
| 28 | TS-04 | Desarrollar API para registrar una venta | Como Developer, quiero crear una API que registre productos vendidos, cantidades y total. | 5 |
| 29 | TS-05 | Desarrollar API para generar reportes de ventas | Como Developer, quiero crear una API que genere reportes filtrados por fechas, vendedores o categorías. | 5 |
| 30 | TS-06 | Desarrollar API para exportación de reportes | Como Developer, quiero crear una API que permita exportar los reportes en PDF o Excel. | 3 |
| 31 | TS-07 | Desarrollar API para geolocalización de vendedores | Como Developer, quiero crear una API que registre coordenadas de vendedores en tiempo real. | 5 |

# Capítulo IV: Strategic-Level Software Design.

## 4.1. Strategic-Level Attribute-Driven Design.

### 4.1.1. Design Purpose.

El propósito del diseño es desarrollar una solución tecnológica compuesta por una aplicación móvil para vendedores y una aplicación web para administradores. Esta solución debe facilitar la **gestión de productos**, **ventas y stock**, optimizando los tiempos de atención y asegurando la trazabilidad de las operaciones.

### 4.1.2. Attribute-Driven Design Inputs.
- Como **vendedor**, quiero usar reconocimiento de objetos para identificar productos rápidamente.

- Como **vendedor**, quiero verificar el stock en tiempo real para confirmar la disponibilidad del producto.

- Como **vendedor**, quiero reservar productos para asegurar que estén disponibles para el cliente.

- Como **vendedor**, quiero registrar las ventas para llevar un control de las transacciones.

- Como **vendedor**, quiero generar facturas para entregar un comprobante de compra al cliente.

- Como **administrador**, quiero revisar las ventas para mantener el control financiero.

- Como **administrador**, quiero ver y actualizar la lista de productos desde la web.

- Como **administrador**, quiero gestionar el inventario para evitar desabastecimientos o excesos.

- Como **administrador**, quiero crear y gestionar usuarios con diferentes roles y permisos.

- Como **administrador**, quiero generar reportes de ventas e inventario para la toma de decisiones.

- Como **cliente**, quiero ver el catálogo de productos con sus descripciones y precios.

#### 4.1.2.1. Primary Functionality (Primary User Stories).
Con el objetivo de priorizar las historias de usuario clave para el funcionamiento básico del sistema y la satisfacción de los usuarios finales, se listaron aquellas con mayor impacto funcional y valor de negocio en el *product backlog*.

| ID   | Título                                  | Descripción                                                                                                                                                                                                                             | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                                                           | Relacionado con (Epic ID) |
|------|------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------|
| US01 | Reconocimiento de Producto por Imagen    | Como vendedor, quiero escanear un producto con la cámara del celular para obtener su información automáticamente, de forma rápida y precisa.                                                                                           | Escenario 1: Reconocimiento exitoso. Dado que el vendedor escanea un producto, cuando el sistema reconoce el objeto, entonces se muestra su información (nombre, precio, stock).<br>Escenario 2: Error en reconocimiento. Dado que el sistema no reconoce el producto, cuando el vendedor lo escanea, entonces se muestra un mensaje indicando que no se encontró y se sugiere verificar la imagen o buscar manualmente. | EP01                       |
| US02 | Registro de Venta                        | Como vendedor, quiero registrar rápidamente la venta de un producto reconocido, para agilizar el proceso de atención al cliente.                                                                                                        | Escenario 1: Venta registrada correctamente. Dado que el producto fue reconocido, cuando el vendedor selecciona "Registrar venta", entonces la venta se almacena en el sistema y se actualiza el stock.<br>Escenario 2: Error en el registro. Dado un fallo en el sistema, cuando el vendedor intenta registrar la venta, entonces se muestra un mensaje de error y se sugiere reintentar.                            | EP02                       |
| US03 | Seguimiento de Ventas                    | Como administrador, quiero acceder a un panel donde pueda ver un resumen de las ventas realizadas, para monitorear el rendimiento del negocio.                                                                                        | Escenario 1: Visualización de estadísticas. Dado que el administrador accede al panel de ventas, cuando selecciona un rango de fechas, entonces el sistema muestra gráficos y datos agregados.<br>Escenario 2: Fallo en la carga del panel. Dado un error del sistema, cuando el administrador intenta visualizar las estadísticas, entonces se muestra un mensaje indicando la falla.                         | EP03                       |
| US04 | Proyecciones de Ventas                   | Como administrador, quiero ver proyecciones de ventas futuras basadas en el historial, para tomar decisiones informadas sobre inventario y estrategia comercial.                                                                       | Escenario 1: Proyección generada. Dado que el sistema cuenta con suficientes datos históricos, cuando el administrador solicita una proyección, entonces se muestra un gráfico con estimaciones de venta.<br>Escenario 2: Datos insuficientes. Dado que el historial de ventas es insuficiente, cuando se solicite una proyección, el sistema informará que no puede generar predicciones precisas aún.             | EP04                       |
#### 4.1.2.2. Quality attribute Scenarios.
| **Aspecto**     | **Escenario**                                                                                       | **Respuesta**                                                                                  |
|------------------|----------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| Rendimiento      | Cuando un vendedor escanea un objeto, la aplicación debe mostrar la información del producto en 2 segundos. | Alta prioridad, debe cumplirse para asegurar la satisfacción del usuario.                     |
| Usabilidad       | La interfaz de la aplicación móvil debe ser intuitiva, permitiendo que un nuevo vendedor aprenda las funciones básicas en 10 minutos de uso inicial. | El diseño debe priorizar la claridad y la navegación sencilla.                                |
| Seguridad        | El acceso a datos sensibles como los registros de ventas debe requerir mecanismos de autenticación y autorización. | Crítico para proteger la información del negocio.                                             |
| Disponibilidad   | La aplicación debe estar disponible el 99.9% del tiempo durante las horas de trabajo.             | Necesario para operaciones diarias confiables.                                                |
| Mantenibilidad   | El código debe ser modular y bien documentado para permitir actualizaciones y depuraciones sencillas. | Mejora la eficiencia del desarrollo y soporte a largo plazo.                                  |

#### 4.1.2.3. Constraints.

### 4.1.2.2. Technical Stories

Estas historias técnicas representan tareas esenciales para el soporte de funcionalidades clave, así como la mantenibilidad, rendimiento y seguridad de la aplicación.

| Technical Story ID | Título                                 | Descripción                                                                                                                                         | Criterios de Aceptación                                                                                                                                                                                                                       | Relacionado con (Epic ID) |
|--------------------|-----------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------|
| TS01               | Integración del Reconocimiento por Cámara | Implementar la funcionalidad que permite acceder a la cámara del dispositivo móvil para capturar imágenes y analizarlas con el modelo de IA.        | Escenario 1: Acceso correcto a la cámara. Cuando el usuario activa la cámara desde la app, entonces se debe abrir correctamente y permitir capturar una imagen.<br>Escenario 2: Fallo de acceso. Si la cámara no puede abrirse, mostrar error. | EP01                       |
| TS02               | Entrenamiento del Modelo de IA          | Entrenar y validar un modelo de machine learning capaz de identificar productos desde imágenes capturadas.                                          | Escenario 1: Precisión mayor al 90%. Al evaluar el modelo, debe alcanzar al menos un 90% de precisión en el reconocimiento.<br>Escenario 2: Generación de reporte de métricas de desempeño del modelo.                                      | EP01                       |
| TS03               | API de Ventas                           | Diseñar e implementar una API RESTful para registrar y consultar ventas realizadas a través de la aplicación móvil.                                 | Escenario 1: Registro exitoso. Cuando se envía una venta por POST, debe almacenarse correctamente y devolver una respuesta 200.<br>Escenario 2: Validación de campos obligatorios en el request.                                           | EP02                       |
| TS04               | Panel de Control para Administradores   | Crear el módulo backend y frontend para mostrar las estadísticas de ventas y proyecciones a los administradores.                                   | Escenario 1: El administrador puede consultar estadísticas por fecha y ver gráficos.<br>Escenario 2: El sistema debe alertar si los datos son insuficientes para proyecciones.                                                            | EP03 / EP04                |
| TS05               | Sistema de Autenticación                | Implementar un sistema de autenticación segura con tokens JWT para proteger rutas de administrador y vendedor.                                     | Escenario 1: Login válido. Dado un usuario registrado, cuando introduce sus credenciales, recibe un token JWT válido.<br>Escenario 2: Acceso restringido sin token. Si no hay token, no se puede acceder a rutas protegidas.               | EP03                       |


### 4.1.3. Architectural Drivers Backlog

Esta sección identifica los impulsores clave de la arquitectura que influyen significativamente en las decisiones de diseño del sistema.

| Driver ID | Título de Driver                     | Descripción                                                                                                           | Importancia para Stakeholders | Impacto en Architecture Technical Complexity |
|-----------|--------------------------------------|-----------------------------------------------------------------------------------------------------------------------|-------------------------------|----------------------------------------------|
| AD01      | Rendimiento en Reconocimiento de Objetos | El sistema debe reconocer objetos en menos de 2 segundos para asegurar fluidez en la experiencia de venta.            | High                          | High                                         |
| AD02      | Seguridad de Datos de Ventas         | Los datos de ventas y usuarios deben estar protegidos mediante autenticación y autorización robusta.                  | High                          | Medium                                       |
| AD03      | Escalabilidad del Sistema            | El sistema debe poder escalar a múltiples usuarios y dispositivos sin pérdida significativa de rendimiento.           | Medium                        | High                                         |
| AD04      | Disponibilidad de la Aplicación      | La app debe estar disponible el 99.9% del tiempo durante horarios de venta.                                           | High                          | Medium                                       |
| AD05      | Mantenibilidad del Código            | El sistema debe tener un código modular y documentado para facilitar actualizaciones futuras.                         | Medium                        | Medium                                       |
| AD06      | Interfaz Intuitiva                   | La interfaz debe ser lo suficientemente sencilla como para que un nuevo usuario la aprenda en 10 minutos.             | High                          | Low                                          |

### 4.1.4. Architectural Design Decisions.


Esta sección documenta las decisiones arquitectónicas clave tomadas durante el desarrollo del sistema, incluyendo el contexto, las alternativas evaluadas y las razones de la elección final.

| Decisión ID | Título de la Decisión                          | Descripción                                                                                                                                                                 | Justificación                                                                                                  |
|-------------|------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| DD01        | Uso de Arquitectura Basada en Componentes      | Se decidió estructurar la aplicación móvil y backend en componentes independientes (reconocimiento, ventas, autenticación, administración, etc.).                         | Favorece la mantenibilidad, permite trabajo paralelo y facilita futuras migraciones a microservicios.         |
| DD02        | Integración de Modelo IA con TensorFlow Lite   | Se optó por usar TensorFlow Lite para correr el modelo de reconocimiento de objetos directamente en dispositivos móviles.                                                  | Alta precisión y velocidad en dispositivos móviles; buena compatibilidad con Android/iOS.                     |
| DD03        | Almacenamiento en Firebase y Firestore         | Se eligió Firebase Authentication y Firestore para el backend de autenticación y almacenamiento de datos.                                                                  | Reduce complejidad operativa, ofrece escalabilidad y se integra fácilmente con apps móviles.                  |
| DD04        | Uso de JWT para Autenticación                  | Se decidió implementar autenticación basada en tokens JWT para proteger endpoints y gestionar sesiones de usuario.                                                         | Es una solución moderna, segura y ampliamente utilizada en aplicaciones móviles/web.                          |
| DD05        | Framework Flutter para el Frontend             | Se seleccionó Flutter como tecnología base para el desarrollo de la app móvil.                                                                                              | Permite desarrollo multiplataforma nativo (Android/iOS), alta velocidad de desarrollo y buena experiencia UX. |
| DD06        | API RESTful para Comunicación entre Módulos    | Se adoptó REST como estilo arquitectónico para la comunicación entre frontend y backend.                                                                                    | Simplicidad, amplia adopción y fácil de consumir desde cualquier cliente HTTP.                                |
| DD07        | Diseño Responsivo y Accesibilidad              | Se tomó la decisión de diseñar la interfaz siguiendo principios de diseño accesible y adaptable a distintos tamaños de pantalla.                                            | Mejora la experiencia del usuario y asegura inclusión de distintos perfiles de usuarios.                      |

### 4.1.5. Quality Attribute Scenario Refinements.
### 4.1.5. Quality Attribute Scenario Refinements

Refinamientos detallados para los escenarios de atributos de calidad, con el objetivo de precisar sus condiciones, respuestas esperadas y métricas asociadas.

| Quality Attribute | Escenario Original                                                                 | Refinamiento                                                                                                                               |
|-------------------|--------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| Rendimiento       | Mostrar información del producto en 2 segundos tras escanear un objeto              | El sistema debe garantizar que el tiempo total desde que el usuario abre la cámara hasta mostrar los resultados no exceda los 2000 ms.     |
| Usabilidad        | Interfaz intuitiva que permita aprender funciones básicas en 10 minutos             | Al menos el 90% de los nuevos usuarios debe poder completar una venta simulada en menos de 10 minutos sin ayuda externa.                   |
| Seguridad         | Requiere autenticación para acceder a datos sensibles                               | El acceso a datos sensibles debe requerir autenticación multifactor y roles de usuario (admin/vendedor) diferenciados.                    |
| Disponibilidad    | Disponible el 99.9% del tiempo durante horas de trabajo                             | Debe haber monitoreo activo y recuperación automática ante fallos para garantizar la disponibilidad mínima de 99.9% entre 8am y 8pm.       |
| Mantenibilidad    | Código modular y documentado                                                         | Todo nuevo módulo debe incluir pruebas unitarias, comentarios explicativos y cumplir con las guías internas de estilo y arquitectura.      |


## 4.2. Strategic-Level Domain-Driven Design.

### 4.2.1. EventStorming.
Dentro de este punto nos encontramos con estos 9 pasos a realizar:

**Step 1: Unstructured Exploration**

En este paso, se detectaron los siguientes puntos, los cuales posteriormente fueron utilizados dentro del sistema.

<img src="assets/capitulo-4/Eventstorming-Step-1.jpg" alt="Eventstorming-Step-1" width="900"/>

**Step 2: Timelines:**

En este paso se realizaron las distintas conexiones entre eventos del flujo de la aplicación.

<img src="assets/capitulo-4/Eventstorming-Step-2.jpg" alt="Eventstorming-Step-2" width="900"/>

**Step 3: Pain points**

En este paso se colocaron los eventos críticos y sus respectivos pain events identificados.

<img src="assets/capitulo-4/Eventstorming-Step-3.jpg" alt="Eventstorming-Step-3" width="900"/>

**Step 4: Pivotal points**

En este paso se incluyeron los pivotal points dentro del flujo de la aplicación

<img src="assets/capitulo-4/Eventstorming-Step-4.jpg" alt="Eventstorming-Step-4" width="900"/>

**Step 5: Commands**

En este paso se identificó los comandos realizados por sus respectivos actores.

<img src="assets/capitulo-4/Eventstorming-Step-5.jpg" alt="Eventstorming-Step-5" width="900"/>

**Step 6: Policies**

En este paso se incluyeron las políticas, escenarios donde la aplicación ejecuta alguna acción.

<img src="assets/capitulo-4/Eventstorming-Step-6.jpg" alt="Eventstorming-Step-6" width="900"/>

**Step 7: Read Models**

En este paso se realizó el modelo de lectura de cada sistema de la aplicación.

<img src="assets/capitulo-4/Eventstorming-Step-7.jpg" alt="Eventstorming-Step-7" width="900"/>

**Step 8: External systems**

En este paso se identificaron algunos sistemas externos.

<img src="assets/capitulo-4/Eventstorming-Step-8.jpg" alt="Eventstorming-Step-8" width="900"/>

**Step 9: Aggregates**

En este paso se implementan los agregados de cada sistema de la aplicación.

<img src="assets/capitulo-4/Eventstorming-Step-9.jpg" alt="Eventstorming-Step-9" width="900"/>

### 4.2.2. Candidate Context Discovery.

En este punto luego de la realización del Event storming, se identificaron los bounded context a trabajar. En este caso se lograron identificar 6.

<img src="assets/capitulo-4/Context Discovery-IAM.jpg" alt="Context Discovery-IAM" width="900"/>

<img src="assets/capitulo-4/Context Discovery-Object-Recognition.jpg" alt="Context Discovery-Object-Recognition" width="900"/>

<img src="assets/capitulo-4/Context Discovery-Notification.jpg" alt="Context Discovery-Notification" width="900"/>

<img src="assets/capitulo-4/Context Discovery-Tracking-And-Monitoring.jpg" alt="Context Discovery-Tracking-And-Monitoring" width="900"/>

<img src="assets/capitulo-4/Context Discovery-Reporting.jpg" alt="Context Discovery-Reporting" width="900"/>

<img src="assets/capitulo-4/Context Discovery-Sales.jpg" alt="Context Discovery-Sales" width="900"/>

Aquí podemos apreciarlo completo:

<img src="assets/capitulo-4/Context Discovery.jpg" alt="Context Discovery" width="900"/>

### 4.2.3. Domain Message Flows Modeling.

**Actor:** Supplier

**Escenario:** El proveedor inicia sesión

<img src="assets/capitulo-4/Modeling 1.jpg" alt="Modeling 1" width="900"/>

**Actor:** Supplier

**Escenario:** El proveedor registra una venta luego del escaneo exitoso

<img src="assets/capitulo-4/Modeling 2.jpg" alt="Modeling 2" width="900"/>

**Actor:** Supplier

**Escenario:** El proveedor registra una venta luego del escaneo exitoso

<img src="assets/capitulo-4/Modeling 3.jpg" alt="Modeling 3" width="900"/>

**Actor:** Admin

**Escenario:** El administrador revisa rutas y estado en vivo de vendedores

<img src="assets/capitulo-4/Modeling 4.jpg" alt="Modeling 4" width="900"/>

### 4.2.4. Bounded Context Canvases.

- IAM:

<img src="assets/capitulo-4/IAM.jpg" alt="IAM" width="900"/>

- Sales:

<img src="assets/capitulo-4/Sales.jpg" alt="Sales" width="900"/>

- Object Recognition:

<img src="assets/capitulo-4/Object Recognition.jpg" alt="Object Recognition" width="900"/>

- Tracking & Monitoring:

<img src="assets/capitulo-4/Tracking & Monitoring.jpg" alt="Tracking & Monitoring" width="900"/>

- Notifications:

<img src="assets/capitulo-4/Notifications.jpg" alt="Notifications" width="900"/>

### 4.2.5. Context Mapping.

## 4.3. Software Architecture.

### 4.3.1. Software Architecture System Landscape Diagram.

### 4.3.2. Software Architecture Context Level Diagrams.

<p align="center">
  <img src="assets/capitulo-4/structurizr-101688-SystemContext-001.png" alt="Imagen extraída de Figma" width="900"/>
</p>

### 4.3.3. Software Architecture Container Level Diagrams.

<p align="center">
  <img src="assets/capitulo-4/structurizr-101688-Container-001.png" alt="Imagen extraída de Figma" width="900"/>
</p>

### 4.3.4. Software Architecture Deployment Diagrams.

<p align="center">
  <img src="assets/capitulo-4/structurizr-101688-Component-001.png" alt="Imagen extraída de Figma" width="900"/>
</p>

