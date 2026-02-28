# System Brief – StudyTrack

## Visión
Ser una herramienta simple y efectiva para la organización académica universitaria.

## Problema
Desorganización en tareas y fechas límite.

## Stakeholders
- Estudiantes
- Docentes
- Administradores

## Scope
- Registro/Login
- Gestión de materias
- Gestión de tareas
- Seguimiento de progreso

## No-Scope
- Integración con sistemas universitarios
- Chat
- App móvil nativa

## Diagrama de Contexto

```mermaid
graph TD
    Estudiante -->|Gestiona| StudyTrack
    StudyTrack -->|Muestra progreso| Estudiante
    Admin -->|Administra sistema| StudyTrack
