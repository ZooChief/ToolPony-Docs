# Guia de uso · Conversor de legendas



Converta SRT e WebVTT, desloque ou ajuste os tempos e confira sobreposições.





## Primeiros passos



1. Cole o texto ou importe SRT ou VTT e escolha o formato de saída.
2. Um deslocamento positivo atrasa as legendas. Multiplique o tempo relativo ao ponto de referência pela escala e some o deslocamento. Confira cortes e sobreposições.







## Exemplo



### Entrada



```
1
00:00:00,120 --> 00:00:01,400
A line
Second line

2
00:00:01,350 --> 00:00:02,700
Overlap 50 ms
```



### Resultado esperado



```
WEBVTT

00:00:00.120 --> 00:00:01.400
A line
Second line

00:00:01.350 --> 00:00:02.700
Overlap 50 ms
```







## Experimente

[Abrir ferramenta completa · Conversor de legendas](<https://toolpony.com/pt-br/tools/subtitle-converter/>)





## Limites



Até 1 MiB e 10.000 legendas. Legendas que terminam antes de zero são removidas e as que cruzam zero começam nele. SRT não comporta todas as posições, estilos e identificadores do WebVTT.





**Referências do método** [W3C · WebVTT](<https://www.w3.org/TR/webvtt1/>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fsubtitle-converter%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/subtitle-converter/)
