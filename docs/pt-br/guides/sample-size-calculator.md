# Calculadora do tamanho da amostra



Encontre uma amostra mínima do inquérito ou estime a margem de erro com correção de população finita.





## Primeiros passos



1. Use o exemplo ou insira seus próprios valores.
2. Calcule, copie o resultado ou baixe os detalhes disponíveis.







## Exemplo



### Entrada



```
95% confiança, 4% margem, 35% proporção, N = 1.000
```



### Resultado esperado



```
354 amostras
```







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/sample-size-calculator/>)







## Notas de uso



O cálculo é feito no seu navegador. Use unidades consistentes.







## Método de cálculo



O tamanho inicial é z2p(1−p)/e2. Para uma população finita, divida esse tamanho por 1 + (tamanho inicial -1)/N e arredonde. O cálculo de erro usa a mesma proporção e modelo de população finita.



$$
n_0=\frac{z^2p(1-p)}{e^2},\qquad n=\left\lceil\frac{n_0}{1+(n_0-1)/N}\right\rceil
$$







## Modo de cálculo



**Procurar tamanho da amostra**

- Nível de confiança · %
- Margem de erro · %
- Proporção da população · %
- Dimensão da população (0 para ilimitado)





**Procurar a margem de erro**

- Nível de confiança · %
- Tamanho da amostra
- Proporção da população · %
- Dimensão da população (0 para ilimitado)

[Documentação](https://docs.toolpony.com/pt-br/guides/sample-size-calculator/)
