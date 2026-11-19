# Calculadora de intervalo de confiança



Estimar um intervalo médio normal ou um intervalo Wilson para uma proporção.





## Exemplo



### Entrada



```
n = 36, média 56, desvio padrão 8, 99%
```



### Resultado esperado



```
56 ± 3.434
```







## Experimente

[Abrir ferramenta completa · Calculadora de intervalo de confiança](<https://toolpony.com/pt-br/tools/confidence-interval-calculator/>)





## Método de cálculo



A margem normal é z vezes o erro padrão s/?n. Intervalos de pontuação Wilson ajustar o centro e largura para proporções e permanecer dentro \[0,1\].



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## Modo de cálculo



**Intervalo médio normal**

- Tamanho da amostra
- Média
- Desvio padrão
- Nível de confiança · %





**Intervalo de proporção de Wilson**

- Tamanho da amostra
- Sucessos
- Nível de confiança · %







[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fconfidence-interval-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/confidence-interval-calculator/)
