# Enfoque arquitectónico

El sistema adopta Clean Architecture, separando presentación, aplicación, dominio e infraestructura.

![Enfoque arquitectónico: Clean Architecture](img/enfoque-arquitectonico-clean-architecture.svg)


## Justificación

Se elige Clean Architecture porque separa las reglas del negocio de la interfaz, la base de datos y los servicios externos. Esto facilita el mantenimiento y las pruebas de los procesos de registro, derivación y firma, reduciendo el impacto de los cambios tecnológicos.