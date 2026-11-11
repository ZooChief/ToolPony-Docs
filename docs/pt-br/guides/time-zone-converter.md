# Conversor de fusos horários



Converta data e horário entre fusos IANA ou deslocamentos UTC fixos.





## Primeiros passos



1. Use o exemplo ou insira seus próprios valores.
2. Calcule, copie o resultado ou baixe os detalhes disponíveis.







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



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/time-zone-converter/>)







## Notas de uso



O cálculo é feito no seu navegador. Use unidades consistentes.







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

[Documentação](https://docs.toolpony.com/pt-br/guides/time-zone-converter/)
