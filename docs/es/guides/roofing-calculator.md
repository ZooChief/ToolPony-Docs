# Guía de uso · Calculadora de tejados



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





<a id="case-study"></a>



## Comprar tejas



1. Un tejado plano de 25 × 40 ft cubre 1.000 ft². Con 10 % de margen y 3 paquetes por 100 ft², compra 33 paquetes. A 75 cada uno cuestan 2.475.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/roofing-calculator/#example-roof-order>)





## Leer la cobertura del paquete



Para 1.100 ft², 33 paquetes de 33,3 ft² cubren 1.098,9 ft². Hacen falta 34, que cubren 1.132,2 ft².



[Ejecutar ejemplo](<https://toolpony.com/es/tools/roofing-calculator/#example-package-label>)







## Dos voladizos distintos



En una planta de 8 × 5 m, con 25 cm de alero y 40 cm en cada hastial, la proyección es 8,8 × 5,5 m. A 5/12 de pendiente, 10 % de margen y 3 m² por paquete se compran 20 paquetes.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/roofing-calculator/#example-roof-overhang>)







## Pruébalo

[Abrir herramienta completa · Calculadora de tejados](<https://toolpony.com/es/tools/roofing-calculator/>)





## Método de cálculo



Con solo el área en planta, usa A + 4,4e(√A + e) para el voladizo horizontal e. Con lados rectangulares medidos, usa (l + 2e)(w + 2e). Aplica el factor de pendiente. Un square de cubierta equivale a 100 ft². Verifica el rendimiento de cada producto.



$$
A_{\rm proj}\approx A+4.4e(\sqrt A+e),\qquad A_{\rm rect}=(l+2e)(w+2e)
$$



$$
A_{\rm roof}=A_{\rm proj}\sqrt{1+(p/12)^2}=\frac{A_{\rm proj}}{\cos\theta},\quad N_{\rm squares}=\left\lceil\frac{A_{\rm roof,ft^2}(1+a/100)}{100}\right\rceil
$$







## Modo de cálculo





### Planta y pendiente



- Área en planta
- Unidad de superficie · cm² / m² / in² / ft² / yd² / acre / ¡Ja!
- Elevación por 12 horizontales
- Voladizo horizontal
- Unidad de voladizo · mm / cm / m / dentro / ft / Yd
- Precio unitario
- Unidad de precio · cm² / m² / in² / ft² / yd² / acre / ¡Ja!
- Margen por desperdicio · %
- Cobertura por paquete · Paquetes por cuadrado de techo / Superficie por paquete
- Paquetes por 100 ft²
- Cobertura efectiva por paquete
- Precio por paquete (opcional)







### Planta y ángulo



- Área en planta
- Unidad de superficie · cm² / m² / in² / ft² / yd² / acre / ¡Ja!
- Ángulo del tejado · °
- Voladizo horizontal
- Unidad de voladizo · mm / cm / m / dentro / ft / Yd
- Precio unitario
- Unidad de precio · cm² / m² / in² / ft² / yd² / acre / ¡Ja!
- Margen por desperdicio · %
- Cobertura por paquete · Paquetes por cuadrado de techo / Superficie por paquete
- Paquetes por 100 ft²
- Cobertura efectiva por paquete
- Precio por paquete (opcional)







### Superficie de tejado conocida



- Superficie del tejado
- Unidad de superficie · cm² / m² / in² / ft² / yd² / acre / ¡Ja!
- Precio unitario
- Unidad de precio · cm² / m² / in² / ft² / yd² / acre / ¡Ja!
- Margen por desperdicio · %
- Cobertura por paquete · Paquetes por cuadrado de techo / Superficie por paquete
- Paquetes por 100 ft²
- Cobertura efectiva por paquete
- Precio por paquete (opcional)







### Largo y ancho medidos



- Largo
- Unidad de largo · mm / cm / m / dentro / ft / Yd
- Ancho
- Unidad de ancho · mm / cm / m / dentro / ft / Yd
- Elevación por 12 horizontales
- Voladizo horizontal
- Unidad de voladizo · mm / cm / m / dentro / ft / Yd
- Voladizo de hastial si varía
- Precio unitario
- Unidad de precio · cm² / m² / in² / ft² / yd² / acre / ¡Ja!
- Margen por desperdicio · %
- Cobertura por paquete · Paquetes por cuadrado de techo / Superficie por paquete
- Paquetes por 100 ft²
- Cobertura efectiva por paquete
- Unidad de superficie · cm² / m² / in² / ft² / yd² / acre / ¡Ja!
- Precio por paquete (opcional)







**Fuentes del método** [GAF · Bundle coverage per roofing square](<https://www.gaf.com/en-us/blog/your-home/how-many-bundles-of-shingles-are-in-a-square---63a47862-f7e1-4e73-abcf-8d09917a8b8d>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Froofing-calculator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/roofing-calculator/)
