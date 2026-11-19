# Calculadora de custo de eletricidade



Estime consumo e custo por aparelho, carga e tarifa, em prazo fixo ou do dia ao ano.





## Primeiros passos



1. Informe potência elétrica, uso e tarifa. Os valores predefinidos são exemplos editáveis.







## Exemplo



### Entrada



```
1.000 W, 2 h/dia, 30 dias, 0,2 por kWh
```



### Resultado esperado



```
60 kWh, custo de 12
```







## Experimente

[Abrir ferramenta completa · Calculadora de custo de eletricidade](<https://toolpony.com/pt-br/tools/electricity-cost-calculator/>)





## Método de cálculo



A energia é kW vezes horas, carga média e quantidade de aparelhos. O custo usa tarifa fixa, mês de 30,44 dias e ano de 365,25. Em refrigeração, use a potência elétrica de entrada.



$$
E_{\rm kWh}=P_{\rm kW}\,t_{\rm h}\,f\,n,\qquad C=E_{\rm kWh}\,r
$$







## Modo de cálculo



**Número fixo de dias**

- Potência
- Unidade de potência · W / kW / BTU/h / PS / TR
- Carga média · %
- Aparelhos
- Horas por dia · h
- Dias
- Preço por kWh





**Estimativa diária a anual**

- Aparelho predefinido
- Potência
- Unidade de potência · W / kW / BTU/h / PS / TR
- Carga média · %
- Aparelhos
- Uso
- Unidade de uso · Minutos por dia / Horas por dia / Horas por semana / Horas por mês / Dias por semana / Dias por mês / Dias por ano / Meses por ano
- Preço por kWh







[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Felectricity-cost-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/electricity-cost-calculator/)
