# Guía de uso · Calculadora de intervalos de confianza



Estima una media con datos o estadísticas resumidas usando z o t de Student, o una proporción con Wilson.





## Ejemplo



### Entrada



```
n = 36, media 56, desviación estándar 8, 99%
```



### Resultado esperado



```
56 ± 3.434
```





<a id="case-study"></a>



## Un intervalo con cinco mediciones



1. Las mediciones 48, 49, 50, 51 y 52 tienen media 50. Con la desviación muestral y cuatro grados de libertad, el intervalo t del 95 % para la media es aproximadamente 48,04–51,96. Se suponen observaciones independientes y una población aproximadamente normal.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/confidence-interval-calculator/#example-five-measurements>)





## Cero fallos en 30 controles



En 30 controles independientes no hubo fallos. El intervalo de Wilson del 95 % para la proporción de fallos va de 0 % a aproximadamente el 11,35 %. Más controles sin fallos estrechan el intervalo.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/confidence-interval-calculator/#example-no-failures>)







## Pruébalo

[Abrir herramienta completa · Calculadora de intervalos de confianza](<https://toolpony.com/es/tools/confidence-interval-calculator/>)





## Método de cálculo



El margen es el valor crítico × desviación / √n. Usa z si se conoce σ y t con n − 1 grados de libertad para una desviación muestral. Wilson estima una proporción binomial desde los éxitos y ensayos.



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## Modo de cálculo





### Intervalo de la media



- Origen de los datos · σ conocida / s muestral / Observaciones
- Tamaño de la muestra
- Media
- Desviación estándar
- Observaciones
- Nivel de confianza · %







### Intervalo de proporción de Wilson



- Tamaño de la muestra
- Éxitos
- Nivel de confianza · %







**Fuentes del método** [NIST · Confidence limits for the mean](<https://www.itl.nist.gov/div898/handbook/eda/section3/eda352.htm>) · [NIST · Confidence limits for a proportion](<https://www.itl.nist.gov/div898/handbook/prc/section2/prc241.htm>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fconfidence-interval-calculator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/confidence-interval-calculator/)
