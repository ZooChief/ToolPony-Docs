# Calculadora de divisores



Liste cada divisor positivo, todos los pares de factor, y la factorización principal.





## Ejemplo



### Entrada



```
120
```



### Resultado esperado



```
16 divisores positivos, incluidos 1 y 120
```







## Pruébalo

[Abrir herramienta completa · Calculadora de divisores](<https://toolpony.com/es/tools/factor-calculator/>)





## Método de cálculo



Un divisor divide la entrada con cero restante. Cada pequeño divisor d pares con n/d, por lo que la búsqueda hasta √n encuentra cada par.



$$
d\mid n\iff n\bmod d=0,\qquad n=d\cdot(n/d)
$$





[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Ffactor-calculator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/factor-calculator/)
