# YAML a JSON



Pruebe un documento YAML y conviértelo a JSON. Las capturas deben usar las teclas de cadena; la salida se formatea y está lista para copiar o descargar.





## Primeros pasos



1. Pruebe un documento YAML con claves de mapeo de cadenas.
2. Convertirse en JSON.
3. Inspeccionar, copiar o descargar el resultado.







## Ejemplo



### Entrada



```
name: ToolPony
ready: true
```



### Resultado esperado



```
{
  "name": "ToolPony",
  "ready": true
}
```







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/yaml-to-json/>)







## Notas de uso



Múltiples documentos, etiquetas personalizadas, alias cíclicos y valores que JSON no puede representar son rechazados. Cita un valor si se refiere a una cadena en lugar de un booleano o número.







## Límites



Hasta 1 MB. Se rechazan las etiquetas personalizadas, múltiples documentos, claves no pendientes, alias excesivos, estructuras cíclicas y valores que JSON no puede preservar.

[Documentación](https://docs.toolpony.com/es/guides/yaml-to-json/)
