# Comprobador de contraste



Compara dos colores opacos con los umbrales de contraste de WCAG 2.2.





## Ejemplo



### Entrada



```
#000000 sobre #FFFFFF
```



### Resultado esperado



```
21:1
```







## Pruébalo

[Abrir herramienta completa · Comprobador de contraste](<https://toolpony.com/es/tools/contrast-checker/>)





## Método de cálculo



La relación divide (luminancia clara + 0,05) entre (luminancia oscura + 0,05). La prueba usa el valor sin redondear. El texto normal requiere 4,5:1 para AA y 7:1 para AAA. El texto grande requiere 3:1 y 4,5:1.

[Documentación](https://docs.toolpony.com/es/guides/contrast-checker/)
