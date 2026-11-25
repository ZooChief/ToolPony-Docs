# Guía de uso · Calculadora de áreas



Encuentra el área de formas de plano en once modos con unidades de entrada mixtas y una unidad de salida seleccionable.





## Ejemplo



### Entrada



```
Un rectángulo de 4 m por 3 m
```



### Resultado esperado



```
12 m²
```





<a id="case-study"></a>



## Recortar un anillo



1. Para una junta plana de diámetro exterior 60 mm y orificio de 40 mm, introduce radios de 30 y 20 mm. Elige mm² como unidad de área.
2. El área es 500π mm², unos 1.570,80 mm². Los dos cortes suman 100π mm, unos 314,16 mm. El archivo incluye cada circunferencia y las medidas originales.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/area-calculator/#example-gasket>)





## Pruébalo

[Abrir herramienta completa · Calculadora de áreas](<https://toolpony.com/es/tools/area-calculator/>)





## Método de cálculo



Dimensiones se convierten a metros antes del cálculo. El triángulo de tres caras utiliza la fórmula de Heron. Un sector utiliza la mitad del radio cuadrado veces su ángulo en radians.



$$
A_{\mathrm{rectangle}}=lw,\qquad A_{\mathrm{sector}}=\tfrac12 r^2\theta
$$



$$
A_{\mathrm{triangle}}=\sqrt{s(s-a)(s-b)(s-c)},\quad s=\tfrac12(a+b+c)
$$







## Modo de cálculo





### Rectángulo



- Longitud
- Unidad de longitud
- Ancho
- Unidad de ancho
- Unidad de área







### Plaza



- Longitud del lado
- Unidad del lado
- Unidad de área







### Triángulo · tres lados



- Primer lado
- Primera unidad lateral
- Segundo lado
- Segunda unidad lateral
- Tercer lado
- Tercera unidad lateral
- Unidad de área







### Triángulo · base y altura



- Longitud de la base
- Unidad de la base
- Altura perpendicular
- Unidad de altura perpendicular
- Unidad de área







### Trapecio



- Primera cara paralela
- Primera unidad lateral paralela
- Segundo lado paralelo
- Segunda unidad lateral paralela
- Altura perpendicular
- Unidad de altura perpendicular
- Unidad de área







### Círculo



- Radio
- Unidad radiactiva
- Unidad de área







### Sector circular



- Radio
- Unidad radiactiva
- Ángulo central
- Unidad angular · Grados / Radianes
- Unidad de área







### Elipse



- Primer semi-eje
- Primera unidad semi-eje
- Segundo semi-eje
- Segunda unidad semi-eje
- Unidad de área







### Parallelograma



- Longitud de la base
- Unidad de la base
- Altura perpendicular
- Unidad de altura perpendicular
- Unidad de área







### Corona circular



- radio exterior
- Unidad de radio exterior
- Radio interior
- Unidad de radio interior
- Unidad de área







### Pólvora regular



- Longitud del lado
- Unidad del lado
- Número de lados
- Unidad de área







**Fuentes del método** [BIPM · SI](<https://www.bipm.org/en/publications/si-brochure>) · [NIST DLMF · Lengths of plane curves](<https://dlmf.nist.gov/19.30>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Farea-calculator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/area-calculator/)
