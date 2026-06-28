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
