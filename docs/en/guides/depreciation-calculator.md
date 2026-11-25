# Depreciation calculator guide



Build an annual straight-line, declining-balance, or sum-of-years’ digits schedule.





## Example



### Input



```
17,500 cost, 2,500 salvage, 6 years, straight-line
```



### Expected result



```
2,500 per year
```







## Try it

[Open full tool · Depreciation calculator](<https://toolpony.com/en/tools/depreciation-calculator/>)





## Calculation method



Straight-line divides depreciable cost by useful life. Declining balance applies factor/life to opening book value and stops at salvage. Sum-of-years’ digits allocates by the remaining years’ weights. Amounts are rounded per year.



$$
D_{\mathrm{SL}}=\frac{C-S}{n},\quad D_{k,\mathrm{SYD}}=(C-S)\frac{n-k+1}{n(n+1)/2}
$$







## Calculation mode





### Straight-line



- Asset cost
- Salvage value
- Useful life
- Rounding · Two decimal places / Whole amount







### Declining balance



- Asset cost
- Salvage value
- Useful life
- Depreciation factor
- Rounding · Two decimal places / Whole amount







### Sum-of-years’ digits



- Asset cost
- Salvage value
- Useful life
- Rounding · Two decimal places / Whole amount







[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fdepreciation-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/depreciation-calculator/)
