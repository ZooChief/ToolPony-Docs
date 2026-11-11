# Formatador JSON



Colar JSON, escolher uma indentação, e formatar ou minimizá-lo. Copie o resultado ou baixe um arquivo JSON. Cmd/Ctrl + Enter executa o formatador.





## Primeiros passos



1. Colar um documento da JSON.
2. Escolha dois ou quatro espaços, em seguida, formato; use Minify para um resultado compacto.
3. Copie o resultado ou baixe o arquivo JSON.







## Exemplo



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







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/json-formatter/>)







## Notas de uso



Chaves e cadeias de caracteres precisam de aspas duplas. Os comentários e as vírgulas não são JSON. Os números fora da precisão segura são rejeitados para evitar alterar silenciosamente os seus valores.







## Limites



Até 1 MB. JSON inválido e precisão numérica insegura são rejeitados. A formatação não se valida contra um esquema de aplicação.

[Documentação](https://docs.toolpony.com/pt-br/guides/json-formatter/)
