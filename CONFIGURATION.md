# ZG ZoneGuardian 3.4.1 — configuration / configuración

## English

**No editable ForgeConfigSpec TOML is used by this release.** `config/ZONEMODS/zoneguardian/regiones/creadas.toml` is written by ZoneCore's config service as a **read-only export** after region changes. Its `[[regiones]]` entries include name, dimension, owner UUID, horizontal bounds and active flag values. Editing this export will not update the region. Authoritative records are stored as world saved data (`zoneguardian_regions`); back up the world before updating.

Create: `/zoneguardian pos1`, `/zoneguardian pos2`, `/zoneguardian crear <name>`. Inspect: `lista`, `info <name>`, `config lista`, `config region <dimension> <name> info`. Edit: `editar [name]`, `flags <name>`, `flag <name> <flag> <value>`, `activar`, `desactivar`, `restablecer`; administrators may use `config region <dimension> <name> flag <flag> <value>` from console. `/zoneguardian reload` validates the active catalogue and exports regions; it does **not** import manual TOML edits.

The 13 panel tasks are territory/building; blocks/containers/machines; entities/vehicles; items/experience; mob spawning; explosions; weather/fluids; growth; movement; chat/commands; health/hunger; messages; and Lightman's Currency. Stable IDs include `block-break`, `block-place`, `chest-access`, `protect-entities`, `pvp`, `entry`, `allowed-cmds`, `water-flow`, `lc-machines`, `lc-trade` and `lc-auction`. The last three require the optional Lightman's Currency mod. `allowed-cmds` is a whitelist; legacy saved values are migrated to internal exceptions. A block with its own menu or Forge item capability is governed by `chest-access`, unless explicit `lc-machines` applies. Datapacks may add blocks to `zoneguardian:machine_interactable`.

Permissions: `zoneguardian.region.create`, `zoneguardian.region.manage`, `zoneguardian.admin`, `zoneguardian.command.<command>` and `zoneguardian.flag.<flag>`. Owner, admin and delegated permissions are checked server-side. The `game-mode` flag has stricter admin handling. Use the in-game panel for valid values and current flag names.

## Español

**No hay TOML ForgeConfigSpec editable en esta versión.** `config/ZONEMODS/zoneguardian/regiones/creadas.toml` es una **exportación de lectura** que incluye `[[regiones]]` con nombre, dimensión, UUID del dueño, límites y flags. Editarla no modifica la región. Los datos autoritativos viven en el mundo (`zoneguardian_regions`); haz copia antes de actualizar.

Crear: `/zoneguardian pos1`, `/zoneguardian pos2`, `/zoneguardian crear <nombre>`. Consultar: `lista`, `info <nombre>`, `config lista`, `config region <dimension> <nombre> info`. Editar: `editar [nombre]`, `flags <nombre>`, `flag <nombre> <flag> <valor>`, `activar`, `desactivar`, `restablecer`; desde consola puede usarse `config region <dimension> <nombre> flag <flag> <valor>`. `/zoneguardian reload` valida el catálogo y vuelve a exportar, pero **no importa** ediciones hechas al TOML.

El panel agrupa 108 flags en 13 tareas: territorio, bloques/máquinas, entidades, objetos, aparición, explosiones, ambiente/fluidos, crecimiento, movimiento, chat, salud, mensajes y Lightman's Currency. Ejemplos de ID: `block-break`, `block-place`, `chest-access`, `protect-entities`, `pvp`, `entry`, `allowed-cmds`, `water-flow`, `lc-machines`, `lc-trade`, `lc-auction`. Las últimas tres requieren el mod opcional. `allowed-cmds` es lista blanca; los valores antiguos se migran a excepciones internas. Menús propios y capacidades Forge usan `chest-access`, salvo regla `lc-machines` explícita. Los datapacks pueden ampliar `zoneguardian:machine_interactable`.

Permisos: `zoneguardian.region.create`, `zoneguardian.region.manage`, `zoneguardian.admin`, `zoneguardian.command.<comando>` y `zoneguardian.flag.<flag>`. El servidor valida dueño, administrador y delegaciones. `game-mode` tiene control administrativo más estricto. Usa el panel para ver valores válidos y los nombres actuales.

