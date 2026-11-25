# Guía de uso · Calculadora estadística



Resumir un conjunto de datos con mediana, modos, cuartiles y dispersión de la población y la muestra.





## Ejemplo



### Entrada



```
2, 4, 4, 6, 9
```



### Resultado esperado



```
5, mediana 4
```







## Pruébalo

[Abrir herramienta completa · Calculadora estadística](<https://toolpony.com/es/tools/statistics-calculator/>)





## Método de cálculo



Los cuartiles se calculan por interpolación lineal en (n−1)p. La varianza poblacional divide por n y la muestral por n−1. Introduce hasta 1.000 valores separados por comas o espacios.



$$
\bar x=\frac{1}{n}\sum_{i=1}^{n} x_i,\qquad s=\sqrt{\frac{\sum_i(x_i-\bar x)^2}{n-1}}
$$



$$
\operatorname{SE}(\bar x)=\frac{s}{\sqrt n},\qquad \bar x\pm z\operatorname{SE}(\bar x)
$$



Use la desviación estándar de muestra para un subconjunto de una población y la desviación estándar de población para un conjunto completo. La tabla de confianza muestra la aproximación normal para el medio en varios niveles de confianza.







## Modo de cálculo





### Resumen del conjunto de datos



- Valores







### Muestra de desviación estándar



- Valores







### Desviación normal de la población



- Valores







[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fstatistics-calculator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/statistics-calculator/)
