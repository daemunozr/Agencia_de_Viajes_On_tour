# Propuesta Técnica

## Descripción del caso Agencia de Viajes "On Tour"

### ¿Quiénes son?

Agencia con más de 20 años de experiencia en turismo internacional. En los últimos 5 años expandió su oferta hacia giras de estudio para colegios, un segmento en crecimiento por la baja en precios de vuelos y la tendencia de colegios a realizar este tipo de actividades.

### ¿Cómo funciona el proceso hoy?

Un colegio contacta a la agencia, firma un contrato con un ejecutivo de ventas y debe juntar un fondo común entre los apoderados del curso para pagar el paquete turístico. Los aportes se hacen mediante actividades como fiestas y rifas, y los depósitos se envían por correo electrónico a la agencia.

---

### La Problemática

El proceso actual es completamente manual y poco transparente, lo que genera tres grandes problemas:

**Para los apoderados**
- No tienen copia del contrato ni acceso a las condiciones del viaje
- No saben cuánto han aportado ni cuánto les falta pagar
- No conocen los seguros contratados ni los planes de emergencia
- Deben pedir reuniones o escribir correos solo para obtener información básica

**Para la agencia**
- No tiene visibilidad clara y oportuna de los depósitos recibidos por curso
- Pierde oportunidades de negocio porque no puede satisfacer las exigencias de información de los apoderados
- Le cuesta negociar seguros de forma eficiente con aseguradoras externas

La falta de transparencia y comunicación genera desconfianza en los clientes, lo que impacta directamente en las ventas de la agencia.

---

## Descripción del proyecto

El sistema Agencia de Viajes OnTour permite a ejecutivos, apoderados, representantes de curso y el dueño de la agencia acceder en cualquier momento a información actualizada sobre contratos, aportes, seguros y estado de avance de cada curso.

## Objetivos

- Consultar saldo acumulado.
- Visualizar historial de depósitos.
- Descargar contratos.
- Descargar pólizas.
- Generar reportes para la gerencia.

## Actores

| Actor | Necesidad |
|--------|-----------|
| Apoderado | Consultar saldo acumulado |
| Ejecutivo | Administrar contratos |
| Administrador | Mantener información |
| Gerencia | Consultar indicadores |

## Funcionalidades

| Funcionalidad | Prioridad |
|---------------|-----------|
| Consultar saldo | Alta |
| Descargar contrato | Alta |
| Descargar póliza | Alta |
| Consultar depósitos | Alta |

## Tecnologías

- HTML5
- CSS3
- JavaScript
- GitHub

# Historias de Usuario

## HU-01 - Inicio de Sesión

**Como** apoderado  **Quiero** iniciar sesión con mi RUT y contraseña  **Para** acceder de forma segura a la información de la gira de mi hijo/a.

---

## HU-02 - Dashboard Financiero

**Como** apoderado  **Quiero** ver mi saldo acumulado, meta total, saldo pendiente y porcentaje de avance  **Para** conocer el estado financiero de la gira en tiempo real.

---

## HU-03 - Historial de Depósitos

**Como** apoderado  **Quiero** revisar el historial completo de mis depósitos con fecha, monto y comprobante  **Para** verificar que todos mis pagos fueron registrados correctamente.

---

## HU-04 - Descarga de Contrato

**Como** apoderado  **Quiero** descargar mi contrato en formato PDF  **Para** revisar las condiciones del servicio cuando lo necesite.

---

## HU-05 - Descarga de Póliza

**Como** apoderado  **Quiero** descargar la póliza de seguro de la gira  **Para** conocer las coberturas contratadas antes del viaje.

---

## HU-06 - Administración de Contratos

**Como** ejecutivo  **Quiero** cargar, actualizar y administrar los contratos de los apoderados  **Para** mantener la documentación disponible y actualizada.

---

## HU-07 - Reporte de Avance

**Como** gerente  **Quiero** visualizar un reporte consolidado del avance financiero de las giras  **Para** tomar decisiones estratégicas y realizar seguimiento.

---

## HU-08 - Gestión de Usuarios

**Como** administrador  **Quiero** gestionar usuarios y roles del sistema  **Para** mantener el control de acceso y la seguridad de la plataforma.

# Criterios de Aceptación

## HU-01 - Inicio de Sesión

