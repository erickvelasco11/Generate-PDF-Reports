# Generación de PDF a partir de Markdown

Este documento proporciona instrucciones sobre cómo convertir archivos Markdown a PDF utilizando la herramienta en línea [Markdown to PDF](https://www.markdowntopdf.com/).

## Pasos para Generar un PDF

1. **Prepara tu archivo Markdown**

   Asegúrate de tener el archivo Markdown que deseas convertir en PDF. El archivo debe tener una extensión `.md`, por ejemplo, `documento.md`.
   Si el reporte generado va a tener imágenes se deben incluir como etiquetas HTML donde adicional se puede poner un ancho específico y un pie de página, además el Source de la imagen debe ser una URL válida pública.

   Ejemplo

```
<div style="text-align:center">
  <img src="[maps](https://raw.githubusercontent.com/erickvelasco11/Test/fac1453fa32689c2f12fcade4a48cb90e5faab7d/maps/4.png" alt="Sendero de la calle 12D" width="500">
  <p><em>Figura 16: Mapa del Sendero de la calle 12D</em></p>
</div>
```

3. **Accede a la herramienta en línea**

   Abre tu navegador web y ve a [Markdown to PDF](https://www.markdowntopdf.com/).

4. **Carga tu archivo Markdown**

   - En la página principal de la herramienta, encontrarás un área para cargar archivos.
   - Haz clic en el botón **"Choose File"** (Elegir archivo) y selecciona tu archivo Markdown (`documento.md`).

5. **Genera el PDF**

   - Después de seleccionar el archivo, haz clic en el botón **"Convert"** (Convertir).
   - La herramienta procesará el archivo y generará un archivo PDF para descargarlo automáticamente
