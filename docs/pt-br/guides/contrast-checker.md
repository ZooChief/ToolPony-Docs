# Verificador de contraste



Compare duas cores opacas com os limites de contraste da WCAG 2.2.





## Exemplo



### Entrada



```
#000000 sobre #FFFFFF
```



### Resultado esperado



```
21:1
```





<a id="case-study"></a>



## Escolher um cinza que atinja AA para texto normal sobre branco



1. Teste \#777777 sobre branco. A razão é de aproximadamente 4,48:1. O valor com uma casa decimal parece 4,5, mas a avaliação usa o valor sem arredondar e o texto normal fica abaixo do nível AA das WCAG.
2. Teste \#767676 no mesmo fundo. A razão sobe para cerca de 4,54:1 e o texto normal atinge AA. Ambos atingem o limite de 3:1 para texto grande.
3. Confira as cores realmente exibidas. Para texto sobre uma imagem ou camada translúcida, colete as cores finais no ponto de menor contraste do fundo. O resultado vale para o par de cores sólidas informado.





## Experimente

[Abrir ferramenta completa · Verificador de contraste](<https://toolpony.com/pt-br/tools/contrast-checker/>)





## Método de cálculo



A razão divide (luminância clara + 0,05) por (luminância escura + 0,05). A avaliação usa o valor sem arredondar. Texto normal exige 4,5:1 para AA e 7:1 para AAA. Texto grande exige 3:1 e 4,5:1.





**Referências do método** [W3C · WCAG 2.2 (1.4.3, AA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html>) · [W3C · WCAG 2.2 (1.4.6, AAA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-enhanced.html>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fcontrast-checker%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/contrast-checker/)
