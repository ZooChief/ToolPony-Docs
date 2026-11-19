# Calculadora de hash de arquivos e texto



Escolha texto ou arquivos, selecione um algoritmo SHA-2 e calcule. Cole um digest esperado para verificar uma correspondência ou baixe os resultados como CSV.





## Primeiros passos



1. Escolha o texto ou selecione um ou mais arquivos.
2. Selecione SHA-256, SHA-384, ou SHA-512, em seguida, calcular.
3. Colar um hash esperado para verificá-lo, ou baixar o resultado CSV.







## Exemplo



### Entrada



```
Texto: abc, UTF-8, SHA-256
```



### Resultado esperado



```
ba7816bf8f01cfea414140de5dae2223b00361a396177a9cb410ff61f20015ad
```







## Experimente

[Abrir ferramenta completa · Calculadora de hash de arquivos e texto](<https://toolpony.com/pt-br/tools/file-hash-calculator/>)





## Notas de uso



A verificação do Hash compara os bytes. Uma codificação diferente, um final de linha ou mesmo um byte alterado produz uma digest diferente.







## Limites



Até 16 arquivos e 64 MB combinados, ou um milhão de caracteres de texto. O texto usa UTF-8. Os arquivos são processados sequencialmente no navegador.





**Referências do método** [NIST · FIPS 180-4 (SHA-2)](<https://csrc.nist.gov/pubs/fips/180-4/upd1/final>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Ffile-hash-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/file-hash-calculator/)
