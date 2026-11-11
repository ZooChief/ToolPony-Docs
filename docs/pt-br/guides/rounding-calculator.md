# Calculadora de arredondamento



Decimais precisos redondos por decimal ou uma fração binária com nove modos de arredondamento.





## Primeiros passos



1. Use o exemplo ou insira seus próprios valores.
2. Calcule, copie o resultado ou baixe os detalhes disponíveis.







## Exemplo



### Entrada



```
−2,5, um, metade para igual
```



### Resultado esperado



```
−2
```







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/rounding-calculator/>)







## Notas de uso



O cálculo é feito no seu navegador. Use unidades consistentes.







## Método de cálculo



Compare o restante decimal exato com meio passo. Para os laços, selecione uma regra de direção ou paridade. O mais próximo usa laços longe de zero.



$$
x=qs+r,\qquad 0\le r<s,\qquad r=\tfrac{s}{2}\text{ at a tie}
$$



Um lugar de 2 rodadas para centésimos, 0 rodadas para unidades, e −2 rodadas para centenas. Uma rodada de passo fracionária para um múltiplo como 1/4 ou 1/16.



Meio-para-mesmo escolhe o mesmo múltiplo apenas em um empate exato. Por exemplo, −2,5 vai para −2 e −3.5 vai para −4. O teto sempre se move em direção ao infinito positivo.

[Documentação](https://docs.toolpony.com/pt-br/guides/rounding-calculator/)
