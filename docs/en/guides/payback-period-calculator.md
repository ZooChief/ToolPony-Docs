# Payback period calculator



Find regular and discounted payback from growing or irregular annual cash flows.





## Get started



1. Use the example values or enter your own measurements.
2. Calculate, then copy the result or download the available details.







## Example



### Input



```
17,500 initial, first inflow 4,700, growth 8%, discount 6%
```



### Expected result



```
Payback ≈ 3.379 years, discounted ≈ 3.841 years
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/payback-period-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



Accumulate cash flows from the initial outlay. On the first crossing of zero, interpolate the fraction of that year. Discounted cash flows divide year k by (1+r)^k. A constant stream uses the inverse annuity formula for discounted payback.



$$
C_k=\sum_{i=0}^{k}F_i,\qquad F_i^{\mathrm{PV}}=\frac{F_i}{(1+r)^i}
$$







## Calculation mode



**Regular or growing cash flows**

- Initial investment
- First-year cash flow
- Annual growth or decline · %
- Years
- Annual discount rate · %





**Irregular annual cash flows**

- Initial investment
- Subsequent annual cash flows
- Annual discount rate · %

[Documentation](https://docs.toolpony.com/en/guides/payback-period-calculator/)
