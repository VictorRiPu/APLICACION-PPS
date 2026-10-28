# Política de seguridad

## Reportar una vulnerabilidad
No abrir una issue pública. Contactar directamente con los autores.

## Medidas implementadas

### Repositorio
- [x] Secretos fuera del repositorio (`.gitignore` + `.env.example`)
- [ ] Verificación en dos pasos en todas las cuentas
- [ ] Protección de las ramas `main` y `develop`
- [ ] Dependabot activado
- [ ] Detección de secretos antes del commit (gitleaks)

### Aplicación (se completará durante el desarrollo)
- [ ] Autenticación y gestión de contraseñas
- [ ] Validación de datos de entrada
- [ ] Protección frente a inyección SQL
- [ ] Protección frente a XSS
- [ ] Gestión segura de errores
- [ ] Cabeceras de seguridad HTTP
- [ ] Limitación de intentos (rate limiting)

## Registro de cambios de seguridad
| Fecha | Cambio | Autor |
|-------|--------|-------|
|       |        |       |