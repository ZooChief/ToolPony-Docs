# Calculadora de subredes IP



Inspeccione redes IPv4 e IPv6, máscaras, rangos y conteos de direcciones, o pruebe si una IP pertenece a un bloque CIDR.





## Primeros pasos



1. Usa el ejemplo o introduce tus propios valores.
2. Calcula, copia el resultado o descarga los detalles disponibles.







## Ejemplo



### Entrada



```
192.0.2.129 /27
```



### Resultado esperado



```
Red 192.0.2.128/27, 30 hosts utilizables
```







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/ip-subnet-calculator/>)







## Notas de uso



El cálculo se ejecuta en tu navegador. Usa unidades coherentes.







## Método de cálculo



Y la dirección con una máscara de prefijo para encontrar la primera dirección. La parte de host tiene 2^ (provistos de dirección − prefijo) posibilidades. IPv4 /31 utiliza el host legado contando por defecto, con una opción RFC 3021 punto a punto. Un prefijo de CIDR inline tiene precedencia.



$$
\text{Addresses}=2^{w-p},\qquad w\in\{32,128\}
$$



IPv4 acepta una longitud de prefijo o una máscara contigua. Por ejemplo, 192.0.2.129 con 255.255.255.224 da la misma red que 192.0.2.129/27.



La categoría de tamaño prefijo sigue la convención A/B/C de la herramienta de comparación. La clase de dirección histórica aparece por separado. Utilice el rango de dirección para la membresía CIDR. El ajuste de punto a punto opcional cambia /31 host sólo contando.







## Modo de cálculo



**IPv4**

- Dirección IPv4 o CIDR
- Máscara de prefijo o subnet
- Use ambas direcciones en /31 enlaces punto a punto





**IPv6**

- Dirección IPv6 o CIDR
- Prefijo





**Composición de la dirección de verificación**

- Red de CIDR
- Dirección para comprobar

[Documentación](https://docs.toolpony.com/es/guides/ip-subnet-calculator/)
