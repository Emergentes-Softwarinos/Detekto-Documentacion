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
|  Ampudia Flores, Jose Carlos Isaac| u202112936 |
|  De La Piedra Quintanilla, Erwin Miquel      | U202112179 |
|  Elsner De La Torre Ugarte         | u202111654 |
| Gutierrez Zumaeta, Manuel Alonso           | U202112353 |

#### Ciclo 2025-10

##### Abril, 2025

---

# Registro de Versiones del informe

| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|--------|------------------------------|
| 0.1     |       |        |                              |
| 0.2     |       |        |                              |
| 0.3     |       |        |                              |
| 0.4     |       |        |                              |
| 0.5     |       |        |                              |

# Project Report Collaboration Insights
Para el desarrollo del proyecto, se ha utilizado la plataforma de GitHub para el control correcto de versiones y la colaboración de los integrantes del equipo. A continuación se presenta el link directo a la organización del equipo:

**Link de organización Softwarinos:**  
[https://github.com/Emergentes-Softwarinos](https://github.com/Emergentes-Softwarinos)

## TB1

Para la entrega de la TB1 se realizó una reunión donde se asignaron las responsabilidades a cada integrante del equipo. A continuación se muestra la siguiente tabla con los detalles:

| Integrante           | Responsabilidad |
|----------------------|-----------------|
| José Ampudia         |                 |
| Manuel Gutierrez     |                 |
| Miquel De la Piedra  |                 |
| Julio De la Torre    |                 |

Durante la elaboración de las aplicaciones, tanto web como mobile, se realizaron *commits* respectivos con el fin de mantener el orden y un control de versiones eficiente.

Para tener mejor precisión en los integrantes del equipo, a continuación presentamos los usuarios de GitHub de los integrantes:

- José Ampudia (@IsaacAmp24)  
- Manuel Gutierrez (@ManuGZ)  
- Miquel De la Piedra (@MiquelDlp)  
- Julio De la Torre (@)  

A continuación se presentan las capturas del repositorio de GitHub donde se realizaron los avances correspondientes.

# Tabla de contenidos

# Studen Outcome

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo
## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática
### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.
#### 1.2.2.2. Lean UX Assumptions.
#### 1.2.2.3. Lean UX Hypothesis Statements.
#### 1.2.2.4. Lean UX Canvas.
## 1.3. Segmentos objetivo.
# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
### 2.1.1. Análisis competitivo.
### 2.1.2. Estrategias y tácticas frente a competidores.
## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
### 2.2.2. Registro de entrevistas.
### 2.2.3. Análisis de entrevistas.
## 2.3. Needfinding.
### 2.3.1. User Personas.
### 2.3.2. User Task Matrix.
### 2.3.3. Empathy Mapping.
### 2.3.4. As-is Scenario Mapping.
## 2.4. Ubiquitous Language.
# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping.
## 3.2. User Stories.
## 3.3. Impact Mapping.
## 3.4. Product Backlog.
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


### 4.1.3. Architectural Drivers Backlog.
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
### 4.1.4. Architectural Design Decisions

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
