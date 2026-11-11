# Mortgage payoff calculator



Compare a mortgage’s remaining payments, extra payments, a lump sum and two biweekly schedules.





## Get started



1. Use your statement balance and principal-and-interest payment if you have made previous extras. Otherwise you can derive the balance from the original loan and remaining term.
2. Choose a plan. For extras, enter monthly, yearly or one-time amounts. By default these start in months 1, 12 and 1. Change the start periods in More options.
3. Compare the selected and regular plans, then download the remaining schedule or the comparison CSV.
4. This model covers principal and fixed interest. An actual payoff quote can include daily interest, charges and penalties. Confirm the amount with your lender.







## Example



### Input



```
400,000 originally for 30 years at 6%. 25 years remain. Add 500 monthly.
```



### Expected result



```
207 months remaining, 122,306.21 interest saved
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/mortgage-payoff-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



Original-loan mode assumes all earlier payments followed the original schedule. Monthly interest is balance times the annual rate divided by twelve. The grouped biweekly plan adds half a monthly payment every six months. The 26-payment plan uses half a monthly payment and the annual rate divided by 26.



$$
B=M\frac{1-(1+r)^{-n}}r\quad(r>0),\qquad B=Mn\quad(r=0)
$$



$$
I_k=rB_{k-1},\qquad B_k=\max(0,B_{k-1}-M+I_k-E_k)
$$



$$
E_{6j}=M/2\quad\text{(grouped)},\qquad M_{26}=M/2,\quad r_{26}=r_{\rm annual}/26
$$







## Calculation mode



**Original loan and remaining term**

- Original loan amount
- Original term years
- Additional original months
- Annual rate · %
- Remaining years
- Additional remaining months
- Repayment plan · Extra payments / Regular payments / Biweekly, grouped by month / Biweekly, 26 payments per year / Pay principal now
- Extra monthly payment
- Extra yearly payment
- One-time extra payment
- First month for monthly extras
- First month for yearly extras
- Month for one-time payment





**Current balance and payment**

- Remaining principal
- Monthly payment
- Annual rate · %
- Repayment plan · Extra payments / Regular payments / Biweekly, grouped by month / Biweekly, 26 payments per year / Pay principal now
- Extra monthly payment
- Extra yearly payment
- One-time extra payment
- First month for monthly extras
- First month for yearly extras
- Month for one-time payment

[Documentation](https://docs.toolpony.com/en/guides/mortgage-payoff-calculator/)
