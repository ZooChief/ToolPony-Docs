# Guia de uso · Converter imagens



Adicione imagens de diferentes formatos. O formato é detectado pelo conteúdo do arquivo. Configure formato, qualidade e fundo por imagem. Baixe arquivos individuais ou um ZIP.





## Primeiros passos



1. Adicione imagens de diferentes formatos. O formato é detectado pelo conteúdo do arquivo.
2. Configure formato, qualidade e fundo por imagem. Baixe arquivos individuais ou um ZIP.







## Exemplo



### Entrada



```
PNG · 64 × 32 px (cantos transparentes) → JPEG · fundo branco
```

[Exemplo · PNG](<https://toolpony.com/samples/toolpony-64x32.png>)

### Resultado esperado



```
JPEG · 64 × 32 px (cantos brancos)
```





<a id="case-study"></a>



## Conferir o fundo de um PNG transparente antes de enviar em JPEG



1. No conversor vazio, escolha “Testar arquivos de exemplo”. Ele carrega um PNG transparente e um JPEG opaco, ambos com 64 × 32 px. As saídas são JPEG para o primeiro e PNG para o segundo.
2. Compare o original e o resultado lado a lado. Selecione uma imagem para vê-la no tamanho real. Os cantos do primeiro JPEG ficam brancos. Os do PNG gerado a partir do JPEG continuam opacos, pois os pixels brancos já faziam parte da imagem. Para manter a transparência original, exporte o primeiro arquivo em PNG com fundo transparente.
3. Em um banner longo, confira as dimensões de saída na linha do arquivo. Uma imagem de 10.000 × 100 px fica com 8.192 × 82 px após a redução proporcional. O ajuste de qualidade afeta apenas a codificação.
4. Para conferir o pixel, abra o JPEG de exemplo no seletor de cores e examine (0, 0). No Chromium o valor decodificado foi RGBA (255, 255, 243, 255). O PNG exportado desse JPEG conserva os valores, inclusive o alfa 255 de opacidade total.



[Seletor de cores da imagem](<https://toolpony.com/pt-br/tools/image-color-picker/>)





## Experimente

[Abrir ferramenta completa · Converter imagens](<https://toolpony.com/pt-br/tools/image-converter/#example-mixed-images>)





## Limites



Até 20 MB, 24 megapixels e 8.192 pixels por lado na saída. A leitura de AVIF depende do navegador. Animações viram imagens estáticas e os metadados originais são removidos. Até 12 imagens e 64 MiB no total por lote.



Escolha PNG para manter a transparência e JPEG para fotos e compatibilidade. O JPEG preenche áreas transparentes com o fundo escolhido. O WebP admite transparência e qualidade ajustável. O AVIF aparece quando o navegador pode codificá-lo.



Por exemplo, um logotipo WebP transparente pode virar um PNG transparente. Para um formulário que só aceita JPEG, você pode escolher um fundo branco. Um JPEG convertido em PNG conserva os detalhes visíveis da imagem.





**Referências do método** [W3C · PNG](<https://www.w3.org/TR/png-3/>) · [WHATWG · HTML Canvas](<https://html.spec.whatwg.org/multipage/canvas.html#dom-canvas-toblob-dev>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fimage-converter%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/image-converter/)