| ID   | Criterio de Aceptación |
|------|------------------------|
| CA01 | El usuario puede iniciar sesión con RUT y contraseña. |
| CA02 | Si las credenciales son incorrectas, el sistema muestra un mensaje de error. |
| CA03 | La sesión se inicia correctamente al validar los datos. |

---

## HU-02 - Dashboard Financiero

| ID   | Criterio de Aceptación |
|------|------------------------|
| CA01 | Se muestra el saldo acumulado. |
| CA02 | Se muestra la meta total. |
| CA03 | Se calcula correctamente el saldo pendiente. |
| CA04 | Se muestra el porcentaje de avance. |

---

## HU-03 - Historial de Depósitos

| ID   | Criterio de Aceptación |
|------|------------------------|
| CA01 | Se listan todos los depósitos registrados. |
| CA02 | Cada depósito muestra fecha, monto y comprobante. |
| CA03 | Los depósitos aparecen ordenados por fecha. |
| CA04 | El sistema envía automáticamente un correo electrónico con el resultado del depósito, tanto al apoderado como al ejecutivo. |
| CA05 | El correo electrónico enviado incluye los datos clave del abono para asegurar la transparencia financiera inmediata. |

---

## HU-04 - Descarga de Contrato

| ID   | Criterio de Aceptación |
|------|------------------------|
| CA01 | El contrato puede descargarse en formato PDF. |
| CA02 | Si no existe contrato, se informa al usuario. |
| CA03 | El nombre del archivo descargado incluye el RUT del apoderado y la fecha de emisión. |

---

## HU-05 - Descarga de Póliza

| ID   | Criterio de Aceptación |
|------|------------------------|
| CA01 | La póliza puede descargarse en PDF. |
| CA02 | Se muestran las coberturas del seguro. |
| CA03 | El sistema valida que la póliza esté asociada al alumno antes de permitir la descarga. |

---

## HU-06 - Administración de Contratos

| ID   | Criterio de Aceptación |
|------|------------------------|
| CA01 | El sistema permite al ejecutivo cargar documentos digitales de contratos. |
| CA02 | El sistema valida que el RUT del apoderado tenga formato válido y exista en el sistema antes de permitir guardar o actualizar el estado del contrato. |
| CA03 | El ejecutivo puede modificar y actualizar el estado del contrato. |
| CA04 | El sistema permite al ejecutivo agregar y configurar las pólizas de seguros. |
| CA05 | El sistema confirma visualmente al ejecutivo y al apoderado cuando el contrato se ha guardado exitosamente. |

---

## HU-07 - Reporte de Avance

| ID   | Criterio de Aceptación |
|------|------------------------|
| CA01 | La gerencia puede visualizar indicadores. |
| CA02 | El reporte puede exportarse a PDF y Excel. |
| CA03 | El reporte refleja datos actualizados en tiempo real según los depósitos registrados. |

---

## HU-08 - Gestión de Usuarios

| ID   | Criterio de Aceptación |
|------|------------------------|
| CA01 | El administrador puede crear, modificar y desactivar cuentas de usuarios, asociándoles un rol. |
| CA02 | El sistema permite al administrador crear y actualizar los destinos de viaje disponibles. |
| CA03 | El sistema permite al administrador registrar y modificar los tipos de actividades comunes que los cursos pueden realizar para recaudar fondos. |
| CA04 | El sistema permite al administrador mantener la información maestra de los clientes que contratan servicios. |
| CA05 | Al intentar registrar un elemento duplicado, el sistema despliega un mensaje de advertencia y bloquea la duplicidad. |
| CA06 | El administrador puede visualizar un listado de todos los mantenedores activos con opciones de búsqueda o filtrado básico. |

## Evaluación de Calidad ISO/IEC 25010

