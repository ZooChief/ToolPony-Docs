# Calculadora de telhado



Estime área de telhado, squares, pacotes de telhas, rolos de feltro e custo.





## Primeiros passos



1. Escolha área em planta com inclinação ou ângulo. Para uma planta retangular, informe comprimento e largura.
2. Para um telhado complexo, some as áreas inclinadas medidas e informe o total em Área de telhado conhecida.







## Exemplo



### Entrada



```
Área em planta de 2.000 ft², inclinação 6/12 e beiral de 1 ft.
```



### Resultado esperado



```
Cerca de 2.461 ft², 28 squares com margem de 10%.
```







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/roofing-calculator/>)







## Notas de uso



O cálculo é feito no seu navegador. Use unidades consistentes.







## Método de cálculo



Só com a área em planta, estime o beiral horizontal e usando A + 4,4e(√A + e). Com lados retangulares medidos, use (l + 2e)(w + 2e). Aplique o fator de inclinação. Um square equivale a 100 ft². Confira a cobertura indicada pelo fabricante.



$$
A_{\rm proj}\approx A+4.4e(\sqrt A+e),\qquad A_{\rm rect}=(l+2e)(w+2e)
$$



$$
A_{\rm roof}=A_{\rm proj}\sqrt{1+(p/12)^2}=\frac{A_{\rm proj}}{\cos\theta},\quad N_{\rm squares}=\left\lceil\frac{A_{\rm roof,ft^2}(1+a/100)}{100}\right\rceil
$$







## Modo de cálculo



**Área em planta e inclinação**

- Área em planta
- Unidade de área · cm² / m² / in² / ft² / yd² / acre / ha
- Elevação a cada 12 na horizontal
- Projeção horizontal do beiral
- Unidade do beiral · mm / cm / m / em / ft / yd
- Preço unitário
- Unidade de preço · cm² / m² / in² / ft² / yd² / acre / ha
- Margem de perda · %





**Área em planta e ângulo**

- Área em planta
- Unidade de área · cm² / m² / in² / ft² / yd² / acre / ha
- Ângulo do telhado · °
- Projeção horizontal do beiral
- Unidade do beiral · mm / cm / m / em / ft / yd
- Preço unitário
- Unidade de preço · cm² / m² / in² / ft² / yd² / acre / ha
- Margem de perda · %





**Área de telhado conhecida**

- Área de telhado
- Unidade de área · cm² / m² / in² / ft² / yd² / acre / ha
- Preço unitário
- Unidade de preço · cm² / m² / in² / ft² / yd² / acre / ha
- Margem de perda · %





**Comprimento e largura medidos**

- Comprimento
- Unidade de comprimento · mm / cm / m / em / ft / yd
- Largura
- Unidade de largura · mm / cm / m / em / ft / yd
- Elevação a cada 12 na horizontal
- Projeção horizontal do beiral
- Unidade do beiral · mm / cm / m / em / ft / yd
- Preço unitário
- Unidade de preço · cm² / m² / in² / ft² / yd² / acre / ha
- Margem de perda · %

[Documentação](https://docs.toolpony.com/pt-br/guides/roofing-calculator/)
