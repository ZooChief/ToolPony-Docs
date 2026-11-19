# Payback period calculator



Find regular and discounted payback from growing or irregular annual cash flows.





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

[Open full tool · Payback period calculator](<https://toolpony.com/en/tools/payback-period-calculator/>)





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







[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fpayback-period-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/payback-period-calculator/)
