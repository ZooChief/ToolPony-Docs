# Guía de uso · Conversor Unicode



Convierte puntos de código, bytes UTF-8 y escapes JavaScript. Examina caracteres y compara formas de normalización.





## Ejemplo



### Entrada



```
🐴
```



### Resultado esperado



```
U+1F434 o F0 9F 90 B4
```





<a id="case-study"></a>



## Comparar dos escrituras de é



1. Una e seguida de U+0301, un espacio y 🐴 suman 3 grafemas, 4 puntos de código, 5 unidades UTF-16 y 8 bytes UTF-8. NFC forma U+00E9 y reduce UTF-8 a 7 bytes. 🐴 sigue ocupando un punto de código y dos unidades UTF-16.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/unicode-converter/#example-combining-accent>)





## Pruébalo

[Abrir herramienta completa · Conversor Unicode](<https://toolpony.com/es/tools/unicode-converter/>)





## Método de cálculo



El modo Code-point trata a un personaje suplementario como un escalar. UTF-16 utiliza dos unidades de código para tal carácter. Se rechazan secuencias surrogadas inválidas y bytes UTF-8 inválidos.







## Modo de cálculo





### codificar texto



- Entrada
- Codificación · Puntos de código Unicode / Bytes hexadecimales UTF-8 / Escapes UTF-16 de JavaScript / Escapes JS de puntos de código







### Decodificar texto



- Entrada
- Codificación · Puntos de código Unicode / Bytes hexadecimales UTF-8 / Escapes UTF-16 de JavaScript / Escapes JS de puntos de código







### Inspeccionar caracteres



- Entrada
- Normalización · Original / NFC / NFD / NFKC / NFKD







**Fuentes del método** [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>) · [Unicode · UAX \#15](<https://www.unicode.org/reports/tr15/>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Funicode-converter%2F>)

[Documentación](https://docs.toolpony.com/es/guides/unicode-converter/)
