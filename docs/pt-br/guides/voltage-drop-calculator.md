# Guia de uso · Calculadora de queda de tensão



Estime a queda de tensão em CC, monofásica ou trifásica equilibrada pelo calibre ou pela resistência.





## Primeiros passos



1. Escolha um modelo. Em trifásico, informe a tensão entre fases e a corrente de linha. Informe a distância de ida.
2. A distância limite usa o percentual escolhido. Confira separadamente a capacidade de corrente, a temperatura e os requisitos de instalação.







## Exemplo



### Entrada



```
120 V, monofásico, 500 ft, 1 A e 1,2 Ω/km
```



### Resultado esperado



```
Queda de 0,37 V, 0,30%
```





<a id="case-study"></a>



## Usar uma tabela de cabos



1. Com 1 mV/(A·m), 50 m de ida e 100 A, a queda no cabo é 5 V. O exemplo da Schneider soma 10 V a montante, totalizando 15 V.



[Executar exemplo](<https://toolpony.com/pt-br/tools/voltage-drop-calculator/#example-cable-table>)





## Circuito trifásico paralelo



Dois condutores por fase dividem 20 A. Com 400 V, 100 m, R = 1 Ω/km, X = 0,5 Ω/km e fator indutivo 0,8, a queda é 1,91 V e a carga recebe 398,09 V.



[Executar exemplo](<https://toolpony.com/pt-br/tools/voltage-drop-calculator/#example-parallel-cable>)







## Queda superior à fonte



Com 24 V CC, 10 A e 1 km de ida a 5 Ω/km, a queda seria 100 V. Para essa corrente o modelo não fornece uma tensão de carga.



[Executar exemplo](<https://toolpony.com/pt-br/tools/voltage-drop-calculator/#example-cable-limit>)







## Experimente

[Abrir ferramenta completa · Calculadora de queda de tensão](<https://toolpony.com/pt-br/tools/voltage-drop-calculator/>)





## Método de cálculo



Use o comprimento de ida e condutores paralelos idênticos. Multiplique I·L·R por 2 em CC ou monofásico e por √3 em trifásico equilibrado. Para carga indutiva, combine R e X pelo fator de potência. A bitola usa resistência nominal perto de 20 °C. Use os dados do fabricante para o cabo real.



$$
\Delta V=\frac{k I L R_{\rm eff}}{n},\quad k=2\ \text{(DC, 1)}\phi,\quad k=\sqrt{3}\ \text{(3)}\phi
$$



$$
R_{\rm eff}=R\cos\theta+X\sin\theta,\quad \%\Delta V=100\frac{\Delta V}{V_s}
$$







## Modo de cálculo





### Resistência ou impedância conhecida



- Valor da ficha · Impedância do condutor / Coeficiente de queda do circuito
- Resistência ou impedância por comprimento
- Unidade por comprimento · Ω/km / Ω/m / mΩ/m / ?/1000 ft / Ω/ft / mΩ/ft
- Coeficiente tabelado do circuito · mV/(A·m)
- Tensão · V
- Circuito · DC / CA monofásica / CA trifásica
- Condutores em paralelo por fase
- Distância de ida
- Unidade de comprimento · ft / m / mi / km
- Corrente · A
- Limite de queda para estimar a distância · %







### Estimar pelo calibre



- Material · Cobre / Alumínio / Prata / Ouro
- Bitola do fio
- Tensão · V
- Circuito · DC / CA monofásica / CA trifásica
- Condutores em paralelo por fase
- Distância de ida
- Unidade de comprimento · ft / m / mi / km
- Corrente · A
- Limite de queda para estimar a distância · %







### Estimar pela área



- Material · Cobre / Alumínio / Prata / Ouro
- Área transversal · mm²
- Tensão · V
- Circuito · DC / CA monofásica / CA trifásica
- Condutores em paralelo por fase
- Distância de ida
- Unidade de comprimento · ft / m / mi / km
- Corrente · A
- Limite de queda para estimar a distância · %







### Resistência e reatância



- Resistência
- Reatância por comprimento
- Unidade por comprimento · Ω/km / Ω/m / mΩ/m / ?/1000 ft / Ω/ft / mΩ/ft
- Fator de potência indutivo
- Tensão · V
- Circuito · DC / CA monofásica / CA trifásica
- Condutores em paralelo por fase
- Distância de ida
- Unidade de comprimento · ft / m / mi / km
- Corrente · A
- Limite de queda para estimar a distância · %







**Referências do método** [Schneider Electric · Voltage drop in steady load conditions](<https://www.electrical-installation.org/enwiki/Calculation_of_voltage_drop_in_steady_load_conditions>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fvoltage-drop-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/voltage-drop-calculator/)
