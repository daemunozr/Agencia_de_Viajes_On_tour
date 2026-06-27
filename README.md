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

- Apoderado
- Ejecutivo
- Gerencia
- Administrador

## Tecnologías

- HTML5
- CSS3
- JavaScript
- GitHub
# Historias de Usuario

## HU-01 - Inicio de Sesión

**Como** apoderado  
**Quiero** iniciar sesión con mi RUT y contraseña  
**Para** acceder de forma segura a la información de la gira de mi hijo/a.

---

## HU-02 - Dashboard Financiero

**Como** apoderado  
**Quiero** ver mi saldo acumulado, meta total, saldo pendiente y porcentaje de avance  
**Para** conocer el estado financiero de la gira en tiempo real.

---

## HU-03 - Historial de Depósitos

**Como** apoderado  
**Quiero** revisar el historial completo de mis depósitos con fecha, monto y comprobante  
**Para** verificar que todos mis pagos fueron registrados correctamente.

---

## HU-04 - Descarga de Contrato

**Como** apoderado  
**Quiero** descargar mi contrato en formato PDF  
**Para** revisar las condiciones del servicio cuando lo necesite.

---

## HU-05 - Descarga de Póliza

**Como** apoderado  
**Quiero** descargar la póliza de seguro de la gira  
**Para** conocer las coberturas contratadas antes del viaje.

---

## HU-06 - Administración de Contratos

**Como** ejecutivo  
**Quiero** cargar, actualizar y administrar los contratos de los apoderados  
**Para** mantener la documentación disponible y actualizada.

---

## HU-07 - Reporte de Avance

**Como** gerente  
**Quiero** visualizar un reporte consolidado del avance financiero de las giras  
**Para** tomar decisiones estratégicas y realizar seguimiento.

---

## HU-08 - Gestión de Usuarios

**Como** administrador  
**Quiero** gestionar usuarios y roles del sistema  
**Para** mantener el control de acceso y la seguridad de la plataforma.
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

---

## HU-04 - Descarga de Contrato

- El contrato puede descargarse en formato PDF.
- Si no existe contrato, se informa al usuario.

---

## HU-05 - Descarga de Póliza

- La póliza puede descargarse en PDF.
- Se muestran las coberturas del seguro.

---

## HU-06 - Administración de Contratos

- El ejecutivo puede cargar contratos.
- El sistema valida el RUT del apoderado.
- Se actualiza el estado del contrato.

---

## HU-07 - Reporte de Avance

- La gerencia puede visualizar indicadores.
- El reporte puede exportarse a PDF y Excel.

---

## HU-08 - Gestión de Usuarios

- El administrador puede crear usuarios.
- Puede modificar roles.
- Puede desactivar usuarios.
