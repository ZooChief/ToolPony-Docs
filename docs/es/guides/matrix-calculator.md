# Calculadora de matrices



Añadir, multiplicar, transponer, invertir, resolver o encontrar el rango y determinante. Copiar el resultado como TSV o descargar CSV.





## Ejemplo



### Entrada



```
A = [2, 4; 1, 3], B = [1, −2; 4, 5]
```



### Resultado esperado



```
A + B = [3, 2; 5, 8]
```







## Pruébalo

[Abrir herramienta completa · Calculadora de matrices](<https://toolpony.com/es/tools/matrix-calculator/>)





## Método de cálculo



Separar cada fila con una nueva línea o semicolon. Los valores pueden ser separados por espacios o comas. Se acepta un array JSON anidado. Los métodos de cuadrícula utilizan la eliminación gaisiana con pivote escalado.



$$
(AB)_{ij}=\sum_{k=1}^{n}A_{ik}B_{kj},\qquad A^{-1}A=I
$$



$$
[A\mid B]\longrightarrow[I\mid X]\quad\Rightarrow\quad AX=B
$$







## Modo de cálculo



**A + B**

- Matriz A
- Matriz B





**Subtract A - B**

- Matriz A
- Matriz B





**Multiplicar A × B**

- Matriz A
- Matriz B





**Resolver A × X = B**

- Matriz A
- Matriz B





**Determinante**

- Matriz A





**Inverso**

- Matriz A





**Transponer**

- Matriz A





**Poder entero**

- Matriz A
- Exponente





**Multiplicación de escalar**

- Matriz A
- Escalar





**Rank y forma de echelon de fila reducida**

- Matriz A







[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fmatrix-calculator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/matrix-calculator/)
