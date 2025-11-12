# Ritmo - Landing para GitHub Pages

Este repo contiene la landing estática para el acceso anticipado de la app *Ritmo*.

## Archivos
- `index.html` - landing principal (ya presente)
- `styles.css` - estilos
- `privacy.html` - política de privacidad (ya presente)
- `success.html` - página de agradecimiento tras formulario

## Publicar en GitHub Pages
1. Crear repo (público) y subir estos archivos.
2. En GitHub → Settings → Pages:
   - Branch: `main` (o `gh-pages`)
   - Folder: `/ (root)`
3. Guardar. GitHub generará la URL: `https://<usuario>.github.io/<repo>/`.

## Formulario
El formulario en `index.html` usa Formspree. Reemplaza el `action` con tu endpoint Formspree (p.ej. `https://formspree.io/f/{TU_FORM_ID}`) o el endpoint que uses (Mailchimp, etc.).  
Configura la redirección al `success.html` para mejor UX.

## Dominio personalizado (opcional)
En Settings → Pages añade el nombre de tu dominio y crea un `CNAME` en tu DNS apuntando al dominio de GitHub Pages. GitHub gestionará HTTPS.

