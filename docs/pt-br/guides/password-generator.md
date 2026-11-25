# Guia de uso · Gerador de senhas



Gere senhas localmente com conjuntos de caracteres, exclusões personalizadas e caracteres únicos opcionais.





## Exemplo



### Entrada



```
20 caracteres, quatro grupos de caracteres
```



### Resultado esperado



```
Uma nova senha aleatória
```





<a id="case-study"></a>



## Códigos de teste para digitação



1. Gere seis códigos de 16 caracteres com maiúsculas e algarismos. Exclua 2Z5S8B para evitar três pares que se confundem no papel.
2. Cada linha usa os dois grupos sem repetir caracteres. Copie uma linha para testar o formulário. Reabrir o exemplo gera novos valores no seu aparelho.



[Executar exemplo](<https://toolpony.com/pt-br/tools/password-generator/#example-readable-codes>)





## Experimente

[Abrir ferramenta completa · Gerador de senhas](<https://toolpony.com/pt-br/tools/password-generator/>)





## Método de cálculo



A criptografia Web fornece aleatoriedade. Quando grupos necessários estão habilitados, um caractere é selecionado de cada grupo, então as posições são embaralhadas. As senhas estão ao vivo na página atual até que você saia ou limpe- a.





**Referências do método** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fpassword-generator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/password-generator/)
