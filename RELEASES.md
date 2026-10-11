# ZG ZoneGuardian — releases and compatibility

Current protected pair: **server 3.4.1 + client 3.4.1**, protocol 7. Use both files from the same CurseForge project on Minecraft 1.20.1, Forge 47.4.x and Java 17. The server requires ZoneCore 2.1.0+; the client does not. Lightman's Currency 1.20.1-2.3.0.5+ is optional on the server. Do not install `-dev`, fixture, source or unprotected build JARs. Stop the server and back up the persistent world before replacing the pair.

Validation: both Gradle builds, 8 headless UI checks, 13 shared classes verified byte-identical, 718 dedicated Forge fixture checks with Lightman's Currency on unprotected 3.4.1, and protected server startup/command/clean shutdown with and without Lightman's Currency. This does not prove graphical-client behavior, two-player networking, a full modpack or hosting.

## Español

Pareja protegida actual: **servidor 3.4.1 + cliente 3.4.1**, protocolo 7. Instala ambos lados desde un único proyecto CurseForge en Minecraft 1.20.1, Forge 47.4.x y Java 17. ZoneCore 2.1.0+ es obligatorio solo en servidor; Lightman's Currency 1.20.1-2.3.0.5+ es opcional. No instales JAR `-dev`, fixture, fuente ni compilación sin proteger. Detén el servidor y respalda el mundo antes de sustituir la pareja.

Se aprobaron ambas compilaciones, 8 pruebas UI sin ventana, identidad de 13 clases compartidas, 718 comprobaciones de Forge con Lightman's Currency sobre la versión sin proteger, y arranque/comandos/cierre del servidor protegido con y sin esa integración. Faltan cliente gráfico, conexión real de dos jugadores, modpack completo y hosting.

