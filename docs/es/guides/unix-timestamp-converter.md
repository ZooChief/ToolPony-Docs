# Guía de uso · Conversor de marcas de tiempo Unix



Convierte segundos, milisegundos, microsegundos o nanosegundos Unix a UTC y viceversa sin perder dígitos.





## Ejemplo



### Entrada



```
0 segundos
```



### Resultado esperado



```
1970-01-01T00:00:00.000Z
```





<a id="case-study"></a>



## Un nanosegundo antes de la época



1. Selecciona ns e introduce -1. La hora UTC es 1969-12-31T23:59:59.999999999Z. Invierte la conversión para recuperar el mismo entero.
2. 1970-01-01T05:44:59.999999999+05:45 representa el mismo instante. Copia una unidad o exporta las cuatro en una fila CSV.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/unix-timestamp-converter/#example-before-epoch>)





## Pruébalo

[Abrir herramienta completa · Conversor de marcas de tiempo Unix](<https://toolpony.com/es/tools/unix-timestamp-converter/>)





## Método de cálculo



El tiempo Unix cuenta desde 1970-01-01T00:00:00Z y excluye segundos intercalares. Admite fechas UTC de 1900 a 9999, con desplazamiento explícito y hasta nueve decimales.







## Modo de cálculo





### Marca de tiempo → Fecha



- Marca de tiempo Unix
- Unidad · Segundos / Milisegundos / Microsegundos / Nanosegundos







### Fecha → Marca de tiempo



- Fecha ISO 8601 con desfase UTC
- Unidad · Segundos / Milisegundos / Microsegundos / Nanosegundos







**Fuentes del método** [GNU · Seconds since the Epoch](<https://www.gnu.org/software/coreutils/manual/html_node/Seconds-since-the-Epoch.html>) · [IETF · RFC 3339](<https://www.rfc-editor.org/rfc/rfc3339>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Funix-timestamp-converter%2F>)

[Documentación](https://docs.toolpony.com/es/guides/unix-timestamp-converter/)
