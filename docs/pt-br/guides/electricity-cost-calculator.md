# Guia de uso · Calculadora de custo de eletricidade



Calcule o custo do consumo pela potência elétrica, pela refrigeração e eficiência ou por duas leituras do medidor. Confira os kWh por dia e período.





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





<a id="case-study"></a>



## Ler os watts do ar-condicionado de janela



1. A ficha do LG LW6014ER informa 6.000 BTU/h de refrigeração e 530 W de potência elétrica. Em carga plena, 8 horas por dia durante 30 dias dão 0,53 × 8 × 30 = 127,2 kWh. A 0,20 por kWh, o consumo custa 25,44.



[Executar exemplo](<https://toolpony.com/pt-br/tools/electricity-cost-calculator/#example-window-power>)





## Conferir duas leituras do medidor



Em 30 dias, a leitura passa de 612345,125 para 612492,365 kWh. A diferença é 147,24 kWh, ou 4,908 kWh por dia. A 0,15 por kWh, o consumo fica em 22,086 antes de tarifas fixas e impostos.



[Executar exemplo](<https://toolpony.com/pt-br/tools/electricity-cost-calculator/#example-meter-readings>)







## Estimar a potência elétrica pelo EER



Com 6.000 BTU/h de refrigeração e EER nominal de 12 BTU/Wh, a potência elétrica é 6.000 ÷ 12 = 500 W. Em carga plena, 8 horas por dia durante 30 dias somam 120 kWh. Use o EER das condições indicadas.



[Executar exemplo](<https://toolpony.com/pt-br/tools/electricity-cost-calculator/#example-cooling-eer>)







## Experimente

[Abrir ferramenta completa · Calculadora de custo de eletricidade](<https://toolpony.com/pt-br/tools/electricity-cost-calculator/>)





## Método de cálculo



Custo do consumo = kWh × tarifa. O consumo medido é a leitura final menos a inicial. BTU/h divididos pelo EER, ou watts de refrigeração divididos pelo COP, dão os watts elétricos. As estimativas usam 30,44 dias por mês e 365,25 por ano.



$$
E_{\rm kWh}=M_1-M_0,\qquad P_{\rm W}=\frac{Q_{\rm Btu/h}}{\mathrm{EER}}=\frac{Q_{\rm W}}{\mathrm{COP}}
$$



$$
E_{\rm kWh}=P_{\rm kW}\,t_{\rm h}\,f\,n,\qquad C=E_{\rm kWh}\,r
$$







## Modo de cálculo





### Número fixo de dias



- Base do cálculo · Potência elétrica / Capacidade de refrigeração / Leituras do medidor
- Potência elétrica
- Unidade de potência · W / kW / BTU/h / PS / TR
- Capacidade de refrigeração
- Unidade da capacidade de refrigeração · BTU/h / kW / TR
- Tipo de eficiência · EER (BTU/Wh) / COP (W/W)
- Eficiência nominal
- Leitura inicial · kWh
- Leitura final · kWh
- Carga média · %
- Aparelhos
- Horas por dia · h
- Dias
- Preço por kWh







### Estimativa diária a anual



- Aparelho predefinido
- Base do cálculo · Potência elétrica / Capacidade de refrigeração
- Potência elétrica
- Unidade de potência · W / kW / BTU/h / PS / TR
- Capacidade de refrigeração
- Unidade da capacidade de refrigeração · BTU/h / kW / TR
- Tipo de eficiência · EER (BTU/Wh) / COP (W/W)
- Eficiência nominal
- Carga média · %
- Aparelhos
- Uso
- Unidade de uso · Minutos por dia / Horas por dia / Horas por semana / Horas por mês / Dias por semana / Dias por mês / Dias por ano / Meses por ano
- Preço por kWh







**Referências do método** [LG · LW6014ER electrical specification](<https://images.thdstatic.com/catalog/pdfImages/e3/e3b8396a-44d1-4372-b120-7532036b2488.pdf>) · [Ohio Consumers’ Counsel · Read an electric meter](<https://www.occ.ohio.gov/sites/default/files/2021-07/OCC-How-to-Read-an-Electric-Meter.pdf>) · [U.S. Department of Energy · Room air conditioner ratings](<https://www.energy.gov/sites/prod/files/2015/06/f22/room_ac_rfi.pdf>) · [NIST · International Table Btu](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-footnotes>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Felectricity-cost-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/electricity-cost-calculator/)
