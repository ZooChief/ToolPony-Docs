# Rounding calculator



Round exact decimals by decimal place or a binary fraction with nine rounding modes.





## Get started



1. Use the example values or enter your own measurements.
2. Calculate, then copy the result or download the available details.







## Example



### Input



```
−2.5, ones, half to even
```



### Expected result



```
−2
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/rounding-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



Compare the exact decimal remainder with half a step. For ties, select a direction or parity rule. Nearest uses ties away from zero.



$$
x=qs+r,\qquad 0\le r<s,\qquad r=\tfrac{s}{2}\text{ at a tie}
$$



A place of 2 rounds to hundredths, 0 rounds to units, and −2 rounds to hundreds. A fractional step rounds to a multiple such as 1/4 or 1/16.



Half-to-even chooses the even multiple only at an exact tie. For example, −2.5 goes to −2 and −3.5 goes to −4. Ceiling always moves toward positive infinity.

[Documentation](https://docs.toolpony.com/en/guides/rounding-calculator/)
