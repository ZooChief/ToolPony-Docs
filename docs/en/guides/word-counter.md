# Word counter



Paste text or import text, DOCX, ODT, PDF, SRT or WebVTT. Caption files are counted by dialogue. Compare word counts and the frequency of one- to three-word terms, then export CSV.





## Get started



1. Enter text or import a plain-text file, DOCX, ODT or a PDF with selectable text.
2. Import SRT or WebVTT to count dialogue without timestamps or markup.
3. Choose one-, two- or three-word terms under Frequent words. Download statistics and the displayed frequency list as CSV.







## Example



### Input



```
Blue sky blue sky
```



### Expected result



```
4 words, 2 unique words
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/word-counter/>)







## Good to know



The text limit is 1 MiB in UTF-8. Character counts use Unicode code points. Phrases stop at punctuation and line breaks. Density uses all counted terms of the same length.







## Limits



Up to 1 MiB of UTF-8 text. Segmentation follows the browser’s language rules. PDF imports use the text layer. DOCX and ODT use the main body. Phrase density divides a term’s count by all terms of the selected length.

[Documentation](https://docs.toolpony.com/en/guides/word-counter/)
