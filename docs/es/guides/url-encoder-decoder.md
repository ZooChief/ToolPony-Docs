# Guía de uso · Codificar y decodificar URL



Codifica o decodifica URL y formularios, o edita parámetros ordenados con nombres repetidos y valores vacíos.





## Ejemplo



### Entrada



```
Componente de código: a+b & c
```



### Resultado esperado



```
a%2Bb%20%26%20c
```





<a id="case-study"></a>



## Conservar los signos más de una búsqueda



1. Codifica C++ &amp; tea como valor de formulario. Sale C%2B%2B+%26+tea. Cada signo más pasa a %2B, cada espacio a + y &amp; a %26. Invierte para recuperar el texto. En un componente URI el espacio es %20.
2. En el ejemplo con dos parámetros tag, cambia el segundo a UI &amp; UX. Se mantienen el primero, el valor vacío y \#filters, y el nuevo valor queda como UI+%26+UX.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/url-encoder-decoder/#example-query-plus>)





## Pruébalo

[Abrir herramienta completa · Codificar y decodificar URL](<https://toolpony.com/es/tools/url-encoder-decoder/>)





## Método de cálculo



Un componente codifica los separadores y una URL completa los conserva. En formularios, + representa el espacio. La edición codifica cada nombre y valor por separado y conserva la ruta y el fragmento.





**Fuentes del método** [IETF · RFC 3986](<https://www.rfc-editor.org/rfc/rfc3986>) · [WHATWG · Form encoding](<https://url.spec.whatwg.org/#application/x-www-form-urlencoded>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Furl-encoder-decoder%2F>)

[Documentación](https://docs.toolpony.com/es/guides/url-encoder-decoder/)
