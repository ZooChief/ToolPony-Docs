# Calculadora de azulejos



Estimar fichas, cajas y costo de las dimensiones de la baldosa, espaciamiento de la grout, y el área a cubrir.





## Primeros pasos



1. Introduzca la longitud de la baldosa, la anchura y el espaciamiento. Una brecha negativa significa la solapa de las baldosas.
2. Introduzca un área conocida o dos dimensiones de la habitación. Introduzca fichas por caja para computar cajas enteras.
3. Para el corte y la rotura, ingrese una asignación en Más opciones. La herramienta calcula la cobertura por área.







## Ejemplo



### Entrada



```
180 ft², baldosas de 12 in × 12 in, junta de ¼ in, 12 por caja
```



### Resultado esperado



```
173 baldosas, 15 cajas
```







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/tile-calculator/>)







## Notas de uso



El cálculo se ejecuta en tu navegador. Usa unidades coherentes.







## Método de cálculo



Divide el área por (la longitud de la alimentación + la brecha) × (la anchura del material + la brecha), luego redondear. Modelos de brecha negativo superponen. Añadir una asignación seleccionada por el usuario antes de convertir a cajas enteras.



$$
N=\left\lceil\frac{A}{(l+g)(w+g)}\right\rceil,\quad N_{\rm order}=\left\lceil N(1+a/100)\right\rceil
$$



A 180 pies2 con 12 baldosas cuadradas y 1⁄4 de espacio, la estimación es de 173 baldosas. Con una asignación de 10% y 12 baldosas por caja, orden 191 baldosas, redondeado hasta 16 cajas.



El modelo de cobertura utiliza una longitud y anchura efectivas para cada baldosa. Permite cubrir el corte, patrones y rotura. Confirme el diseño final con sus dimensiones de espacio y azulejos reales.







## Modo de cálculo



**Espacio conocido**

- Longitud del azul
- Unidad de longitud
- Ancho de azul
- Unidad de ancho de azul
- Gap o overlap
- Unidad de solapamiento o superposición
- Superficie total
- Unidad de área
- Azulejos por caja
- Precio unitario
- Precio por
- Prestaciones por desechos · %





**Habitación rectangular**

- Longitud del azul
- Unidad de longitud
- Ancho de azul
- Unidad de ancho de azul
- Gap o overlap
- Unidad de solapamiento o superposición
- Longitud de la habitación
- Unidad de longitud de la habitación
- Ancho de la habitación
- Unidad de ancho de habitación
- Azulejos por caja
- Precio unitario
- Precio por
- Prestaciones por desechos · %

[Documentación](https://docs.toolpony.com/es/guides/tile-calculator/)
