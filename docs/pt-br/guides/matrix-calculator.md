# Guia de uso · Calculadora de matrizes



Resolva sistemas lineares e calcule determinantes, inversas, postos e produtos com frações e decimais exatos. Cole células de uma planilha e exporte o resultado.





## Exemplo



### Entrada



```
A = [2, 4; 1, 3], B = [1, −2; 4, 5]
```



### Resultado esperado



```
A + B = [3, 2; 5, 8]
```





<a id="case-study"></a>



## Contar dois tipos de pacote



1. Um pacote pequeno tem 2 clipes pretos e 1 branco. Um grande tem 3 pretos e 2 brancos. Ao todo, são 17 pretos e 10 brancos. As colunas de A descrevem os pacotes e B contém os totais. O resultado é 4 pacotes pequenos e 3 grandes. Confira os totais com A × X.



[Executar exemplo](<https://toolpony.com/pt-br/tools/matrix-calculator/#example-packing-matrix>)





## Determinante igual a um



O produto da diagonal principal é um bilhão ao quadrado. O outro é (um bilhão − 1) × (um bilhão + 1). A diferença é exatamente 1 e as linhas são independentes.



[Executar exemplo](<https://toolpony.com/pt-br/tools/matrix-calculator/#example-determinant-one>)







## Duas variáveis livres



A segunda equação é o dobro da primeira. Em x + y + z = 4, escolha y e z livremente e faça x = 4 − y − z. A partir de (4, 0, 0), os dois vetores do núcleo dão as variações possíveis. Mude o segundo total de 8 para 9 para ver a contradição.



[Executar exemplo](<https://toolpony.com/pt-br/tools/matrix-calculator/#example-free-variables>)







## Experimente

[Abrir ferramenta completa · Calculadora de matrizes](<https://toolpony.com/pt-br/tools/matrix-calculator/>)





## Método de cálculo



A redução por linhas usa aritmética racional exata. O número de colunas pivô dá o posto. Em A × X = B, uma linha nula à esquerda com termo independente não nulo indica incompatibilidade. As colunas livres determinam as direções que se somam a uma solução particular.



$$
(AB)_{ij}=\sum_{k=1}^{n}A_{ik}B_{kj},\qquad A^{-1}A=I
$$



$$
[A\mid B]\longrightarrow[I\mid X]\quad\Rightarrow\quad AX=B
$$







## Modo de cálculo





### Adicionar A + B



- Matriz A
- Matriz B







### Subtrair A − B



- Matriz A
- Matriz B







### Multiplicar A × B



- Matriz A
- Matriz B







### Resolver A × X = B



- Matriz A
- Matriz B







### Determinante



- Matriz A







### Inverso



- Matriz A







### Transpor



- Matriz A







### Potência total



- Matriz A
- Expoente







### Multiplicação escalonar



- Matriz A
- Escalar







### Forma de escalonamento e de fila reduzida



- Matriz A







**Referências do método** [MIT OpenCourseWare · Solving Ax = b](<https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/resources/solving-ax-b-row-reduced-form-r/>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fmatrix-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/matrix-calculator/)
