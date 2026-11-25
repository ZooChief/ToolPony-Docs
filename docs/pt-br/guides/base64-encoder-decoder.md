# Guia de uso · Codificar e decodificar Base64



Codifique texto UTF-8 ou bytes hexadecimais em Base64 ou Base64url e salve os bytes decodificados.





## Exemplo



### Entrada



```
Codificar hello
```



### Resultado esperado



```
aGVsbG8=
```





<a id="case-study"></a>



## Recuperar bytes de Base64url



1. Escolha decodificar, alfabeto URL e bytes hexadecimais. \_wCA7w resulta em FF 00 80 EF, com um byte nulo e valores inválidos para UTF-8. O download binário conserva os quatro bytes.



[Executar exemplo](<https://toolpony.com/pt-br/tools/base64-encoder-decoder/#example-binary-bytes>)





## Experimente

[Abrir ferramenta completa · Codificar e decodificar Base64](<https://toolpony.com/pt-br/tools/base64-encoder-decoder/>)





## Método de cálculo



O padrão usa + e /, e a versão URL usa - e \_ sem preenchimento na saída. O texto UTF-8 é validado e mantém o U+FEFF inicial. Limite de 500.000 unidades UTF-16 ou 500.000 bytes.





**Referências do método** [IETF · RFC 4648 (Base64)](<https://www.rfc-editor.org/rfc/rfc4648>) · [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fbase64-encoder-decoder%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/base64-encoder-decoder/)
