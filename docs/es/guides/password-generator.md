# Guía de uso · Generador de contraseñas



Generar contraseñas localmente con conjuntos de caracteres, exclusiones personalizadas y caracteres opcionales únicos.





## Ejemplo



### Entrada



```
20 caracteres, cuatro grupos de caracteres
```



### Resultado esperado



```
Una contraseña aleatoria fresca
```





<a id="case-study"></a>



## Códigos de prueba para copiar a mano



1. Genera seis códigos de 16 caracteres con mayúsculas y cifras. Excluye 2Z5S8B para evitar tres pares difíciles de distinguir en papel.
2. Cada fila contiene ambos grupos, sin caracteres repetidos. Copia una fila en el formulario de prueba. Volver a abrir el ejemplo genera valores nuevos en tu dispositivo.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/password-generator/#example-readable-codes>)





## Pruébalo

[Abrir herramienta completa · Generador de contraseñas](<https://toolpony.com/es/tools/password-generator/>)





## Método de cálculo



Web Crypto proporciona aleatoriedad. Cuando los grupos requeridos están habilitados, se selecciona un personaje de cada grupo, luego las posiciones se encogen. Las contraseñas viven en la página actual hasta que se vaya o se despeje.





**Fuentes del método** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fpassword-generator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/password-generator/)
