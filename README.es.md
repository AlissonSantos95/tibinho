⚔️ Tibia Cooldowns & Atajos y MÁS — Overlay en Tiempo Real
Overlay flotante e invisible para Tibia que muestra los cooldowns de hechizos y runas en tiempo real, con drag & drop, scraper integrado de TibiaWiki y persistencia de datos.

📋 Descripción
Aplicación desarrollada en Python que funciona como un overlay transparente sobre el juego Tibia, permitiendo realizar un seguimiento visual del tiempo de recarga (cooldown) de tus hechizos y runas de forma automatizada y personalizable.
Construido en Python; se utilizó IA para comprender las bibliotecas siguientes y para el diseño de la interfaz de usuario (UI), ya que no tengo conocimientos avanzados en PYTHON.

✨ Funcionalidades
🎯 Overlay Flotante Invisible (Chroma Key)
La interfaz utiliza transparencia nativa (-transparentcolor), haciendo que el fondo sea completamente ignorado por Windows. Solo los íconos, barras de progreso y descripciones quedan visibles superpuestos al juego.
Atajo: CTRL + SHIFT + ALT + Q — Abre el menú de configuración

🙈 Auto-Hide Inteligente
El script monitorea la ventana activa del sistema. Si Tibia está en foco, el overlay aparece; al hacer Alt+Tab hacia el navegador o Discord, desaparece automáticamente.

🖱️ Administrador de Slots Dinámico (Drag & Drop)
Organiza hechizos y pociones arrastrándolos desde las pestañas de categorías (Knight, Sorcerer, Druid, Paladin, Monk y Runas) directamente a los slots activos. Agrega tantos slots como desees con el botón + Agregar Slot.

🌐 Scraper Integrado de TibiaWiki
Con un solo clic, el programa busca automáticamente los íconos oficiales de hechizos y runas, convirtiéndolos al formato ideal. También extrae el nivel mínimo, coste de maná y descripción oficial, actualizándose automáticamente con cada update o forzando la sincronización.

💾 Persistencia de Datos (JSON)
Todas las elecciones de slots, atajos y preferencias se guardan en:
overlay_config.json
Al reabrir el programa, todo estará exactamente como lo dejaste.

🔔 Integración con Tray Icon
El programa se ejecuta oculto en la bandeja de notificaciones con un menú de acceso rápido y mantiene presencia en la barra de tareas de Windows.

🔒 Modo Bloqueado y Barra de Control
Barra flotante con:

    Asa de arrastre (≡)

    Botón de configuración (⚙)

    Candado de seguridad (🔓 / 🔒) — bloquea la posición para evitar clics accidentales

    Botón de cierre rápido (✕)

🗺️ Roadmap

    [x] Cooldown por hechizo — La barra de cooldown debajo de los íconos de la barra flotante debe reflejar el cooldown del hechizo colocado en el atajo, no el cooldown global.

    [x] Cooldown global visual — Cooldown global de 2s: poner todos los íconos en gris mientras se ejecuta, con un contador de 2s + milisegundos encima de la imagen (sin taparla; la imagen puede ponerse gris).

    [x] Overlay limpio — Mostrar solo el ícono de la imagen. Sin detalles, maná, nivel o cualquier otra información.

    [x] Botón "Sincronizar" — Renombrar el botón de actualizar íconos a "Sincronizar". Al hacer clic, fuerza la sincronización de íconos con GitHub Pages.

    [x] Bloqueo de movimiento — Al activarlo, ocultar todos los íconos excepto las habilidades y el cooldown. Las opciones, cerrar y mover desaparecen.

    [ ] Actualización de íconos de hechizos y runas

    [ ] Menú de configuración — Separar la configuración en pestañas:

    [ ] Tooltip de detalles — Cuando "mostrar detalles" esté activo en la configuración, pasar el cursor sobre el hechizo muestra los detalles.

        [ ] Overlay Spells/Icons — Configuración actual de atajos

        [ ] Sync Character for Hunts — Sincronizar personaje para hunts

        [ ] Hunts

            [ ] Casilla premarcada "Sync with character" — busca hunts solo para la clase y nivel del personaje conectado

            [ ] Campo para escribir el nombre del personaje — extrae datos del sitio oficial de Tibia con opción de overlay de los datos de la hunt

            [ ] Filtro de hunt por XP, botín (loot), XP/hr, etc.

    [ ] Documentación del código — Comentar todas las líneas detalladamente explicando lo que hace cada bloque, con ejemplos.

    [ ] Monitoreo con Notificación — Monitoreo con notificación de Char Bazaar

    [ ] Mini-MAP expandido
