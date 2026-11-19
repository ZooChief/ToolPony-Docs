# Confidence interval calculator



Estimate a normal mean interval or a Wilson interval for a proportion.





## Example



### Input



```
n = 36, mean 56, standard deviation 8, 99%
```



### Expected result



```
56 ± 3.434
```







## Try it

[Open full tool · Confidence interval calculator](<https://toolpony.com/en/tools/confidence-interval-calculator/>)





## Calculation method



The normal margin is z times the standard error s/√n. Wilson score intervals adjust the center and width for proportions and remain within \[0,1\].



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## Calculation mode



**Normal mean interval**

- Sample size
- Mean
- Standard deviation
- Confidence level · %





**Wilson proportion interval**

- Sample size
- Successes
- Confidence level · %







[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fconfidence-interval-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/confidence-interval-calculator/)
