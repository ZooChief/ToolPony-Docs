# Calculadora de tejados



Estima la superficie del tejado, squares, paquetes de tejas, rollos de fieltro y coste.





## Primeros pasos



1. Elige planta con pendiente o ángulo. Para una planta rectangular, introduce el largo y ancho medidos.
2. Para un tejado complejo, suma las superficies inclinadas medidas e introduce el total en Superficie de tejado conocida.







## Ejemplo



### Entrada



```
Planta de 2.000 ft², pendiente 6/12 y voladizo de 1 ft.
```



### Resultado esperado



```
Unos 2.461 ft², 28 squares con margen del 10 %.
```







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/roofing-calculator/>)







## Notas de uso



El cálculo se ejecuta en tu navegador. Usa unidades coherentes.







## Método de cálculo



Con solo el área en planta, usa A + 4,4e(√A + e) para el voladizo horizontal e. Con lados rectangulares medidos, usa (l + 2e)(w + 2e). Aplica el factor de pendiente. Un square de cubierta equivale a 100 ft². Verifica el rendimiento de cada producto.



$$
A_{\rm proj}\approx A+4.4e(\sqrt A+e),\qquad A_{\rm rect}=(l+2e)(w+2e)
$$



$$
A_{\rm roof}=A_{\rm proj}\sqrt{1+(p/12)^2}=\frac{A_{\rm proj}}{\cos\theta},\quad N_{\rm squares}=\left\lceil\frac{A_{\rm roof,ft^2}(1+a/100)}{100}\right\rceil
$$







## Modo de cálculo



**Planta y pendiente**

- Área en planta
- Unidad de superficie · cm² / m² / in² / ft² / yd² / acre / ¡Ja!
- Elevación por 12 horizontales
- Voladizo horizontal
- Unidad de voladizo · mm / cm / m / dentro / ft / Yd
- Precio unitario
- Unidad de precio · cm² / m² / in² / ft² / yd² / acre / ¡Ja!
- Margen por desperdicio · %





**Planta y ángulo**

- Área en planta
- Unidad de superficie · cm² / m² / in² / ft² / yd² / acre / ¡Ja!
- Ángulo del tejado · °
- Voladizo horizontal
- Unidad de voladizo · mm / cm / m / dentro / ft / Yd
- Precio unitario
- Unidad de precio · cm² / m² / in² / ft² / yd² / acre / ¡Ja!
- Margen por desperdicio · %





**Superficie de tejado conocida**

- Superficie del tejado
- Unidad de superficie · cm² / m² / in² / ft² / yd² / acre / ¡Ja!
- Precio unitario
- Unidad de precio · cm² / m² / in² / ft² / yd² / acre / ¡Ja!
- Margen por desperdicio · %





**Largo y ancho medidos**

- Largo
- Unidad de largo · mm / cm / m / dentro / ft / Yd
- Ancho
- Unidad de ancho · mm / cm / m / dentro / ft / Yd
- Elevación por 12 horizontales
- Voladizo horizontal
- Unidad de voladizo · mm / cm / m / dentro / ft / Yd
- Precio unitario
- Unidad de precio · cm² / m² / in² / ft² / yd² / acre / ¡Ja!
- Margen por desperdicio · %

[Documentación](https://docs.toolpony.com/es/guides/roofing-calculator/)
