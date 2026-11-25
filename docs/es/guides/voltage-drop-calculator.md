# Guía de uso · Calculadora de caída de tensión



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





<a id="case-study"></a>



## Usar una tabla de cables



1. Con 1 mV/(A·m), 50 m de ida y 100 A, este cable pierde 5 V. Schneider suma otros 10 V aguas arriba, con un total de 15 V para todo el trayecto.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/voltage-drop-calculator/#example-cable-table>)





## Circuito trifásico paralelo



Dos conductores por fase comparten 20 A. Con 400 V, 100 m, R = 1 Ω/km, X = 0,5 Ω/km y factor inductivo 0,8, la caída es 1,91 V y la carga recibe 398,09 V.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/voltage-drop-calculator/#example-parallel-cable>)







## Caída superior a la fuente



Con 24 V CC, 10 A y 1 km de ida a 5 Ω/km, la caída sería 100 V. Con esa corriente el modelo no da una tensión de carga.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/voltage-drop-calculator/#example-cable-limit>)







## Pruébalo

[Abrir herramienta completa · Calculadora de caída de tensión](<https://toolpony.com/es/tools/voltage-drop-calculator/>)





## Método de cálculo



Usa la longitud de ida y conductores idénticos en paralelo. Multiplica I·L·R por 2 para CC o monofásica y por √3 para trifásica equilibrada. Para una carga inductiva, combina R y X mediante el factor de potencia. El calibre usa valores nominales cerca de 20 °C. Para el cable real, usa datos del fabricante.



$$
\Delta V=\frac{k I L R_{\rm eff}}{n},\quad k=2\ \text{(DC, 1)}\phi,\quad k=\sqrt{3}\ \text{(3)}\phi
$$



$$
R_{\rm eff}=R\cos\theta+X\sin\theta,\quad \%\Delta V=100\frac{\Delta V}{V_s}
$$







## Modo de cálculo





### Resistencia o impedancia conocida



- Dato publicado · Impedancia del conductor / Coeficiente de caída del circuito
- Resistencia o impedancia por longitud
- Unidad por longitud · Ω/km / Ω/m / mΩ/m / Ω/1000 pies / Ω/ft / mΩ/ft
- Coeficiente tabulado del circuito · mV/(A·m)
- Tensión · V
- Circuito · DC / CA monofásica / CA trifásica
- Conductores en paralelo por fase
- Distancia de ida
- Unidad de longitud · ft / m / mi / km
- Corriente · A
- Límite de caída para estimar la distancia · %







### Estimar según el calibre



- Material · Cobre / Aluminio / Plata / Oro
- Calibre del cable
- Tensión · V
- Circuito · DC / CA monofásica / CA trifásica
- Conductores en paralelo por fase
- Distancia de ida
- Unidad de longitud · ft / m / mi / km
- Corriente · A
- Límite de caída para estimar la distancia · %







### Estimar según el área



- Material · Cobre / Aluminio / Plata / Oro
- Área transversal · mm²
- Tensión · V
- Circuito · DC / CA monofásica / CA trifásica
- Conductores en paralelo por fase
- Distancia de ida
- Unidad de longitud · ft / m / mi / km
- Corriente · A
- Límite de caída para estimar la distancia · %







### Resistencia y reactancia



- Resistencia
- Reactancia por longitud
- Unidad por longitud · Ω/km / Ω/m / mΩ/m / Ω/1000 pies / Ω/ft / mΩ/ft
- Factor de potencia inductivo
- Tensión · V
- Circuito · DC / CA monofásica / CA trifásica
- Conductores en paralelo por fase
- Distancia de ida
- Unidad de longitud · ft / m / mi / km
- Corriente · A
- Límite de caída para estimar la distancia · %







**Fuentes del método** [Schneider Electric · Voltage drop in steady load conditions](<https://www.electrical-installation.org/enwiki/Calculation_of_voltage_drop_in_steady_load_conditions>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fvoltage-drop-calculator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/voltage-drop-calculator/)
