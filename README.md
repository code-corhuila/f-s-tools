# f-s-tools

Paquete de herramientas compartidas que puede usar el proyecto.

Forma parte del proyecto **facture-stores** (`f-s`) — Ingeniería para el Desarrollo Móvil (posgrado) · CORHUILA 2026-B.

| | |
|---|---|
| Rol | Paquete de herramientas |
| Contenerizado | Sí: se entrega con su `Dockerfile`. |
| Gobierno y documentación | [`f-s-docs`](https://github.com/code-corhuila/f-s-docs) |
| Backlog | GitHub Project `f-s-backlog` |

## Ramas

| Rama | Uso |
|---|---|
| `develop` | Integración (rama por defecto) |
| `qa` | Pruebas |
| `main` | Producción |

**Todo cambio a `develop`, `qa` o `main` entra por pull request.** Ninguna de las tres admite
commits directos, force-push ni borrado (tampoco para administradores).

1. Trabajo diario: rama `feat/<tema>` o `fix/<tema>` desde `develop` → PR a `develop`.
2. Promoción: PR `develop` → `qa` y PR `qa` → `main`.
3. El PR a `main` necesita la aprobación del docente. La rama de trabajo se borra al fusionar.

## Repositorios del proyecto

| Repositorio | Rol |
|---|---|
| [`f-s-docs`](https://github.com/code-corhuila/f-s-docs) | Gobierno único del proyecto |
| [`f-s-api`](https://github.com/code-corhuila/f-s-api) | Core de negocio (API) |
| [`f-s-app`](https://github.com/code-corhuila/f-s-app) | Aplicación móvil |
| [`f-s-portal`](https://github.com/code-corhuila/f-s-portal) | Portal web |
| [`f-s-db`](https://github.com/code-corhuila/f-s-db) | Migraciones de base de datos |
| [`f-s-infra`](https://github.com/code-corhuila/f-s-infra) | Infraestructura y orquestación |
| [`f-s-tools`](https://github.com/code-corhuila/f-s-tools) | Paquete de herramientas |
