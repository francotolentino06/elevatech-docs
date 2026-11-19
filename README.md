# ElevaTech – Documentación y base de datos

Proyecto del curso **Proyecto Integrador**, Cibertec. Digitalización de las inspecciones de mantenimiento de **ElevaTech**: app Android con SQLite (modo sin conexión), servicios REST (.NET 8), portal web (Angular 18) y base de datos SQL Server.

> **Este repositorio es solo de documentación y base de datos.** Cada aplicación tiene su propio repositorio, con la misma secuencia de nombres.

## Repositorios del proyecto

| Repositorio | Contenido | Enlace |
|---|---|---|
| `elevatech-docs` | **Este repositorio:** documentación en PDF y scripts de la base de datos | [github.com/francotolentino06/elevatech-docs](https://github.com/francotolentino06/elevatech-docs) |
| `elevatech-api` | Servicio web REST (.NET 8) | [github.com/francotolentino06/elevatech-api](https://github.com/francotolentino06/elevatech-api) |
| `elevatech-portal` | Portal web administrativo (Angular 18) | [github.com/francotolentino06/elevatech-portal](https://github.com/francotolentino06/elevatech-portal) |
| `elevatech-app` | Aplicación móvil Android (Kotlin + SQLite) | [github.com/francotolentino06/elevatech-app](https://github.com/francotolentino06/elevatech-app) |

## Contenido de este repositorio

| Carpeta | Qué hay |
|---|---|
| `documentacion_pdf/` | Documentación del proyecto (`1_Informe_Proyecto_ElevaTech.pdf` y `2_Documentacion_Tecnica_ElevaTech.pdf` si se renombraron, o los PDF correspondientes) |
| `database/` | `01_schema.sql` (estructura) y `02_seed.sql` (datos de prueba) para SQL Server |
| `config/` | `db.example.env`: plantilla de la cadena de conexión, sin claves |

## Base de datos

Ejecutar en orden `database/01_schema.sql` y luego `database/02_seed.sql`. La cadena de conexión real va en `config/db.local.env` (copiar desde `db.example.env`); ese archivo no se sube al repositorio.