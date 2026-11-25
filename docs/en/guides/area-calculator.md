# Area calculator guide



Find the area of plane shapes in eleven modes with mixed input units and a selectable output unit.





## Example



### Input



```
A rectangle 4 m by 3 m
```



### Expected result



```
12 m²
```





<a id="case-study"></a>



## Cut a ring with a circular opening



1. For a flat gasket with an outer diameter of 60 mm and a 40 mm opening, enter radii of 30 and 20 mm. Choose mm² for the material area.
2. The material covers 500π mm², about 1,570.80 mm². Cutting both circles takes 100π mm, about 314.16 mm of cut. The export keeps each circumference and the original measurements.



[Run example](<https://toolpony.com/en/tools/area-calculator/#example-gasket>)





## Try it

[Open full tool · Area calculator](<https://toolpony.com/en/tools/area-calculator/>)





## Calculation method



Dimensions convert to meters before calculation. The three-side triangle uses Heron’s formula. A sector uses half the squared radius times its angle in radians.



$$
A_{\mathrm{rectangle}}=lw,\qquad A_{\mathrm{sector}}=\tfrac12 r^2\theta
$$



$$
A_{\mathrm{triangle}}=\sqrt{s(s-a)(s-b)(s-c)},\quad s=\tfrac12(a+b+c)
$$







## Calculation mode





### Rectangle



- Length
- Length unit
- Width
- Width unit
- Area unit







### Square



- Side length
- Side length unit
- Area unit







### Triangle · three sides



- First side
- First side unit
- Second side
- Second side unit
- Third side
- Third side unit
- Area unit







### Triangle · base and height



- Base length
- Base length unit
- Perpendicular height
- Perpendicular height unit
- Area unit







### Trapezoid



- First parallel side
- First parallel side unit
- Second parallel side
- Second parallel side unit
- Perpendicular height
- Perpendicular height unit
- Area unit







### Circle



- Radius
- Radius unit
- Area unit







### Circular sector



- Radius
- Radius unit
- Central angle
- Angle unit · Degrees / Radians
- Area unit







### Ellipse



- First semi-axis
- First semi-axis unit
- Second semi-axis
- Second semi-axis unit
- Area unit







### Parallelogram



- Base length
- Base length unit
- Perpendicular height
- Perpendicular height unit
- Area unit







### Annulus



- Outer radius
- Outer radius unit
- Inner radius
- Inner radius unit
- Area unit







### Regular polygon



- Side length
- Side length unit
- Number of sides
- Area unit







**Method references** [BIPM · SI](<https://www.bipm.org/en/publications/si-brochure>) · [NIST DLMF · Lengths of plane curves](<https://dlmf.nist.gov/19.30>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Farea-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/area-calculator/)
