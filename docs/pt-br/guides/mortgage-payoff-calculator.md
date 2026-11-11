# Calculadora de quitação imobiliária



Compare as parcelas restantes, pagamentos extras, quitação imediata e dois planos de pagamento a cada duas semanas.





## Primeiros passos



1. Após extras anteriores, use o saldo e a parcela de principal e juros do extrato. Também é possível obter o saldo pelo empréstimo original e prazo restante.
2. Escolha um plano e informe extras mensais, anuais ou únicos. Por padrão começam nos meses 1, 12 e 1. Altere o início nas opções avançadas.
3. Compare o plano escolhido com o regular e baixe a tabela restante ou o CSV comparativo.
4. O modelo cobre principal e juros fixos. A quitação real pode incluir juros diários, taxas e multas. Confirme o valor com o credor.







## Exemplo



### Entrada



```
400.000 por 30 anos a 6%. Restam 25 anos e são pagos 500 extras por mês.
```



### Resultado esperado



```
207 meses restantes, 122.306,21 de juros poupados
```







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/mortgage-payoff-calculator/>)







## Notas de uso



O cálculo é feito no seu navegador. Use unidades consistentes.







## Método de cálculo



O modo de empréstimo original supõe que os pagamentos anteriores seguiram o plano. O juro mensal é o saldo vezes a taxa anual dividida por doze. O modelo agrupado acrescenta meia parcela a cada seis meses. O de 26 pagamentos usa meia parcela mensal e divide a taxa anual por 26.



$$
B=M\frac{1-(1+r)^{-n}}r\quad(r>0),\qquad B=Mn\quad(r=0)
$$



$$
I_k=rB_{k-1},\qquad B_k=\max(0,B_{k-1}-M+I_k-E_k)
$$



$$
E_{6j}=M/2\quad\text{(grouped)},\qquad M_{26}=M/2,\quad r_{26}=r_{\rm annual}/26
$$







## Modo de cálculo



**Empréstimo original e prazo restante**

- Valor original
- Anos do prazo original
- Meses adicionais do prazo original
- Taxa anual · %
- Anos restantes
- Meses restantes adicionais
- Plano de pagamento · Pagamentos extras / Pagamentos regulares / A cada duas semanas, agrupado por mês / A cada duas semanas, 26 pagamentos por ano / Quitar o principal agora
- Pagamento extra mensal
- Pagamento extra anual
- Pagamento extra único
- Primeiro mês para extras mensais
- Primeiro mês para extras anuais
- Mês do pagamento único





**Saldo atual e parcela**

- Principal restante
- Parcela mensal
- Taxa anual · %
- Plano de pagamento · Pagamentos extras / Pagamentos regulares / A cada duas semanas, agrupado por mês / A cada duas semanas, 26 pagamentos por ano / Quitar o principal agora
- Pagamento extra mensal
- Pagamento extra anual
- Pagamento extra único
- Primeiro mês para extras mensais
- Primeiro mês para extras anuais
- Mês do pagamento único

[Documentação](https://docs.toolpony.com/pt-br/guides/mortgage-payoff-calculator/)
