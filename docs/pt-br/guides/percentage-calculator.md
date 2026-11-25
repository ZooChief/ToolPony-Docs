# Guia de uso · Calculadora de porcentagem



Calcule porcentagens, compare taxas em pontos ou aplique e reverta dois descontos.





## Primeiros passos



1. Para uma parte como 15% de 240, escolha a Percentagem de um valor. Se a parte é 36 e você sabe o total ou a taxa, escolha o modo inverso correspondente.
2. Escolha a alteração percentual para um valor antigo e novo ordenado. Use a diferença percentual para dois valores positivos sem linha de base.
3. Digite 15 para 15%. Compare o resultado com os exemplos trabalhados abaixo.







## Exemplo



### Entrada



```
15% de 240
```



### Resultado esperado



```
36
```





<a id="case-study"></a>



## Dois descontos sucessivos



1. Um preço de 250 cai para 200 com 20% de desconto. O segundo desconto de 10% incide sobre 200 e leva o preço a 180. A redução total é de 28%. Inverta o cálculo para recuperar o preço inicial.



[Executar exemplo](<https://toolpony.com/pt-br/tools/percentage-calculator/#example-two-discounts>)





## Passar de 4% para 5%



A taxa de cadastro passa de 4% para 5%. A diferença é de um ponto percentual. Em relação aos 4% iniciais, o aumento é de 1 ÷ 4 = 25%.



[Executar exemplo](<https://toolpony.com/pt-br/tools/percentage-calculator/#example-percentage-points>)







## Experimente

[Abrir ferramenta completa · Calculadora de porcentagem](<https://toolpony.com/pt-br/tools/percentage-calculator/>)





## Método de cálculo



A variação relativa usa o módulo do valor inicial como base. Subtrair duas taxas dá pontos percentuais. Fatores sucessivos se multiplicam. A diferença simétrica usa a média dos módulos.



$$
x=yp/100,\quad p=100x/y,\quad y=100x/p
$$



$$
\Delta\%=100\frac{x_1-x_0}{|x_0|},\quad D\%=200\frac{|x_1-x_0|}{|x_1|+|x_0|}
$$



80 → 100 é uma mudança de 25% porque 80 é o valor inicial. A diferença percentual entre os mesmos números é de cerca de 22,22% porque o denominador é sua média, 90.



Após um aumento de 20% para 120, uma mudança inversa dá 100. Uma mudança de -100% não pode ser invertida. A alteração de um valor inicial zero não tem resultado percentual.



Para um valor medido de 90 e referência de 96, o erro percentual absoluto é de 6,25%. O resultado assinado com essa referência positiva é de −6,25%.







## Modo de cálculo





### Percentagem de um valor



- Percentagem · %
- Valor







### Procurar a percentagem



- Parte
- Inteiro







### Encontrar o todo



- Parte
- Percentagem · %







### Variação percentual



- Tipo dos valores · Quantidades / Taxas (%)
- Valor inicial
- Novo valor







### Diferença percentual



- Primeiro valor
- Segundo valor







### Diferença com os valores assinados



- Primeiro valor
- Segundo valor







### Aplicar uma alteração



- Valor inicial
- Alteração assinada · %
- Segunda variação · %







### Inverter uma alteração



- Novo valor
- Alteração assinada · %
- Segunda variação · %







### Erro percentual



- Valor medido
- Valor de referência
- Convenção de Erros · Absoluto / Com sinal relativo à referência







**Referências do método** [Eurostat · Percentage point](<https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Glossary:Percentage_point>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fpercentage-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/percentage-calculator/)
