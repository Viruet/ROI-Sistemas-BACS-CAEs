# ROI Sistemas BACS + CAEs · GitHub Pages

Repositorio listo para publicar la calculadora HTML como sitio estático en GitHub Pages.

## Archivos incluidos

- `index.html` → aplicación completa (HTML + CSS + JavaScript embebidos)
- `.nojekyll` → evita procesamiento Jekyll innecesario
- `404.html` → redirección básica al inicio
- `.gitignore` → exclusiones comunes

## Opción recomendada: publicar desde la rama `main`

1. Crea un repositorio nuevo en GitHub.
2. Sube el contenido de esta carpeta a la raíz del repositorio.
3. En GitHub ve a **Settings → Pages**.
4. En **Build and deployment**, selecciona:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Guarda los cambios.
6. GitHub publicará la web con una URL del tipo:
   - `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`

## Subida rápida con Git

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/NOMBRE-DEL-REPO.git
git push -u origin main
```

## Notas

- La app es 100% estática, así que no necesita backend ni base de datos.
- Si cambias cualquier archivo y haces `git push`, GitHub Pages volverá a publicar automáticamente.
- Si quieres que la URL sea `https://TU-USUARIO.github.io/`, el repositorio debe llamarse exactamente `TU-USUARIO.github.io`.
