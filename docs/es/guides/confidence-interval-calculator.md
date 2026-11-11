# Calculadora de intervalos de confianza



Estimar un intervalo promedio normal o un intervalo de Wilson para una proporción.





## Primeros pasos



1. Usa el ejemplo o introduce tus propios valores.
2. Calcula, copia el resultado o descarga los detalles disponibles.







## Ejemplo



### Entrada



```
n = 36, media 56, desviación estándar 8, 99%
```



### Resultado esperado



```
56 ± 3.434
```







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/confidence-interval-calculator/>)







## Notas de uso



El cálculo se ejecuta en tu navegador. Usa unidades coherentes.







## Método de cálculo



El margen normal es z veces el error estándar s/√n. Los intervalos de puntuación de Wilson ajustan el centro y la anchura para las proporciones y permanecen dentro \[0,1\].



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## Modo de cálculo



**Intervalo medio normal**

- Tamaño de la muestra
- Media
- Desviación estándar
- Nivel de confianza · %





**Intervalo de proporción de Wilson**

- Tamaño de la muestra
- Éxitos
- Nivel de confianza · %

[Documentación](https://docs.toolpony.com/es/guides/confidence-interval-calculator/)
