# Normas de trabajo

## Ramas
- `main` → código estable. No se hace push directo.
- `develop` → integración del trabajo terminado.
- Ramas de trabajo, creadas siempre desde `develop`:
  - `feature/nombre` → nueva funcionalidad
  - `fix/nombre` → corrección de errores
  - `security/nombre` → mejora de seguridad
  - `docs/nombre` → documentación

## Flujo
1. Actualizar `develop` (`git pull`)
2. Crear rama de trabajo
3. Hacer commits pequeños
4. Subir la rama y abrir un Pull Request hacia `develop`
5. El otro miembro revisa y aprueba
6. Merge y borrar la rama

## Formato de commits (Conventional Commits)
`tipo(ámbito): descripción en imperativo`

Tipos:
- `feat` → nueva funcionalidad
- `fix` → corrección de error
- `security` → mejora de seguridad
- `docs` → documentación
- `refactor` → reorganizar código sin cambiar comportamiento
- `test` → pruebas
- `chore` → mantenimiento (dependencias, configuración)


## Secretos
- Nunca subir `.env`, contraseñas ni claves.
- Si se sube un secreto por error: avisar, cambiarlo (rotarlo) inmediatamente y después limpiar el historial.