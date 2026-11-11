# Calculadora de liquidación hipotecaria



Compara las cuotas restantes, pagos extra, liquidación inmediata y dos calendarios de pago cada dos semanas.





## Primeros pasos



1. Si ya hiciste pagos extra, usa el saldo y la cuota de principal e intereses del extracto. También puedes deducir el saldo del préstamo original y del plazo restante.
2. Elige un plan y añade extras mensuales, anuales o únicos. Empiezan en los meses 1, 12 y 1 por defecto. Cambia los inicios en Más opciones.
3. Compara el plan elegido con el regular y descarga la tabla restante o el CSV comparativo.
4. El modelo cubre principal e interés fijo. La liquidación real puede incluir interés diario, comisiones y penalizaciones. Confirma el importe con la entidad.







## Ejemplo



### Entrada



```
400.000 a 30 años al 6 %. Quedan 25 años y se pagan 500 extra al mes.
```



### Resultado esperado



```
207 meses restantes, 122.306,21 de intereses ahorrados
```







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/mortgage-payoff-calculator/>)







## Notas de uso



El cálculo se ejecuta en tu navegador. Usa unidades coherentes.







## Método de cálculo



El modo de préstamo original supone que las cuotas previas siguieron el plan. El interés mensual es el saldo por la tasa anual dividida entre doce. El modelo agrupado añade media cuota cada seis meses. El de 26 pagos usa media cuota mensual y divide la tasa anual entre 26.



$$
B=M\frac{1-(1+r)^{-n}}r\quad(r>0),\qquad B=Mn\quad(r=0)
$$



$$
I_k=rB_{k-1},\qquad B_k=\max(0,B_{k-1}-M+I_k-E_k)
$$



$$
E_{6j}=M/2\quad\text{(grouped)},\qquad M_{26}=M/2,\quad r_{26}=r_{\rm annual}/26
$$







## Modo de cálculo



**Préstamo original y plazo restante**

- Importe original
- Años del plazo original
- Meses adicionales originales
- Tasa anual · %
- Años restantes
- Meses restantes adicionales
- Plan de pago · Pagos extra / Pagos normales / Cada dos semanas, agrupado por mes / Cada dos semanas, 26 pagos al año / Liquidar el principal ahora
- Pago extra mensual
- Pago extra anual
- Pago extra único
- Primer mes para extras mensuales
- Primer mes para extras anuales
- Mes del pago único





**Saldo actual y cuota**

- Principal pendiente
- Cuota mensual
- Tasa anual · %
- Plan de pago · Pagos extra / Pagos normales / Cada dos semanas, agrupado por mes / Cada dos semanas, 26 pagos al año / Liquidar el principal ahora
- Pago extra mensual
- Pago extra anual
- Pago extra único
- Primer mes para extras mensuales
- Primer mes para extras anuales
- Mes del pago único

[Documentación](https://docs.toolpony.com/es/guides/mortgage-payoff-calculator/)
