# Percentage calculator guide



Find a percentage, compare rates in percentage points, or apply and reverse two successive discounts.





## Get started



1. For a part such as 15% of 240, choose Percentage of a value. If the part is 36 and you know the total or the rate, choose the corresponding inverse mode.
2. Choose Percentage change for an ordered old and new value. Use Percentage difference for two positive values with no baseline.
3. Enter 15 for 15%. Compare the result against the worked examples below.







## Example



### Input



```
15% of 240
```



### Expected result



```
36
```





<a id="case-study"></a>



## Two discounts on one price



1. Start at 250. Reducing by 20% gives 200. The next 10% applies to 200, so the price becomes 180. The overall reduction is 28%. Reverse the calculation to recover the starting price.



[Run example](<https://toolpony.com/en/tools/percentage-calculator/#example-two-discounts>)





## From a 4% rate to 5%



A signup rate rises from 4% to 5%. The change is one percentage point. Compared with the original 4%, the relative increase is 1 ÷ 4 = 25%.



[Run example](<https://toolpony.com/en/tools/percentage-calculator/#example-percentage-points>)







## Try it

[Open full tool · Percentage calculator](<https://toolpony.com/en/tools/percentage-calculator/>)





## Calculation method



Relative change divides the difference by the magnitude of the original value. For two rates, their subtraction gives the percentage-point change. Successive changes multiply their factors. Symmetric difference uses the mean magnitude of the two inputs.



$$
x=yp/100,\quad p=100x/y,\quad y=100x/p
$$



$$
\Delta\%=100\frac{x_1-x_0}{|x_0|},\quad D\%=200\frac{|x_1-x_0|}{|x_1|+|x_0|}
$$



80 → 100 is a 25% change because 80 is the starting value. The percentage difference between the same numbers is about 22.22% because the denominator is their mean, 90.



After a 20% increase to 120, Reverse a change gives 100. A change of −100% cannot be reversed. Change from a zero baseline has no percentage result.



For a measured value of 90 and reference of 96, absolute percent error is 6.25%. The signed result with that positive reference is −6.25%.







## Calculation mode





### Percentage of a value



- Percentage · %
- Value







### Find the percentage



- Part
- Whole







### Find the whole



- Part
- Percentage · %







### Percentage change



- Values represent · Amounts / Rates (%)
- Original value
- New value







### Percentage difference



- First value
- Second value







### Difference with signed values



- First value
- Second value







### Apply a change



- Original value
- Signed change · %
- Second change · %







### Reverse a change



- New value
- Signed change · %
- Second change · %







### Percent error



- Measured value
- Reference value
- Error convention · Absolute / Signed relative to reference







**Method references** [Eurostat · Percentage point](<https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Glossary:Percentage_point>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fpercentage-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/percentage-calculator/)
