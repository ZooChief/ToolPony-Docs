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





<a id="case-study"></a>



## Localizar a página sem texto em um PDF misto



1. O PDF de exemplo traz “Order 417” na página 1, somente uma imagem azul na página 2 e “Total 42” na página 3. No modo completo, o botão de PDF misto carrega o arquivo, seleciona 3, 2, 1 e define a saída JSON.
2. Ao extrair, o primeiro registro contém “Total 42” da página 3, o segundo mantém a página 2 com o campo text vazio e o último mostra “Order 417” da página 1. A página sem texto também é indicada pelo número original 2.
3. Antes de importar o texto em outro sistema, confira as páginas indicadas. Um diagrama pode ser salvo como imagem. Em uma página digitalizada com palavras impressas, use OCR para criar uma camada de texto.



[Converter PDF em JPG ou PNG](<https://toolpony.com/pt-br/tools/pdf-to-jpg/>)



[toolpony-mixed-pages.pdf](<https://toolpony.com/samples/toolpony-mixed-pages.pdf>)





## Experimente

[Abrir ferramenta completa · Converter PDF em texto](<https://toolpony.com/pt-br/tools/pdf-to-text/>)





## Limites



Até 30 MB, 300 páginas, dois milhões de caracteres e 200.000 segmentos. A ordem do texto segue o PDF. Páginas digitalizadas exigem OCR. PDFs criptografados são recusados.



Se um documento digitalizado estiver legível mas não retornar texto, tente selecionar uma palavra em um leitor de PDF. Uma página fotografada precisa primeiro de uma camada de texto criada por OCR. Em um documento misto, o JSON indica o campo text vazio e o respectivo número da página original.





**Referências do método** [PDF Association · ISO 32000-2](<https://pdfa.org/resource/iso-32000-2/>) · [Adobe · PDF / OCR](<https://helpx.adobe.com/acrobat/desktop/create-documents/scan-documents-to-pdfs/recognize-text.html>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fpdf-to-text%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/pdf-to-text/)
