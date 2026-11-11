# Comparador de CSV



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







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/csv-compare/>)







## Limites



Até 1 MiB em UTF-8, 5.000 linhas e 80 colunas por tabela. A comparação preserva zeros à esquerda. Chaves vazias ou repetidas são listadas separadamente. Os números contam registros a partir do cabeçalho.

[Documentação](https://docs.toolpony.com/pt-br/guides/csv-compare/)
