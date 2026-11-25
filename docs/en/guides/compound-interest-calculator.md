# Compound interest calculator guide



Project a balance with recurring contributions and inflation, or convert between compounding frequencies.





## Example



### Input



```
10,000 at 5% annually for 10 years
```



### Expected result



```
16,288.95
```





<a id="case-study"></a>



## Compare deposits over 30 months



1. Start with 10,000 and add 100 each month for two years and six months. At 6% nominal interest compounded monthly, end-of-month contributions give 14,842.00, including 13,000 contributed. Moving each deposit to the start of the month gives 14,858.14. At 3% annual inflation, the first balance has purchasing power of 13,784.77 today.





## Try it

[Open full tool · Compound interest calculator](<https://toolpony.com/en/tools/compound-interest-calculator/#example-30-months>)





## Calculation method



Effective annual growth is (1+r/m)^m−1, or exp(r)−1 with continuous compounding. Contributions earn interest from the selected beginning or end of each period.



$$
A=P(1+r/m)^{mt},\qquad \mathrm{APY}=(1+r/m)^m-1
$$







## Calculation mode





### Future balance



- Principal
- Annual rate · %
- Years
- Months
- Compounding
- Periodic contribution
- Contribution frequency · Yearly / Semiannual / Quarterly / Monthly / Twice a month / Biweekly / Weekly / Daily
- Contribute at start of period
- Annual inflation · %







### Equivalent interest rate



- Annual rate · %
- Original compounding
- Target compounding







**Method references** [Investor.gov · Compound Interest](<https://www.investor.gov/financial-tools-calculators/calculators/compound-interest-calculator>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fcompound-interest-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/compound-interest-calculator/)
