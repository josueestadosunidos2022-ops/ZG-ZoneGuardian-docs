# ZG ZoneGuardian

## English

Protect player regions on a dedicated Minecraft 1.20.1 / Forge 47.4.x server. Current pair: **server 3.4.1 + client 3.4.1**, protocol 7. Uploads are two separate files on one CurseForge project. Install the server file only on the server, the client file only on clients, and ZoneCore 2.1.0+ on the server. The client does not require ZoneCore. Lightman's Currency 1.20.1-2.3.0.5+ is optional for its machine, trade and auction flags.

Use `/zoneguardian pos1`, `pos2`, then `crear <name>` to protect a selection. `/zoneguardian editar [name]` opens the custom flag panel; `/zoneguardian flag <name> <flag> <value>` edits by command. The panel organizes 108 flags into 13 tasks, including building, machines, entities, weather, movement, commands and economy. The server validates edits and permissions. `zoneguardian.region.create`, `zoneguardian.region.manage`, `zoneguardian.admin`, `zoneguardian.command.<command>` and `zoneguardian.flag.<flag>` are permission nodes. Owners can manage their own regions; delegated flag permissions limit what can be edited.

The generated `config/ZONEMODS/zoneguardian/regiones/creadas.toml` is a **read-only export** of current regions, not an editable configuration input. Use commands or the panel to change rules. The authoritative region data lives in the world save; back it up before upgrading. See [configuration and commands](CONFIGURATION.md) and [release compatibility](RELEASES.md).

## Español

Protege regiones de jugadores en un servidor dedicado Minecraft 1.20.1 / Forge 47.4.x. Pareja actual: **servidor 3.4.1 + cliente 3.4.1**, protocolo 7. Son dos archivos en un único proyecto CurseForge. Instala el JAR servidor solo en el servidor y el cliente solo en los clientes; ZoneCore 2.1.0+ se requiere en servidor. El cliente no requiere ZoneCore. Lightman's Currency 1.20.1-2.3.0.5+ es opcional para flags de máquinas, comercio y subastas.

Marca `/zoneguardian pos1`, `pos2` y usa `crear <nombre>` para proteger una selección. `/zoneguardian editar [nombre]` abre el panel custom; `/zoneguardian flag <nombre> <flag> <valor>` modifica por comando. El panel organiza 108 flags en 13 tareas. El servidor valida cambios y permisos. Nodos: `zoneguardian.region.create`, `zoneguardian.region.manage`, `zoneguardian.admin`, `zoneguardian.command.<comando>` y `zoneguardian.flag.<flag>`. El dueño administra su región y los permisos delegados limitan las ediciones.

`config/ZONEMODS/zoneguardian/regiones/creadas.toml` es una **exportación de lectura**, no un TOML de entrada. Cambia reglas desde comandos o panel. Los datos autoritativos están en el mundo; respáldalo antes de actualizar. Consulta [configuración y comandos](CONFIGURATION.md) y [compatibilidad](RELEASES.md).

© Elgochogms. This public repository contains documentation and its ZG avatar, no source code or private server data.

