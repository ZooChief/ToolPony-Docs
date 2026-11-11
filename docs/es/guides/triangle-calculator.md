# Calculadora de triángulos



Calcula ángulos, alturas, medianas y centros a partir de tres medidas.





## Primeros pasos



1. Introduce tres medidas, al menos una de un lado.
2. Selecciona radianes para π/2. En LLA, tanto un ángulo agudo como su suplementario pueden ser válidos.
3. En la tabla, A está en el origen y B en el eje x positivo. Exporta la tabla seleccionada como CSV.







## Ejemplo



### Entrada



```
a = 7, b = 10, A = 30°
```



### Resultado esperado



```
Dos soluciones con c ≈ 13,55923 y 3,76127.
```







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/triangle-calculator/>)







## Notas de uso



El cálculo se ejecuta en tu navegador. Usa unidades coherentes.







## Método de cálculo



Usa una sola unidad de longitud. El lado a se opone al ángulo A, igual para b/B y c/C. Los ángulos por sí solos no fijan el tamaño.



$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C},\qquad a^2=b^2+c^2-2bc\cos A
$$



$$
\Delta=\sqrt{s(s-a)(s-b)(s-c)},\quad s=\tfrac{a+b+c}{2},\quad h_a=2\Delta/a
$$



$$
m_a=\tfrac12\sqrt{2b^2+2c^2-a^2},\qquad r=\Delta/s,\qquad R=abc/(4\Delta)
$$







## Modo de cálculo



**Datos conocidos**

- Lado a
- Lado b
- Lado c
- Ángulo A
- Ángulo B
- Ángulo C
- Unidad angular · Grados / Radianes





**Tres lados (LLL)**

- Lado a
- Lado b
- Lado c





**Dos lados y ángulo comprendido (LAL)**

- Lado b
- Lado c
- Ángulo A · °





**Dos ángulos y un lado**

- Ángulo A · °
- Ángulo B · °
- Lado conocido · a / b / c
- Lado





**Dos lados y un ángulo opuesto (LLA)**

- Lado a
- Lado b
- Ángulo A · °





**Catetos del triángulo rectángulo**

- Lado a
- Lado b

[Documentación](https://docs.toolpony.com/es/guides/triangle-calculator/)
