# ZoneGuardian

## Current builds / Versiones actuales — 2026-11-04

| Side / Lado | Version / Versión | File / Archivo |
|---|---|---|
| server | 3.6.0 | [zoneguardian-server-3.6.0-protected.jar](https://www.curseforge.com/projects/1738034/files/9438525) |
| client | 3.6.0 | [zoneguardian-client-3.6.0-protected.jar](https://www.curseforge.com/projects/1738034/files/9438544) |

Minecraft 1.20.1 / Forge 47.4.x / Java 17. Protected public Beta builds; availability depends on each file approval. / Betas públicas protegidas; disponibilidad según aprobación de cada archivo.

## English — What is new

New original pixel interface, recolored shield, six-row pages, global flag/command search and explicit Enable/Disable/Reset actions. Enable restores the previous configured value; Reset removes the override and applies inheritance. Deleted regions now report a visible error during edits. Retains 108 flags, 13 groups, protocol 7 and persistent data. Update the 3.6.0 pair together; Core only on server.

## Español — Novedades

Interfaz de píxeles propia, escudo recoloreado, seis filas paginadas, búsqueda global de flags/comandos y acciones Activar/Desactivar/Restablecer. Activar recupera el valor previo; Restablecer elimina la configuración explícita y aplica herencia. Regiones eliminadas durante edición devuelven error visible. Conserva 108 flags, 13 grupos, protocolo 7 y datos; actualizar pareja 3.6.0. Core solo servidor.

## Installation / Instalación

Use the exact server/client pair in the table. Do not mix earlier network revisions. / Usa la pareja exacta de la tabla; no mezcles revisiones de red anteriores.

Stop the affected instance, back up the world/config, remove only the previous same-mod/same-side JAR, and install the table version. Preserve character data, wallets and TOML. Do not put server-only dependencies on clients. / Detén la instancia, respalda mundo/config, sustituye solo el JAR anterior del mismo mod y lado, y conserva personajes, cartera y TOML. No instales dependencias exclusivas de servidor en el cliente.

## Dependencies / Dependencias

**server**: `zonecore` [2.1.0,) (required/obligatorio; SERVER); `lightmanscurrency` [1.20.1-2.3.0.5,) (optional/opcional; SERVER).

**client**: No additional Zone requirement / Sin requisito Zone adicional.

[Full changes and usage / Novedades y uso](RELEASE-2026-11-04.md) · [Configuration / Configuración](CONFIGURATION.md) · [Historical releases / Entregas históricas](RELEASES.md).

## Validation / Verificación

Original release checks and isolated startup/command registration of the protected set were reviewed. Shared schemas: Essentials 35, Guardian 13 and Misions 4 classes, with no mapping differences. This does not certify a new graphical client session, two-player gameplay, full third-party modpack, hosting deployment or FPS/TPS. / Revisadas las verificaciones de entrega y el arranque/registro de comandos del conjunto protegido. Esquemas compartidos sin diferencias de mapeo: Essentials 35, Guardian 13 y Misions 4 clases. No certifica una nueva sesión gráfica, dos jugadores, modpack completo, hosting ni FPS/TPS.

## Ownership / Titularidad

Original ZONE code and visual assets © Elgochogms. Public documentation only: no mod sources, private obfuscation maps, credentials or production player data. Existing rights of earlier distributions are preserved.
