# Guía de uso · Generador de direcciones ficticias



Genera direcciones de prueba para 18 países y territorios, con subdivisiones, formato local y exportación por lotes.





## Primeros pasos



1. Elige el país y la región, indica la cantidad y decide si incluir datos de contacto.
2. Repite la semilla y los ajustes para reproducir un lote. Copia campos o exporta TXT, CSV o JSON.
3. Las direcciones guardadas se conservan en este navegador. Puedes eliminarlas desde la herramienta.







## Ejemplo



### Entrada



```
Alemania · Berlín · Semilla pony-demo
```



### Resultado esperado



```
Testperson 001
Beispielstraße 4957
10115 Berlin
Deutschland
```





<a id="case-study"></a>



## Comprobar una dirección canadiense con unidad



1. Con la semilla label-review, genera dos direcciones de prueba de Ontario con unidad y sin datos de contacto. Los mismos ajustes reproducen el mismo par.
2. En el texto, la unidad precede al número del edificio y se separa con un guion. En la línea de la ciudad, ON va seguido de dos espacios y el código postal. El JSON incluye además los campos por separado.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/sample-address-generator/#example-canadian-label>)





## Pruébalo

[Abrir herramienta completa · Generador de direcciones ficticias](<https://toolpony.com/es/tools/sample-address-generator/>)





## Método de cálculo



Hasta 100 ejemplos por lote. La localidad y el código postal ilustran el formato. La calle y el destinatario son sintéticos. El teléfono usa números reservados o máscaras. Para pruebas de formularios y software.





**Fuentes del método** [USPS · Publication 28, §213](<https://pe.usps.com/text/pub28/28c2_003.htm>) · [Canada Post · Civic address](<https://www.canadapost-postescanada.ca/cpc/en/support/articles/addressing-guidelines/civic-address.page>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fsample-address-generator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/sample-address-generator/)
