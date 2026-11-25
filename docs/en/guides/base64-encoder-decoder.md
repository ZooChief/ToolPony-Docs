# Base64 encode and decode guide



Encode UTF-8 text or hex bytes as Base64 or Base64url, inspect decoded bytes and save a binary file.





## Example



### Input



```
Encode hello
```



### Expected result



```
aGVsbG8=
```





<a id="case-study"></a>



## Recover bytes from Base64url



1. Choose Decode, URL-safe and Hex bytes. Paste \_wCA7w. It contains FF 00 80 EF, including a zero byte and values that cannot form UTF-8 text. Download bytes to keep exactly those four bytes.



[Run example](<https://toolpony.com/en/tools/base64-encoder-decoder/#example-binary-bytes>)





## Try it

[Open full tool · Base64 encode and decode](<https://toolpony.com/en/tools/base64-encoder-decoder/>)





## Calculation method



Standard Base64 uses + and /. Base64url uses - and \_ and omits output padding. Text mode preserves a leading U+FEFF and validates UTF-8. Text input accepts 500,000 UTF-16 code units and binary input accepts 500,000 bytes.





**Method references** [IETF · RFC 4648 (Base64)](<https://www.rfc-editor.org/rfc/rfc4648>) · [IETF · RFC 3629](<https://www.rfc-editor.org/rfc/rfc3629>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fbase64-encoder-decoder%2F>)

[Documentation](https://docs.toolpony.com/en/guides/base64-encoder-decoder/)
