# 🥃 Encuesta Old Parr Tropical

Formulario moderno y sencillo para recolección de datos de la encuesta Old Parr Tropical.

## 🚀 Despliegue en Cloudflare Pages

1. Conectá tu repositorio de GitHub a Cloudflare Pages
2. Seleccioná este repositorio (`encuesta-activacion`)
3. Configuración de build:
   - **Build command:** (dejar vacío)
   - **Build output directory:** (dejar vacío o `.`)
4. ¡Listo! Cloudflare Pages detectará que es un sitio estático

## ⚙️ Configuración del Webhook

Antes de desplegar, editá `index.html` y reemplazá:

```javascript
const WEBHOOK_URL = 'TU_WEBHOOK_URL_AQUI';
```

Por la URL de tu webhook en n8n.

## 📊 Campos del Formulario

- **Género:** Hombre / Mujer
- **Edad:** 18-25 / 26-35 / 36-45 / 45+
- **¿Consumes Whisky?:** Sí / No
- **¿Te gustó Old Parr Tropical?:** Sí / No

## 🎨 Características

- ✅ Diseño moderno y responsive
- ✅ Validación de campos
- ✅ Feedback visual al usuario
- ✅ Compatible con móviles
- ✅ Sin dependencias externas

## 📄 Licencia

MIT
