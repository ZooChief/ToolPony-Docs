# Guia de uso · Conversor de cores



Converta cores CSS em HEX, RGB, HSL e OKLCH com opacidade e alternativa sRGB.





## Exemplo



### Entrada



```
rgb(102, 51, 153)
```



### Resultado esperado



```
#663399, hsl(270 50% 40%)
```





<a id="case-study"></a>



## Preparar uma alternativa sRGB para um recurso



1. Cole color(display-p3 0 1 0 / 70%). Esse verde está fora de sRGB. As amostras mostram o original e a alternativa; o mapeamento resulta em \#00FB29B3.
2. A linha RGB mantém a opacidade exata de 0,7. No HEX de oito dígitos, B3 equivale a 179/255.



[Executar exemplo](<https://toolpony.com/pt-br/tools/color-converter/#example-wide-gamut>)





## Experimente

[Abrir ferramenta completa · Conversor de cores](<https://toolpony.com/pt-br/tools/color-converter/>)





## Método de cálculo



HEX arredonda canais sRGB para bytes. Cores fora da gama são mapeadas pela croma OKLCH. A prévia original mantém seu espaço de cor.





**Referências do método** [W3C · CSS Color 4](<https://www.w3.org/TR/css-color-4/>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fcolor-converter%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/color-converter/)
