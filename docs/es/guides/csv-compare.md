# Guía de uso · Comparador CSV



Pega o importa las dos tablas. Conserva el encabezado y elige el separador y las columnas clave. Compara y filtra los cambios. Usa CSV para hojas de cálculo y JSON para conservar el texto original y el informe completo.





## Primeros pasos



1. Pega o importa las dos tablas. Conserva el encabezado y elige el separador y las columnas clave.
2. Compara y filtra los cambios. Usa CSV para hojas de cálculo y JSON para conservar el texto original y el informe completo.







## Ejemplo



### Entrada



```
ID,Name,Qty
001,Oak,2
002,Pine,1
004,Ash,3

Qty,ID,Name
4,001,Oak
1,003,Fir
3,004,Ash
```



### Resultado esperado



```
Añadidas 1 · Eliminadas 1 · Modificadas 1
```





<a id="case-study"></a>



## Conciliar dos inventarios con columnas en distinto orden



1. Carga el ejemplo de inventario y elige ID como clave. El archivo anterior tiene las columnas ID, Name, Qty, y el nuevo empieza por Qty. Compara ambos archivos.
2. La cantidad de 001 (Oak) pasa de 2 a 4, desaparece 002, se añade 003 y 004 queda igual. A pesar del cambio de orden, hay un cambio, una baja y un alta.
3. Cambia solo 001 por 1 en el archivo nuevo. Ahora hay dos altas, dos bajas y cero cambios. Conserva los ceros iniciales al exportar para volver a conciliar el mismo artículo.





## Pruébalo

[Abrir herramienta completa · Comparador CSV](<https://toolpony.com/es/tools/csv-compare/#example-inventory>)





## Límites



Hasta 1 MiB UTF-8, 5.000 filas y 80 columnas por tabla. La comparación conserva los ceros iniciales. Las claves vacías y duplicadas se muestran por separado. Los números cuentan registros desde el encabezado.



Para comparar inventarios, usa una referencia estable como clave. Si 0012 pasa a 12 en el nuevo archivo, verás una baja y un alta. Conserva los ceros iniciales en ambos archivos para comparar las cantidades del mismo artículo.





**Fuentes del método** [IETF · RFC 4180 (CSV)](<https://www.rfc-editor.org/rfc/rfc4180>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fcsv-compare%2F>)

[Documentación](https://docs.toolpony.com/es/guides/csv-compare/)
