# Calculadora de divisores



Liste todos os divisores positivos, todos os pares de fatores, e a fatoração primária.





## Exemplo



### Entrada



```
120
```



### Resultado esperado



```
16 divisores positivos, incluindo 1 e 120
```







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/factor-calculator/>)







## Método de cálculo



Um divisor divide a entrada com o restante zero. Cada divisor d pequeno se junta com n/d, por isso, procurar até √n encontra cada par.



$$
d\mid n\iff n\bmod d=0,\qquad n=d\cdot(n/d)
$$

[Documentação](https://docs.toolpony.com/pt-br/guides/factor-calculator/)
