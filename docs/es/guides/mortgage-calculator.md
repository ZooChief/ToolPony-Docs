# Guía de uso · Calculadora hipotecaria



Compare una hipoteca de tipo fijo con el pago inicial, costos recurrentes, pagos adicionales y pago bisemanal.





## Ejemplo



### Entrada



```
Hogar 400.000; 20%; 30 años; 6%
```



### Resultado esperado



```
≈1,918.56 mensual principal e interés
```







## Pruébalo

[Abrir herramienta completa · Calculadora hipotecaria](<https://toolpony.com/es/tools/mortgage-calculator/>)





## Método de cálculo



El interés mensual es igual a los tiempos principales restantes de la tasa anual dividida por 12. Los costos siguen sus insumos anuales y las tasas de crecimiento. PMI puede parar en un 80% del valor original del hogar en este modelo. Biweekly compara la mitad del pago mensual programado cada dos semanas con interés dividido por 26.



$$
I_k=r B_{k-1},\qquad B_k=B_{k-1}-(M_k-I_k)
$$





**Fuentes del método** [CFPB · Mortgage amortization](<https://www.consumerfinance.gov/ask-cfpb/how-does-paying-down-a-mortgage-work-en-1943/>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fmortgage-calculator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/mortgage-calculator/)
