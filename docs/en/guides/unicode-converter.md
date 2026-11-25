# Unicode converter guide



Convert code points, UTF-8 bytes and JavaScript escapes. Inspect characters and compare Unicode normalization forms.





## Example



### Input



```
🐴
```



### Expected result



```
U+1F434 or F0 9F 90 B4
```





<a id="case-study"></a>



## Compare two spellings of é



1. Inspect e followed by U+0301, a space and 🐴. The original has 3 grapheme clusters, 4 code points, 5 UTF-16 code units and 8 UTF-8 bytes. Select NFC. The accent combines into U+00E9 and the UTF-8 length falls to 7 bytes. The horse stays one code point and two UTF-16 units.



[Run example](<https://toolpony.com/en/tools/unicode-converter/#example-combining-accent>)





## Try it

[Open full tool · Unicode converter](<https://toolpony.com/en/tools/unicode-converter/>)





## Calculation method



Code-point mode treats a supplementary character as one scalar. UTF-16 uses two code units for such a character. Invalid surrogate sequences and invalid UTF-8 bytes are rejected.







## Calculation mode





### Encode text



- Input
- Encoding · Unicode code points / UTF-8 hexadecimal bytes / JavaScript UTF-16 escapes / JavaScript code point escapes







### Decode text



- Input
- Encoding · Unicode code points / UTF-8 hexadecimal bytes / JavaScript UTF-16 escapes / JavaScript code point escapes







### Inspect characters



- Input
- Normalization · Original / NFC / NFD / NFKC / NFKD







**Method references** [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>) · [Unicode · UAX \#15](<https://www.unicode.org/reports/tr15/>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Funicode-converter%2F>)

[Documentation](https://docs.toolpony.com/en/guides/unicode-converter/)
