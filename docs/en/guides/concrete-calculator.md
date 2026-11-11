# Concrete calculator



Estimate concrete volume, weight and whole bags for slabs, footings, tubes, curbs and stairs.





## Get started



1. Choose the matching shape and set units for each measurement. A tube uses outer and inner diameters.
2. For stairs, enter the number of rises and the length of the top platform separately. Use the number of identical pieces for other shapes.
3. Replace the default density with the value on the material label if known. Use the whole-bag table for orders.







## Example



### Input



```
7 ft × 3 ft × 5 in slab, quantity 2
```



### Expected result



```
17.5 ft³, 2,327.50 lb at 133 lb/ft³
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/concrete-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



Volume equals the cross-sectional area times length. The default uses 133 lb/ft³ for pounds and 2,130 kg/m³ for kilograms. A custom density converts both results from one value. Add any allowance before rounding an order to whole bags.



$$
V_{\rm slab}=lwhq,\quad V_{\rm tube}=\pi hq(d_o^2-d_i^2)/4
$$



$$
V_{\rm stairs}=brn\left[p+u(n-1)/2\right],\qquad m=V\rho
$$



In the stair formula, b is the width, r the rise, u the horizontal run, n the number of rises, and p the depth of the top platform. The solid volume includes n−1 treads and the top platform.



For two 7 ft × 3 ft × 5 in slabs, 133 lb/ft³ gives 2327.50 lb, or 38.79 equivalents of a 60 lb bag. The order table rounds that to 39 bags before any allowance.







## Calculation mode



**Slab or rectangular footing**

- Length
- Length unit
- Width
- Width unit
- Thickness or height
- Thickness or height unit
- Quantity
- Custom concrete density · lb/ft³
- Waste allowance · %





**Column or round footing**

- Diameter
- Diameter unit
- Depth or height
- Depth or height unit
- Quantity
- Custom concrete density · lb/ft³
- Waste allowance · %





**Circular slab or tube**

- Outer diameter
- Outer diameter unit
- Inner diameter
- Inner diameter unit
- Depth or height
- Depth or height unit
- Quantity
- Custom concrete density · lb/ft³
- Waste allowance · %





**Curb and gutter**

- Curb depth
- Curb depth unit
- Gutter width
- Gutter width unit
- Curb height above gutter
- Curb height above gutter unit
- Flag thickness
- Flag thickness unit
- Length
- Length unit
- Quantity
- Custom concrete density · lb/ft³
- Waste allowance · %





**Solid stairs and platform**

- Run per step
- Run per step unit
- Rise per step
- Rise per step unit
- Stair width
- Stair width unit
- Top platform depth
- Top platform depth unit
- Number of steps
- Custom concrete density · lb/ft³
- Waste allowance · %

[Documentation](https://docs.toolpony.com/en/guides/concrete-calculator/)
