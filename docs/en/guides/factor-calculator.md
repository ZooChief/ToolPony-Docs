# Factor calculator



List every positive divisor, all factor pairs, and the prime factorization.





## Example



### Input



```
120
```



### Expected result



```
16 positive divisors, including 1 and 120
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/factor-calculator/>)







## Calculation method



A divisor divides the input with zero remainder. Each small divisor d pairs with n/d, so searching up to √n finds every pair.



$$
d\mid n\iff n\bmod d=0,\qquad n=d\cdot(n/d)
$$

[Documentation](https://docs.toolpony.com/en/guides/factor-calculator/)
