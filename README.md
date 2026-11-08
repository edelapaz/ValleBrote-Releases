# Valle Brote

**Versión actual: 0.13.1.** [Novedades y descargas](https://github.com/edelapaz/ValleBrote-Releases/releases/tag/v0.13.1) · [Historial de versiones](HISTORY.md)

## Si ya tienes el juego

Abre el juego y pulsa **Cerrar y actualizar a 0.13.1** en el menú, o **Guardar, cerrar y actualizar** durante la partida. El actualizador descarga el paquete firmado, crea copias de seguridad, instala y vuelve a abrir el juego. No necesitas extraer otro ZIP manualmente.

Si la instalación anterior no abre o no puede actualizarse, descarga [ValleBrote-Reparar.exe](https://github.com/edelapaz/ValleBrote-Releases/releases/download/v0.13.1/ValleBrote-Reparar.exe). Cierra las ventanas del juego y ejecútalo desde la misma cuenta de Windows donde jugabas. Ofrece instalar una copia completa y verificada en `%LOCALAPPDATA%\Programs\ValleBrote`, conservando la instalación anterior y el guardado local. Conserva cualquier carpeta `backup` y su archivo `error.txt` para revisar un fallo.

Los guardados son locales y pertenecen al usuario de Windows: este repositorio no sincroniza partidas entre equipos ni cuentas. El reparador conserva el perfil guardado. Si Windows impide ejecutarlo, conserva el mensaje exacto para revisarlo sin desactivar protecciones.

## Primera instalación en Windows de 64 bits

[Descargar ValleBrote-0.13.1-win-x64.zip](https://github.com/edelapaz/ValleBrote-Releases/releases/download/v0.13.1/ValleBrote-0.13.1-win-x64.zip)

1. Extrae **todos** los archivos a una carpeta donde tengas permiso de escritura.
2. Abre `ValleBrote.exe`. Conserva `ValleBrote_Data`, `MonoBleedingEdge` y las DLL junto al ejecutable.
3. El juego comprueba nuevas versiones al iniciar. Internet es necesario para descargar actualizaciones; puedes jugar sin conexión.

## Novedades de la 0.13.1

- Protege el cierre frente a la reconexión de proveedores de accesibilidad de Windows durante la desconexión de UI Automation.
- Mantiene el cierre normal de Unity y sus callbacks de guardado, sin terminar el proceso a la fuerza ni cambiar la configuración de accesibilidad del sistema.
- Conserva el rediseño de tienda, feria, fabricación y almacén de la 0.13.0 y las mejoras de fluidez.
- Conserva partidas, inventario, accesos rápidos, investigaciones, talentos, animales, decoración, amistad y opciones.
- Actualización firmada con verificación de archivos y copias de seguridad.

Consulta [HISTORY.md](HISTORY.md) para ver las funciones y fechas de las entregas anteriores, incluida la ganadería, la compostera renovada, las mejoras de mochila y tiendas, el hogar y las investigaciones.

## Ayuda y controles

Desde la versión 0.12.0, entra en **Guía del valle** desde el menú o pulsa **F1**. El buscador local encuentra temas como semillas mixtas, cumpleaños, pesca, queso o guardado, con o sin acentos.

- WASD/flechas: moverte; Shift: correr.
- 1–9: seleccionar un acceso; clic izquierdo: usarlo; clic derecho: opciones del destino.
- Rueda: zoom; TAB: menú; Esc: volver o pausar.
- I: investigaciones; C: regalos diarios; V: guardarropa; K: calendario; G: decorar.

Opciones permite ajustar sonido, música, zoom, pantalla y gráficos. Los menús muestran controles de mando y detienen el reloj del valle.

## Partidas y estadísticas

El actualizador verifica la firma y el contenido del paquete y conserva una copia de la partida antes de instalar. Mantén la misma cuenta de Windows para continuar tu progreso.

Las estadísticas son **opcionales y están desactivadas por defecto**, en Opciones → Privacidad y estadísticas. El jugador puede retirar el permiso y solicitar el borrado de su instalación. No se publican partidas ni datos privados en este repositorio.

El código fuente se mantiene en un repositorio privado. Aquí se publican información de distribución y archivos compilados en **[Releases](https://github.com/edelapaz/ValleBrote-Releases/releases/latest)**.