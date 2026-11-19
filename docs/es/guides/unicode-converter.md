# Conversor Unicode



Convertir texto en Puntos de código Unicode, UTF-8 bytes hexadecimal o UTF-16 escapa, y decodificarlos de nuevo al texto.





## Ejemplo



### Entrada



```
🐴
```



### Resultado esperado



```
U+1F434 o F0 9F 90 B4
```







## Pruébalo

[Abrir herramienta completa · Conversor Unicode](<https://toolpony.com/es/tools/unicode-converter/>)





## Método de cálculo



El modo Code-point trata a un personaje suplementario como un escalar. UTF-16 utiliza dos unidades de código para tal carácter. Se rechazan secuencias surrogadas inválidas y bytes UTF-8 inválidos.







## Modo de cálculo



**codificar texto**

- Entrada
- Codificación · Puntos de código Unicode / Bytes hexadecimales UTF-8 / Escapes UTF-16 de JavaScript





**Decodificar texto**

- Entrada
- Codificación · Puntos de código Unicode / Bytes hexadecimales UTF-8 / Escapes UTF-16 de JavaScript







[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Funicode-converter%2F>)

[Documentación](https://docs.toolpony.com/es/guides/unicode-converter/)
