# Guía de uso · Calculadora del tamaño de muestra



Busque una muestra de encuesta mínima o estime el margen de error con corrección de población finita.





## Ejemplo



### Entrada



```
95% de confianza, 4% de margen, 35% de proporción, N = 1.000
```



### Resultado esperado



```
354 muestras
```







## Pruébalo

[Abrir herramienta completa · Calculadora del tamaño de muestra](<https://toolpony.com/es/tools/sample-size-calculator/>)





## Método de cálculo



El tamaño inicial es z2p(1−p)/e2. Para una población finita, dividir ese tamaño en 1 + (tamaño inicial−1)/N y redondear. El cálculo del error utiliza el mismo modelo de proporción y población finita.



$$
n_0=\frac{z^2p(1-p)}{e^2},\qquad n=\left\lceil\frac{n_0}{1+(n_0-1)/N}\right\rceil
$$







## Modo de cálculo





### Busque el tamaño de la muestra



- Nivel de confianza · %
- Margen de error · %
- Porcentaje de población · %
- Tamaño de la población (0 para ilimitados)







### Encontrar margen de error



- Nivel de confianza · %
- Tamaño de la muestra
- Porcentaje de población · %
- Tamaño de la población (0 para ilimitados)







[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fsample-size-calculator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/sample-size-calculator/)
