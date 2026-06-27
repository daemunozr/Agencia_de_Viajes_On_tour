# Propuesta Técnica

## Descripción del proyecto

El sistema Agencia de Viajes OnTour permite que los apoderados consulten información sobre la gira de estudios de sus hijos mediante una plataforma web.

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

- El usuario puede iniciar sesión con RUT y contraseña.
- Si las credenciales son incorrectas, el sistema muestra un mensaje de error.
- La sesión se inicia correctamente al validar los datos.

---

## HU-02 - Dashboard Financiero

- Se muestra el saldo acumulado.
- Se muestra la meta total.
- Se calcula correctamente el saldo pendiente.
- Se muestra el porcentaje de avance.

---

## HU-03 - Historial de Depósitos

- Se listan todos los depósitos registrados.
- Cada depósito muestra fecha, monto y comprobante.
- Los depósitos aparecen ordenados por fecha.
- Envio automatico de correo electronico con el resultado del deposito, tanto al apoderado como al ejecutivo.
- El correo electrónico enviado debe incluir los datos clave del abono  para asegurar la transparencia financiera inmediata.

---

## HU-04 - Descarga de Contrato

- El contrato puede descargarse en formato PDF.
- Si no existe contrato, se informa al usuario.
- Si el contrato no está disponible, el sistema muestra un mensaje informativo al usuario.

---

## HU-05 - Descarga de Póliza

- La póliza puede descargarse en PDF.
- Se muestran las coberturas del seguro.
- El sistema valida que la póliza esté asociada al alumno antes de permitir la descarga.

---

## HU-06 - Administración de Contratos

- El sistema permite al ejecutivo cargar documentos digitales de contratos. 
- El sistema valida obligatoriamente que el RUT del apoderado antes de guardar o actualizar el estado del contrato.
- El ejecutivo puede modificar y actualizar el estado del contrato.
- El sistema permite al ejecutivo agregar y configurar las pólizas de seguros.
- El sistema confirma visualmente al ejecutivo y al apoderado cuando el contrato se han guardado exitosamente.

---

## HU-07 - Reporte de Avance

- La gerencia puede visualizar indicadores.
- El reporte puede exportarse a PDF y Excel.
- Criterio adicional sugerido: "El reporte refleja datos actualizados en tiempo real según los depósitos registrados.

---

## HU-08 - Gestión de Usuarios

- El administrador puede crear, modificar y desactivar cuentas de usuarios, asociándoles un rol.
- El sistema permite al administrador crear y actualizar los destinos de viaje disponibles.
- El sistema permite al administrador registrar y modificar los tipos de actividades comunes que los cursos pueden realizar para recaudar fondos.
- El sistema permite al administrador mantener la información maestra de los clientes que contratan servicios.
- Al intentar registrar un elemento duplicado, el sistema despliega un mensaje de advertencia y bloquea la duplicidad.
- El administrador puede visualizar un listado de todos los mantenedores activos con opciones de búsqueda o filtrado básico.

## Evaluación de Calidad ISO/IEC 25010

| Característica | De la Aplicación                                                                                                                                                                                                                                           |
| ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Usabilidad         | El proyecto está orientado a los apoderados, permitiéndoles consultar información relevante como saldo, depósitos, contratos y pólizas desde una plataforma web. La definición clara de los objetivos facilita el diseño de una interfaz sencilla e intuitiva. |
| Fiabilidad         | Se identifican las funciones principales que manejarán información financiera y contractual, lo que permite establecer una base para ofrecer datos consistentes y actualizados a los usuarios.                                                                 |
| Seguridad          | La definición de distintos actores (Apoderado, Ejecutivo, Gerencia y Administrador) permite implementar posteriormente un control de acceso basado en roles, restringiendo las funciones según el perfil del usuario.                                          |
| Eficiencia         | Al concentrar las funcionalidades principales en una plataforma web, los usuarios podrán acceder rápidamente a la información sin depender de reuniones presenciales o solicitudes por correo electrónico, reduciendo tiempos de consulta.                     |
| Mantenibilidad     | El uso de tecnologías estándar como HTML5, CSS3 y JavaScript favorece el mantenimiento y futuras mejoras del sistema. Además, GitHub permite gestionar cambios, controlar versiones y facilitar el trabajo colaborativo durante el desarrollo.                 |
