# Calculadora de quantidade de concreto



Estimar volume de concreto, peso e sacos inteiros para lajes, rodapés, tubos, freios e escadas.





## Primeiros passos



1. Escolha a forma e unidades de ajuste correspondentes para cada medição. Um tubo usa diâmetros externos e internos.
2. Para escadas, digite o número de subidas e o comprimento da plataforma superior separadamente. Use o número de peças idênticas para outras formas.
3. Substitua a densidade padrão pelo valor no rótulo do material, se conhecido. Use a tabela de pacotes inteiros para pedidos.







## Exemplo



### Entrada



```
7 pés × 3 pés × 5 em laje, quantidade 2
```



### Resultado esperado



```
17,5 ft³, 2.327,50 lb a 133 lb/ft³
```







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/concrete-calculator/>)







## Notas de uso



O cálculo é feito no seu navegador. Use unidades consistentes.







## Método de cálculo



O volume é igual ao comprimento da área transversal vezes. O padrão usa 133 lb/ft3 para libras e 2.130 kg/m3 para quilogramas. Uma densidade personalizada converte ambos os resultados de um valor. Adicione qualquer subsídio antes de arredondar uma ordem para sacos inteiros.



$$
V_{\rm slab}=lwhq,\quad V_{\rm tube}=\pi hq(d_o^2-d_i^2)/4
$$



$$
V_{\rm stairs}=brn\left[p+u(n-1)/2\right],\qquad m=V\rho
$$



Na fórmula da escada, b é a largura, r a elevação, u a execução horizontal, n o número de subidas, e p a profundidade da plataforma superior. O volume sólido inclui n-1 pisos e a plataforma superior.



Para dois 7 pés × 3 pés × 5 em lajes, 133 lb/ft3 dá 2327,50 lb, ou 38,79 equivalentes de um saco de 60 lb. A mesa de encomenda ronda que para 39 sacos antes de qualquer subsídio.







## Modo de cálculo



**Pés de lâmina ou retangular**

- Comprimento
- Unidade de comprimento
- Largura
- Unidade da largura
- Espessura ou altura
- Unidade de espessura ou altura
- Quantidade
- Densidade de concreto personalizada · lb/ft³
- Desperdícios · %





**Coluna ou pé redondo**

- Diâmetro
- Unidade de diâmetro
- Profundidade ou altura
- Unidade de profundidade ou altura
- Quantidade
- Densidade de concreto personalizada · lb/ft³
- Desperdícios · %





**Laje circular ou tubo**

- Diâmetro exterior
- Unidade de diâmetro exterior
- Diâmetro interno
- Unidade de diâmetro interior
- Profundidade ou altura
- Unidade de profundidade ou altura
- Quantidade
- Densidade de concreto personalizada · lb/ft³
- Desperdícios · %





**Meio-fio e sarjeta**

- Profundidade da curva
- Unidade de profundidade da curva
- Largura da escotilha
- Unidade de largura da tampa
- Altura da curva acima da calha
- Altura da curva acima da calha
- Espessura da bandeira
- Unidade de espessura da bandeira
- Comprimento
- Unidade de comprimento
- Quantidade
- Densidade de concreto personalizada · lb/ft³
- Desperdícios · %





**Escadas e plataformas sólidas**

- Executar por passo
- Executar por unidade de passo
- Subir por passo
- Subir por unidade de passo
- Largura da escada
- Unidade de largura da escada
- Profundidade da plataforma superior
- Unidade de profundidade da plataforma superior
- Número de passos
- Densidade de concreto personalizada · lb/ft³
- Desperdícios · %

[Documentação](https://docs.toolpony.com/pt-br/guides/concrete-calculator/)
