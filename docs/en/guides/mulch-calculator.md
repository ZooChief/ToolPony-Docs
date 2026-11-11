# Mulch calculator



Estimate mulch volume, bag counts and cost for one or several plots.





## Get started



1. Enter total area or one rectangle per line, for example 6, 2, m. Each row may use a different unit.
2. Set the depth and select a bulk or bag price unit. For a custom bag, enter its capacity under More options.







## Example



### Input



```
200 ft² at 2 in, 2 ft³ bags at 5 each.
```



### Expected result



```
33.3 ft³, 17 bags, total cost 85.
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/mulch-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



Add the areas of non-overlapping plots, then multiply by depth and apply the allowance. Divide by bag capacity and round up. A bulk price uses the calculated volume.



$$
A=\sum_i l_iw_i,\quad V=Ad(1+a/100),\quad N=\left\lceil\frac{V}{V_{\rm bag}}\right\rceil
$$







## Calculation mode



**Known area**

- Area
- Area unit · cm² / m² / in² / ft² / yd² / acre / ha
- Depth
- Depth unit · mm / cm / m / in / ft / yd
- Unit price
- Price unit
- Bag capacity
- Bag unit · ft³ / yd³ / m³ / L
- Waste allowance · %





**Multiple rectangles**

- Length, width, unit per line
- Depth
- Depth unit · mm / cm / m / in / ft / yd
- Unit price
- Price unit
- Bag capacity
- Bag unit · ft³ / yd³ / m³ / L
- Waste allowance · %

[Documentation](https://docs.toolpony.com/en/guides/mulch-calculator/)
