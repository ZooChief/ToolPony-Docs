# Calculadora de área em pés quadrados



Estimativa da área e do custo do material para nove formas, com medições mistas e um subsídio de desperdício.





## Primeiros passos



1. Escolha a forma da área. Use as dimensões externas para a borda ou anel retângulo. O setor ocupa um raio e um ângulo central.
2. Defina a unidade ao lado de cada medição. Insira o número de áreas idênticas e, opcionalmente, o preço por unidade de área selecionada.
3. Leia a área da rede em pés quadrados e metros. Adicione um subsídio de desperdício sob Mais opções para estimar quanto para encomendar.







## Exemplo



### Entrada



```
13 pés × 9 pés, quantidade 1
```



### Resultado esperado



```
117 ft² (10,86965568 m²)
```







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/square-footage-calculator/>)







## Notas de uso



O cálculo é feito no seu navegador. Use unidades consistentes.







## Método de cálculo



Converter dimensões para uma unidade comum, encontrar a área de uma forma, e multiplicar por quantidade. Custo usa a área com qualquer subsídio selecionado, convertido para a unidade de preço. Dimensões de borda são medidas fora para fora.



$$
A_{\rm border}=lw-(l-2b)(w-2b),\qquad A_{\rm ring}=\pi b(d-b)
$$



$$
A_{\rm sector}=r^2\theta/2,\qquad A_{\rm order}=q A(1+w/100)
$$



A largura b da borda é medida para dentro a partir de cada lado. Em uma coroa circular, d é o diâmetro externo. Um retângulo externo de 13 ft × 9 ft com borda de 2 ft tem 72 ft² de borda por peça.



Para um setor, r é o raio e Δ é o ângulo em radianos após qualquer conversão. Na fórmula de ordem, q é a quantidade e w é o subsídio percentual.







## Modo de cálculo



**Rectângulo**

- Comprimento
- Unidade de comprimento
- Largura
- Unidade da largura
- Quantidade
- Preço unitário
- Preço por superfície
- Desperdícios · %





**Contorno retângulo**

- Comprimento
- Unidade de comprimento
- Largura
- Unidade da largura
- Largura da borda
- Unidade de largura da borda
- Quantidade
- Preço unitário
- Preço por superfície
- Desperdícios · %





**Círculo**

- Diâmetro
- Unidade de diâmetro
- Quantidade
- Preço unitário
- Preço por superfície
- Desperdícios · %





**Anel**

- Diâmetro exterior
- Unidade de diâmetro exterior
- Largura da borda
- Unidade de largura da borda
- Quantidade
- Preço unitário
- Preço por superfície
- Desperdícios · %





**Triângulo · três lados**

- Primeiro lado
- Unidade do primeiro lado
- Segundo lado
- Unidade do segundo lado
- Terceiro lado
- Unidade do terceiro lado
- Quantidade
- Preço unitário
- Preço por superfície
- Desperdícios · %





**Triângulo · base e altura**

- Base
- Unidade de base
- Altura perpendicular
- Unidade de altura perpendicular
- Quantidade
- Preço unitário
- Preço por superfície
- Desperdícios · %





**Trapézio**

- Primeiro lado paralelo
- Primeira unidade lateral paralela
- Segundo lado paralelo
- Segunda unidade lateral paralela
- Altura perpendicular
- Unidade de altura perpendicular
- Quantidade
- Preço unitário
- Preço por superfície
- Desperdícios · %





**Sector circular**

- Raio
- Unidade de raios
- Ângulo central
- Unidade de ângulo · Graus / Radianos
- Quantidade
- Preço unitário
- Preço por superfície
- Desperdícios · %





**Paralelograma**

- Base
- Unidade de base
- Altura perpendicular
- Unidade de altura perpendicular
- Quantidade
- Preço unitário
- Preço por superfície
- Desperdícios · %

[Documentação](https://docs.toolpony.com/pt-br/guides/square-footage-calculator/)
