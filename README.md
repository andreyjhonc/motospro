# 🏍️ Motos@Motos Pro - Gestión de Rutas y Logística

Aplicación Web Progresiva (PWA) de alto rendimiento diseñada para la gestión de transporte, recogida y entrega de motocicletas. Cuenta con una interfaz optimizada estilo **Tesla Cyber-Cockpit** para chóferes y transportistas.

---

## 🚀 Características Principales

- **Gestión de Rutas y Paradas:** Línea temporal interactiva con waypoints conectados, navegación directa con Google Maps y Waze.
- **Tarjetas Compactas de Expediente:** Control inmediato de cada moto (`ENTREGA` / `RECOGIDA`), cobro en efectivo (`€`) o transferencia, checkboxes de cobrado en mano o Bizum.
- **Alertas y Preavisos:** Envío instantáneo de avisos de llegada por WhatsApp (preaviso, 60 min, 30 min, 15 min).
- **Inspección y Daños:** Registro fotográfico de daños de motocicletas, etiquetas rápidas (carenado, escape, llaves, papeles) y peritaje.
- **Albaranes y Firma Digital:** Captura fotográfica de albaranes y recogida de firma digital en pantalla.
- **Control de Gastos y Arqueo:** Registro de repostajes de gasoil y balance total de cobros de ruta.
- **PWA Offline Ready:** Soporte para instalación como aplicación nativa en iOS y Android mediante `manifest.json` y `sw.js`.

---

## 📁 Archivos del Proyecto

| Archivo | Descripción |
| :--- | :--- |
| [`index.html`](index.html) | Interfaz principal de la aplicación |
| [`styles.css`](styles.css) | Sistema de diseño Tesla Cyber-Cockpit y temas |
| [`app.js`](app.js) | Lógica interactiva de rutas, cobros y almacenamiento local |
| [`manifest.json`](manifest.json) | Configuración para instalación PWA en móviles |
| [`sw.js`](sw.js) | Service Worker para caché y funcionamiento sin conexión |
| `icon-*.png` | Iconos de la aplicación en diferentes resoluciones |
| [`todo_en_uno.html`](todo_en_uno.html) | Versión monobloque portable autocontenida |

---

## 🌐 Publicación en GitHub Pages (Gratis)

1. En tu repositorio de GitHub, entra a **Settings** (Configuración) > **Pages**.
2. En **Build and deployment** > **Branch**, selecciona la rama `main` (carpeta `/root`).
3. Haz clic en **Save**. En un par de minutos tendrás una URL pública HTTPS para abrir la app desde cualquier móvil.
