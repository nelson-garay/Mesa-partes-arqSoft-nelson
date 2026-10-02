# Restricciones

Sistema de Mesa de Partes Digital — Instituto Manuel Antonio Hierro Pozo

| ID | Restricción | Descripción |
|---|---|---|
| RC01 | Aplicación web | El sistema debe ser accesible mediante navegador web, sin requerir instalación de software adicional. |
| RC02 | Servidor propio | El sistema debe desplegarse en el servidor propio del instituto, sin depender de hosting en la nube. |
| RC03 | Control de versiones | El código fuente debe gestionarse mediante Git, en un repositorio compartido. |
| RC04 | API REST | La comunicación entre el frontend y la lógica de negocio debe realizarse mediante una API REST. |
| RC05 | Firma sin entidad certificadora externa | El mecanismo de firma electrónica debe implementarse de forma interna (criptografía propia), con reconocimiento institucional, no validez legal externa. |