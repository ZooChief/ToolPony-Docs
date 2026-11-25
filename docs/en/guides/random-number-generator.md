# Random number generator guide



Generate random integers in an inclusive range, with optional uniqueness and sorting.





## Example



### Input



```
Min 1, max 10, count 5
```



### Expected result



```
Five random integers from 1 through 10
```





<a id="case-study"></a>



## Draw four tickets



1. Number 12 tickets from 101 to 112. Draw four with unique values enabled. Sort the result to read out the numbers, then switch sorting off to see the original draw order. The CSV records the original position of each ticket.



[Run example](<https://toolpony.com/en/tools/random-number-generator/#example-ticket-draw>)





## Try it

[Open full tool · Random number generator](<https://toolpony.com/en/tools/random-number-generator/>)





## Calculation method



Random values come from Web Crypto. Rejection sampling avoids modulo bias. Generate up to 1,000 values in the range −1,000,000,000 to 1,000,000,000.





**Method references** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Frandom-number-generator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/random-number-generator/)
