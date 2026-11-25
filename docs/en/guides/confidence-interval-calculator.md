# Confidence interval calculator guide



Estimate a mean from observations or summary statistics using a z or Student t interval, or use Wilson for a proportion.





## Example



### Input



```
n = 36, mean 56, standard deviation 8, 99%
```



### Expected result



```
56 ± 3.434
```





<a id="case-study"></a>



## An interval from five measurements



1. Five measurements are 48, 49, 50, 51 and 52. Their mean is 50. With a sample standard deviation and four degrees of freedom, the 95% Student t interval for the mean is about 48.04 to 51.96. This calculation assumes independent observations from an approximately normal population.



[Run example](<https://toolpony.com/en/tools/confidence-interval-calculator/#example-five-measurements>)





## Zero failures in 30 checks



In 30 independent checks, the observed failure count is zero. The 95% Wilson interval for the underlying failure proportion runs from 0% to about 11.35%. A larger sample with the same outcome narrows the interval.



[Run example](<https://toolpony.com/en/tools/confidence-interval-calculator/#example-no-failures>)







## Try it

[Open full tool · Confidence interval calculator](<https://toolpony.com/en/tools/confidence-interval-calculator/>)





## Calculation method



For a mean, the margin is the critical value × standard deviation / √n. Use z with a known population deviation and Student t with n − 1 degrees of freedom for a sample deviation. A Wilson score interval estimates a binomial proportion from successes and trials.



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## Calculation mode





### Mean interval



- Data source · Known σ / Sample s / Observations
- Sample size
- Mean
- Standard deviation
- Sample values
- Confidence level · %







### Wilson proportion interval



- Sample size
- Successes
- Confidence level · %







**Method references** [NIST · Confidence limits for the mean](<https://www.itl.nist.gov/div898/handbook/eda/section3/eda352.htm>) · [NIST · Confidence limits for a proportion](<https://www.itl.nist.gov/div898/handbook/prc/section2/prc241.htm>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fconfidence-interval-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/confidence-interval-calculator/)
