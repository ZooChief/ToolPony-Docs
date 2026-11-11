# Roofing calculator



Estimate roof surface, squares, shingle bundles, felt rolls and cost.





## Get started



1. Choose footprint and pitch or angle. Use measured length and width for a rectangular footprint.
2. For a complex roof, add measured sloped sections and enter their total in Known roof area.







## Example



### Input



```
2,000 ft² footprint, 6/12 pitch, 1 ft overhang.
```



### Expected result



```
About 2,461 ft², 28 roofing squares with 10% allowance.
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/roofing-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



With footprint alone, the overhang estimate uses A + 4.4e(√A + e), where e is horizontal overhang. With measured rectangular sides, use (l + 2e)(w + 2e). Apply the slope factor to that horizontal area. One roofing square is 100 ft². Counts use typical US coverage; check product specifications.



$$
A_{\rm proj}\approx A+4.4e(\sqrt A+e),\qquad A_{\rm rect}=(l+2e)(w+2e)
$$



$$
A_{\rm roof}=A_{\rm proj}\sqrt{1+(p/12)^2}=\frac{A_{\rm proj}}{\cos\theta},\quad N_{\rm squares}=\left\lceil\frac{A_{\rm roof,ft^2}(1+a/100)}{100}\right\rceil
$$







## Calculation mode



**Footprint and pitch**

- Footprint area
- Area unit · cm² / m² / in² / ft² / yd² / acre / ha
- Rise per 12 horizontal
- Horizontal overhang
- Overhang unit · mm / cm / m / in / ft / yd
- Unit price
- Price unit · cm² / m² / in² / ft² / yd² / acre / ha
- Waste allowance · %





**Footprint and angle**

- Footprint area
- Area unit · cm² / m² / in² / ft² / yd² / acre / ha
- Roof angle · °
- Horizontal overhang
- Overhang unit · mm / cm / m / in / ft / yd
- Unit price
- Price unit · cm² / m² / in² / ft² / yd² / acre / ha
- Waste allowance · %





**Known roof area**

- Roof area
- Area unit · cm² / m² / in² / ft² / yd² / acre / ha
- Unit price
- Price unit · cm² / m² / in² / ft² / yd² / acre / ha
- Waste allowance · %





**Measured length and width**

- Length
- Length unit · mm / cm / m / in / ft / yd
- Width
- Width unit · mm / cm / m / in / ft / yd
- Rise per 12 horizontal
- Horizontal overhang
- Overhang unit · mm / cm / m / in / ft / yd
- Unit price
- Price unit · cm² / m² / in² / ft² / yd² / acre / ha
- Waste allowance · %

[Documentation](https://docs.toolpony.com/en/guides/roofing-calculator/)
