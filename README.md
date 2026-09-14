# 🎬 Generador de GIF Rápido

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Client Side Only](https://img.shields.io/badge/Processing-100%25%20Client--Side-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

Una herramienta web moderna, liviana y ultrarrápida para convertir múltiples imágenes en un GIF animado directamente desde el navegador. Diseñada con un enfoque *mobile-first*, procesamiento de memoria optimizado y privacidad total al no requerir servidores backend.

---

## ⚡ Características Principales
* **Soporte para Formatos Móviles (`HEIC` / `HEIF`):** Convierte automáticamente fotos tomadas con dispositivos iOS/Android sin necesidad de convertidores externos.
* **Procesamiento Eficiente en Memoria:** Redimensiona dinámicamente imágenes de alta resolución mediante Canvas en el cliente para evitar el colapso de memoria RAM.
* **Resoluciones Multi-propósito:**

| Resolución | Caso de Uso Recomendado |
| :--- | :--- |
| `16 × 16 px` | Favicon clásico |
| `32 × 32 px` | Favicon HD / Avatar micro |
| `64 × 64 px` | Avatar retro / Foros |
| `128 × 128 px` | Icono de app / Chats |
| `256 × 256 px` | Foto de perfil estándar |
| `500 × 500 px` | Imagen de producto / Redes sociales |
| `800 × 800 px` | Ilustración digital / Avatar HD |
| `1000 × 1000 px` | Lienzo Master en alta calidad |

* **Control de Animación:** Ajuste personalizado del tiempo de transición por fotograma (desde 0.1s hasta 5.0s).
* **Gestión de Galería:** Vista previa interactiva con eliminación individual de fotogramas antes del procesamiento.
* **Barra de Progreso en Tiempo Real:** Realimentación visual fluida durante la compilación del render.
* **Privacidad por Diseño:** Las imágenes nunca se suben a ningún servidor; todo el proceso ocurre localmente en tu dispositivo.

---

## 🛠️ Tecnologías Utilizadas
* **HTML5 & CSS3:** Arquitectura con variables CSS, Flexbox, Grid y diseño adaptativo.
* **JavaScript (Vanilla ES6+):** Manipulación de Canvas 2D, Blob API y manejo asíncrono con `Promises`.
* **[gifshot](https://github.com/yahoo/gifshot):** Librería cliente para la codificación y renderizado de animaciones GIF mediante Web Workers.
* **[heic2any](https://github.com/alexcorvi/heic2any):** Conversión local en el navegador de formatos HEIC/HEIF a JPEG.

---

## 🚀 Inicio Rápido
No se requiere ningún entorno de ejecución (`Node.js`, `npm`, etc.) ni servidor web.
1. **Clona el repositorio:**
   ```bash
   git clone [https://github.com/tu-usuario/generador-gif-rapido.git](https://github.com/tu-usuario/generador-gif-rapido.git)
    ```
---

### ​📄 Licencia:

<div align="center">
Desarrollado con 💚 por <strong>Thaurock</strong>
</div>

