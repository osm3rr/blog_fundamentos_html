**Proyecto**: Fundamentos HTML

**Descripción**: Este repositorio contiene ejemplos y recursos básicos para practicar HTML estático. Incluye una página de blog de ejemplo, notas y una carpeta de fotos/recursos. Es ideal para estudiantes que están empezando con HTML y para ejercicios sencillos de maquetación y organización de archivos.

**Estructura del proyecto**
- **`blog.html`**: Página HTML principal del proyecto. Es el punto de entrada para ver el ejemplo de blog.
- **`notes.txt`**: Notas del autor, recordatorios o checklist del proyecto.
- **`fotos/`**: Carpeta con recursos relacionados a fotografías.
  - **`fotos/fotos.txt`**: Descripción o lista de las fotos incluidas (si aplica).
- **`imagenes/`**: Carpeta para almacenar imágenes usadas por `blog.html` u otras páginas.

**Contenido y propósito de archivos**
- `blog.html`: Contiene ejemplos de estructura HTML (cabecera, artículos, imágenes y pie de página). Ábrelo en tu navegador para ver el resultado visual.
- `notes.txt`: Información de soporte, ideas o pasos pendientes.
- `fotos/fotos.txt`: Puede contener metadatos, nombres de archivos o notas sobre las imágenes.

**Cómo ver el proyecto (instrucciones rápidas)**
- Doble clic en `blog.html` para abrirla en el navegador predeterminado.
- O, desde la raíz del proyecto, sirve los archivos con un servidor estático (recomendado para evitar problemas con rutas relativas y CORS):

```powershell
# Servidor rápido usando Python 3
python -m http.server 8000

# Luego abrir en el navegador: http://localhost:8000/blog.html
```

**Flujo de trabajo recomendado**
- Mantén los archivos estáticos (HTML, CSS, JS e imágenes) organizados en carpetas: usar `imagenes/` para activos gráficos.
- Usa control de versiones (`git`) para guardar cambios y añadir mensajes claros en commits.
- Para pruebas rápidas en VS Code: instala la extensión "Live Server" y pulsa "Go Live" para servir `blog.html` automáticamente.

**Buenas prácticas sugeridas**
- Estructura semántica: usa `header`, `main`, `article`, `section`, `footer` para mejorar accesibilidad.
- Mantén CSS y JS en archivos separados (por ejemplo `styles.css`, `script.js`) y enlázalos desde `blog.html`.
- Nombres de archivos en minúscula y con guiones para evitar problemas en distintos sistemas operativos.

**Comandos útiles**
- Iniciar servidor local (ver más arriba):

```powershell
python -m http.server 8000
```

- Inicializar repo Git (si aún no existe):

```powershell
git init
git add .
git commit -m "Initial commit: proyecto fundamentos HTML"
```

**Posibles mejoras futuras**
- Añadir `styles.css` para organizar estilos y demostrar responsive design.
- Añadir ejemplos de plantillas (header/footer reutilizables) o fragmentos HTML.
- Incluir una pequeña guía de ejercicios para estudiantes (tareas prácticas con soluciones).
- Agregar mini servidor de desarrollo con `npm` y `live-server` si se va a ampliar con JS.

**Resolución de problemas**
- Si las imágenes no se muestran, revisa la ruta relativa en `blog.html` apuntando a `imagenes/`.
- Si el navegador bloquea recursos, sirve el proyecto con un servidor local en lugar de abrir el archivo directamente.

**Licencia y autor**
- **Autor**: (Añade tu nombre aquí)
- **Licencia**: (Especifica la licencia, por ejemplo MIT, si corresponde)

**Contacto y notas**
- Si quieres que amplíe este README con ejemplos de CSS, estructura de archivos más compleja o integración con herramientas (Live Server, npm), dímelo y lo preparo.

---

Fecha de creación: 2026-02-21
