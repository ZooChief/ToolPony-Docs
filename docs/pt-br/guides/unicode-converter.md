# Guia de uso · Conversor Unicode



Converta pontos de código, bytes UTF-8 e escapes JavaScript. Inspecione caracteres e compare formas de normalização.





## Exemplo



### Entrada



```
🐴
```



### Resultado esperado



```
U+1F434 ou F0 9F 90 B4
```





<a id="case-study"></a>



## Comparar duas formas de é



1. Um e seguido de U+0301, espaço e 🐴 tem 3 grafemas, 4 pontos de código, 5 unidades UTF-16 e 8 bytes UTF-8. NFC forma U+00E9, reduzindo o total para 7 bytes. 🐴 continua com um ponto de código e duas unidades UTF-16.



[Executar exemplo](<https://toolpony.com/pt-br/tools/unicode-converter/#example-combining-accent>)





## Experimente

[Abrir ferramenta completa · Conversor Unicode](<https://toolpony.com/pt-br/tools/unicode-converter/>)





## Método de cálculo



O modo de ponto de código trata um caractere suplementar como um escalar. O UTF- 16 usa duas unidades de código para tal caractere. Sequências de substituição inválidas e bytes UTF- 8 inválidos são rejeitados.







## Modo de cálculo





### Codificar texto



- Entrada
- Codificação · Pontos de código Unicode / Bytes hexadecimais UTF-8 / Escapes UTF-16 do JavaScript / Escapes JS de pontos de código







### Descodificar texto



- Entrada
- Codificação · Pontos de código Unicode / Bytes hexadecimais UTF-8 / Escapes UTF-16 do JavaScript / Escapes JS de pontos de código







### Inspecionar caracteres



- Entrada
- Normalização · Original / NFC / NFD / NFKC / NFKD







**Referências do método** [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>) · [Unicode · UAX \#15](<https://www.unicode.org/reports/tr15/>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Funicode-converter%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/unicode-converter/)
