# Conversor de fusos horários



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







## Experimente

[Abrir ferramenta completa · Conversor de fusos horários](<https://toolpony.com/pt-br/tools/time-zone-converter/>)





## Método de cálculo



Fusos IANA usam regras do navegador. Uma hora repetida tem dois instantes e uma pulada não tem nenhum. Um deslocamento UTC fixo é constante no ano.



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## Modo de cálculo



**IANA**

- Data
- Hora local
- Fuso IANA de origem
- Fuso IANA de destino
- Hora repetida · Primeira ocorrência / Última ocorrência





**Deslocamentos UTC fixos**

- Data
- Hora local
- Deslocamento de origem
- Deslocamento de destino







**Referências do método** [IANA · Time Zone Database](<https://www.iana.org/time-zones>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Ftime-zone-converter%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/time-zone-converter/)
