# Guía de uso · Conversor y calculadora de bases



Convertir números enteros firmados entre las bases 2–36 y realizar operaciones aritméticas exactas, continuas o bitwise.





## Ejemplo



### Entrada



```
FF, base 16 a base 10
```



### Resultado esperado



```
255
```





<a id="case-study"></a>



## Leer un identificador hexadecimal largo



1. Convierte 0x20\_0000\_0000\_0001 a decimal. El último 1 se conserva en 9007199254740993. Intercambia las bases o copia la fila binaria sin espacios.



[Ejecutar ejemplo](<https://toolpony.com/es/tools/base-converter/#example-large-hex-id>)





## Pruébalo

[Abrir herramienta completa · Conversor y calculadora de bases](<https://toolpony.com/es/tools/base-converter/>)





## Método de cálculo



BigInt conserva todos los dígitos. La conversión admite hasta 4096 bits y las operaciones admiten 256 dígitos por operando. La división entera trunca hacia cero. Puedes separar los dígitos con espacios o guiones bajos.







## Modo de cálculo





### Convertir base



- Entero
- Base de entrada
- Base de producción
- Dígitos mínimos de salida







### Integer aritmética



- Primer entero
- Segundo entero
- Base de entrada
- Base de producción
- Dígitos mínimos de salida
- Operación · Añadir / Subtract / Multiply / Divide / Resto / AND / OR / XOR







[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fbase-converter%2F>)

[Documentación](https://docs.toolpony.com/es/guides/base-converter/)
