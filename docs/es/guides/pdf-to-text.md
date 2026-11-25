# Guía de uso · Convertir PDF a texto



Extrae el texto seleccionable de páginas PDF en TXT o JSON en tu dispositivo.





## Primeros pasos



1. Abre un PDF con texto seleccionable.
2. Indica el orden de las páginas y extrae el texto. Guarda TXT o JSON con los números de página originales.







## Ejemplo



### Entrada



```
PDF mixto en JSON, páginas 3, 2, 1. La página 2 contiene solo una muestra de color azul.
```

[Ejemplo · PDF](<https://toolpony.com/samples/toolpony-mixed-pages.pdf>)

### Resultado esperado



```
[{"page":3,"text":"Total 42"},{"page":2,"text":""},{"page":1,"text":"Order 417"}]
```





<a id="case-study"></a>



## Localizar la página sin texto en un PDF mixto



1. El PDF de muestra contiene «Order 417» en la página 1, solo una imagen azul en la 2 y «Total 42» en la 3. El botón de PDF mixto en la herramienta completa carga el archivo, selecciona las páginas 3, 2, 1 y elige JSON.
2. Tras extraer el texto, el primer registro contiene «Total 42» de la página 3, el segundo conserva la página 2 con el campo text vacío y el último muestra «Order 417» de la página 1. El resultado también indica el número original 2.
3. Antes de importar el texto a otro sistema, revisa las páginas señaladas. Puedes conservar un diagrama como imagen. Si la página es un escaneo de palabras impresas, el OCR permite crear una capa de texto.



[Convertir PDF a JPG o PNG](<https://toolpony.com/es/tools/pdf-to-jpg/>)



[toolpony-mixed-pages.pdf](<https://toolpony.com/samples/toolpony-mixed-pages.pdf>)





## Pruébalo

[Abrir herramienta completa · Convertir PDF a texto](<https://toolpony.com/es/tools/pdf-to-text/#example-mixed-pdf>)





## Notas de uso



Hasta 30 MB, 300 páginas, dos millones de caracteres y 200.000 fragmentos. Se sigue el orden de texto del PDF. Las páginas escaneadas requieren OCR. Se rechazan los PDF cifrados. Si el documento tiene hasta ocho páginas, borra la selección y toca los números en el orden de salida. En documentos más largos puedes seleccionar solo las páginas pares o impares.







## Límites



Hasta 30 MB, 300 páginas, dos millones de caracteres y 200.000 fragmentos. Se sigue el orden de texto del PDF. Las páginas escaneadas requieren OCR. Se rechazan los PDF cifrados.



Si un escaneo legible no devuelve texto, intenta seleccionar una palabra en un lector de PDF. Una página fotografiada necesita primero una capa de texto creada con OCR. En un documento mixto, el JSON identifica los campos text vacíos junto con su número de página original.





**Fuentes del método** [PDF Association · ISO 32000-2](<https://pdfa.org/resource/iso-32000-2/>) · [Adobe · PDF / OCR](<https://helpx.adobe.com/acrobat/desktop/create-documents/scan-documents-to-pdfs/recognize-text.html>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fpdf-to-text%2F>)

[Documentación](https://docs.toolpony.com/es/guides/pdf-to-text/)
