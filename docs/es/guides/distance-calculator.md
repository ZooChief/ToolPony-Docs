# Calculadora de distancias



Encontrar la distancia entre dos puntos 2D o 3D, o estimar la distancia superficial entre coordenadas geográficas.





## Primeros pasos



1. Usa el ejemplo o introduce tus propios valores.
2. Calcula, copia el resultado o descarga los detalles disponibles.







## Ejemplo



### Entrada



```
2D: (0, 0) a (3, 4)
```



### Resultado esperado



```
Distancia 5
```







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/distance-calculator/>)







## Notas de uso



El cálculo se ejecuta en tu navegador. Usa unidades coherentes.







## Método de cálculo



La distancia cartesiana utiliza la norma euclidiana. Los modos geográficos utilizan el elipsoide WGS 84 y la aproximación de Lambert. Casi los puntos antipodal usan una aproximación esférica. Esto es una estimación superficial.



$$
d=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2+(z_2-z_1)^2}
$$



Utilice el modo 2D o 3D para coordenadas que ya comparten una escala lineal. Convierta ambos puntos en la misma unidad primero.



Para las coordenadas geográficas, norte y este son positivas. Utilice el modo de grado-minuto segundo cuando una encuesta da campos angulares separados. El resultado calcula una ruta de superficie elipsoidal.







## Modo de cálculo



**2D**

- X1
- Y1
- X2
- Y2





**3D**

- X1
- Y1
- Z1
- X2
- Y2
- Z2





**Latitud y longitud**

- Primera latitud · °
- Primera longitud · °
- Segunda latitud · °
- Segunda longitud · °





**Grados, minutos y segundos**

- Primer grado de latitud
- Primeros minutos de latitud
- Primeros segundos de latitud
- Primer hemisferio de latitud · N / S
- Primeros grados de longitud
- Primeros minutos de longitud
- Primeros segundos de longitud
- Hemisferio de primera longitud · E / W
- Segundo grado de latitud
- Segunda latitud minutos
- Segundos de latitud
- Segundo hemisferio de latitud · N / S
- Segundo grado de longitud
- Segundos minutos de longitud
- Segundos de longitud
- Hemisferio de segunda longitud · E / W

[Documentación](https://docs.toolpony.com/es/guides/distance-calculator/)
