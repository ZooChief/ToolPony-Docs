# Sample size calculator



Find a minimum survey sample or estimate the margin of error with finite-population correction.





## Get started



1. Use the example values or enter your own measurements.
2. Calculate, then copy the result or download the available details.







## Example



### Input



```
95% confidence, 4% margin, 35% proportion, N = 1,000
```



### Expected result



```
354 samples
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/sample-size-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



The initial size is z²p(1−p)/e². For a finite population, divide that size by 1 + (initial size−1)/N and round up. The error calculation uses the same proportion and finite-population model.



$$
n_0=\frac{z^2p(1-p)}{e^2},\qquad n=\left\lceil\frac{n_0}{1+(n_0-1)/N}\right\rceil
$$







## Calculation mode



**Find sample size**

- Confidence level · %
- Margin of error · %
- Population proportion · %
- Population size (0 for unlimited)





**Find margin of error**

- Confidence level · %
- Sample size
- Population proportion · %
- Population size (0 for unlimited)

[Documentation](https://docs.toolpony.com/en/guides/sample-size-calculator/)
