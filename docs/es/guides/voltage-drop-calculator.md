# Calculadora de caída de tensión



Estima la caída de tensión en CC, monofásica o trifásica equilibrada según el calibre o la resistencia.





## Primeros pasos



1. Elige un modelo. Para trifásica introduce tensión entre líneas y corriente de línea. Indica solo la distancia de ida.
2. La distancia límite usa tu porcentaje de caída. Comprueba por separado la intensidad admisible, la temperatura y los requisitos de instalación.







## Ejemplo



### Entrada



```
120 V, monofásica, 500 ft, 1 A y 1,2 Ω/km
```



### Resultado esperado



```
Caída de 0,37 V, 0,30 %
```







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/voltage-drop-calculator/>)







## Notas de uso



El cálculo se ejecuta en tu navegador. Usa unidades coherentes.







## Método de cálculo



Usa la longitud de ida y conductores idénticos en paralelo. Multiplica I·L·R por 2 para CC o monofásica y por √3 para trifásica equilibrada. Para una carga inductiva, combina R y X mediante el factor de potencia. El calibre usa valores nominales cerca de 20 °C. Para el cable real, usa datos del fabricante.



$$
\Delta V=\frac{k I L R_{\rm eff}}{n},\quad k=2\ \text{(DC, 1)}\phi,\quad k=\sqrt{3}\ \text{(3)}\phi
$$



$$
R_{\rm eff}=R\cos\theta+X\sin\theta,\quad \%\Delta V=100\frac{\Delta V}{V_s}
$$







## Modo de cálculo



**Resistencia o impedancia conocida**

- Resistencia o impedancia por longitud
- Unidad por longitud · Ω/km / Ω/m / mΩ/m / Ω/1000 pies / Ω/ft / mΩ/ft
- Tensión · V
- Circuito · DC / CA monofásica / CA trifásica
- Conductores en paralelo por fase
- Distancia de ida
- Unidad de longitud · ft / m / \# / km
- Corriente · A
- Límite de caída para estimar la distancia · %





**Estimar según el calibre**

- Material · Cobre / Aluminio / Plata / Oro
- Calibre del cable
- Tensión · V
- Circuito · DC / CA monofásica / CA trifásica
- Conductores en paralelo por fase
- Distancia de ida
- Unidad de longitud · ft / m / \# / km
- Corriente · A
- Límite de caída para estimar la distancia · %





**Estimar según el área**

- Material · Cobre / Aluminio / Plata / Oro
- Área transversal · mm²
- Tensión · V
- Circuito · DC / CA monofásica / CA trifásica
- Conductores en paralelo por fase
- Distancia de ida
- Unidad de longitud · ft / m / \# / km
- Corriente · A
- Límite de caída para estimar la distancia · %





**Resistencia y reactancia**

- Resistencia
- Reactancia por longitud
- Unidad por longitud · Ω/km / Ω/m / mΩ/m / Ω/1000 pies / Ω/ft / mΩ/ft
- Factor de potencia inductivo
- Tensión · V
- Circuito · DC / CA monofásica / CA trifásica
- Conductores en paralelo por fase
- Distancia de ida
- Unidad de longitud · ft / m / \# / km
- Corriente · A
- Límite de caída para estimar la distancia · %

[Documentación](https://docs.toolpony.com/es/guides/voltage-drop-calculator/)
