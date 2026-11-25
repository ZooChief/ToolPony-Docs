# Adult BMI calculator guide



Calculate adult BMI in metric or US units, compare reference ranges, and see BMI Prime and ponderal index.





## Example



### Input



```
70 kg, 175 cm
```



### Expected result



```
BMI ≈22.86 kg/m²
```





<a id="case-study"></a>



## Read the boundary at BMI 25



1. At 180 cm and 80.99 kg the BMI is about 24.997. At 81 kg it is exactly 25, the start of the next CDC adult screening category. The display keeps extra digits near a boundary.



[Run example](<https://toolpony.com/en/tools/bmi-calculator/#example-bmi-boundary>)





## Try it

[Open full tool · Adult BMI calculator](<https://toolpony.com/en/tools/bmi-calculator/>)





## Calculation method



BMI = kg ÷ m². Reference ranges are the CDC adult screening categories for ages 20 and above. BMI Prime divides BMI by 25. Ponderal index = kg ÷ m³.



$$
\operatorname{BMI}=\frac{m_{\mathrm{kg}}}{h_{\mathrm{m}}^2}
$$







## Calculation mode





### Metric



- Age
- Weight · kg
- Height · cm







### US customary



- Age
- Weight · lb
- Height in feet · ft
- Additional inches · in







**Method references** [CDC · Adult BMI Categories](<https://www.cdc.gov/bmi/adult-calculator/bmi-categories.html>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fbmi-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/bmi-calculator/)
