# Historial de Valle Brote

Cada entrega conserva su fecha y novedades para seguir el progreso del proyecto. También puedes consultarlo desde el menú principal del juego.

[Ver la versión más reciente](https://github.com/edelapaz/ValleBrote-Releases/releases/latest)

## v0.3.2 · 06/11/2026 · Publicada

- Canasta inicial disponible y equipada sin gastar investigación; puedes seleccionarla en la barra para recoger cultivos maduros. La barra inicial incluye la canasta y se respetan las barras personalizadas.
- Cesta recolectora investigada y equipada: +1 semilla del arbusto diario, 1 vigor menos por cosecha y 1 producto adicional cada 5 cosechas.
- Cesta de campo investigada, fabricada y equipada: +2 semillas del arbusto, 1 vigor menos por cosecha y 1 producto adicional cada 3 cosechas. Los bonos sustituyen a los de la canasta básica.
- Los encargos de recolección piden una cantidad de semillas que el arbusto puede proporcionar durante su propio objetivo, incluso sin talentos. Los encargos ya aceptados conservan progreso y recompensa.
- Migración de la canasta inicial sin duplicar equipo ni sustituir accesorios elegidos. Se conserva la decisión de quitarla después de actualizar.
- Continúan el historial de versiones, las actualizaciones verificadas y las estadísticas voluntarias.

## v0.3.1 · 06/11/2026 · Publicada

Valle Brote 0.3.1

- Nuevo historial de versiones desde el menú principal: consulta fechas, novedades y la versión instalada.
- Versiones anteriores conservadas para seguir el progreso del proyecto, incluidas las entregas sustituidas y sus correcciones.
- Historial incluido para consultar sin conexión y actualización del listado desde la nube al abrirlo.
- Cada publicación incorpora automáticamente sus novedades al historial del juego y al historial público del repositorio.

- Actualización más resistente: comprueba bloqueos y escritura antes de reemplazar archivos; verifica copias y restaura únicamente lo modificado.
- Reparador independiente para instalaciones que no pueden actualizarse: instala en la carpeta del usuario y conserva el perfil de juego.
- El juego prepara una copia de su guardado antes de iniciar la actualización y verifica la firma del actualizador descargado.
- Estadísticas opcionales con consentimiento: tiempo de partida activa e instalaciones estimadas, sin enviar nombres, recursos ni partidas. Opción para desactivar y solicitar eliminación.
- Panel HTML local y privado para consultar totales, tendencias y versiones. Solo el colector de estadísticas se aloja en Cloudflare.
- Publicación condicionada a pruebas de instalación limpia, actualización de versiones anteriores y conservación del perfil.

Se mantienen las funciones de la 0.3.0 y su formato de guardado. No se modifican permisos ni protecciones de Windows.

## v0.3.0 · 06/11/2026 · Publicada

Valle Brote 0.3.0

- Botón COMER visible en la mochila. Los alimentos comunes recuperan vigor parcial; el festín de cosecha recupera hasta 100. No se consume comida si no puede recuperar vigor.
- Dormir recupera vigor una sola vez por día del juego. El bloqueo se conserva al guardar y cargar. Comer no consume el descanso diario.
- La tienda muestra qué nivel e investigación faltan y bloquea las compras que no cumplen, incluso dentro de un carrito con varios productos.
- Tres tratamientos de cultivo: tónico de crecimiento (+15 % durante 12 h), gel de humedad (25 % menos pérdida de agua durante 24 h) y bálsamo vegetal (repara daño y fertilidad).
- Nueva sección de tratamientos en Investigaciones, con requisitos y puntos compartidos con los conocimientos anteriores. Las 39 investigaciones anteriores se conservan.
- Investigaciones con estados grandes y diferenciados por texto y color: ACTIVADA, LISTA PARA ACTIVAR y BLOQUEADA.
- Descarga completa para Windows, con DirectStorage. Actualización desde el juego con guardado conservado, verificación de firma e integridad y copia de seguridad.

## v0.2.2 · 06/11/2026 · Publicada

Valle Brote 0.2.2

Corregido el error «No se encontró DSTORAGE.dll» al abrir una descarga nueva en Windows.

- El ZIP incluye dstorage.dll, dstoragecore.dll y todas las bibliotecas nativas de la compilación.
- El empaquetado verifica la presencia y el SHA-256 de cada DLL antes de firmar el manifiesto.
- El instalador rechaza paquetes que omiten las bibliotecas DirectStorage antes de modificar la instalación.

Descarga y extrae TODOS los archivos del ZIP a una carpeta nueva. Abre ValleBrote.exe desde la carpeta extraída. No es necesario descargar DLL por separado. Tu partida anterior se conserva en el mismo equipo.

Incluye las mejoras de avisos, accesos rápidos, controles con ratón, regalos y cultivos con el reloj del valle y actualizaciones desde la nube.

## v0.2.1 · 06/11/2026 · Sustituida

Valle Brote 0.2.1

- Avisos más visibles durante 12 segundos, incluso junto a edificios y cultivos.
- Barra rápida compacta con objetos disponibles y asignaciones conservadas.
- Camina con clic y acércate automáticamente a vecinos, puertas, cofre, cama y estaciones.
- Cambia el cultivo de las semillas mixtas pulsando su nombre sobre la barra rápida.
- Regalos tras 30 minutos activos del reloj del valle, con un cobro por día del juego.
- Cultivos sincronizados con el reloj del valle, incluido el descanso.
- Consulta de versiones y novedades al iniciar y durante la partida. Actualizaciones firmadas, SHA-256, copia de seguridad e instalación al guardar y cerrar.
- Corregida la ubicación del instalador en Windows para evitar el acceso denegado al reemplazar archivos.

Si descargaste la versión de prueba 0.2.0, descarga y extrae este ZIP completo una vez. Se conserva tu partida; las futuras actualizaciones utilizan el instalador corregido.

## v0.2.0 · 06/11/2026 · Sustituida

Valle Brote 0.2.0

- Avisos más grandes, contrastados y visibles durante 12 segundos, incluso junto a edificios y cultivos.
- Barra rápida compacta: solo aparecen objetos disponibles. Se conservan las asignaciones manuales.
- Desplazamiento con clic y aproximación automática a vecinos, puertas, estaciones y almacenamiento.
- Cambia el cultivo de las semillas mixtas haciendo clic en su nombre sobre la barra rápida.
- Calendario de agradecimiento basado en el reloj del valle: 30 minutos activos del juego por día. Dormir comienza otro día sin sumar minutos activos.
- Los cultivos avanzan con el reloj del valle, incluido el descanso, respetando agua, estación y bonos.
- Consulta de versiones y novedades antes de jugar, aviso durante la partida e instalación automática al guardar y cerrar. Actualizaciones firmadas con verificación SHA-256 y copia de seguridad.

