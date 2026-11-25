# Guía de uso · Calculadora de probabilidades



Compara probabilidades condicionales con una tabla de frecuencias o probabilidades y calcula eventos independientes y ensayos repetidos.





## Ejemplo



### Entrada



```
Eventos independientes A = 0,31 B = 0,56
```



### Resultado esperado



```
Al menos un evento 0,6964
```





<a id="case-study"></a>



## Asistencia a dos talleres



1. De 50 personas, 18 asistieron a ambas sesiones, 12 solo por la mañana (AM), 6 solo por la tarde (PM) y 14 a ninguna. De las 24 de la tarde, 18 fueron también por la mañana (75 %). De las 30 de la mañana, 18 volvieron (60 %).



[Ejecutar ejemplo](<https://toolpony.com/es/tools/probability-calculator/#example-workshop-attendance>)





## Pruébalo

[Abrir herramienta completa · Calculadora de probabilidades](<https://toolpony.com/es/tools/probability-calculator/>)





## Método de cálculo



La unión es la suma de probabilidades marginales menos la intersección. Dentro de B, la proporción de A es P(A ∩ B) / P(B). Si son independientes, la intersección es el producto de las marginales.



$$
P(A\cup B)=P(A)+P(B)-P(A\cap B)
$$



$$
P(A\cap B)=P(A)P(B)\quad\text{(independent)}
$$







## Modo de cálculo





### Dos eventos independientes



- Probabilidad de A
- Probabilidad de B







### Intersección conocida



- Introducir · Probabilidades / Frecuencias
- Probabilidad de A
- Probabilidad de B
- Ambos eventos
- Nombre del evento A
- Nombre del evento B
- A ∩ B
- A ∩ ¬B
- ¬A ∩ B
- ¬A ∩ ¬B







### Recuperar eventos independientes



- Primera cantidad conocida · Probabilidad de A / Probabilidad de B / No es una / No B / Ambos eventos / Al menos un evento / Exactamente un evento / Ni siquiera suceso
- Primera probabilidad
- Segunda cantidad conocida · Probabilidad de A / Probabilidad de B / No es una / No B / Ambos eventos / Al menos un evento / Exactamente un evento / Ni siquiera suceso
- Segunda probabilidad







### Repetidas pruebas independientes



- Probabilidad de A
- Juicios de A
- Probabilidad de B
- Juicios de B







### Intervalo de distribución normal



- Media
- Desviación estándar
- Límite inferior
- Límite superior







**Fuentes del método** [OpenStax · Contingency Tables](<https://openstax.org/books/introductory-statistics-2e/pages/3-4-contingency-tables>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fprobability-calculator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/probability-calculator/)
