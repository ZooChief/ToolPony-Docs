# Guía de uso · Conversor de color



Convierte colores CSS a HEX, RGB, HSL y OKLCH con opacidad y alternativa sRGB.





## Ejemplo



### Entrada



```
rgb(102, 51, 153)
```



### Resultado esperado



```
#663399, hsl(270 50% 40%)
```





<a id="case-study"></a>



## Preparar una alternativa sRGB para un recurso



1. Pega color(display-p3 0 1 0 / 70%). Este verde supera sRGB. Las muestras enseñan el original y su alternativa, que con este método es \#00FB29B3.
2. La línea RGB conserva la opacidad exacta de 0,7. En HEX de ocho dígitos, B3 equivale a 179/255.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/color-converter/#example-wide-gamut>)





## Pruébalo

[Abrir herramienta completa · Conversor de color](<https://toolpony.com/es/tools/color-converter/>)





## Método de cálculo



HEX redondea los canales sRGB a bytes. Los colores fuera de gama se ajustan en croma OKLCH. La vista original conserva su espacio de color.





**Fuentes del método** [W3C · CSS Color 4](<https://www.w3.org/TR/css-color-4/>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fcolor-converter%2F>)

[Documentación](https://docs.toolpony.com/es/guides/color-converter/)
