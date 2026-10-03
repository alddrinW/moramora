# Documento de Requerimientos del Sistema (SRS) - Experiencia Digital "Helados de Mora"

## 1. Visión del Producto
Experiencia web interactiva ("Landing Page Romántica") para dispositivo móvil y de escritorio con temática de Helados de Mora, orientada a brindar un detalle digital inmersivo, elegante, tierno y lúdico.

## 2. Requerimientos Funcionales
- **RF-01: Parámetros Personalizables Centralizados:** Constantes al inicio del script para `NOMBRE_ELLA`, `MI_NOMBRE`, mensajes, teléfonos y sabores.
- **RF-02: Pantalla de Bienvenida:** Animación SVG de cono derritiéndose, máquina de escribir, botón con confeti y scroll suave.
- **RF-03: Sección Helado Interactivo (3 Bolas):** Bolas interactivas con rebote, mensajes flotantes, contador 0/3 y animación de celebración.
- **RF-04: Menú de Sabores (Tarjetas 3D Flip):** 6 tarjetas con giros 3D, microcopy tierno, efectos de sonido sintetizados con Web Audio API y botón de silenciar.
- **RF-05: Morómetro de Belleza:** Medidor por presión continua (touch/mouse down) con cálculo progresivo, vibración háptica y confeti al 1000%.
- **RF-06: Mini-juego Atrapa las Moras:** Temporizador de 15s con moras cayendo en canvas/DOM, contador de puntos y mensaje ganador garantizado.
- **RF-07: Botón Travieso de Invitación:** Pregunta de invitación con botón evasivo "Mmm... déjame pensarlo" que huye y encoge, y botón "¡Sí!" que crece y desata fiesta de confeti.
- **RF-08: Cupón Raspable Digital (Premio):** Ticket perforado elegante con código dinámico `MORA-XXXX`, fecha del día, vigencia de 7 días, efecto de raspadita en HTML5 Canvas y aviso para captura de pantalla.
- **RF-09: Carta Final y Acción WhatsApp:** Mensaje tipográfico y botón directo para responder por WhatsApp (`wa.me`).
- **RF-10: Extras de Interactividad:** Barra de progreso superior con mora SVG, estela interactiva al toque/cursor, toasts dinámicos y Easter Egg al tocar el logo 5 veces.

## 3. Requerimientos No Funcionales
- Cero emojis en interfaz y código (todo íconos SVG inline y tipografía estilizada).
- 100% responsivo Mobile-First (optimizado de 360px a 430px y pantallas desktop).
- Animaciones a 60 FPS con aceleración por GPU (`transform`, `opacity`).
- Compatibilidad para despliegue directo en Vercel y Vite.
