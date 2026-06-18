# Pisco Lima — Las Rastras
### Sitio Web One-Page · Alta Cocina Peruana · Talca, Chile

Sitio web completo de una sola página (One-Page Scroll) para **Pisco Lima**, restaurante de gastronomía peruana vanguardista ubicado en **Av. San Miguel 3830, Las Rastras, Talca**.

---

## 🚀 Publicar en GitHub Pages (paso a paso)

### Opción A — Subir desde GitHub.com (sin código)

1. Ve a [github.com](https://github.com) e inicia sesión (o crea una cuenta gratuita).
2. Haz clic en **"New repository"** (botón verde).
3. Nombre del repositorio: `pisco-lima` (o el que prefieras).
4. Marca la opción **"Public"**.
5. Haz clic en **"Create repository"**.
6. En la página del repo vacío, haz clic en **"uploading an existing file"**.
7. Arrastra el archivo `index.html` y el `README.md` a la zona de carga.
8. Haz clic en **"Commit changes"** (botón verde abajo).

### Activar GitHub Pages

1. Ve a **Settings** (pestaña de tu repositorio).
2. En el menú izquierdo, haz clic en **"Pages"**.
3. En **"Branch"**, selecciona `main` y carpeta `/ (root)`.
4. Haz clic en **"Save"**.
5. En ~2 minutos tu sitio estará en:
   ```
   https://TU-USUARIO.github.io/pisco-lima/
   ```

---

## ✏️ Personalización antes de publicar

Abre `index.html` con cualquier editor de texto (Notepad, VS Code, etc.) y reemplaza:

| Marcador | Reemplazar con |
|---|---|
| `56912345678` | Número real de WhatsApp (sin + ni espacios) |
| `@piscolima.lasrastras` | Handle real de Instagram |
| Horarios en sección Contacto | Horarios reales del restaurante |

> **Buscar y reemplazar:** usa `Ctrl + H` en cualquier editor de texto.

---

## 🗺️ Mapa de Google Maps (instrucciones)

El sitio incluye un mapa estilizado propio que siempre funciona. Si quieres reemplazarlo por el mapa real de Google Maps embebido:

1. Ve a [maps.google.com](https://maps.google.com).
2. Busca **"Av. San Miguel 3830, Talca"**.
3. Haz clic en **Compartir** → **Insertar un mapa**.
4. Copia el código `<iframe>`.
5. En `index.html`, busca `<div class="map-visual">` y reemplaza todo el bloque por tu `<iframe>`.

---

## 📁 Estructura de archivos

```
pisco-lima-website/
├── index.html      ← Todo el sitio (HTML + CSS + JS en un solo archivo)
└── README.md       ← Esta guía
```

El sitio es **completamente autónomo**: no requiere servidor, base de datos ni dependencias externas. Solo un navegador.

---

## 🎨 Tecnologías

- HTML5 semántico
- CSS3 (variables, grid, flexbox, animaciones)
- JavaScript vanilla (tabs de menú, burbuja WA, scroll reveal)
- Google Fonts: Cormorant Garamond + Montserrat
- Sin frameworks · Sin dependencias · Sin build step

---

## 📞 Secciones del sitio

| Sección | ID | Descripción |
|---|---|---|
| Hero | `#inicio` | Eslogan, tagline y CTA principal |
| Concepto | `#concepto` | Historia y filosofía del restaurante |
| La Carta | `#carta` | Menú con tabs: Entradas, Fondos, Coctelería |
| Reservas | `#reservas` | Bloques de conversión Salón + Delivery |
| Contacto | `#contacto` | Dirección, horarios, mapa y redes |

---

*Desarrollado para Pisco Lima — Las Rastras · © 2026*
