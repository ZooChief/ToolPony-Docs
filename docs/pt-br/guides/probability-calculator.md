# Calculadora de probabilidade



Calcular probabilidades de eventos, recuperar probabilidades independentes de dois valores conhecidos, ou usar um intervalo normal.





## Exemplo



### Entrada



```
Acontecimentos independentes A = 0,31, B = 0,56
```



### Resultado esperado



```
Ao menos um evento 0,6964
```







## Experimente

[Abrir ferramenta completa · Calculadora de probabilidade](<https://toolpony.com/pt-br/tools/probability-calculator/>)





## Método de cálculo



Os eventos independentes satisfazem P(A) = P(A) P(B). Para eventos dependentes, entre na interseção diretamente. As tentativas repetidas multiplicam suas probabilidades, e a probabilidade de pelo menos um sucesso usa o complemento.



$$
P(A\cup B)=P(A)+P(B)-P(A\cap B)
$$



$$
P(A\cap B)=P(A)P(B)\quad\text{(independent)}
$$







## Modo de cálculo



**Dois eventos independentes**

- Probabilidade de A
- Probabilidade de B





**Intersecção conhecida**

- Probabilidade de A
- Probabilidade de B
- Ambos os eventos





**Recuperar eventos independentes**

- Quantidades conhecidas pela primeira vez · Probabilidade de A / Probabilidade de B / Não A / Não B / Ambos os eventos / Pelo menos um evento / Exatamente um evento / Nenhum evento
- Primeira probabilidade
- Segunda quantidade conhecida · Probabilidade de A / Probabilidade de B / Não A / Não B / Ambos os eventos / Pelo menos um evento / Exatamente um evento / Nenhum evento
- Segunda probabilidade





**Ensaios independentes repetidos**

- Probabilidade de A
- Testes de A
- Probabilidade de B
- Ensaios de B





**Intervalo de distribuição normal**

- Média
- Desvio padrão
- Limite inferior
- Limite superior







[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fprobability-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/probability-calculator/)
