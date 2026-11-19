# Converter PDF em texto



Extraia o texto selecionável das páginas de PDF em TXT ou JSON no seu dispositivo.





## Primeiros passos



1. Abra um PDF com texto selecionável.
2. Indique a ordem das páginas e extraia o texto. Salve em TXT ou JSON com os números das páginas originais.







## Exemplo



### Entrada



```
PDF com “One” e “Two” nas primeiras duas páginas, seleção 2, 1
```

[Exemplo · PDF](<https://toolpony.com/samples/toolpony-pages.pdf>)

### Resultado esperado



```
JSON com a página 2 “Two”, seguida da página 1 “One”
```







## Experimente

[Abrir ferramenta completa · Converter PDF em texto](<https://toolpony.com/pt-br/tools/pdf-to-text/>)





## Limites



Até 30 MB, 300 páginas, dois milhões de caracteres e 200.000 segmentos. A ordem do texto segue o PDF. Páginas digitalizadas exigem OCR. PDFs criptografados são recusados.



Se um documento digitalizado estiver legível mas não retornar texto, tente selecionar uma palavra em um leitor de PDF. Uma página fotografada precisa primeiro de uma camada de texto criada por OCR. Em um documento misto, o JSON indica o campo text vazio e o respectivo número da página original.

[Documentação](https://docs.toolpony.com/pt-br/guides/pdf-to-text/)
