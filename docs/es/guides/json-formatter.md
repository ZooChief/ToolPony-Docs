# Formateador JSON



Pruebe JSON, elija una indentación, y formato o la menifique. Copia el resultado o descarga un archivo JSON. Cmd/Ctrl + Enter ejecuta el formatter.





## Primeros pasos



1. Pruebe un documento JSON.
2. Elija dos o cuatro espacios, luego formato; use Minify para un resultado compacto.
3. Copia el resultado o descarga el archivo JSON.







## Ejemplo



### Entrada



```
{"name":"ToolPony","ready":true}
```



### Resultado esperado



```
{
  "name": "ToolPony",
  "ready": true
}
```







## Pruébalo



[Abrir herramienta completa](<https://toolpony.com/es/tools/json-formatter/>)







## Notas de uso



Las claves y las cuerdas necesitan citas dobles. Los comentarios y las comas que siguen no son JSON. Los números fuera de la precisión segura son rechazados para evitar cambiar silenciosamente sus valores.







## Límites



Hasta 1 MB. Se rechazan el JSON no válido y los números que no pueden representarse con precisión. El formateo no valida un esquema de aplicación.

[Documentación](https://docs.toolpony.com/es/guides/json-formatter/)
