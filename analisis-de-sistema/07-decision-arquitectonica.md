# Decisiones arquitectónicas (ADR)

Sistema de Mesa de Partes Digital — Instituto Manuel Antonio Hierro Pozo

| ID | Decisión arquitectónica | Driver relacionado | Justificación | Resultado |
|---|---|---|---|---|
| ADR-001 | Monolito modular | DA08 – Mantenibilidad y plazo; DA02 – Servidor propio | Organizar las funcionalidades en módulos independientes dentro de una misma aplicación desplegable. | Módulos de Trámites, Derivación y Trazabilidad, Firma Electrónica, Asistente IA, Usuarios y Roles, y Reportes. |
| ADR-002 | Clean Architecture | DA08 – Mantenibilidad y plazo | Separar las reglas del negocio de los detalles tecnológicos. | Dominio, Aplicación, Infraestructura y Presentación. |
| ADR-003 | Registro de movimientos por trámite | DA01 – Trazabilidad | Registrar cada derivación, cambio de estado y firma como un movimiento nuevo, sin sobrescribir los anteriores. | Historial completo y consultable de cada trámite. |
| ADR-004 | Estrategia de caché | DA05 – Rendimiento y concurrencia | Reducir consultas repetitivas a la fuente de datos. | Caché para catálogos (áreas, tipos de documento) y consultas frecuentes de estado. |
| ADR-005 | Firma electrónica mediante interfaz y componente propio | DA03 – Firma electrónica propia | Desacoplar los casos de uso del mecanismo de firma, que se implementa internamente porque no hay entidad certificadora externa. | Contrato de firma y componente interno de firma y verificación mediante código/QR. |