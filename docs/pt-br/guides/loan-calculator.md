# Calculadora de empréstimos



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







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/loan-calculator/>)







## Notas de uso



O cálculo é feito no seu navegador. Use unidades consistentes.







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



**Parcelas**

- Principal
- Anos
- Meses
- Taxa anual · %
- Capitalização
- Frequência de pagamento · Anual / Semestral / Trimestral / Mensal / Duas vezes ao mês / A cada duas semanas / Semanal / Diária
- Extra por pagamento





**Prazo a partir da parcela**

- Principal
- Parcela mensal
- Taxa anual · %





**Pagamentos extras com datas**

- Principal
- Anos
- Meses
- Taxa anual · %
- Mês do primeiro pagamento
- Pagamento extra mensal
- Início dos extras mensais
- Pagamento extra anual
- Início dos extras anuais
- Pagamentos únicos (AAAA-MM, valor)





**Pagamento único no vencimento**

- Principal
- Anos
- Meses
- Taxa anual · %
- Capitalização





**Valor presente de um pagamento único**

- Montante no vencimento
- Anos
- Meses
- Taxa anual · %
- Capitalização

[Documentação](https://docs.toolpony.com/pt-br/guides/loan-calculator/)
