# Calculadora de queda de tensão



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







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/voltage-drop-calculator/>)







## Notas de uso



O cálculo é feito no seu navegador. Use unidades consistentes.







## Método de cálculo



Use o comprimento de ida e condutores paralelos idênticos. Multiplique I·L·R por 2 em CC ou monofásico e por √3 em trifásico equilibrado. Para carga indutiva, combine R e X pelo fator de potência. A bitola usa resistência nominal perto de 20 °C. Use os dados do fabricante para o cabo real.



$$
\Delta V=\frac{k I L R_{\rm eff}}{n},\quad k=2\ \text{(DC, 1)}\phi,\quad k=\sqrt{3}\ \text{(3)}\phi
$$



$$
R_{\rm eff}=R\cos\theta+X\sin\theta,\quad \%\Delta V=100\frac{\Delta V}{V_s}
$$







## Modo de cálculo



**Resistência ou impedância conhecida**

- Resistência ou impedância por comprimento
- Unidade por comprimento · Ω/km / Ω/m / mΩ/m / ?/1000 ft / Ω/ft / mΩ/ft
- Tensão · V
- Circuito · DC / CA monofásica / CA trifásica
- Condutores em paralelo por fase
- Distância de ida
- Unidade de comprimento · ft / m / mi / km
- Corrente · A
- Limite de queda para estimar a distância · %





**Estimar pelo calibre**

- Material · Cobre / Alumínio / Prata / Ouro
- Bitola do fio
- Tensão · V
- Circuito · DC / CA monofásica / CA trifásica
- Condutores em paralelo por fase
- Distância de ida
- Unidade de comprimento · ft / m / mi / km
- Corrente · A
- Limite de queda para estimar a distância · %





**Estimar pela área**

- Material · Cobre / Alumínio / Prata / Ouro
- Área transversal · mm²
- Tensão · V
- Circuito · DC / CA monofásica / CA trifásica
- Condutores em paralelo por fase
- Distância de ida
- Unidade de comprimento · ft / m / mi / km
- Corrente · A
- Limite de queda para estimar a distância · %





**Resistência e reatância**

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

[Documentação](https://docs.toolpony.com/pt-br/guides/voltage-drop-calculator/)
