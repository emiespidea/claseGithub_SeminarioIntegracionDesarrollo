## Problema y objetivo

**Problema:**
En los proyectos de equipo es común hacer cambios directamente sobre la rama principal, sin registrar qué se quiere lograr ni revisar el cambio antes de integrarlo. Esto dificulta saber por qué se hizo un cambio, quién lo revisó y si cumplió lo que se esperaba.

**Objetivo:**
Completar el flujo Issue → rama → commit → Pull Request → revisión → merge, de modo que el 19 de octubre de 2026 la Issue #1 quede cerrada automáticamente por un PR fusionado en `main`.

**Siguiente paso:**
Aplicar este mismo flujo en el repositorio del proyecto modular, creando una Issue y una rama por cada cambio en lugar de trabajar directo sobre `main`.