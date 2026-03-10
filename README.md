# Hola

No hay mucho que ver aquí todavía.

## Instrucciones para usar una imagen de portada local

Para que la portada use una imagen local en lugar de hotlink a Unsplash, coloca un archivo llamado `portada.jpg` en la raíz del proyecto (junto a `index.html`).

Puedes descargar la foto desde Unsplash y guardarla con ese nombre. Ejemplo usando PowerShell (ejecutar en la carpeta del proyecto):

```powershell
# Descarga optimizada desde Unsplash (ajusta parámetros si lo deseas)
Invoke-WebRequest -Uri "https://images.unsplash.com/photo-1611262587963-0d2f9f7e0c3a?ixlib=rb-4.0.3&auto=format&fit=crop&w=1600&q=80" -OutFile .\portada.jpg
```

Después de descargarla, abre `index.html` en el navegador y deberías ver la imagen como fondo de la portada.

### Atribución

Foto desde Unsplash. Unsplash permite uso gratuito pero la atribución es recomendada como cortesía al autor.
