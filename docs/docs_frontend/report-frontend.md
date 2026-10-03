# Reporte Técnico de Frontend - Experiencia Helados de Mora

## 1. Módulos y Componentes Implementados
1. **Motor de Partículas y Estela (Canvas 2D):**
   - Sistema de confeti dinámico para celebraciones.
   - Estela de interacción táctil y de cursor para pantallas táctiles y escritorio.
   - Fondo ambiental con partículas flotantes y efecto parallax suave.
2. **Sintetizador Web Audio API:**
   - Generación procedimental de tonos "pop" y secuencias de acorde mayores para celebraciones sin necesidad de descargar archivos `.mp3` o `.wav` externos.
3. **Módulo de Raspadita (*Scratch-off*):**
   - Canvas interactivo superpuesto al cupón ticket con detección de eventos `touchmove` y `mousemove` usando `globalCompositeOperation = 'destination-out'`.
4. **Minijuegos Interactivos:**
   - Morómetro de Belleza: control por presión sostenida con retroalimentación háptica (`navigator.vibrate`) y desbordamiento progresivo.
   - Atrapa las Moras: bucle de juego a 60 FPS con contador regresivo de 15 segundos y mensajes flotantes.
5. **Comportamiento Evasivo:**
   - Algoritmo de evasión para el botón de duda, incentivando la interacción hacia la confirmación.

## 2. Validación de Accesibilidad y Rendimiento
- Compatible con `prefers-reduced-motion`.
- Áreas interactivas mínimas de 44px para cumplimiento táctil en móviles.
- Cero dependencias externas pesadas, carga instantánea y funcionamiento offline tras precargar Google Fonts.
