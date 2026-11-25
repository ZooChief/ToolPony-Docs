# Guia de uso · Calculadora de empréstimos



Calcule parcelas, obtenha o prazo a partir do pagamento mensal ou programe pagamentos extras. Exporte a tabela completa.





## Primeiros passos



1. Escolha prazo fixo, parcela desejada ou pagamentos extras com datas.
2. Informe o primeiro mês de pagamento. Digite um extra por linha, como 2026-06, 500.
3. Calcule e selecione a tabela que deseja baixar.







## Exemplo



### Entrada



```
100.000 por 10 anos a 6%, pagamento mensal
```



### Resultado esperado



```
≈1.110,21 por mês
```





<a id="case-study"></a>



## Quanto se economiza pagando 100 a mais por mês?



1. Escolha o exemplo com 100 a mais por mês. O principal é 100.000 em dez anos a uma taxa fixa de 6% ao ano, com capitalização e pagamentos mensais.
2. A prestação prevista é 1.110,21. Amortizando mais 100 por mês, o prazo passa de 120 para 107 parcelas e os juros caem de 33.224,60 para 29.328,37.
3. Compare as curvas e confira a última parcela de 1.046,63 na tabela. O cálculo usa a prestação antes do arredondamento e abate o pagamento extra do principal.





## Experimente

[Abrir ferramenta completa · Calculadora de empréstimos](<https://toolpony.com/pt-br/tools/loan-calculator/#example-extra-payment>)





## Método de cálculo



As parcelas usam a taxa nominal convertida ao período de pagamento. Extras com data são aplicados após a parcela mensal. A taxa é fixa e os valores intermediários não são arredondados.



$$
M=\frac{Pr}{1-(1+r)^{-n}},\qquad M=\frac Pn\quad(r=0)
$$



$$
n=\frac{-\ln(1-Pr/M)}{\ln(1+r)},\qquad M>Pr\quad(r>0)
$$



$$
I_k=r B_{k-1},\qquad B_k=\max(0,B_{k-1}-(M-I_k)-E_k)
$$



P é o principal, r a taxa por período, M a parcela e n o número de períodos. Para obter o prazo e calcular extras com data, divida o percentual anual por 1.200. B é o saldo, I são os juros e E é o extra aplicado ao principal.



Com 45.000 a 6,3% e parcela de 785, o prazo estimado é de 68,38 meses. Em meses completos são 69 pagamentos, com parcela final menor. Escolha a tabela antes de baixar.







## Modo de cálculo





### Parcelas



- Principal
- Anos
- Meses
- Taxa anual · %
- Capitalização
- Frequência de pagamento · Anual / Semestral / Trimestral / Mensal / Duas vezes ao mês / A cada duas semanas / Semanal / Diária
- Extra por pagamento







### Prazo a partir da parcela



- Principal
- Parcela mensal
- Taxa anual · %







### Pagamentos extras com datas



- Principal
- Anos
- Meses
- Taxa anual · %
- Mês do primeiro pagamento
- Pagamento extra mensal
- Início dos extras mensais
- Pagamento extra anual
- Início dos extras anuais
- Pagamentos únicos







### Pagamento único no vencimento



- Principal
- Anos
- Meses
- Taxa anual · %
- Capitalização







### Valor presente de um pagamento único



- Montante no vencimento
- Anos
- Meses
- Taxa anual · %
- Capitalização







**Referências do método** [CFPB · Mortgage amortization](<https://www.consumerfinance.gov/ask-cfpb/how-does-paying-down-a-mortgage-work-en-1943/>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Floan-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/loan-calculator/)
