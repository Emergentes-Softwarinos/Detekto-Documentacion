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
### 4.1.2. Attribute-Driven Design Inputs.
#### 4.1.2.1. Primary Functionality (Primary User Stories).
#### 4.1.2.2. Quality attribute Scenarios.
#### 4.1.2.3. Constraints.
### 4.1.3. Architectural Drivers Backlog.
### 4.1.4. Architectural Design Decisions.
### 4.1.5. Quality Attribute Scenario Refinements.
## 4.2. Strategic-Level Domain-Driven Design.
### 4.2.1. EventStorming.
### 4.2.2. Candidate Context Discovery.
### 4.2.3. Domain Message Flows Modeling.
### 4.2.4. Bounded Context Canvases.
### 4.2.5. Context Mapping.
## 4.3. Software Architecture.
### 4.3.1. Software Architecture System Landscape Diagram.
### 4.3.1. Software Architecture Context Level Diagrams.
### 4.3.2. Software Architecture Container Level Diagrams.
### 4.3.3. Software Architecture Deployment Diagrams.
