# Square footage calculator



Estimate area and material cost for nine shapes, with mixed measurements and a waste allowance.





## Get started



1. Choose the shape of the area. Use outside dimensions for the rectangle border or ring. The sector takes a radius and a central angle.
2. Set the unit next to each measurement. Enter the number of identical areas and optionally the price per selected area unit.
3. Read the net area in square feet and meters. Add a waste allowance under More options to estimate how much to order.







## Example



### Input



```
13 ft × 9 ft, quantity 1
```



### Expected result



```
117 ft² (10.86965568 m²)
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/square-footage-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



Convert dimensions to a common unit, find the area of one shape, and multiply by quantity. Cost uses area with any selected allowance, converted to the price unit. Border dimensions are measured outside to outside.



$$
A_{\rm border}=lw-(l-2b)(w-2b),\qquad A_{\rm ring}=\pi b(d-b)
$$



$$
A_{\rm sector}=r^2\theta/2,\qquad A_{\rm order}=q A(1+w/100)
$$



The border width b is measured inward from each edge. For a ring, d is the outside diameter. A 13 ft × 9 ft outside rectangle with a 2 ft border has 72 ft² of border per piece.



For a sector, r is radius and θ is the angle in radians after any conversion. In the order formula, q is quantity and w is the percentage allowance.







## Calculation mode



**Rectangle**

- Length
- Length unit
- Width
- Width unit
- Quantity
- Unit price
- Price per area
- Waste allowance · %





**Rectangle border**

- Length
- Length unit
- Width
- Width unit
- Border width
- Border width unit
- Quantity
- Unit price
- Price per area
- Waste allowance · %





**Circle**

- Diameter
- Diameter unit
- Quantity
- Unit price
- Price per area
- Waste allowance · %





**Ring**

- Outer diameter
- Outer diameter unit
- Border width
- Border width unit
- Quantity
- Unit price
- Price per area
- Waste allowance · %





**Triangle · three sides**

- First side
- First side unit
- Second side
- Second side unit
- Third side
- Third side unit
- Quantity
- Unit price
- Price per area
- Waste allowance · %





**Triangle · base and height**

- Base
- Base unit
- Perpendicular height
- Perpendicular height unit
- Quantity
- Unit price
- Price per area
- Waste allowance · %





**Trapezoid**

- First parallel side
- First parallel side unit
- Second parallel side
- Second parallel side unit
- Perpendicular height
- Perpendicular height unit
- Quantity
- Unit price
- Price per area
- Waste allowance · %





**Circular sector**

- Radius
- Radius unit
- Central angle
- Angle unit · Degrees / Radians
- Quantity
- Unit price
- Price per area
- Waste allowance · %





**Parallelogram**

- Base
- Base unit
- Perpendicular height
- Perpendicular height unit
- Quantity
- Unit price
- Price per area
- Waste allowance · %

[Documentation](https://docs.toolpony.com/en/guides/square-footage-calculator/)
