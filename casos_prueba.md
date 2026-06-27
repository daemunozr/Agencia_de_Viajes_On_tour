# Casos de Prueba

| ID | Caso de Prueba | Datos Entrada | Resultado Esperado | Resultado Obtenido | Estado |
|---|---|---|---|---|---|
| CP-01 | Login con credenciales válidas | RUT: 12345678-9 / Pass: 1234 | Acceso al dashboard | — | Pendiente |
| CP-02 | Login con contraseña incorrecta | RUT: 12345678-9 / Pass: wrong | Mensaje de error | — | Pendiente |
| CP-03 | Ver saldo acumulado en dashboard | Usuario autenticado | Muestra saldo, meta y % avance | — | Pendiente |
| CP-04 | Historial de depósitos ordenado | Usuario con 3 depósitos | Lista ordenada por fecha | — | Pendiente |
| CP-05 | Descargar contrato en PDF | Contrato disponible | Archivo PDF descargado | — | Pendiente |
| CP-06 | Descargar contrato sin archivo | Sin contrato registrado | Mensaje "contrato no disponible" | — | Pendiente |
| CP-07 | Descargar póliza de seguro | Póliza disponible | PDF con coberturas descargado | — | Pendiente |
| CP-08 | Ejecutivo carga contrato nuevo | RUT válido + archivo PDF | Contrato registrado en sistema | — | Pendiente |
| CP-09 | Ejecutivo carga contrato con RUT inválido | RUT: 00000000-0 | Error de validación | — | Pendiente |
| CP-10 | Gerencia visualiza reporte de avance | Usuario con rol Gerencia | Reporte con % por curso visible | — | Pendiente |
| CP-11 | Admin crea nuevo usuario | Datos completos del usuario | Usuario creado y activo | — | Pendiente |
| CP-12 | Admin desactiva usuario | Usuario existente | Usuario marcado como inactivo | — | Pendiente |
