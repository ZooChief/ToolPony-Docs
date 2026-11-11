# Calculadora de hoja de horas



Registra turnos y descansos semanales con redondeo, reglas de pago y CSV.





## Primeros pasos



1. Introduce horas como 08:30, 8.30 o 8:30 AM. Indica los descansos en horas y minutos, como 00:30.
2. Elige redondeo y reglas opcionales de pago. Descarga CSV o imprime. Guardar el borrador en el navegador es opcional.







## Ejemplo



### Entrada



```
08:30–17:00 con 00:30 de descanso
```



### Resultado esperado



```
08:00:00
```







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/time-card-calculator/>)







## Notas de uso



El cálculo se ejecuta en tu navegador. Usa unidades coherentes.







## Método de cálculo



Resta el descanso y redondea el tiempo neto. Un final anterior corresponde al día siguiente. Los límites diarios o semanales y las tarifas los indicas tú.



$$
t_i=(e_i-s_i)\bmod 1440-b_i,\qquad t'_i=q\,\operatorname{round}(t_i/q)\quad(q>0)
$$



$$
P=(t_{\rm base}+m\,t_{\rm overtime})r/60
$$

[Documentación](https://docs.toolpony.com/es/guides/time-card-calculator/)
