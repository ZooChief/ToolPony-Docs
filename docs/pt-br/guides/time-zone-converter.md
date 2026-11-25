# Guia de uso · Conversor de fusos horários



Converta data e horário entre fusos IANA ou deslocamentos UTC fixos.





## Exemplo



### Entrada



```
2026-01-15 09:00, Asia/Shanghai → America/New_York
```



### Resultado esperado



```
2026-01-14 20:00:00
```





<a id="case-study"></a>



## Uma reunião na hora repetida



1. Em 1º de novembro de 2026 há duas ocorrências de 01:30 em Nova York. Em Xangai elas correspondem a 13:30 e 14:30. Escolha a do convite e copie o instante UTC. Inverter as cidades preserva o horário da reunião.



[Executar exemplo](<https://toolpony.com/pt-br/tools/time-zone-converter/#example-repeated-meeting>)





## Uma ligação em novembro em Havana



Cuba manteve UTC−04:00 em novembro de 2026. Em 23 de novembro, uma ligação às 09:00 em Havana corresponde a 13:00 UTC. Escolha America/Havana para aplicar as regras locais da data.



[Executar exemplo](<https://toolpony.com/pt-br/tools/time-zone-converter/#example-havana-clock>)







## Quando o relógio adianta 30 minutos



Em 4 de outubro de 2026, a ilha Lord Howe passa de 01:59:59 para 02:30:00. Experimente digitar 02:15. Você pode deslocar o horário em meia hora para 01:45 ou 02:45. A segunda opção equivale a 15:45 UTC de 3 de outubro.



[Executar exemplo](<https://toolpony.com/pt-br/tools/time-zone-converter/#example-half-hour-change>)







## Experimente

[Abrir ferramenta completa · Conversor de fusos horários](<https://toolpony.com/pt-br/tools/time-zone-converter/>)





## Método de cálculo



A hora local segue as regras IANA da data escolhida. Um horário repetido corresponde a dois instantes UTC. Ao adiantar o relógio, um intervalo é pulado. Um deslocamento fixo é constante.



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## Modo de cálculo





### IANA



- Data
- Hora local
- Fuso IANA de origem
- Fuso IANA de destino
- Hora repetida · Primeira ocorrência / Última ocorrência







### Deslocamentos UTC fixos



- Data
- Hora local
- Deslocamento de origem
- Deslocamento de destino







**Referências do método** [IANA · Time Zone Database](<https://www.iana.org/time-zones>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Ftime-zone-converter%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/time-zone-converter/)
