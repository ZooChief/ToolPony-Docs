# Sample size calculator guide



Find a minimum survey sample or estimate the margin of error with finite-population correction.





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

[Open full tool · Sample size calculator](<https://toolpony.com/en/tools/sample-size-calculator/>)





## Calculation method



The initial size is z²p(1−p)/e². For a finite population, divide that size by 1 + (initial size−1)/N and round up. The error calculation uses the same proportion and finite-population model.



$$
n_0=\frac{z^2p(1-p)}{e^2},\qquad n=\left\lceil\frac{n_0}{1+(n_0-1)/N}\right\rceil
$$







## Calculation mode





### Find sample size



- Confidence level · %
- Margin of error · %
- Population proportion · %
- Population size (0 for unlimited)







### Find margin of error



- Confidence level · %
- Sample size
- Population proportion · %
- Population size (0 for unlimited)







[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fsample-size-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/sample-size-calculator/)
