# Publicación en GitHub Pages

No basta con subir los archivos HTML. La raíz del repositorio público debe contener esta estructura:

```text
index.html
frag-inicio.html
frag-reportes.html
frag-mapas.html
frag-calendario.html
frag-cedula.html
frag-mision.html
.nojekyll
assets/
  portal.css
  banners/
    agenda.webp
    cedula.webp
    inicio.webp
    mision.webp
    reportes.webp
    territorio.webp
```

El archivo `assets/portal.css` es el CSS compilado de Tailwind. Todos los HTML deben conservar la referencia `assets/portal.css`.

Después de reemplazar los archivos en GitHub, espera uno o dos minutos y fuerza la recarga del navegador con `Ctrl + F5`.
