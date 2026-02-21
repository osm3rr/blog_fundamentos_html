# 🚀 Fundamentos HTML — Proyecto de práctica

[![Estado](https://img.shields.io/badge/estado-activo-brightgreen)](https://github.com/) [![HTML5](https://img.shields.io/badge/HTML5-orange)](https://developer.mozilla.org/es/docs/Web/HTML) ![Última actualización](https://img.shields.io/badge/actualizado-2026--02--21-blue)

> Un repositorio liviano para aprender y practicar conceptos básicos de HTML: estructura semántica, inclusión de imágenes y organización de assets. Perfecto para estudiantes y ejercicios rápidos.

╭────────────────────────────╮
│ ✨ Vista previa rápida ✨    │
╰────────────────────────────╯

Abrir `blog.html` en tu navegador para ver el ejemplo visual del mini-blog.

---

## 🗂 Estructura del proyecto

- `blog.html` — Página de ejemplo (entrada principal).
- `notes.txt` — Notas y recordatorios.
- `fotos/` — Carpeta de recursos fotográficos.
  - `fotos/fotos.txt` — Listado o descripciones de imágenes (si existe).
- `imagenes/` — Imágenes usadas por la página.

> Consejo: mantener nombres en minúsculas y con guiones, por ejemplo `mi-imagen.jpg`.

---

## ✨ Qué incluye y por qué importa

- Ejemplo de estructura semántica: `header`, `main`, `article`, `footer` para accesibilidad.
- Organización simple de assets para que la práctica escale con CSS/JS.
- Instrucciones rápidas para servir localmente y evitar problemas con rutas/CORS.

---

## 🎯 Características destacadas (lo "cool")

- Diseño pensado para enseñar: estructura limpia y fácil de modificar.
- Fácil integración con `Live Server` en VS Code.
- Ideal como plantilla base para mini-proyectos y ejercicios.

---

## 🚀 Rápida puesta en marcha

1. Abre `blog.html` con doble clic para una vista inmediata.
2. Recomendado: usar un servidor local para desarrollo:

```powershell
# Desde la raíz del proyecto
python -m http.server 8000
# Abrir en el navegador: http://localhost:8000/blog.html
```

3. Alternativa (VS Code): instala la extensión **Live Server** y pulsa **Go Live**.

---

## 🛠 Comandos útiles

- Inicializar repo Git (si hace falta):

```powershell
git init
git add .
git commit -m "Initial commit: proyecto fundamentos HTML"
```

- Servidor rápido con Node (opcional):

```powershell
npm install -g live-server
live-server --port=8000
```

---

## 🎨 Ideas estéticas y mejoras (siguientes pasos)

- Añadir `styles.css` con paleta moderna (gradientes suaves, tipografía grande).
- Incluir `assets/preview.png` con captura del blog para que el README muestre una preview.
- Añadir badges y GIFs cortos para hacerlo más dinámico.

Ejemplo de paleta recomendada para `styles.css`:

```css
:root{
  --bg: #0f172a; /* navy */
  --accent: #7c3aed; /* violeta */
  --muted: #94a3b8; /* gris suave */
}
body{background:linear-gradient(135deg,var(--bg),#020617);color:#e6eef8}
```

---

## 📸 Galería / Capturas

Si quieres que incluya imágenes de ejemplo en el README, coloca los archivos en `imagenes/` y dime cuáles quieres mostrar; yo inserto las miniaturas.

---

## 🧭 Resolución de problemas comunes

- Si las imágenes no aparecen: verifica que las rutas en `blog.html` apunten a `imagenes/` y que los nombres coincidan.
- Si el navegador bloquea archivos locales: usa un servidor local como los ejemplos anteriores.

---

## 🧾 Licencia y autor

- **Autor**: (añade tu nombre aquí)
- **Licencia**: (por ejemplo, MIT) — especifica si quieres que la añada.

---

Fecha de última edición: 2026-02-21

¿Quieres que también agregue un `styles.css` de ejemplo y una captura de pantalla para que el README muestre preview? Dímelo y lo incluyo.

