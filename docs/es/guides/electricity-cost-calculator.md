# Calculadora del coste de electricidad



Estima el consumo y el coste según aparato, carga y tarifa, para un plazo fijo o de diario a anual.





## Primeros pasos



1. Indica la potencia eléctrica, el uso y la tarifa. Los valores predefinidos son ejemplos editables.







## Ejemplo



### Entrada



```
1.000 W, 2 h/día, 30 días, 0,2 por kWh
```



### Resultado esperado



```
60 kWh, coste de 12
```







## Pruébalo

[Abrir herramienta completa · Calculadora del coste de electricidad](<https://toolpony.com/es/tools/electricity-cost-calculator/>)





## Método de cálculo



La energía es kW por horas, carga media y número de aparatos. El coste usa una tarifa fija y períodos de 30,44 días al mes y 365,25 al año. Para refrigeración, usa la potencia eléctrica de entrada.



$$
E_{\rm kWh}=P_{\rm kW}\,t_{\rm h}\,f\,n,\qquad C=E_{\rm kWh}\,r
$$







## Modo de cálculo



**Número fijo de días**

- Potencia
- Unidad de potencia · W / kW / BTU/h / PS / TR
- Carga media · %
- Aparatos
- Horas al día · h
- Días
- Precio por kWh





**Estimación diaria a anual**

- Aparato predefinido
- Potencia
- Unidad de potencia · W / kW / BTU/h / PS / TR
- Carga media · %
- Aparatos
- Uso
- Unidad de uso · Minutos por día / Horas al día / Horas por semana / Horas por mes / Días por semana / Días por mes / Días por año / Meses por año
- Precio por kWh







[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Felectricity-cost-calculator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/electricity-cost-calculator/)
