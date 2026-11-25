# Guia de uso · Calculadora de depreciação



Construa um calendário anual de dígitos em linha reta, em declínio ou soma de anos.





## Exemplo



### Entrada



```
17.500 custo, 2.500 salvamento, 6 anos, linha reta
```



### Resultado esperado



```
2.500 por ano
```







## Experimente

[Abrir ferramenta completa · Calculadora de depreciação](<https://toolpony.com/pt-br/tools/depreciation-calculator/>)





## Método de cálculo



A linha reta divide o custo depreciável pela vida útil. O saldo em declínio aplica o fator/vida à abertura do valor contabilístico e paragens no salvamento. Os dígitos da soma dos anos alocam-se pelos pesos dos anos restantes. Os montantes são arredondados por ano.



$$
D_{\mathrm{SL}}=\frac{C-S}{n},\quad D_{k,\mathrm{SYD}}=(C-S)\frac{n-k+1}{n(n+1)/2}
$$







## Modo de cálculo





### Linha reta



- Custo do activo
- Valor da salvação
- Vida útil
- Arredondamento · Duas casas decimais / Montante total







### Equilíbrio de redução



- Custo do activo
- Valor da salvação
- Vida útil
- Factor de amortização
- Arredondamento · Duas casas decimais / Montante total







### Números da soma dos anos



- Custo do activo
- Valor da salvação
- Vida útil
- Arredondamento · Duas casas decimais / Montante total







[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fdepreciation-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/depreciation-calculator/)
