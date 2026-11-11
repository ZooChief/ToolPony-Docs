# Conversor de legendas



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



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/subtitle-converter/>)







## Limites



Até 1 MiB e 10.000 legendas. Legendas que terminam antes de zero são removidas e as que cruzam zero começam nele. SRT não comporta todas as posições, estilos e identificadores do WebVTT.

[Documentação](https://docs.toolpony.com/pt-br/guides/subtitle-converter/)
