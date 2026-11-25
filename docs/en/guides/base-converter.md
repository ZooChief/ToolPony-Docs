# Base converter and calculator guide



Convert signed integers between bases 2–36 and perform exact arithmetic, remainder or bitwise operations.





## Example



### Input



```
FF, base 16 to base 10
```



### Expected result



```
255
```





<a id="case-study"></a>



## Read a large hexadecimal ID



1. Convert 0x20\_0000\_0000\_0001 to decimal. The final 1 survives in 9007199254740993. Switch back to hexadecimal or copy the grouped binary row as unbroken digits.



[Run example](<https://toolpony.com/en/tools/base-converter/#example-large-hex-id>)





## Try it

[Open full tool · Base converter and calculator](<https://toolpony.com/en/tools/base-converter/>)





## Calculation method



BigInt preserves every digit. Base conversion accepts integers up to 4,096 bits. Arithmetic accepts 256 digits per operand and division truncates toward zero. Spaces or underscores may separate digits.







## Calculation mode





### Convert base



- Integer
- Input base
- Output base
- Minimum output digits







### Integer arithmetic



- First integer
- Second integer
- Input base
- Output base
- Minimum output digits
- Operation · Add / Subtract / Multiply / Divide / Remainder / AND / OR / XOR







[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fbase-converter%2F>)

[Documentation](https://docs.toolpony.com/en/guides/base-converter/)
