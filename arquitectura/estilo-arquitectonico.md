# Estilo arquitectónico

El sistema utiliza un monolito modular organizado en capas de presentación, lógica de negocio y datos.

![Estilo arquitectónico: monolito modular](img/diagrama-estilo-arquitectonico.svg)

## Justificación

Se elige el monolito modular porque organiza las funcionalidades en módulos con responsabilidades claras, dentro de una sola aplicación. Esto simplifica el despliegue en el servidor del instituto y facilita el desarrollo incremental 