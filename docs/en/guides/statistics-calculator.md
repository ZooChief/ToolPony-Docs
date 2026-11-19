# Statistics calculator



Summarize a dataset with mean, median, modes, quartiles and population and sample dispersion.





## Example



### Input



```
2, 4, 4, 6, 9
```



### Expected result



```
Mean 5, median 4
```







## Try it

[Open full tool · Statistics calculator](<https://toolpony.com/en/tools/statistics-calculator/>)





## Calculation method



Quartiles use linear interpolation at (n−1)p. Population variance divides by n and sample variance by n−1. Enter up to 1,000 values separated by commas or whitespace.



$$
\bar x=\frac{1}{n}\sum_{i=1}^{n} x_i,\qquad s=\sqrt{\frac{\sum_i(x_i-\bar x)^2}{n-1}}
$$



$$
\operatorname{SE}(\bar x)=\frac{s}{\sqrt n},\qquad \bar x\pm z\operatorname{SE}(\bar x)
$$



Use sample standard deviation for a subset of a population and population standard deviation for a complete set. The confidence table shows the normal approximation for the mean at several confidence levels.







## Calculation mode



**Dataset summary**

- Values





**Sample standard deviation**

- Values





**Population standard deviation**

- Values







[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fstatistics-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/statistics-calculator/)
