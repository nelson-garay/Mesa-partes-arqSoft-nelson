# Drivers arquitectónicos

Sistema de Mesa de Partes Digital — Instituto Manuel Antonio Hierro Pozo

| ID | Driver arquitectónico | Origen | ¿Por qué influye en la arquitectura? |
|---|---|---|---|
| DA01 | El sistema debe mantener trazabilidad completa de cada trámite entre áreas. | AC03 — Trazabilidad | Condiciona el modelo de datos (registro de eventos/historial) y el diseño de la lógica de derivación; es el núcleo del sistema. |
| DA02 | El sistema debe operar sobre el servidor propio, sin depender de internet externo. | RC02 | Condiciona la estrategia de despliegue local, evitando la dependencia que hizo fracasar al sistema anterior (SISGEDO). |
| DA03 | El sistema debe soportar firma electrónica con verificación propia. | RC05 | Requiere un módulo criptográfico propio (generación/gestión de claves, hash, verificación), sin integración con un proveedor externo. |
| DA04 | El sistema debe estar disponible 24/7 para recepción en línea. | AC02 — Disponibilidad | Condiciona la arquitectura de despliegue y la separación entre el canal en línea y la atención presencial. |
| DA05 | El sistema debe ser utilizable por personal sin experiencia previa en sistemas digitales. | AC05 — Usabilidad | Condiciona el diseño de la interfaz (frontend simple) y evita arquitecturas que compliquen la capa de presentación. |
| DA06 | El sistema debe completarse en 14 semanas usando SDD. | RC06, RC07 | Prioriza una arquitectura simple y modular que permita especificar e implementar cada módulo de forma incremental. |
| DA07 | El sistema debe soportar acceso concurrente de varias áreas. | AC06 — Escalabilidad/Concurrencia | Condiciona el uso de una capa de caché y el diseño de las consultas a base de datos para evitar cuellos de botella. |