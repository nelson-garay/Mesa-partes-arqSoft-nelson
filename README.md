# Sistema de Mesa de Partes Digital

## nombre
Integrante 1: Nelson Garay Curi

**Instituto Manuel Antonio Hierro Pozo**

Sistema de gestión documentaria "cero papeles" que digitaliza el registro, derivación, seguimiento y firma electrónica de trámites administrativos y académicos del instituto, reemplazando el proceso manual actual basado en cuadernos físicos.

## Problema que resuelve

El instituto gestiona sus trámites de forma manual, sin trazabilidad una vez que un documento es derivado entre áreas, y sin opción de atención remota para estudiantes y docentes que no pueden asistir presencialmente. Más detalle en [`docs/analisis-del-sistema/`](./docs/analisis-del-sistema/).

## Alcance principal

- Registro y presentación de trámites (presencial y en línea)
- Derivación y trazabilidad entre áreas (Dirección, Secretaría Académica, Administración, Programas de Estudio)
- Firma electrónica institucional con verificación por código/QR
- Asistente basado en IA para orientar al usuario externo
- Reportes de gestión documentaria

## Stack tecnológico

- **Backend:** Laravel (PHP)
- **Frontend:** Bootstrap + Blade
- **Base de datos:** MySQL
- **Caché:** Redis
- **Despliegue:** servidor propio del instituto

## Metodología

- **Gestión de proyecto:** Scrum (sprints de 2 semanas, 14 semanas totales)
- **Técnica de desarrollo:** Specification-Driven Development (SDD)

## Estructura del repositorio
docs/
├── analisis-del-sistema/
│ ├── 01-actores.md
│ ├── 02-historias-de-usuario.md
│ ├── 03-requisitos-funcionales.md
│ └── 04-atributos-de-calidad.md
│ └── 05-restricciones.md
│ └── 06-driver-arquitectonicos.md
├── arquitectura
│ └── arquitectura-inicial.md

## Curso
Arquitectura de Software

## Estado del proyecto

En desarrollo — fase de análisis y diseño.