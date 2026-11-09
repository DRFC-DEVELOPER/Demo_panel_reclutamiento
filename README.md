# Panel de Candidatos DRFC

Este repositorio se publica como sitio estático en GitHub Pages usando `index.html`.

## Publicar

1. En GitHub, abre **Settings → Pages** y selecciona **GitHub Actions** como origen.
2. Sube los cambios a la rama `main` o ejecuta manualmente el workflow **Deploy to GitHub Pages** desde la pestaña **Actions**.
3. Al terminar el workflow, GitHub mostrará la URL del sitio en **Settings → Pages**.

## Importante sobre seguridad

GitHub Pages sirve el HTML y JavaScript públicamente. Todo valor incluido en el navegador puede ser leído por los visitantes; una contraseña comprobada en JavaScript no protege el sitio. Antes de publicar, rota las claves compartidas que ya aparecen en el código y mueve las operaciones que dependen de secretos a un backend protegido. La clave publicable de Supabase también requiere políticas RLS correctamente configuradas.
