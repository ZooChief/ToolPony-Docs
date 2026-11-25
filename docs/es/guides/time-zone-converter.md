# Guía de uso · Conversor de zonas horarias



Convierte fecha y hora entre zonas IANA o desfases UTC fijos.





## Ejemplo



### Entrada



```
2026-01-15 09:00, Asia/Shanghai → America/New_York
```



### Resultado esperado



```
2026-01-14 20:00:00
```





<a id="case-study"></a>



## Una reunión en la hora repetida



1. El 1 de noviembre de 2026 hay dos 01:30 en Nueva York. En Shanghái son las 13:30 y las 14:30 respectivamente. Elige la de la invitación y copia el instante UTC. Al invertir las ciudades se conserva la hora de la reunión.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/time-zone-converter/#example-repeated-meeting>)





## Una llamada en noviembre en La Habana



Cuba mantuvo UTC−04:00 en noviembre de 2026. Una llamada en La Habana a las 09:00 del 23 de noviembre corresponde a las 13:00 UTC. Elige America/Havana para aplicar las reglas locales de la fecha.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/time-zone-converter/#example-havana-clock>)







## Cuando el reloj adelanta 30 minutos



El 4 de octubre de 2026, la isla de Lord Howe pasa de las 01:59:59 a las 02:30:00. Prueba a introducir 02:15. Puedes mover la cita media hora a las 01:45 o a las 02:45. Esta última corresponde a las 15:45 UTC del 3 de octubre.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/time-zone-converter/#example-half-hour-change>)







## Pruébalo

[Abrir herramienta completa · Conversor de zonas horarias](<https://toolpony.com/es/tools/time-zone-converter/>)





## Método de cálculo



Se aplican las reglas IANA de la fecha elegida. Una hora repetida corresponde a dos instantes UTC. Al adelantar el reloj queda un intervalo sin hora local. Un desfase fijo permanece constante.



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## Modo de cálculo





### IANA



- Fecha
- Hora local
- Zona IANA de origen
- Zona IANA de destino
- Hora repetida · Primera ocurrencia / Última ocurrencia







### Desfases UTC fijos



- Fecha
- Hora local
- Desfase de origen
- Desfase de destino







**Fuentes del método** [IANA · Time Zone Database](<https://www.iana.org/time-zones>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Ftime-zone-converter%2F>)

[Documentación](https://docs.toolpony.com/es/guides/time-zone-converter/)
