# Long division calculator guide



Divide integers or decimals and inspect the quotient, remainder, decimal value, and each long-division step.





## Example



### Input



```
12,345 ÷ 67
```



### Expected result



```
184 remainder 17
```







## Try it

[Open full tool · Long division calculator](<https://toolpony.com/en/tools/long-division-calculator/>)





## Calculation method



Scale both inputs by the same power of ten. The integer quotient truncates toward zero, and the signed remainder satisfies dividend = quotient × divisor + remainder. The step table uses absolute magnitudes.



$$
a=bq+r,\quad q=\operatorname{trunc}(a/b),\quad |r|<|b|
$$





[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Flong-division-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/long-division-calculator/)
