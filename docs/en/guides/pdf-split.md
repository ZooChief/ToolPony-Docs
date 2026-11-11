# Split PDF



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



### Expected result



```
One PDF containing pages 5, 1, 2, 3 in that order.
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/pdf-split/>)







## Good to know



A fixed count of 2 splits the example into \[5, 1\] and \[2, 3\]. The size cap measures each generated PDF in decimal kB or MB. Pages are copied without recompression; increase the cap if one page exceeds it.







## Limits



30 MB and 300 pages. PDFs in a ZIP are limited to 64 MB combined. Size grouping uses the written PDF bytes without recompression. Raise the cap if a single page exceeds it. Page numbers cannot repeat. Encrypted PDFs are rejected. Forms, bookmarks and signatures may be lost.

[Documentation](https://docs.toolpony.com/en/guides/pdf-split/)
