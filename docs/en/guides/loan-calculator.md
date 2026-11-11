# Loan calculator



Calculate installment loans, find a term from a monthly payment, or plan dated extra payments. Export a full schedule.





## Get started



1. Choose a fixed term, a target monthly payment, or dated extra payments.
2. For dated extras, enter the first payment month. Add one-off entries one per line, such as 2026-06, 500.
3. Calculate and switch between schedules before downloading the selected table.







## Example



### Input



```
100,000 for 10 years at 6%, monthly
```



### Expected result



```
≈1,110.21 per month
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/loan-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



Installments convert the nominal rate to the payment period. Dated payments use monthly interest and apply extras after the scheduled payment. Rates are fixed and intermediate amounts are not rounded to cents.



$$
M=\frac{Pr}{1-(1+r)^{-n}},\qquad M=\frac Pn\quad(r=0)
$$



$$
n=\frac{-\ln(1-Pr/M)}{\ln(1+r)},\qquad M>Pr\quad(r>0)
$$



$$
I_k=r B_{k-1},\qquad B_k=\max(0,B_{k-1}-(M-I_k)-E_k)
$$



P is principal, r is the rate for one period, M is the regular payment, and n is the duration in periods. In the fixed-payment and dated-extra modes, r is the annual percentage divided by 1,200. B is the outstanding balance, I is interest, and E is the extra amount applied to principal.



A payment of 785 on 45,000 at 6.3% gives an estimated 68.38 months. Monthly billing has 69 payments, with a smaller final bill. Select a schedule before downloading it.







## Calculation mode



**Installments**

- Principal
- Years
- Months
- Annual rate · %
- Compounding
- Payment frequency · Yearly / Semiannual / Quarterly / Monthly / Twice a month / Biweekly / Weekly / Daily
- Extra per payment





**Term from monthly payment**

- Principal
- Monthly payment
- Annual rate · %





**Dated extra payments**

- Principal
- Years
- Months
- Annual rate · %
- First payment month
- Extra monthly payment
- Start of monthly extras
- Extra yearly payment
- Start of yearly extras
- One-time payments (YYYY-MM, amount)





**Single payment at maturity**

- Principal
- Years
- Months
- Annual rate · %
- Compounding





**Present value of a lump sum**

- Amount due at maturity
- Years
- Months
- Annual rate · %
- Compounding

[Documentation](https://docs.toolpony.com/en/guides/loan-calculator/)
