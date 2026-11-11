# Calculadora de cobertura vegetal



Estime volume, sacos e custo de cobertura para uma ou mais áreas.





## Primeiros passos



1. Informe a área total ou um retângulo por linha, como 6, 2, m. Cada linha pode usar uma unidade diferente.
2. Informe a espessura e escolha preço a granel ou por saco. Use Mais opções para um saco personalizado.







## Exemplo



### Entrada



```
200 ft², espessura de 2 in, sacos de 2 ft³ a 5 cada.
```



### Resultado esperado



```
33,3 ft³, 17 sacos, custo total de 85.
```







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/mulch-calculator/>)







## Notas de uso



O cálculo é feito no seu navegador. Use unidades consistentes.







## Método de cálculo



Some as áreas sem sobreposição e aplique a espessura e a margem. Divida pela capacidade do saco e arredonde para cima. O preço a granel usa o volume calculado.



$$
A=\sum_i l_iw_i,\quad V=Ad(1+a/100),\quad N=\left\lceil\frac{V}{V_{\rm bag}}\right\rceil
$$







## Modo de cálculo



**Área conhecida**

- Área
- Unidade de área · cm² / m² / in² / ft² / yd² / acre / ha
- Espessura
- Unidade de espessura · mm / cm / m / em / ft / yd
- Preço unitário
- Unidade de preço
- Capacidade por saco
- Unidade por saco · ft³ / yd³ / m³ / L
- Margem de perda · %





**Vários retângulos**

- Comprimento, largura, unidade por linha
- Espessura
- Unidade de espessura · mm / cm / m / em / ft / yd
- Preço unitário
- Unidade de preço
- Capacidade por saco
- Unidade por saco · ft³ / yd³ / m³ / L
- Margem de perda · %

[Documentação](https://docs.toolpony.com/pt-br/guides/mulch-calculator/)
