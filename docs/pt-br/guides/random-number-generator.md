# Guia de uso · Gerador de números aleatórios



Sorteie inteiros com os dois limites incluídos, com opções de evitar repetições e ordenar o resultado.





## Exemplo



### Entrada



```
Mínimo 1, máximo 10, quantidade 5
```



### Resultado esperado



```
Cinco inteiros aleatórios de 1 a 10
```





<a id="case-study"></a>



## Sortear quatro bilhetes



1. Numere 12 bilhetes de 101 a 112 e sorteie quatro sem repetição. Ordene os números para anunciá-los e desative a ordenação para voltar à ordem do sorteio. O CSV conserva a posição original.



[Executar exemplo](<https://toolpony.com/pt-br/tools/random-number-generator/#example-ticket-draw>)





## Experimente

[Abrir ferramenta completa · Gerador de números aleatórios](<https://toolpony.com/pt-br/tools/random-number-generator/>)





## Método de cálculo



Valores aleatórios vêm da Web Crypto. Amostragem de rejeição evita viés modulo. Gerar até 1.000 valores na faixa -1.000.000.000 a 1.000.000.000.





**Referências do método** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Frandom-number-generator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/random-number-generator/)
