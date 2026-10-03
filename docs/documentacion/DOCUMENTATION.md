# Documentación Integral - Proyecto Helados de Mora 

## 1. Resumen Ejecutivo
Landing page interactiva monoplataforma ("Single Page Experience") diseñada como un detalle romántico digital con la temática de Helados de Mora. Desarrollada con estándares web modernos: HTML5 semántico, CSS3 con Glassmorphism y aceleración de hardware (60 FPS), Vanilla JavaScript con Web Audio API, motor de partículas Canvas y capa de raspadita (*scratch-off*).

## 2. Arquitectura del Sistema
```
moramora/
├── index.html                      # Aplicación completa autónoma (HTML + CSS + JS)
├── package.json                    # Configuración de dependencias (Vite / Vercel)
├── vercel.json                     # Encabezados y enrutamiento optimizado para Vercel
└── docs/                           # Documentación de requerimientos y arquitectura
    ├── HU/
    │   └── HU-001-landing-helados-mora.md
    ├── requirements/
    │   ├── REQUIREMENTS.md
    │   └── MANUALMARCA.md
    ├── docs_frontend/
    │   └── report-frontend.md
    ├── backlog.md
    └── documentacion/
        └── DOCUMENTATION.md
```

## 3. Guía de Personalización Rápida
Dentro de `index.html`, en el bloque `<script>`, la constante `CONFIG` centraliza todas las variables:
```javascript
const CONFIG = {
  NOMBRE_ELLA: "Marcelyn <3",
  MI_NOMBRE: "Alddrun",
  NUMERO_WHATSAPP: "593999999999",
  MENSAJE_WHATSAPP: "¡Hola Alddrun! Me encantó la sorpresa del helado de mora...",
  TITULO_BIENVENIDA: "tengo algo dulce para ti...",
  MENSAJE_FINAL: "No sé si lo notaste, pero me gustas, Marcelyn <3...",
  CUPON_TITULO: "1 HELADO DE MORA + 1 SALIDA CONMIGO",
  CUPON_DIAS_VALIDEZ: 7,
  BOLAS_MENSAJES: [ ... ],
  SABORES: [ ... ]
};
```

## 4. Despliegue en Vercel
1. Subir la carpeta al repositorio de GitHub/GitLab.
2. Importar el proyecto en [vercel.com](https://vercel.com).
3. Seleccionar **Other / Vite** como Framework Preset y desplegar.
