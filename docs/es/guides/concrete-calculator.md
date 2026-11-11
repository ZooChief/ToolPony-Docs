# Calculadora de cantidad de concreto



Estimar volumen de hormigón, peso y bolsas enteras para losas, pisadas, tubos, bordillos y escaleras.





## Primeros pasos



1. Elija la forma de juego y las unidades de conjunto para cada medición. Un tubo utiliza diámetros externos e interiores.
2. Para escaleras, introduzca el número de subidas y la longitud de la plataforma superior por separado. Utilice el número de piezas idénticas para otras formas.
3. Reemplazar la densidad predeterminada con el valor en la etiqueta de material si se conoce. Utilice la tabla de bolsa completa para pedidos.







## Ejemplo



### Entrada



```
7 ft × 3 ft × 5 en losas, cantidad 2
```



### Resultado esperado



```
17,5 ft³, 2.327,50 lb a 133 lb/ft³
```







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/concrete-calculator/>)







## Notas de uso



El cálculo se ejecuta en tu navegador. Usa unidades coherentes.







## Método de cálculo



El volumen es igual a la longitud del área transversal. El valor predeterminado utiliza 133 lb/ft3 para libras y 2,130 kg/m3 para kilogramos. Una densidad personalizada convierte ambos resultados de un valor. Agregue cualquier asignación antes de redondear un pedido a bolsas enteras.



$$
V_{\rm slab}=lwhq,\quad V_{\rm tube}=\pi hq(d_o^2-d_i^2)/4
$$



$$
V_{\rm stairs}=brn\left[p+u(n-1)/2\right],\qquad m=V\rho
$$



En la fórmula de escalera, b es el ancho, r el ascenso, u la ejecución horizontal, n el número de subidas, y p la profundidad de la plataforma superior. El volumen sólido incluye n−1 pisadas y la plataforma superior.



Para dos 7 ft × 3 ft × 5 en losas, 133 lb/ft3 da 2327.50 lb, o 38.79 equivalentes de una bolsa de 60 lb. La tabla de pedidos ronda que a 39 bolsas antes de cualquier asignación.







## Modo de cálculo



**Pisado rectangular o de placas**

- Longitud
- Unidad de longitud
- Ancho
- Unidad de ancho
- Espesor o altura
- Unidad de espesor o altura
- Cantidad
- Densidad de hormigón personalizado · lb/ft³
- Prestaciones por desechos · %





**Columna o pie redondo**

- Diámetro
- Unidad de diámetro
- Profundidad o altura
- Unidad de profundidad o altura
- Cantidad
- Densidad de hormigón personalizado · lb/ft³
- Prestaciones por desechos · %





**Elas o tubos circulares**

- Diámetro exterior
- Unidad de diámetro exterior
- Diámetro interior
- Unidad de diámetro interior
- Profundidad o altura
- Unidad de profundidad o altura
- Cantidad
- Densidad de hormigón personalizado · lb/ft³
- Prestaciones por desechos · %





**Bordillo y cuneta**

- Profundidad de la curvatura
- Unidad de profundidad de la placa
- Ancho de goma
- Unidad de ancho de corte
- Altura de la curva por encima de la goma
- Altura de la curva por encima de la unidad de la goma
- Espesor de la bandera
- Unidad de espesor de la bandera
- Longitud
- Unidad de longitud
- Cantidad
- Densidad de hormigón personalizado · lb/ft³
- Prestaciones por desechos · %





**Sólidas escaleras y plataforma**

- Corre por paso
- Corre por unidad paso
- Montaje por paso
- Montaje por unidad paso
- Ancho de escalera
- Unidad de ancho de escalera
- La mayor profundidad de la plataforma
- Unidad de profundidad de plataforma superior
- Número de pasos
- Densidad de hormigón personalizado · lb/ft³
- Prestaciones por desechos · %

[Documentación](https://docs.toolpony.com/es/guides/concrete-calculator/)
