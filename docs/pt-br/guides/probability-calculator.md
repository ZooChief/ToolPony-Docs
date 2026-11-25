# Guia de uso · Calculadora de probabilidade



Compare probabilidades condicionais com uma tabela de contagens ou probabilidades e calcule eventos independentes e tentativas repetidas.





## Exemplo



### Entrada



```
Acontecimentos independentes A = 0,31, B = 0,56
```



### Resultado esperado



```
Ao menos um evento 0,6964
```





<a id="case-study"></a>



## Participação em duas oficinas



1. De 50 pessoas, 18 participaram das duas sessões, 12 só de manhã (AM), 6 só à tarde (PM) e 14 de nenhuma. Das 24 da tarde, 18 também estavam de manhã (75%). Das 30 da manhã, 18 voltaram à tarde (60%).



[Executar exemplo](<https://toolpony.com/pt-br/tools/probability-calculator/#example-workshop-attendance>)





## Experimente

[Abrir ferramenta completa · Calculadora de probabilidade](<https://toolpony.com/pt-br/tools/probability-calculator/>)





## Método de cálculo



A união soma as probabilidades marginais e subtrai a interseção. Entre B, a proporção de A é P(A ∩ B) / P(B). Se forem independentes, a interseção é o produto das marginais.



$$
P(A\cup B)=P(A)+P(B)-P(A\cap B)
$$



$$
P(A\cap B)=P(A)P(B)\quad\text{(independent)}
$$







## Modo de cálculo





### Dois eventos independentes



- Probabilidade de A
- Probabilidade de B







### Intersecção conhecida



- Entrada · Probabilidades / Contagens
- Probabilidade de A
- Probabilidade de B
- Ambos os eventos
- Nome do evento A
- Nome do evento B
- A ∩ B
- A ∩ ¬B
- ¬A ∩ B
- ¬A ∩ ¬B







### Recuperar eventos independentes



- Quantidades conhecidas pela primeira vez · Probabilidade de A / Probabilidade de B / Não A / Não B / Ambos os eventos / Pelo menos um evento / Exatamente um evento / Nenhum evento
- Primeira probabilidade
- Segunda quantidade conhecida · Probabilidade de A / Probabilidade de B / Não A / Não B / Ambos os eventos / Pelo menos um evento / Exatamente um evento / Nenhum evento
- Segunda probabilidade







### Ensaios independentes repetidos



- Probabilidade de A
- Testes de A
- Probabilidade de B
- Ensaios de B







### Intervalo de distribuição normal



- Média
- Desvio padrão
- Limite inferior
- Limite superior







**Referências do método** [OpenStax · Contingency Tables](<https://openstax.org/books/introductory-statistics-2e/pages/3-4-contingency-tables>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fprobability-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/probability-calculator/)
