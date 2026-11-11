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



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/time-card-calculator/>)







## Notas de uso



O cálculo é feito no seu navegador. Use unidades consistentes.







## Método de cálculo



Subtraia a pausa e arredonde o tempo líquido. Um fim anterior fica no dia seguinte. Limites diários ou semanais e valores são definidos por você.



$$
t_i=(e_i-s_i)\bmod 1440-b_i,\qquad t'_i=q\,\operatorname{round}(t_i/q)\quad(q>0)
$$



$$
P=(t_{\rm base}+m\,t_{\rm overtime})r/60
$$

[Documentação](https://docs.toolpony.com/pt-br/guides/time-card-calculator/)
