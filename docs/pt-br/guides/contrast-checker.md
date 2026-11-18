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







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/contrast-checker/>)







## Método de cálculo



A razão divide (luminância clara + 0,05) por (luminância escura + 0,05). A avaliação usa o valor sem arredondar. Texto normal exige 4,5:1 para AA e 7:1 para AAA. Texto grande exige 3:1 e 4,5:1.

[Documentação](https://docs.toolpony.com/pt-br/guides/contrast-checker/)
