# Unicode converter



Convert text to Unicode code points, UTF-8 hexadecimal bytes or UTF-16 escapes, and decode them back to text.





## Example



### Input



```
🐴
```



### Expected result



```
U+1F434 or F0 9F 90 B4
```







## Try it

[Open full tool · Unicode converter](<https://toolpony.com/en/tools/unicode-converter/>)





## Calculation method



Code-point mode treats a supplementary character as one scalar. UTF-16 uses two code units for such a character. Invalid surrogate sequences and invalid UTF-8 bytes are rejected.







## Calculation mode



**Encode text**

- Input
- Encoding · Unicode code points / UTF-8 hexadecimal bytes / JavaScript UTF-16 escapes





**Decode text**

- Input
- Encoding · Unicode code points / UTF-8 hexadecimal bytes / JavaScript UTF-16 escapes







[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Funicode-converter%2F>)

[Documentation](https://docs.toolpony.com/en/guides/unicode-converter/)
