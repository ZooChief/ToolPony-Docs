# Split PDF guide



Choose pages visually or enter ranges such as 1-3, 5. Save one PDF or group by range, page, page count or file size. Output follows the selected order.





## Get started



1. Choose an unlocked PDF.
2. Select thumbnails or enter page numbers and ranges such as 1-3, 5. Each range ascends and pages cannot repeat.
3. Choose a single PDF or group the selection by range, page, fixed page count or maximum file size. Download the PDF or ZIP.







## Example



### Input



```
A 5-page PDF; selection: 5, 1-3
```

[Example · PDF](<https://toolpony.com/samples/toolpony-pages.pdf>)

### Expected result



```
One PDF containing pages 5, 1, 2, 3 in that order.
```







## Try it

[Open full tool · Split PDF](<https://toolpony.com/en/tools/pdf-split/>)





## Good to know



A fixed count of 2 splits the example into \[5, 1\] and \[2, 3\]. The size cap measures each generated PDF in decimal kB or MB. Pages are copied without recompression; increase the cap if one page exceeds it. For up to eight pages, clear the selection and tap the page numbers in the order you want. Longer documents also have odd and even page shortcuts.







## Limits



30 MB and 300 pages. PDFs in a ZIP are limited to 64 MB combined. Size grouping uses the written PDF bytes without recompression. Raise the cap if a single page exceeds it. Page numbers cannot repeat. Encrypted PDFs are rejected. Forms, bookmarks and signatures may be lost.





**Method references** [PDF Association · ISO 32000-2](<https://pdfa.org/resource/iso-32000-2/>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fpdf-split%2F>)

[Documentation](https://docs.toolpony.com/en/guides/pdf-split/)
