# Dice roller guide



Roll one or more dice with custom sides, compare totals and see each roll.





## Example



### Input



```
3 dice, 6 sides
```



### Expected result



```
Three faces and their sum
```





<a id="case-study"></a>



## Reach ten with two dice



1. Set two six-sided dice and a target of 10. Six of the 36 ordered outcomes meet the target (16.67%). Change the modifier to +1. The same faces are kept, and ten outcomes now qualify (27.78%).



[Run example](<https://toolpony.com/en/tools/dice-roller/#example-two-dice>)





## Try it

[Open full tool · Dice roller](<https://toolpony.com/en/tools/dice-roller/>)





## Calculation method



Each die uses an independent uniform Web Crypto draw. Roll up to 100 dice, with 2 to 1,000 sides each.





**Method references** [W3C · Web Cryptography](<https://www.w3.org/TR/WebCryptoAPI/#Crypto-method-getRandomValues>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fdice-roller%2F>)

[Documentation](https://docs.toolpony.com/en/guides/dice-roller/)
