# Valle Brote

**Versión actual: 0.3.1.** [Novedades y descargas](https://github.com/edelapaz/ValleBrote-Releases/releases/tag/v0.3.1) · [Historial de versiones](HISTORY.md)

## Si ya tienes el juego

Abre el juego y pulsa **Cerrar y actualizar a 0.3.1** en el menú, o **Guardar, cerrar y actualizar** durante la partida. Descarga el paquete firmado, instala y vuelve a abrir el juego. No necesitas extraer otro ZIP manualmente.

**Si la actualización falló o el juego dejó de abrir, descarga [ValleBrote-Reparar.exe](https://github.com/edelapaz/ValleBrote-Releases/releases/download/v0.3.1/ValleBrote-Reparar.exe).** Cierra las ventanas del juego y ejecútalo desde la misma cuenta de Windows donde jugabas. Ofrece instalar una copia completa y verificada en `%LOCALAPPDATA%\Programs\ValleBrote`, conservando la instalación anterior y el guardado local. No cambia permisos, antivirus, UAC ni firewall. Conserva cualquier carpeta `backup` y su archivo `error.txt` hasta terminar de revisar un fallo anterior.

Los guardados pertenecen al mismo usuario de Windows y son locales: este repositorio no sincroniza partidas entre equipos ni entre cuentas. El reparador no modifica el perfil guardado. Si Windows impide ejecutarlo, conserva el mensaje exacto para revisarlo sin desactivar protecciones.

## Primera instalación en Windows de 64 bits

[Descargar ValleBrote-0.3.1-win-x64.zip](https://github.com/edelapaz/ValleBrote-Releases/releases/download/v0.3.1/ValleBrote-0.3.1-win-x64.zip)

1. Extrae **todos** los archivos a una carpeta donde tengas permiso de escritura.
2. Abre `ValleBrote.exe`. Conserva `ValleBrote_Data`, `MonoBleedingEdge` y las DLL junto al ejecutable.
3. El juego comprueba nuevas versiones al iniciar. Internet es necesario para descargar actualizaciones; puedes jugar sin conexión.

## Novedades de la 0.3.1

- Historial desde el menú principal, con fechas, novedades y versión instalada. También funciona sin conexión.
- Actualizador que comprueba bloqueos antes de cambiar archivos, verifica copias y restaura únicamente lo modificado.
- Reparador independiente para instalaciones que no pueden actualizarse.
- Copia del guardado antes de actualizar y descarga de futuros instaladores con firma propia.
- Estadísticas **opcionales y desactivadas por defecto** en Opciones → Privacidad y estadísticas. Versión y tiempo de partida activa con identificador aleatorio de instalación; no se envían nombres, partidas, recursos, archivos ni hardware. Cloudflare procesa la conexión de red; la base del proyecto no guarda la IP.
- El jugador puede retirar el permiso y solicitar el borrado de su instalación. Las cifras representan instalaciones participantes estimadas, no personas ni equipos físicos únicos.

Se mantienen los alimentos desde la mochila, el descanso diario, tratamientos de cultivo, investigaciones y funciones de la 0.3.0. El dashboard del administrador es un archivo HTML local; no está alojado en este repositorio público ni en el colector.

## Comprobaciones de esta entrega

1.384 comprobaciones integradas aprobadas; ZIP ejecutado desde una carpeta vacía; 11 pruebas del instalador; actualización con el nuevo helper sobre los ZIP originales 0.2.2 y 0.3.0, con rollback simulado y arranque correcto. El perfil real del jugador mantuvo el mismo hash antes y después. Historial y privacidad revisados a dos tamaños de ventana. Estas pruebas no certifican todas las configuraciones de Windows; para diagnosticar un fallo concreto se necesita su `error.txt`.

Las versiones 0.2.2 y 0.3.0 emplean su helper antiguo durante la primera transición. Si esa actualización falla, usa el reparador anterior. Las siguientes entregas podrán preparar un helper actualizado antes de cerrar el juego.

El código fuente se mantiene en el repositorio privado. Aquí se publican únicamente información de distribución y archivos compilados en **Releases**.
