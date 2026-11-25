# Guía de uso · Formateador JSON



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

[Abrir herramienta completa · Formateador JSON](<https://toolpony.com/es/tools/json-formatter/>)





## Notas de uso



Las claves y las cuerdas necesitan citas dobles. Los comentarios y las comas que siguen no son JSON. Los números fuera de la precisión segura son rechazados para evitar cambiar silenciosamente sus valores.







## Límites



Hasta 1 MB. Se rechazan el JSON no válido y los números que no pueden representarse con precisión. El formateo no valida un esquema de aplicación.





**Fuentes del método** [IETF · RFC 8259 (JSON)](<https://www.rfc-editor.org/rfc/rfc8259>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fjson-formatter%2F>)

[Documentación](https://docs.toolpony.com/es/guides/json-formatter/)
