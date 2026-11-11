# Calculadora de resistencias y códigos de color



Lee de 3 a 6 bandas y calcula resistencias en serie, en paralelo o de un hilo circular.





## Primeros pasos



1. Elige el número de bandas o el circuito. La banda de tolerancia suele estar separada de las demás.
2. Introduce diámetro y longitud del hilo circular. El material predefinido rellena la conductividad, que puedes editar.







## Ejemplo



### Entrada



```
4 bandas: verde, rojo, rojo y oro
```



### Resultado esperado



```
5,200 Ω ±5%
```







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/resistor-calculator/>)







## Notas de uso



El cálculo se ejecuta en tu navegador. Usa unidades coherentes.







## Método de cálculo



Lee los dígitos, el multiplicador, la tolerancia y el coeficiente de temperatura opcional. Tres bandas implican una tolerancia del 20 %. Para un hilo circular uniforme, R = L/(σA). Consulta la ficha del componente para marcas especiales.



$$
R_{\rm series}=\sum_i R_i,\quad R_{\rm parallel}=\left(\sum_i 1/R_i\right)^{-1},\quad R_{\rm wire}=\frac{L}{\sigma\pi(d/2)^2}
$$



$$
R_{\rm band}=D\,10^m,\qquad R_{\min,\max}=R_{\rm band}(1\mp t/100)
$$







## Modo de cálculo



**4 bandas**

- Primer dígito
- Segundo dígito
- Multiplicador
- Tolerancia





**3 bandas**

- Primer dígito
- Segundo dígito
- Multiplicador





**5 bandas**

- Primer dígito
- Segundo dígito
- Tercer dígito
- Multiplicador
- Tolerancia





**6 bandas**

- Primer dígito
- Segundo dígito
- Tercer dígito
- Multiplicador
- Tolerancia
- Coeficiente de temperatura





**Paralelo**

- Resistencias en Ω





**Serie**

- Resistencias en Ω





**Conductor circular**

- Longitud
- Unidad de longitud · mm / cm / m / km / dentro / ft / Yd / \#
- Diámetro
- Unidad de diámetro · mm / cm / m / km / dentro / ft / Yd / \#
- Material predefinido · Personalizado / Cobre / Cobre recocido / Aluminio / Plata / Oro
- Conductividad · S/m

[Documentación](https://docs.toolpony.com/es/guides/resistor-calculator/)
