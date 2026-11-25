# Guía de uso · Convertir imágenes



Añade imágenes de distintos formatos. El formato se detecta a partir del contenido del archivo. Configura formato, calidad y fondo por imagen. Descarga archivos sueltos o un ZIP.





## Primeros pasos



1. Añade imágenes de distintos formatos. El formato se detecta a partir del contenido del archivo.
2. Configura formato, calidad y fondo por imagen. Descarga archivos sueltos o un ZIP.







## Ejemplo



### Entrada



```
PNG · 64 × 32 px (esquinas transparentes) → JPEG · fondo blanco
```

[Ejemplo · PNG](<https://toolpony.com/samples/toolpony-64x32.png>)

### Resultado esperado



```
JPEG · 64 × 32 px (esquinas blancas)
```





<a id="case-study"></a>



## Comprobar el fondo de un PNG transparente antes de enviarlo como JPEG



1. En el conversor vacío, selecciona «Probar archivos de ejemplo». Se cargan un PNG transparente y un JPEG opaco de 64 × 32 px. Sus salidas están configuradas como JPEG y PNG, respectivamente.
2. Compara el original y la salida en paralelo. Selecciona una imagen para verla a tamaño real. El primer JPEG tiene esquinas blancas. El PNG creado a partir del JPEG también tiene esquinas opacas porque el blanco ya estaba en el original. Para conservar la transparencia del primer archivo, expórtalo como PNG con fondo transparente.
3. En un banner largo, comprueba las dimensiones de salida en la fila del archivo. Una imagen de 10 000 × 100 px se escala a 8192 × 82 px. El ajuste de calidad solo modifica la codificación.
4. Para comprobar el píxel, abre el JPEG de ejemplo en el selector de color y consulta (0, 0). En Chromium se obtuvo RGBA (255, 255, 243, 255). El PNG de ese JPEG conserva los mismos valores, incluido el alfa 255 de opacidad total.



[Selector de colores de imagen](<https://toolpony.com/es/tools/image-color-picker/>)





## Pruébalo

[Abrir herramienta completa · Convertir imágenes](<https://toolpony.com/es/tools/image-converter/#example-mixed-images>)





## Límites



Hasta 20 MB, 24 megapíxeles y 8.192 píxeles por lado de salida. La lectura de AVIF depende del navegador. Las animaciones se vuelven estáticas y se eliminan los metadatos originales. Hasta 12 imágenes y 64 MiB en total por lote.



Elige PNG para conservar la transparencia y JPEG para fotos y compatibilidad. JPEG rellena las zonas transparentes con el fondo elegido. WebP admite transparencia y calidad ajustable. AVIF aparece cuando el navegador puede codificarlo.



Por ejemplo, un logotipo WebP transparente se puede convertir en un PNG transparente. Para un formulario que solo admite JPEG, puedes usar un fondo blanco. Un JPEG convertido a PNG conserva los detalles visibles.





**Fuentes del método** [W3C · PNG](<https://www.w3.org/TR/png-3/>) · [WHATWG · HTML Canvas](<https://html.spec.whatwg.org/multipage/canvas.html#dom-canvas-toblob-dev>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fimage-converter%2F>)

[Documentación](https://docs.toolpony.com/es/guides/image-converter/)
