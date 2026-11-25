# Guia de uso · Codificar e decodificar URL



Codifique ou decodifique URLs e valores de formulário ou edite parâmetros ordenados, mantendo nomes repetidos e valores vazios.





## Exemplo



### Entrada



```
Codificar componente: a+b & c
```



### Resultado esperado



```
a%2Bb%20%26%20c
```





<a id="case-study"></a>



## Preservar sinais de mais em uma busca



1. Codifique C++ &amp; tea como valor de formulário. O resultado é C%2B%2B+%26+tea. O sinal de mais vira %2B, o espaço vira + e &amp; vira %26. Inverta para recuperar o texto. Em um componente URI o espaço vira %20.
2. No exemplo com dois parâmetros tag, troque o segundo valor por UI &amp; UX. O primeiro, o valor vazio e \#filters são preservados. O valor alterado vira UI+%26+UX.



[Executar exemplo](<https://toolpony.com/pt-br/tools/url-encoder-decoder/#example-query-plus>)





## Experimente

[Abrir ferramenta completa · Codificar e decodificar URL](<https://toolpony.com/pt-br/tools/url-encoder-decoder/>)





## Método de cálculo



Um componente codifica os separadores reservados e a URL completa os mantém. No formulário, + representa espaço. A edição codifica cada nome e valor separadamente e preserva caminho e fragmento.





**Referências do método** [IETF · RFC 3986](<https://www.rfc-editor.org/rfc/rfc3986>) · [WHATWG · Form encoding](<https://url.spec.whatwg.org/#application/x-www-form-urlencoded>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Furl-encoder-decoder%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/url-encoder-decoder/)
