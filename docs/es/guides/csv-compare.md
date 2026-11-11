# Comparador CSV



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







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/csv-compare/>)







## Límites



Hasta 1 MiB UTF-8, 5.000 filas y 80 columnas por tabla. La comparación conserva los ceros iniciales. Las claves vacías y duplicadas se muestran por separado. Los números cuentan registros desde el encabezado.

[Documentación](https://docs.toolpony.com/es/guides/csv-compare/)
