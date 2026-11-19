# Calculadora de folha de horas



Registre turnos e pausas semanais com arredondamento, regras de pagamento e CSV.





## Primeiros passos



1. Informe horários como 08:30, 8.30 ou 8:30 AM. Use horas e minutos para pausas, como 00:30.
2. Escolha arredondamento e regras opcionais de pagamento. Baixe o CSV ou imprima. Salvar o rascunho no navegador é opcional.







## Exemplo



### Entrada



```
08:30–17:00 com pausa de 00:30
```



### Resultado esperado



```
08:00:00
```







## Experimente

[Abrir ferramenta completa · Calculadora de folha de horas](<https://toolpony.com/pt-br/tools/time-card-calculator/>)





## Método de cálculo



Subtraia a pausa e arredonde o tempo líquido. Um fim anterior fica no dia seguinte. Limites diários ou semanais e valores são definidos por você.



$$
t_i=(e_i-s_i)\bmod 1440-b_i,\qquad t'_i=q\,\operatorname{round}(t_i/q)\quad(q>0)
$$



$$
P=(t_{\rm base}+m\,t_{\rm overtime})r/60
$$





[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Ftime-card-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/time-card-calculator/)
