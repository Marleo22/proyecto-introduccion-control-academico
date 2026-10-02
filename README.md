# Sistema de Control Académico — Proyecto Final

Aplicación académica desarrollada para organizar estudiantes, docentes, cursos, inscripciones, calificaciones y reportes en una sola experiencia.

> Proyecto académico de demostración. No contiene credenciales reales ni datos de acceso públicos.

## Qué incluye

- Modelo relacional en PostgreSQL con tablas, restricciones, vistas, procedimientos y triggers.
- Inicio de sesión con control de sesiones y permisos por rol.
- Paneles diferenciados para administración, docentes y estudiantes.
- Operaciones CRUD para estudiantes, cursos, docentes y asignaciones.
- Inscripciones, notas, historial académico, promedios y reportes exportables.
- Interfaz web con HTML, CSS y JavaScript.

## Stack

- PostgreSQL
- PHP con PDO
- HTML, CSS y JavaScript
- Visual Studio Code

## Estructura general

Base de datos → configuración local → API PHP → interfaz web → paneles por rol.

Las carpetas principales son database/, config/, backend/, js/ y las páginas de cada panel.

## Configuración local

1. Instala PostgreSQL y PHP en tu entorno local.
2. Crea la base de datos usando los scripts de instalación incluidos en database/.
3. Copia config/config.example.php como config/config.php.
4. Completa los valores de conexión únicamente en tu copia local.
5. Inicia el servidor PHP y abre la pantalla de inicio de sesión.

Los archivos con credenciales y las contraseñas de prueba se mantienen fuera del repositorio público. Usa valores propios para cualquier instalación local.

## Seguridad

- Nunca guardes contraseñas, tokens o claves en Git.
- Mantén config/config.php fuera del control de versiones.
- Usa variables de entorno o archivos locales ignorados para secretos.
- Cambia inmediatamente cualquier credencial que haya sido compartida anteriormente.

## Estado

Proyecto académico con módulos integrados de base de datos, autenticación, operaciones CRUD y reportes.
