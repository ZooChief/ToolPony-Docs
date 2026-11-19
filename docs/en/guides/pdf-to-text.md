# PDF to text



Select pages, then copy the text or download TXT or page-numbered JSON.





## Get started



1. Open a PDF with selectable text.
2. Select and order the pages, then extract the text.
3. Copy the result or download TXT or JSON. JSON keeps the source page numbers.







## Example



### Input



```
A PDF whose first two pages read One and Two. Select 2, 1 and JSON.
```

[Example · PDF](<https://toolpony.com/samples/toolpony-pages.pdf>)

### Expected result



```
[{"page":2,"text":"Two"},{"page":1,"text":"One"}]
```







## Try it

[Open full tool · PDF to text](<https://toolpony.com/en/tools/pdf-to-text/>)





## Good to know



TXT uses a form feed between pages. Extraction follows the document’s text order; multi-column layouts may read differently. Scanned pages require OCR.







## Limits



Up to 30 MB, 300 pages, two million characters and 200,000 text runs. Extraction follows the PDF text order. Scanned pages require OCR. Password-protected files are rejected.



If a scan looks readable but extraction finds no text, try selecting a single word in a PDF reader. A photographed page needs a text layer from OCR first. In a mixed document, export JSON to locate pages with an empty text field by their original page number.

[Documentation](https://docs.toolpony.com/en/guides/pdf-to-text/)
