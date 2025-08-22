# Contribución

## Flujo
1. Crear rama desde `main`: `feature/descripcion-corta` o `fix/descripcion-corta`.
2. Commits con **Conventional Commits** (ej. `feat(asistencia): registra scan QR`).
3. Pull Request con plantilla completada y checklist.
4. Revisión (al menos 1 aprobación) + CI en verde.

## Reglas rápidas
- Español en código y comentarios.
- Funciones verbo-sustantivo (`registrarAsistencia`).
- Tablas en plural (`alumnos`, `docentes`).
- Parámetros: obligatorios primero; opcionales al final con valores por defecto.
- Nada de secretos en el repo: usar `.env` + `./.env.example`.

## Pruebas mínimas
- Por cada servicio: 1 prueba éxito + 1 de error.
