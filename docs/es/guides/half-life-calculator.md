# Guía de uso · Calculadora de semivida



Resolver la desintegración exponencial de cualquier tres mediciones, o convertir entre media vida, vida media y constante de descomposición.





## Ejemplo



### Entrada



```
Unidades de 100 a 10 en 50 horas
```



### Resultado esperado



```
Vida media ♥ 15.0515
```







## Pruébalo

[Abrir herramienta completa · Calculadora de semivida](<https://toolpony.com/es/tools/half-life-calculator/>)





## Método de cálculo



La decadencia exponencial es N(t) = N0 · 2^(−t/T). T es media vida, la vida media es T/ln(2), y la constante de decaimiento es ln(2)/T. La conversión utiliza ln(2) redondeado a diez lugares decimales. Utilice la misma unidad de tiempo para todos los campos.



$$
N(t)=N_0\,2^{-t/T},\qquad \lambda=\frac{\ln 2}{T},\qquad \tau=\frac1\lambda
$$



Elija primero lo desconocido. Utilice unidades de tiempo consistentes en los otros tres campos. Por una cantidad inicial de 100 y media vida de 10, la cantidad restante después de 20 unidades de tiempo es 25.







## Modo de cálculo





### Encuentra la mitad de vida



- Cantidad restante
- Cantidad inicial
- Tiempo transcurrido







### Encontrar la cantidad restante



- Cantidad inicial
- Tiempo transcurrido
- La vida media







### Encontrar la cantidad inicial



- Cantidad restante
- Tiempo transcurrido
- La vida media







### Calcular el tiempo



- Cantidad restante
- Cantidad inicial
- La vida media







### Convertir medidas de decaimiento



- Medición conocida · La vida media / Vida media / Constante de declive
- Valor







[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fhalf-life-calculator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/half-life-calculator/)
