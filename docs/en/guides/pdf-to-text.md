# PDF to text guide



Select pages, then copy the text or download TXT or page-numbered JSON.





## Get started



1. Open a PDF with selectable text.
2. Select and order the pages, then extract the text.
3. Copy the result or download TXT or JSON. JSON keeps the source page numbers.







## Example



### Input



```
Mixed PDF, JSON output, pages 3, 2, 1. Page 2 contains only a blue swatch.
```

[Example · PDF](<https://toolpony.com/samples/toolpony-mixed-pages.pdf>)

### Expected result



```
[{"page":3,"text":"Total 42"},{"page":2,"text":""},{"page":1,"text":"Order 417"}]
```





<a id="case-study"></a>



## Find the missing text page in a mixed PDF



1. Open the mixed sample PDF. Its first page says “Order 417”, the second contains only a picture of a blue swatch, and the last says “Total 42”. On the full tool, “Try a mixed PDF” loads the file, selects 3, 2, 1 and sets JSON output.
2. Extract the text. The first record is page 3 with “Total 42”, the middle record is page 2 with an empty text field, and the last is page 1 with “Order 417”. The result identifies page 2 by its original number.
3. Use this check on your own file before importing its text elsewhere. Inspect any pages listed. A diagram can be kept as an image. A scan of printed words needs OCR to create a text layer.



[PDF to JPG or PNG](<https://toolpony.com/en/tools/pdf-to-jpg/>)



[toolpony-mixed-pages.pdf](<https://toolpony.com/samples/toolpony-mixed-pages.pdf>)





## Try it

[Open full tool · PDF to text](<https://toolpony.com/en/tools/pdf-to-text/#example-mixed-pdf>)





## Good to know



TXT uses a form feed between pages. Extraction follows the document’s text order; multi-column layouts may read differently. Scanned pages require OCR. For up to eight pages, clear the selection and tap the page numbers in the order you want. Longer documents also have odd and even page shortcuts.







## Limits



Up to 30 MB, 300 pages, two million characters and 200,000 text runs. Extraction follows the PDF text order. Scanned pages require OCR. Password-protected files are rejected.



If a scan looks readable but extraction finds no text, try selecting a single word in a PDF reader. A photographed page needs a text layer from OCR first. In a mixed document, export JSON to locate pages with an empty text field by their original page number.





**Method references** [PDF Association · ISO 32000-2](<https://pdfa.org/resource/iso-32000-2/>) · [Adobe · PDF / OCR](<https://helpx.adobe.com/acrobat/desktop/create-documents/scan-documents-to-pdfs/recognize-text.html>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fpdf-to-text%2F>)

[Documentation](https://docs.toolpony.com/en/guides/pdf-to-text/)
