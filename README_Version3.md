```markdown
# ONAAG — sitio web

Este repositorio contiene un sitio estático (HTML/CSS/JS) listo para publicarse en GitHub Pages.

Cómo publicar (rápido)
1. Asegúrate de que el repositorio sea público.
2. Coloca `index.html` en la raíz del repositorio (ya está preparado).
3. Si el nombre del repositorio es `sitioonaag.github.io`, GitHub Pages publicará el sitio en:
   https://ONAAG.github.io
   - Si el repositorio tiene otro nombre, ve a Settings > Pages y selecciona la rama `main` (root) o `gh-pages` según prefieras.
4. Opcional: crea un archivo `CNAME` con tu dominio personalizado si tienes uno, por ejemplo:
   ```
   misitio.com
   ```
5. Si tienes problemas con Jekyll o rutas que empiezan con `_`, el archivo `.nojekyll` incluido evita que Jekyll procese el sitio.

Qué revisar antes de publicar
- Reemplaza el favicon (link en el head).
- En el contacto: actualiza el email del formulario en `action="https://formsubmit.co/CONTACT_EMAIL"` con tu correo real.
- Revisa la dirección de WhatsApp y teléfono.
- Sube imágenes reales a `assets/` y ajusta las rutas en el HTML si fuera necesario.
- Si quieres usar `mailto:` en lugar de FormSubmit, cambia el `action` del `<form>` a `mailto:TU_EMAIL`.

Necesitas que lo suba yo?
- Puedo crear the initial commit with these files directly in the main branch for you. Tell me to proceed and confirm you accepted the authorization dialog on GitHub so I can complete the push.
```