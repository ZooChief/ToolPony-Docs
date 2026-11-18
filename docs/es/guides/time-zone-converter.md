# Conversor de zonas horarias



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







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/time-zone-converter/>)







## Método de cálculo



Las zonas IANA usan las reglas del navegador. Una hora repetida tiene dos instantes y una omitida ninguno. Un desfase UTC fijo no varía durante el año.



$$
T_{\rm target}=T_{\rm source}-O_{\rm source}+O_{\rm target}
$$







## Modo de cálculo



**IANA**

- Fecha
- Hora local
- Zona IANA de origen
- Zona IANA de destino
- Hora repetida · Primera ocurrencia / Última ocurrencia





**Desfases UTC fijos**

- Fecha
- Hora local
- Desfase de origen
- Desfase de destino

[Documentación](https://docs.toolpony.com/es/guides/time-zone-converter/)
