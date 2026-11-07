# Valle Brote

**Versión actual: 0.6.1.** [Novedades y descargas](https://github.com/edelapaz/ValleBrote-Releases/releases/tag/v0.6.1) · [Historial de versiones](HISTORY.md)

## Si ya tienes el juego

Abre el juego y pulsa **Cerrar y actualizar a 0.6.1** en el menú, o **Guardar, cerrar y actualizar** durante la partida. El actualizador descarga el paquete firmado, crea copias de seguridad, instala y vuelve a abrir el juego. No necesitas extraer otro ZIP manualmente.

Si la instalación anterior no abre o no puede actualizarse, descarga [ValleBrote-Reparar.exe](https://github.com/edelapaz/ValleBrote-Releases/releases/download/v0.6.1/ValleBrote-Reparar.exe). Cierra las ventanas del juego y ejecútalo desde la misma cuenta de Windows donde jugabas. Ofrece instalar una copia completa y verificada en `%LOCALAPPDATA%\Programs\ValleBrote`, conservando la instalación anterior y el guardado local. Conserva cualquier carpeta `backup` y su archivo `error.txt` para revisar un fallo.

Los guardados son locales y pertenecen al usuario de Windows: este repositorio no sincroniza partidas entre equipos ni cuentas. El reparador conserva el perfil guardado. Si Windows impide ejecutarlo, conserva el mensaje exacto para revisarlo sin desactivar protecciones.

## Primera instalación en Windows de 64 bits

[Descargar ValleBrote-0.6.1-win-x64.zip](https://github.com/edelapaz/ValleBrote-Releases/releases/download/v0.6.1/ValleBrote-0.6.1-win-x64.zip)

1. Extrae **todos** los archivos a una carpeta donde tengas permiso de escritura.
2. Abre `ValleBrote.exe`. Conserva `ValleBrote_Data`, `MonoBleedingEdge` y las DLL junto al ejecutable.
3. El juego comprueba nuevas versiones al iniciar. Internet es necesario para descargar actualizaciones; puedes jugar sin conexión.

## Novedades de la 0.6.1

- Los recursos de accesibilidad de Windows se liberan mientras la ventana y la entrada del juego siguen disponibles, antes del cierre del motor.
- El cierre se procesa desde el bucle del juego, también al salir para instalar una actualización o al cerrar la ventana desde Windows.
- Se conserva el guardado normal y la copia de seguridad del actualizador.
- Incluye la ganadería y la compostera renovada de la 0.6.0, con partidas compatibles.

Consulta [HISTORY.md](HISTORY.md) para ver las funciones y fechas de las entregas anteriores, incluida la ganadería, la compostera renovada, las mejoras de mochila y tiendas, el hogar y las investigaciones.

## Partidas y estadísticas

El actualizador verifica la firma y el contenido del paquete y conserva una copia de la partida antes de instalar. Mantén la misma cuenta de Windows para continuar tu progreso.

Las estadísticas son **opcionales y están desactivadas por defecto**, en Opciones → Privacidad y estadísticas. El jugador puede retirar el permiso y solicitar el borrado de su instalación. No se publican partidas ni datos privados en este repositorio.

El código fuente se mantiene en un repositorio privado. Aquí se publican información de distribución y archivos compilados en **[Releases](https://github.com/edelapaz/ValleBrote-Releases/releases/latest)**.
