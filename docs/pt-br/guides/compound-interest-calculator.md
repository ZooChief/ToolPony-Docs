# Guia de uso · Calculadora de juros compostos



Projete um equilíbrio com contribuições recorrentes e inflação, ou converter entre frequências de compostos.





## Exemplo



### Entrada



```
10 000 a 5% ao ano durante 10 anos
```



### Resultado esperado



```
16,288.95
```





<a id="case-study"></a>



## Comparar aportes durante 30 meses



1. Comece com 10.000 e acrescente 100 por mês por dois anos e seis meses. Com taxa nominal de 6% e capitalização mensal, os aportes no fim do mês resultam em 14.842,00, dos quais 13.000 foram aportados. No início do mês, o saldo chega a 14.858,14. Com inflação anual de 3%, o primeiro saldo equivale hoje a 13.784,77.





## Experimente

[Abrir ferramenta completa · Calculadora de juros compostos](<https://toolpony.com/pt-br/tools/compound-interest-calculator/#example-30-months>)





## Método de cálculo



O crescimento anual efetivo é (1+r/m)^m−1, ou exp(r)−1 com compostos contínuos. Contribuições ganham juros a partir do início ou final de cada período selecionado.



$$
A=P(1+r/m)^{mt},\qquad \mathrm{APY}=(1+r/m)^m-1
$$







## Modo de cálculo





### Saldo futuro



- Principal
- Taxa anual · %
- Anos
- Meses
- Capitalização
- Contribuição periódica
- Frequência da contribuição · Anual / Semestral / Trimestral / Mensal / Duas vezes ao mês / A cada duas semanas / Semanal / Diária
- Contribuir no início do período
- Inflação anual · %







### Taxa de juro equivalente



- Taxa anual · %
- Composição original
- Composto-alvo







**Referências do método** [Investor.gov · Compound Interest](<https://www.investor.gov/financial-tools-calculators/calculators/compound-interest-calculator>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fcompound-interest-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/compound-interest-calculator/)
