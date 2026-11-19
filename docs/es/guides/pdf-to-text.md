# Convertir PDF a texto



Extrae el texto seleccionable de páginas PDF en TXT o JSON en tu dispositivo.





## Primeros pasos



1. Abre un PDF con texto seleccionable.
2. Indica el orden de las páginas y extrae el texto. Guarda TXT o JSON con los números de página originales.







## Ejemplo



### Entrada



```
PDF con «One» y «Two» en las primeras dos páginas, selección 2, 1
```

[Ejemplo · PDF](<https://toolpony.com/samples/toolpony-pages.pdf>)

### Resultado esperado



```
JSON con la página 2 «Two» seguida de la página 1 «One»
```







## Pruébalo

[Abrir herramienta completa · Convertir PDF a texto](<https://toolpony.com/es/tools/pdf-to-text/>)





## Límites



Hasta 30 MB, 300 páginas, dos millones de caracteres y 200.000 fragmentos. Se sigue el orden de texto del PDF. Las páginas escaneadas requieren OCR. Se rechazan los PDF cifrados.



Si un escaneo legible no devuelve texto, intenta seleccionar una palabra en un lector de PDF. Una página fotografiada necesita primero una capa de texto creada con OCR. En un documento mixto, el JSON identifica los campos text vacíos junto con su número de página original.

[Documentación](https://docs.toolpony.com/es/guides/pdf-to-text/)
