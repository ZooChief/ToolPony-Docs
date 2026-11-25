# Guía de uso · Generador de números aleatorios



Sortea enteros incluyendo ambos límites, con opciones para evitar repeticiones y ordenar los resultados.





## Ejemplo



### Entrada



```
Mínimo 1, máximo 10, cantidad 5
```



### Resultado esperado



```
Cinco enteros aleatorios del 1 al 10
```





<a id="case-study"></a>



## Sortear cuatro boletos



1. Numera 12 boletos del 101 al 112 y saca cuatro sin repetir. Ordénalos para anunciarlos y desactiva la ordenación para recuperar el orden del sorteo. El CSV conserva la posición original.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/random-number-generator/#example-ticket-draw>)





## Pruébalo

[Abrir herramienta completa · Generador de números aleatorios](<https://toolpony.com/es/tools/random-number-generator/>)





## Método de cálculo



Los números aleatorios proceden de Web Crypto. El muestreo por rechazo evita el sesgo de módulo. Genera hasta 1.000 enteros entre −1.000.000.000 y 1.000.000.000.





**Fuentes del método** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Frandom-number-generator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/random-number-generator/)
