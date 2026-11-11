# Resistor calculator



Decode 3–6 color bands, combine resistors in series or parallel, or calculate round-wire resistance.





## Get started



1. Choose the band count or circuit arrangement. The tolerance band is often separated from the other bands.
2. For a conductor, enter its round diameter and length. A material preset fills the editable conductivity.







## Example



### Input



```
4 bands: green, red, red, gold
```



### Expected result



```
5,200 Ω ±5%
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/resistor-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



Read the significant digits, multiplier, tolerance and optional temperature coefficient in order. A 3-band resistor has a nominal 20% tolerance. A uniform round conductor uses R = L/(σA). Check the part’s datasheet for special markings.



$$
R_{\rm series}=\sum_i R_i,\quad R_{\rm parallel}=\left(\sum_i 1/R_i\right)^{-1},\quad R_{\rm wire}=\frac{L}{\sigma\pi(d/2)^2}
$$



$$
R_{\rm band}=D\,10^m,\qquad R_{\min,\max}=R_{\rm band}(1\mp t/100)
$$







## Calculation mode



**4 bands**

- First digit
- Second digit
- Multiplier
- Tolerance





**3 bands**

- First digit
- Second digit
- Multiplier





**5 bands**

- First digit
- Second digit
- Third digit
- Multiplier
- Tolerance





**6 bands**

- First digit
- Second digit
- Third digit
- Multiplier
- Tolerance
- Temperature coefficient





**Parallel**

- Resistances in Ω





**Series**

- Resistances in Ω





**Round conductor**

- Length
- Length unit · mm / cm / m / km / in / ft / yd / mi
- Diameter
- Diameter unit · mm / cm / m / km / in / ft / yd / mi
- Material preset · Custom / Copper / Annealed copper / Aluminum / Silver / Gold
- Conductivity · S/m

[Documentation](https://docs.toolpony.com/en/guides/resistor-calculator/)
