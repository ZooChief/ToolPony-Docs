# Guía de uso · Codificar y decodificar Base64



Codifica texto UTF-8 o bytes hexadecimales en Base64 o Base64url y guarda los bytes decodificados.





## Ejemplo



### Entrada



```
Codificar hello
```



### Resultado esperado



```
aGVsbG8=
```





<a id="case-study"></a>



## Recuperar bytes de Base64url



1. Elige decodificar, alfabeto URL y bytes hexadecimales. \_wCA7w da FF 00 80 EF, con un byte nulo y valores ajenos a UTF-8. Descarga los bytes para conservar esos cuatro bytes.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/base64-encoder-decoder/#example-binary-bytes>)





## Pruébalo

[Abrir herramienta completa · Codificar y decodificar Base64](<https://toolpony.com/es/tools/base64-encoder-decoder/>)





## Método de cálculo



El estándar usa + y /, la variante URL usa - y \_ sin relleno de salida. Se valida UTF-8 y se conserva el U+FEFF inicial. Límite de 500.000 unidades UTF-16 o 500.000 bytes.





**Fuentes del método** [IETF · RFC 4648 (Base64)](<https://www.rfc-editor.org/rfc/rfc4648>) · [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fbase64-encoder-decoder%2F>)

[Documentación](https://docs.toolpony.com/es/guides/base64-encoder-decoder/)
