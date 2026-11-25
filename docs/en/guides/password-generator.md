# Password generator guide



Generate passwords locally with character sets, custom exclusions and optional unique characters.





## Example



### Input



```
20 characters, four character groups
```



### Expected result



```
A fresh random password
```





<a id="case-study"></a>



## Test codes for manual entry



1. Generate six 16-character codes using uppercase letters and digits. Exclude 2Z5S8B to remove three more pairs that look similar in print.
2. Each row uses both groups with no repeated character. Copy one row to test a form. Opening the example again generates new values on your device.



[Run example](<https://toolpony.com/en/tools/password-generator/#example-readable-codes>)





## Try it

[Open full tool · Password generator](<https://toolpony.com/en/tools/password-generator/>)





## Calculation method



Web Crypto supplies randomness. When required groups are enabled, one character is selected from each group, then positions are shuffled. Passwords live in the current page until you leave or clear it.





**Method references** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fpassword-generator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/password-generator/)
