# Guia de uso · Calculadora de prazo de retorno



Encontre uma vingança regular e descontada dos fluxos de caixa anuais crescentes ou irregulares.





## Exemplo



### Entrada



```
17.500 inicial, primeira entrada 4.700, crescimento 8%, desconto 6%
```



### Resultado esperado



```
Vingança 3.379 anos, descontado 3.841 anos
```







## Experimente

[Abrir ferramenta completa · Calculadora de prazo de retorno](<https://toolpony.com/pt-br/tools/payback-period-calculator/>)





## Método de cálculo



Acumule os fluxos de caixa a partir da despesa inicial. Na primeira passagem de zero, interpole a fração desse ano. Fluxos de caixa com desconto dividem o ano k por (1+r)^k. Um fluxo constante usa a fórmula de anuidade inversa para pagamento descontado.



$$
C_k=\sum_{i=0}^{k}F_i,\qquad F_i^{\mathrm{PV}}=\frac{F_i}{(1+r)^i}
$$







## Modo de cálculo





### Fluxos de caixa regulares ou em crescimento



- Investimento inicial
- Fluxo de caixa do primeiro ano
- Crescimento anual ou declínio · %
- Anos
- Taxa de desconto anual · %







### Fluxos de caixa anuais irregulares



- Investimento inicial
- Fluxos de caixa anuais subsequentes
- Taxa de desconto anual · %







[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fpayback-period-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/payback-period-calculator/)
