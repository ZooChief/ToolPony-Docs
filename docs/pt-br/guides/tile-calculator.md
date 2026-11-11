# Calculadora de quantidade de pisos



Estimar azulejos, caixas e custo de dimensões de azulejo, espaçamento de grout, e a área para cobrir.





## Primeiros passos



1. Indique o comprimento, a largura e o espaçamento da peça. Uma lacuna negativa significa que as peças se sobrepõem.
2. Indique uma área conhecida ou duas dimensões da sala. Indique as peças por caixa para calcular as caixas inteiras.
3. Para cortar e quebrar, insira um subsídio em Mais opções. A ferramenta estima a cobertura por área.







## Exemplo



### Entrada



```
180 ft², pisos de 12 in × 12 in, junta de ¼ in, 12 por caixa
```



### Resultado esperado



```
173 telhas, 15 caixas
```







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/tile-calculator/>)







## Notas de uso



O cálculo é feito no seu navegador. Use unidades consistentes.







## Método de cálculo



Dividir a área por (comprimento do tile + gap) × (largura do tile + gap), em seguida, arredondar. Modelos de gap negativos sobrepõem-se. Adicione uma licença selecionada pelo usuário antes de converter para caixas inteiras.



$$
N=\left\lceil\frac{A}{(l+g)(w+g)}\right\rceil,\quad N_{\rm order}=\left\lceil N(1+a/100)\right\rceil
$$



A 180 pés2 com 12 em azulejos quadrados e 1⁄4 em espaço, a estimativa é de 173 azulejos. Com um subsídio de 10% e 12 azulejos por caixa, encomendar 191 azulejos, arredondados até 16 caixas.



O modelo de cobertura usa um comprimento e largura eficazes para cada azulejo. O subsídio cobre o corte, os padrões e a quebra. Confirme o layout final com as dimensões reais do seu quarto e azulejo.







## Modo de cálculo



**Área conhecida**

- Comprimento do ladrilho
- Unidade de comprimento da telha
- Largura do ladrilho
- Unidade de largura do ladrilho
- Gap ou sobreposição
- Gap ou unidade de sobreposição
- Área total
- Unidade de área
- Tiles por caixa
- Preço unitário
- Preço por
- Desperdícios · %





**Sala retangular**

- Comprimento do ladrilho
- Unidade de comprimento da telha
- Largura do ladrilho
- Unidade de largura do ladrilho
- Gap ou sobreposição
- Gap ou unidade de sobreposição
- Comprimento do quarto
- Unidade de comprimento do quarto
- Largura do quarto
- Unidade de largura do quarto
- Tiles por caixa
- Preço unitário
- Preço por
- Desperdícios · %

[Documentação](https://docs.toolpony.com/pt-br/guides/tile-calculator/)
