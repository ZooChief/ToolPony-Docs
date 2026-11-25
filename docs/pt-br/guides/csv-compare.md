# Guia de uso · Comparador de CSV



Cole ou importe as duas tabelas. Mantenha o cabeçalho e escolha o separador e as colunas-chave. Compare e filtre as alterações. Use CSV para planilhas e JSON para manter o texto original e o relatório completo.





## Primeiros passos



1. Cole ou importe as duas tabelas. Mantenha o cabeçalho e escolha o separador e as colunas-chave.
2. Compare e filtre as alterações. Use CSV para planilhas e JSON para manter o texto original e o relatório completo.







## Exemplo



### Entrada



```
ID,Name,Qty
001,Oak,2
002,Pine,1
004,Ash,3

Qty,ID,Name
4,001,Oak
1,003,Fir
3,004,Ash
```



### Resultado esperado



```
Adicionadas 1 · Removidas 1 · Alteradas 1
```





<a id="case-study"></a>



## Conciliar estoques depois de mudar a ordem das colunas



1. Carregue o exemplo de estoque e selecione ID como chave. O arquivo anterior contém ID, Name, Qty nessa ordem. O novo começa por Qty. Compare os dois.
2. A quantidade do item 001 (Oak) passa de 2 para 4. O item 002 foi removido, o 003 foi adicionado e o 004 ficou igual. Mesmo com as colunas em outra ordem, há uma alteração, uma remoção e uma inclusão.
3. Troque apenas 001 por 1 no arquivo novo e compare de novo. Surgem duas inclusões, duas remoções e nenhuma alteração. Preserve os zeros à esquerda na exportação para comparar o mesmo item.





## Experimente

[Abrir ferramenta completa · Comparador de CSV](<https://toolpony.com/pt-br/tools/csv-compare/#example-inventory>)





## Limites



Até 1 MiB em UTF-8, 5.000 linhas e 80 colunas por tabela. A comparação preserva zeros à esquerda. Chaves vazias ou repetidas são listadas separadamente. Os números contam registros a partir do cabeçalho.



Ao comparar estoques, use um SKU estável como chave. Se 0012 virar 12 na nova exportação, aparecerão uma remoção e uma inclusão. Preserve os zeros à esquerda nos dois arquivos para comparar as quantidades do mesmo item.





**Referências do método** [IETF · RFC 4180 (CSV)](<https://www.rfc-editor.org/rfc/rfc4180>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fcsv-compare%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/csv-compare/)