| Característica | De la Aplicación                                                                                                                                                                                                                                           |
| ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Usabilidad         | Se diseña una interfaz con navegación lateral fija y acceso directo desde el dashboard a saldo, depósitos, contrato y póliza, reduciendo a un máximo de 2 clics cualquier consulta frecuente del apoderado. |
| Fiabilidad         | Cada depósito registrado actualiza el saldo acumulado de forma inmediata y genera una confirmación por correo al apoderado y ejecutivo, garantizando que la información mostrada refleje siempre el estado real del fondo. |
| Seguridad          | El acceso al sistema requiere autenticación con RUT y contraseña. Cada rol (Apoderado, Ejecutivo, Administrador, Gerencia) tiene acceso restringido solo a las funcionalidades que le corresponden, bloqueando rutas no autorizadas. |
| Eficiencia         | Al concentrar las funcionalidades principales en una plataforma web, los usuarios podrán acceder rápidamente a la información sin depender de reuniones presenciales o solicitudes por correo electrónico, reduciendo tiempos de consulta.                     |
| Mantenibilidad     | El uso de tecnologías estándar como HTML5, CSS3 y JavaScript favorece el mantenimiento y futuras mejoras del sistema. Además, GitHub permite gestionar cambios, controlar versiones y facilitar el trabajo colaborativo durante el desarrollo.                 |

# Casos de Prueba

| ID    | HU / CA          | Caso de Prueba                                    | Datos Entrada                          | Resultado Esperado                          | Resultado Obtenido | Estado    |
|-------|------------------|---------------------------------------------------|----------------------------------------|---------------------------------------------|--------------------|-----------|
| CP-01 | HU-01 / CA01, CA03 | Login con credenciales válidas                  | RUT: 12345678-9 / Pass: 1234           | Acceso al dashboard                         | —                  | Pendiente |
| CP-02 | HU-01 / CA02     | Login con contraseña incorrecta                   | RUT: 12345678-9 / Pass: wrong          | Mensaje de error                            | —                  | Pendiente |
| CP-03 | HU-02 / CA01–CA04 | Ver saldo acumulado en dashboard                 | Usuario autenticado                    | Muestra saldo, meta, saldo pendiente y % avance | —              | Pendiente |
| CP-04 | HU-03 / CA01–CA03 | Historial de depósitos ordenado                  | Usuario con 3 depósitos                | Lista ordenada por fecha con monto y comprobante | —             | Pendiente |
| CP-05 | HU-04 / CA01     | Descargar contrato en PDF                         | Contrato disponible                    | Archivo PDF descargado                      | —                  | Pendiente |
| CP-06 | HU-04 / CA02     | Descargar contrato sin archivo                    | Sin contrato registrado                | Mensaje "contrato no disponible"            | —                  | Pendiente |
| CP-07 | HU-05 / CA01–CA02 | Descargar póliza de seguro                       | Póliza disponible                      | PDF con coberturas descargado               | —                  | Pendiente |
| CP-08 | HU-06 / CA01–CA02 | Ejecutivo carga contrato nuevo                   | RUT válido + archivo PDF               | Contrato registrado en sistema              | —                  | Pendiente |
| CP-09 | HU-06 / CA02     | Ejecutivo carga contrato con RUT inválido         | RUT: 00000000-0                        | Error de validación                         | —                  | Pendiente |
| CP-10 | HU-07 / CA01, CA03 | Gerencia visualiza reporte de avance            | Usuario con rol Gerencia               | Reporte con % por curso visible             | —                  | Pendiente |
| CP-11 | HU-08 / CA01     | Admin crea nuevo usuario                          | Datos completos del usuario            | Usuario creado y activo                     | —                  | Pendiente |
| CP-12 | HU-08 / CA01     | Admin desactiva usuario                           | Usuario existente                      | Usuario marcado como inactivo               | —                  | Pendiente |
| CP-13 | HU-07 / CA02     | Gerencia exporta reporte a PDF                    | Usuario con rol Gerencia y reporte visible | Archivo PDF generado y descargado       | —                  | Pendiente |
| CP-14 | HU-05 / CA03     | Apoderado intenta descargar póliza de otro curso  | Póliza no asociada al alumno           | Mensaje de error y descarga bloqueada       | —                  | Pendiente |
| CP-15 | HU-08 / CA02     | Admin crea nuevo destino de viaje                 | Nombre y descripción del destino       | Destino registrado y visible en el sistema  | —                  | Pendiente |
| CP-16 | HU-08 / CA05     | Admin intenta registrar usuario con RUT duplicado | RUT ya existente en el sistema         | Mensaje de advertencia y bloqueo de duplicidad | —              | Pendiente |

---

# Registro de Defectos

| ID Defecto | Caso Relacionado | Descripción | Severidad | Estado |
|---|---|---|---|---|
| — | — | Sin defectos detectados. Casos de prueba pendientes de ejecución. | — | — |
