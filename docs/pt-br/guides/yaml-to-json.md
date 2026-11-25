# Guia de uso · YAML para JSON



Colar um documento YAML e convertê-lo para JSON. Mappings deve usar as teclas de string; saída é formatada e pronto para copiar ou baixar.





## Primeiros passos



1. Colar um documento YAML com teclas de mapeamento de strings.
2. Converte-te para JSON.
3. Inspecione, copie ou baixe o resultado.







## Exemplo



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







## Experimente

[Abrir ferramenta completa · YAML para JSON](<https://toolpony.com/pt-br/tools/yaml-to-json/>)





## Notas de uso



Vários documentos, etiquetas personalizadas, aliases cíclicos e valores que o JSON não pode representar são rejeitados. Citar um valor se você quiser dizer uma string em vez de um booleano ou número.







## Limites



Até 1 MB. Marcas personalizadas, vários documentos, chaves não- string, pseudônimos excessivos, estruturas cíclicas e valores que o JSON não pode preservar são rejeitados.





**Referências do método** [YAML 1.2.2](<https://yaml.org/spec/1.2.2/>) · [IETF · RFC 8259 (JSON)](<https://www.rfc-editor.org/rfc/rfc8259>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fyaml-to-json%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/yaml-to-json/)
