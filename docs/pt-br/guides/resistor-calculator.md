# Calculadora de resistores e código de cores



Leia de 3 a 6 faixas e calcule resistências em série, em paralelo ou de um fio circular.





## Primeiros passos



1. Escolha a quantidade de faixas ou o circuito. A faixa de tolerância costuma ficar separada das outras.
2. Informe diâmetro e comprimento do fio circular. O material predefinido preenche a condutividade, que pode ser editada.







## Exemplo



### Entrada



```
4 faixas: verde, vermelho, vermelho e ouro
```



### Resultado esperado



```
5,200 Ω ±5%
```







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/resistor-calculator/>)







## Notas de uso



O cálculo é feito no seu navegador. Use unidades consistentes.







## Método de cálculo



Leia os dígitos, o multiplicador, a tolerância e o coeficiente de temperatura quando presente. Três faixas indicam tolerância de 20%. Para fio circular uniforme, R = L/(σA). Confira marcações especiais na ficha do componente.



$$
R_{\rm series}=\sum_i R_i,\quad R_{\rm parallel}=\left(\sum_i 1/R_i\right)^{-1},\quad R_{\rm wire}=\frac{L}{\sigma\pi(d/2)^2}
$$



$$
R_{\rm band}=D\,10^m,\qquad R_{\min,\max}=R_{\rm band}(1\mp t/100)
$$







## Modo de cálculo



**4 faixas**

- Primeiro dígito
- Segundo dígito
- Multiplicador
- Tolerância





**3 faixas**

- Primeiro dígito
- Segundo dígito
- Multiplicador





**5 faixas**

- Primeiro dígito
- Segundo dígito
- Terceiro dígito
- Multiplicador
- Tolerância





**6 faixas**

- Primeiro dígito
- Segundo dígito
- Terceiro dígito
- Multiplicador
- Tolerância
- Coeficiente de temperatura





**Paralelo**

- Resistências em Ω





**Série**

- Resistências em Ω





**Condutor circular**

- Comprimento
- Unidade de comprimento · mm / cm / m / km / em / ft / yd / mi
- Diâmetro
- Unidade de diâmetro · mm / cm / m / km / em / ft / yd / mi
- Material predefinido · Personalizado / Cobre / Cobre recozido / Alumínio / Prata / Ouro
- Condutividade · S/m

[Documentação](https://docs.toolpony.com/pt-br/guides/resistor-calculator/)
