# Guia de uso · Conversor de timestamp Unix



Converta segundos, milissegundos, microssegundos ou nanossegundos Unix em UTC e vice-versa sem perder dígitos.





## Exemplo



### Entrada



```
0 segundos
```



### Resultado esperado



```
1970-01-01T00:00:00.000Z
```





<a id="case-study"></a>



## Um nanossegundo antes da época



1. Selecione ns e digite -1. O horário UTC é 1969-12-31T23:59:59.999999999Z. Inverta a conversão para recuperar o mesmo inteiro.
2. 1970-01-01T05:44:59.999999999+05:45 representa o mesmo instante. Copie uma unidade ou exporte as quatro na mesma linha CSV.



[Executar exemplo](<https://toolpony.com/pt-br/tools/unix-timestamp-converter/#example-before-epoch>)





## Experimente

[Abrir ferramenta completa · Conversor de timestamp Unix](<https://toolpony.com/pt-br/tools/unix-timestamp-converter/>)





## Método de cálculo



O tempo Unix conta desde 1970-01-01T00:00:00Z e exclui segundos intercalares. Aceita datas UTC de 1900 a 9999 com deslocamento explícito e até nove casas decimais.







## Modo de cálculo





### Timestamp → Data



- Timestamp Unix
- Unidade · Segundos / Milissegundos / Microssegundos / Nanossegundos







### Data → Timestamp



- Data ISO 8601 com deslocamento UTC
- Unidade · Segundos / Milissegundos / Microssegundos / Nanossegundos







**Referências do método** [GNU · Seconds since the Epoch](<https://www.gnu.org/software/coreutils/manual/html_node/Seconds-since-the-Epoch.html>) · [IETF · RFC 3339](<https://www.rfc-editor.org/rfc/rfc3339>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Funix-timestamp-converter%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/unix-timestamp-converter/)
