# Roofing calculator guide



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





<a id="case-study"></a>



## Order shingles



1. A flat 25 × 40 ft roof covers 1,000 ft². With 10% extra and 3 bundles per 100 ft², buy 33 bundles. At 75 per bundle the order costs 2,475.



[Run example](<https://toolpony.com/en/tools/roofing-calculator/#example-roof-order>)





## Read the pack label



For 1,100 ft² including allowance, a pack rated at 33.3 ft² yields 1,098.9 ft² from 33 packs. Round up to 34 packs, covering 1,132.2 ft².



[Run example](<https://toolpony.com/en/tools/roofing-calculator/#example-package-label>)







## Two different overhangs



An 8 × 5 m building with eaves of 25 cm and gable overhangs of 40 cm has an 8.8 × 5.5 m projected roof. At 5:12 pitch, 10% allowance and 3 m² per pack, order 20 packs.



[Run example](<https://toolpony.com/en/tools/roofing-calculator/#example-roof-overhang>)







## Try it

[Open full tool · Roofing calculator](<https://toolpony.com/en/tools/roofing-calculator/>)





## Calculation method



With footprint alone, the overhang estimate uses A + 4.4e(√A + e), where e is horizontal overhang. With measured rectangular sides, use (l + 2e)(w + 2e). Apply the slope factor to that horizontal area. One roofing square is 100 ft². Counts use typical US coverage; check product specifications.



$$
A_{\rm proj}\approx A+4.4e(\sqrt A+e),\qquad A_{\rm rect}=(l+2e)(w+2e)
$$



$$
A_{\rm roof}=A_{\rm proj}\sqrt{1+(p/12)^2}=\frac{A_{\rm proj}}{\cos\theta},\quad N_{\rm squares}=\left\lceil\frac{A_{\rm roof,ft^2}(1+a/100)}{100}\right\rceil
$$







## Calculation mode





### Footprint and pitch



- Footprint area
- Area unit · cm² / m² / in² / ft² / yd² / acre / ha
- Rise per 12 horizontal
- Horizontal overhang
- Overhang unit · mm / cm / m / in / ft / yd
- Unit price
- Price unit · cm² / m² / in² / ft² / yd² / acre / ha
- Waste allowance · %
- Package coverage · Bundles per square / Area per package
- Bundles for 100 ft²
- Effective coverage per package
- Price per whole package (optional)







### Footprint and angle



- Footprint area
- Area unit · cm² / m² / in² / ft² / yd² / acre / ha
- Roof angle · °
- Horizontal overhang
- Overhang unit · mm / cm / m / in / ft / yd
- Unit price
- Price unit · cm² / m² / in² / ft² / yd² / acre / ha
- Waste allowance · %
- Package coverage · Bundles per square / Area per package
- Bundles for 100 ft²
- Effective coverage per package
- Price per whole package (optional)







### Known roof area



- Roof area
- Area unit · cm² / m² / in² / ft² / yd² / acre / ha
- Unit price
- Price unit · cm² / m² / in² / ft² / yd² / acre / ha
- Waste allowance · %
- Package coverage · Bundles per square / Area per package
- Bundles for 100 ft²
- Effective coverage per package
- Price per whole package (optional)







### Measured length and width



- Length
- Length unit · mm / cm / m / in / ft / yd
- Width
- Width unit · mm / cm / m / in / ft / yd
- Rise per 12 horizontal
- Horizontal overhang
- Overhang unit · mm / cm / m / in / ft / yd
- Gable-end overhang, if different
- Unit price
- Price unit · cm² / m² / in² / ft² / yd² / acre / ha
- Waste allowance · %
- Package coverage · Bundles per square / Area per package
- Bundles for 100 ft²
- Effective coverage per package
- Area unit · cm² / m² / in² / ft² / yd² / acre / ha
- Price per whole package (optional)







**Method references** [GAF · Bundle coverage per roofing square](<https://www.gaf.com/en-us/blog/your-home/how-many-bundles-of-shingles-are-in-a-square---63a47862-f7e1-4e73-abcf-8d09917a8b8d>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Froofing-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/roofing-calculator/)
