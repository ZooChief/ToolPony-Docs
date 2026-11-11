# Calculadora de superficie en pies cuadrados



Costo estimado del área y del material para nueve formas, con mediciones mixtas y una asignación de residuos.





## Primeros pasos



1. Elija la forma de la zona. Utilice las dimensiones exteriores para la frontera del rectángulo o el anillo. El sector toma un radio y un ángulo central.
2. Establecer la unidad junto a cada medición. Introduzca el número de áreas idénticas y opcionalmente el precio por unidad de área seleccionada.
3. Lea el área neta en pies y metros cuadrados. Agregue una asignación de residuos bajo Más opciones para estimar cuánto pedir.







## Ejemplo



### Entrada



```
13 ft × 9 ft, cantidad 1
```



### Resultado esperado



```
117 ft² (10,86965568 m²)
```







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/square-footage-calculator/>)







## Notas de uso



El cálculo se ejecuta en tu navegador. Usa unidades coherentes.







## Método de cálculo



Convertir dimensiones en una unidad común, encontrar el área de una forma y multiplicarse por cantidad. Usos de costes área con cualquier asignación seleccionada, convertido a la unidad de precio. Las dimensiones fronterizas se miden fuera a fuera.



$$
A_{\rm border}=lw-(l-2b)(w-2b),\qquad A_{\rm ring}=\pi b(d-b)
$$



$$
A_{\rm sector}=r^2\theta/2,\qquad A_{\rm order}=q A(1+w/100)
$$



El ancho del borde b se mide hacia dentro desde cada lado. En una corona circular, d es el diámetro exterior. Un rectángulo exterior de 13 ft × 9 ft con un borde de 2 ft tiene 72 ft² de borde por pieza.



Para un sector, r es radius y θ es el ángulo en radians después de cualquier conversión. En la fórmula de orden, q es cantidad y w es el porcentaje de la asignación.







## Modo de cálculo



**Rectángulo**

- Longitud
- Unidad de longitud
- Ancho
- Unidad de ancho
- Cantidad
- Precio unitario
- Precio por área
- Prestaciones por desechos · %





**Frontera de rectángulo**

- Longitud
- Unidad de longitud
- Ancho
- Unidad de ancho
- Ancho fronterizo
- Unidad de ancho de frontera
- Cantidad
- Precio unitario
- Precio por área
- Prestaciones por desechos · %





**Círculo**

- Diámetro
- Unidad de diámetro
- Cantidad
- Precio unitario
- Precio por área
- Prestaciones por desechos · %





**Anillo**

- Diámetro exterior
- Unidad de diámetro exterior
- Ancho fronterizo
- Unidad de ancho de frontera
- Cantidad
- Precio unitario
- Precio por área
- Prestaciones por desechos · %





**Triángulo · tres lados**

- Primer lado
- Primera unidad lateral
- Segundo lado
- Segunda unidad lateral
- Tercer lado
- Tercera unidad lateral
- Cantidad
- Precio unitario
- Precio por área
- Prestaciones por desechos · %





**Triángulo · base y altura**

- Base
- Unidad de base
- Altura perpendicular
- Unidad de altura perpendicular
- Cantidad
- Precio unitario
- Precio por área
- Prestaciones por desechos · %





**Trapecio**

- Primera cara paralela
- Primera unidad lateral paralela
- Segundo lado paralelo
- Segunda unidad lateral paralela
- Altura perpendicular
- Unidad de altura perpendicular
- Cantidad
- Precio unitario
- Precio por área
- Prestaciones por desechos · %





**Sector circular**

- Radio
- Unidad radiactiva
- Ángulo central
- Unidad de ángulo · Grados / Radians
- Cantidad
- Precio unitario
- Precio por área
- Prestaciones por desechos · %





**Parallelograma**

- Base
- Unidad de base
- Altura perpendicular
- Unidad de altura perpendicular
- Cantidad
- Precio unitario
- Precio por área
- Prestaciones por desechos · %

[Documentación](https://docs.toolpony.com/es/guides/square-footage-calculator/)
