# Guía de uso · Comprobador de contraste



Comprueba el contraste del texto y la interfaz sobre capas opacas o translúcidas y prueba un color que cumpla los umbrales WCAG.





## Ejemplo



### Entrada



```
#000000 sobre #FFFFFF
```



### Resultado esperado



```
21:1
```





<a id="case-study"></a>



## Elegir un gris que cumpla AA para texto normal sobre blanco



1. Prueba \#777777 sobre blanco. La relación es de unos 4,48:1. Redondeada a un decimal parece 4,5, pero al evaluar el valor sin redondear el texto normal queda por debajo de WCAG AA.
2. Prueba \#767676 con el mismo fondo. La relación sube a unos 4,54:1 y el texto normal cumple AA. Ambos ejemplos alcanzan 3:1 para texto grande.
3. Comprueba los colores que realmente se muestran. En texto sobre una imagen o capa translúcida, toma los colores finales de la zona con menos contraste. El resultado corresponde a ese par de colores sólidos.
4. Sobre blanco, \#00000080 da \#7F7F7F y alrededor de 4,00:1. La sugerencia \#767676 alcanza 4,54:1 para texto normal.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/contrast-checker/#example-translucent-text>)





## Pruébalo

[Abrir herramienta completa · Comprobador de contraste](<https://toolpony.com/es/tools/contrast-checker/>)





## Método de cálculo



La relación divide (luminancia clara + 0,05) entre (luminancia oscura + 0,05). La prueba usa el valor sin redondear. El texto normal requiere 4,5:1 para AA y 7:1 para AAA. El texto grande requiere 3:1 y 4,5:1.





**Fuentes del método** [W3C · WCAG 2.2 (1.4.3, AA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html>) · [W3C · WCAG 2.2 (1.4.6, AAA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-enhanced.html>) · [W3C · Non-text contrast](<https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html>) · [W3C · Source-over compositing](<https://www.w3.org/TR/compositing-1/#simplealphacompositing>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fcontrast-checker%2F>)

[Documentación](https://docs.toolpony.com/es/guides/contrast-checker/)
