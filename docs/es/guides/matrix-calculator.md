# Guía de uso · Calculadora de matrices



Resuelve sistemas lineales y calcula determinantes, inversas, rangos y productos con fracciones y decimales exactos. Pega celdas de una hoja de cálculo y exporta el resultado.





## Ejemplo



### Entrada



```
A = [2, 4; 1, 3], B = [1, −2; 4, 5]
```



### Resultado esperado



```
A + B = [3, 2; 5, 8]
```





<a id="case-study"></a>



## Contar dos tipos de paquetes



1. Un paquete pequeño contiene 2 pinzas negras y 1 blanca, y uno grande 3 negras y 2 blancas. En total hay 17 negras y 10 blancas. Las columnas de A describen los paquetes y B contiene los totales. La solución es 4 paquetes pequeños y 3 grandes. Compruébala con A × X.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/matrix-calculator/#example-packing-matrix>)





## Un determinante igual a uno



El producto de la diagonal principal es mil millones al cuadrado. El otro es (mil millones − 1) × (mil millones + 1). La diferencia es exactamente 1 y las filas son independientes.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/matrix-calculator/#example-determinant-one>)







## Dos variables libres



La segunda ecuación duplica la primera. En x + y + z = 4 puedes elegir y y z, y tomar x = 4 − y − z. A la solución particular (4, 0, 0) se suman las dos direcciones del núcleo. Cambia el segundo total de 8 a 9 para ver la contradicción.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/matrix-calculator/#example-free-variables>)







## Pruébalo

[Abrir herramienta completa · Calculadora de matrices](<https://toolpony.com/es/tools/matrix-calculator/>)





## Método de cálculo



La reducción por filas usa aritmética racional exacta. El número de columnas pivote es el rango. En A × X = B, una fila de ceros a la izquierda con término independiente distinto de cero indica una contradicción. Las columnas libres determinan las direcciones que se suman a una solución particular.



$$
(AB)_{ij}=\sum_{k=1}^{n}A_{ik}B_{kj},\qquad A^{-1}A=I
$$



$$
[A\mid B]\longrightarrow[I\mid X]\quad\Rightarrow\quad AX=B
$$







## Modo de cálculo





### A + B



- Matriz A
- Matriz B







### Subtract A - B



- Matriz A
- Matriz B







### Multiplicar A × B



- Matriz A
- Matriz B







### Resolver A × X = B



- Matriz A
- Matriz B







### Determinante



- Matriz A







### Inverso



- Matriz A







### Transponer



- Matriz A







### Poder entero



- Matriz A
- Exponente







### Multiplicación de escalar



- Matriz A
- Escalar







### Rank y forma de echelon de fila reducida



- Matriz A







**Fuentes del método** [MIT OpenCourseWare · Solving Ax = b](<https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/resources/solving-ax-b-row-reduced-form-r/>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fmatrix-calculator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/matrix-calculator/)
