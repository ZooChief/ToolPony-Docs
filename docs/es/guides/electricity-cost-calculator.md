# Guía de uso · Calculadora del coste de electricidad



Calcula el coste por consumo con la potencia eléctrica, la capacidad frigorífica y su eficiencia o dos lecturas del contador. Comprueba los kWh por día y periodo.





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





<a id="case-study"></a>



## Leer los vatios del aire acondicionado



1. La ficha del LG LW6014ER indica 6000 BTU/h de refrigeración y 530 W de consumo eléctrico. A plena carga, 8 horas diarias durante 30 días dan 0,53 × 8 × 30 = 127,2 kWh. A 0,20 por kWh, el consumo cuesta 25,44.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/electricity-cost-calculator/#example-window-power>)





## Comprobar dos lecturas del contador



En 30 días el contador pasa de 612345,125 a 612492,365 kWh. La diferencia es de 147,24 kWh, o 4,908 kWh al día. A 0,15 por kWh, el consumo cuesta 22,086 antes de cargos fijos e impuestos.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/electricity-cost-calculator/#example-meter-readings>)







## Calcular potencia eléctrica con el EER



Con 6000 BTU/h y un EER nominal de 12 BTU/Wh, la potencia eléctrica es 6000 ÷ 12 = 500 W. A plena carga, 8 horas al día durante 30 días suman 120 kWh. Usa el EER de las condiciones de funcionamiento indicadas.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/electricity-cost-calculator/#example-cooling-eer>)







## Pruébalo

[Abrir herramienta completa · Calculadora del coste de electricidad](<https://toolpony.com/es/tools/electricity-cost-calculator/>)





## Método de cálculo



Coste por consumo = kWh × tarifa. El consumo medido es la lectura final menos la inicial. BTU/h divididos entre EER, o vatios frigoríficos divididos entre COP, dan los vatios eléctricos. Las estimaciones usan 30,44 días por mes y 365,25 por año.



$$
E_{\rm kWh}=M_1-M_0,\qquad P_{\rm W}=\frac{Q_{\rm Btu/h}}{\mathrm{EER}}=\frac{Q_{\rm W}}{\mathrm{COP}}
$$



$$
E_{\rm kWh}=P_{\rm kW}\,t_{\rm h}\,f\,n,\qquad C=E_{\rm kWh}\,r
$$







## Modo de cálculo





### Número fijo de días



- Base del cálculo · Potencia eléctrica / Capacidad frigorífica / Lecturas del contador
- Potencia eléctrica
- Unidad de potencia · W / kW / BTU/h / PS / TR
- Capacidad frigorífica
- Unidad de capacidad frigorífica · BTU/h / kW / TR
- Tipo de eficiencia · EER (BTU/Wh) / COP (W/W)
- Eficiencia nominal
- Lectura inicial · kWh
- Lectura final · kWh
- Carga media · %
- Aparatos
- Horas al día · h
- Días
- Precio por kWh







### Estimación diaria a anual



- Aparato predefinido
- Base del cálculo · Potencia eléctrica / Capacidad frigorífica
- Potencia eléctrica
- Unidad de potencia · W / kW / BTU/h / PS / TR
- Capacidad frigorífica
- Unidad de capacidad frigorífica · BTU/h / kW / TR
- Tipo de eficiencia · EER (BTU/Wh) / COP (W/W)
- Eficiencia nominal
- Carga media · %
- Aparatos
- Uso
- Unidad de uso · Minutos por día / Horas al día / Horas por semana / Horas por mes / Días por semana / Días por mes / Días por año / Meses por año
- Precio por kWh







**Fuentes del método** [LG · LW6014ER electrical specification](<https://images.thdstatic.com/catalog/pdfImages/e3/e3b8396a-44d1-4372-b120-7532036b2488.pdf>) · [Ohio Consumers’ Counsel · Read an electric meter](<https://www.occ.ohio.gov/sites/default/files/2021-07/OCC-How-to-Read-an-Electric-Meter.pdf>) · [U.S. Department of Energy · Room air conditioner ratings](<https://www.energy.gov/sites/prod/files/2015/06/f22/room_ac_rfi.pdf>) · [NIST · International Table Btu](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-footnotes>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Felectricity-cost-calculator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/electricity-cost-calculator/)
