# Conversor de subtítulos



Convierte SRT y WebVTT, desplaza o escala los tiempos y comprueba solapamientos.





## Primeros pasos



1. Pega el texto o importa un SRT o VTT y elige el formato de salida.
2. Un desfase positivo retrasa los subtítulos. Multiplica el tiempo respecto al ancla por la escala y suma el desfase. Revisa recortes y solapamientos antes de descargar.







## Ejemplo



### Entrada



```
1
00:00:00,120 --> 00:00:01,400
A line
Second line

2
00:00:01,350 --> 00:00:02,700
Overlap 50 ms
```



### Resultado esperado



```
WEBVTT

00:00:00.120 --> 00:00:01.400
A line
Second line

00:00:01.350 --> 00:00:02.700
Overlap 50 ms
```







## Pruébalo

[Abrir herramienta completa · Conversor de subtítulos](<https://toolpony.com/es/tools/subtitle-converter/>)





## Límites



Hasta 1 MiB y 10.000 subtítulos. Los que terminan antes de cero se eliminan y los que lo cruzan empiezan en cero. SRT no admite todas las posiciones, estilos ni identificadores de WebVTT.





**Fuentes del método** [W3C · WebVTT](<https://www.w3.org/TR/webvtt1/>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fsubtitle-converter%2F>)

[Documentación](https://docs.toolpony.com/es/guides/subtitle-converter/)
