# Requisitos funcionales

Sistema de Mesa de Partes Digital — Instituto Manuel Antonio Hierro Pozo

| ID | Requisito funcional |
|---|---|
| RF01 | El sistema debe permitir a usuarios externos presentar trámites en línea. |
| RF02 | El sistema debe permitir registrar trámites presentados físicamente por el personal de mesa de partes. |
| RF03 | El sistema debe permitir consultar el estado y la ubicación actual de un trámite. |
| RF04 | El sistema debe generar un documento de respuesta firmado electrónicamente y ponerlo a disposición del usuario externo. |
| RF05 | El sistema debe ofrecer un asistente basado en IA para orientar al usuario externo y responder consultas frecuentes. |
| RF06 | El sistema debe permitir derivar un trámite desde mesa de partes hacia una o varias áreas. |
| RF07 | El sistema debe permitir a un área re-derivar un trámite hacia otra área o persona. |
| RF08 | El sistema debe registrar el historial completo de derivaciones de cada trámite. |
| RF09 | El sistema debe permitir a los jefes de área y al Director firmar electrónicamente documentos generados como respuesta institucional. |
| RF10 | El sistema debe generar un mecanismo de verificación de autenticidad (código o QR) para cada documento firmado electrónicamente. |
| RF11 | El sistema debe permitir a cualquier persona, sin iniciar sesión, verificar la autenticidad de un documento mediante dicho código o QR. |
| RF12 | El sistema debe generar reportes de gestión documentaria por área, estado y periodo. |
| RF13 | El sistema debe gestionar usuarios y roles diferenciados (mesa de partes, jefe de área, Director, administrador). |
| RF14 | El sistema debe permitir configurar las áreas/oficinas destino y los tipos de documento. |
| RF15 | El sistema debe mostrar a cada área una bandeja con los trámites que le han sido derivados. |
| RF16 | El sistema debe mantener disponible el registro histórico de trámites de periodos anteriores. |
| RF17 | El sistema debe estar disponible para la recepción de trámites en línea las 24 horas del día. |

## Relación entre historias de usuario y requisitos funcionales

| Historia de usuario | Requisitos funcionales relacionados |
|---|---|
| HU01 — Presentar trámite en línea | RF01, RF17 |
| HU02 — Consultar estado y ubicación | RF03 |
| HU03 — Recibir documento firmado | RF04 |
| HU04 — Consultar al asistente IA | RF05 |
| HU05 — Registrar trámite físico | RF02 |
| HU06 — Derivar trámite | RF06 |
| HU07 — Consultar historial de derivaciones | RF03, RF08 |
| HU08 — Visualizar trámites derivados | RF15 |
| HU09 — Re-derivar trámite | RF07 |
| HU10 — Firmar documentos (jefe de área) | RF09 |
| HU11 — Firmar documentos (Director) | RF09 |
| HU12 — Consultar reportes generales | RF12 |
| HU13 — Gestionar usuarios y roles | RF13 |
| HU14 — Configurar áreas y catálogos | RF14 |
| HU15 — Verificar autenticidad | RF10, RF11 |