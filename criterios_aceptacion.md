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

---

## HU-05 - Descarga de Póliza

- La póliza puede descargarse en PDF.
- Se muestran las coberturas del seguro.

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

---

## HU-08 - Gestión de Usuarios

- El administrador puede crear, modificar y desactivar cuentas de usuarios, asociándoles un rol.
- El sistema permite al administrador crear y actualizar los destinos de viaje disponibles.
- El sistema permite al administrador registrar y modificar los tipos de actividades comunes que los cursos pueden realizar para recaudar fondos.
- El sistema permite al administrador mantener la información maestra de los clientes que contratan servicios.
- Al intentar registrar un elemento duplicado, el sistema despliega un mensaje de advertencia y bloquea la duplicidad.
- El administrador puede visualizar un listado de todos los mantenedores activos con opciones de búsqueda o filtrado básico.
