# Guía de uso · Calculadora de mantillo



Estima el volumen, los sacos y el coste del mantillo para una o varias zonas.





## Primeros pasos



1. Introduce el área total o un rectángulo por línea, por ejemplo 6, 2, m. Cada fila admite una unidad distinta.
2. Indica el espesor y elige precio a granel o por saco. Para un saco personalizado, usa Más opciones.







## Ejemplo



### Entrada



```
200 ft², espesor de 2 in, sacos de 2 ft³ a 5 cada uno.
```



### Resultado esperado



```
33,3 ft³, 17 sacos, coste total de 85.
```







## Pruébalo

[Abrir herramienta completa · Calculadora de mantillo](<https://toolpony.com/es/tools/mulch-calculator/>)





## Método de cálculo



Suma las áreas sin solapamiento, multiplica por el espesor y añade el margen. Divide por la capacidad del saco y redondea hacia arriba. El precio a granel usa el volumen calculado.



$$
A=\sum_i l_iw_i,\quad V=Ad(1+a/100),\quad N=\left\lceil\frac{V}{V_{\rm bag}}\right\rceil
$$







## Modo de cálculo





### Área conocida



- Área
- Unidad de superficie · cm² / m² / in² / ft² / yd² / acre / ¡Ja!
- Espesor
- Unidad de espesor · mm / cm / m / dentro / ft / Yd
- Precio unitario
- Unidad de precio
- Capacidad por saco
- Unidad por saco · ft³ / yd³ / m³ / L
- Margen por desperdicio · %







### Varios rectángulos



- Largo, ancho, unidad por línea
- Espesor
- Unidad de espesor · mm / cm / m / dentro / ft / Yd
- Precio unitario
- Unidad de precio
- Capacidad por saco
- Unidad por saco · ft³ / yd³ / m³ / L
- Margen por desperdicio · %







[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fmulch-calculator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/mulch-calculator/)
