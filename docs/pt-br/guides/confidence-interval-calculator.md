# Guia de uso · Calculadora de intervalo de confiança



Estime a média com observações ou estatísticas resumidas usando z ou t de Student, ou uma proporção com Wilson.





## Exemplo



### Entrada



```
n = 36, média 56, desvio padrão 8, 99%
```



### Resultado esperado



```
56 ± 3.434
```





<a id="case-study"></a>



## Um intervalo com cinco medidas



1. As medidas 48, 49, 50, 51 e 52 têm média 50. Com o desvio da amostra e quatro graus de liberdade, o intervalo t de 95% para a média vai de cerca de 48,04 a 51,96. O cálculo pressupõe observações independentes e uma população aproximadamente normal.



[Executar exemplo](<https://toolpony.com/pt-br/tools/confidence-interval-calculator/#example-five-measurements>)





## Zero falhas em 30 verificações



Em 30 verificações independentes houve zero falhas. O intervalo de Wilson de 95% para a proporção de falhas vai de 0% até cerca de 11,35%. Mais verificações sem falhas estreitam o intervalo.



[Executar exemplo](<https://toolpony.com/pt-br/tools/confidence-interval-calculator/#example-no-failures>)







## Experimente

[Abrir ferramenta completa · Calculadora de intervalo de confiança](<https://toolpony.com/pt-br/tools/confidence-interval-calculator/>)





## Método de cálculo



A margem é o valor crítico × desvio / √n. Use z para σ conhecido e t com n − 1 graus de liberdade para desvio amostral. Wilson estima a proporção binomial a partir de sucessos e tentativas.



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## Modo de cálculo





### Intervalo da média



- Origem dos dados · σ conhecido / s amostral / Observações
- Tamanho da amostra
- Média
- Desvio padrão
- Valores observados
- Nível de confiança · %







### Intervalo de proporção de Wilson



- Tamanho da amostra
- Sucessos
- Nível de confiança · %







**Referências do método** [NIST · Confidence limits for the mean](<https://www.itl.nist.gov/div898/handbook/eda/section3/eda352.htm>) · [NIST · Confidence limits for a proportion](<https://www.itl.nist.gov/div898/handbook/prc/section2/prc241.htm>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fconfidence-interval-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/confidence-interval-calculator/)
