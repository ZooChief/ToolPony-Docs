# Calculadora de préstamos



Calcula cuotas, deduce el plazo a partir del pago mensual o programa pagos extra. Exporta la tabla completa.





## Primeros pasos



1. Elige plazo fijo, cuota objetivo o pagos extra con fechas.
2. Indica el primer mes. Introduce los pagos únicos uno por línea, por ejemplo 2026-06, 500.
3. Calcula y selecciona la tabla que deseas descargar.







## Ejemplo



### Entrada



```
100.000 durante 10 años al 6 %, pago mensual
```



### Resultado esperado



```
≈1.110,21 al mes
```







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/loan-calculator/>)







## Notas de uso



El cálculo se ejecuta en tu navegador. Usa unidades coherentes.







## Método de cálculo



Las cuotas usan la tasa nominal convertida al período de pago. Los pagos extra con fecha se aplican después de la cuota mensual. La tasa es fija y los importes intermedios no se redondean.



$$
M=\frac{Pr}{1-(1+r)^{-n}},\qquad M=\frac Pn\quad(r=0)
$$



$$
n=\frac{-\ln(1-Pr/M)}{\ln(1+r)},\qquad M>Pr\quad(r>0)
$$



$$
I_k=r B_{k-1},\qquad B_k=\max(0,B_{k-1}-(M-I_k)-E_k)
$$



P es el principal, r la tasa por período, M la cuota y n el número de períodos. Para deducir el plazo y los extras con fecha, divide el porcentaje anual por 1.200. B es el saldo, I el interés y E el extra aplicado al principal.



Con 45.000 al 6,3 % y una cuota de 785, el plazo estimado es de 68,38 meses. En meses completos son 69 pagos, con una última cuota menor. Selecciona una tabla antes de descargar.







## Modo de cálculo



**Cuotas**

- Principal
- Años
- Meses
- Tasa anual · %
- Capitalización
- Frecuencia de pago · Anual / Semestral / Trimestral / Mensual / Dos veces al mes / Cada dos semanas / Semanal / Diaria
- Extra por pago





**Plazo a partir de la cuota**

- Principal
- Cuota mensual
- Tasa anual · %





**Pagos extra con fechas**

- Principal
- Años
- Meses
- Tasa anual · %
- Mes del primer pago
- Pago extra mensual
- Inicio de los extras mensuales
- Pago extra anual
- Inicio de los extras anuales
- Pagos únicos (AAAA-MM, importe)





**Pago único al vencimiento**

- Principal
- Años
- Meses
- Tasa anual · %
- Capitalización





**Valor actual de un pago único**

- Importe al vencimiento
- Años
- Meses
- Tasa anual · %
- Capitalización

[Documentación](https://docs.toolpony.com/es/guides/loan-calculator/)
