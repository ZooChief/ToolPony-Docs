# Volume calculator guide



Calculate tank capacity or solid volume in liters or cubic units. For a hollow tube, enter its outer diameter, inner diameter and length to find the volume of its wall.





## Example



### Input



```
Sphere with radius 2 m
```



### Expected result



```
≈33.5103 m³
```





<a id="case-study"></a>



## Estimate how much water fits below a tank’s fill line



1. Measure the inner diameter and the depth to the fill line. For a cylindrical tank 1 m across with 1.2 m of usable depth, choose “Run example”. The workbench sets the radius to 0.5 m and the output to liters.
2. The capacity is π × 0.5² × 1.2 m³, about 942.48 L. If you enter the diameter in the radius field, the squared term makes the result four times too large.
3. Move the fill line down by 0.2 m and enter 1 m for the depth. Capacity becomes about 785.40 L, leaving roughly 157.08 L above the fill line compared with the first calculation.



[Run example](<https://toolpony.com/en/tools/volume-calculator/#example-tank-fill-line>)





## Pipe wall and bore



For one metre of tubing with outer diameter 60 mm and inner diameter 48 mm, the wall occupies about 1.018 L. The bore can hold about 1.810 L. Both results and the two diameters are included in the CSV.



[Run example](<https://toolpony.com/en/tools/volume-calculator/#example-pipe-wall>)







## Try it

[Open full tool · Volume calculator](<https://toolpony.com/en/tools/volume-calculator/>)





## Calculation method



The volume of a prism is its base area times perpendicular height. A cone or pyramid divides that product by three. A hollow tube subtracts the inner cylinder. A spherical cap accepts any two dimensions.



$$
V_{\mathrm{cone}}=\tfrac13\pi r^2h,\qquad V_{\mathrm{sphere}}=\tfrac43\pi r^3
$$







## Calculation mode





### Sphere



- Radius
- Radius unit
- Volume unit







### Cone



- Radius
- Radius unit
- Perpendicular height
- Perpendicular height unit
- Volume unit







### Cube



- Edge length
- Edge length unit
- Volume unit







### Cylinder



- Radius
- Radius unit
- Perpendicular height
- Perpendicular height unit
- Volume unit







### Rectangular tank



- Length
- Length unit
- Width
- Width unit
- Perpendicular height
- Perpendicular height unit
- Volume unit







### Capsule



- Radius
- Radius unit
- Straight cylinder length
- Straight cylinder length unit
- Volume unit







### Spherical cap



- Sphere radius
- Sphere radius unit
- Base radius
- Base radius unit
- Cap height
- Cap height unit
- Cap with both radii known · Smaller cap / Larger cap
- Volume unit







### Conical frustum



- First end radius
- First end radius unit
- Second end radius
- Second end radius unit
- Perpendicular height
- Perpendicular height unit
- Volume unit







### Ellipsoid



- First semi-axis
- First semi-axis unit
- Second semi-axis
- Second semi-axis unit
- Third semi-axis
- Third semi-axis unit
- Volume unit







### Square pyramid



- Edge length
- Edge length unit
- Perpendicular height
- Perpendicular height unit
- Volume unit







### Hollow tube



- Outer diameter
- Outer diameter unit
- Inner diameter
- Inner diameter unit
- Length
- Length unit
- Volume unit







### Hemisphere



- Radius
- Radius unit
- Volume unit







### Ring torus



- Centerline radius
- Centerline radius unit
- Tube radius
- Tube radius unit
- Volume unit







**Method references** [BIPM · SI](<https://www.bipm.org/en/publications/si-brochure>) · [NIST DLMF · Triaxial ellipsoids](<https://dlmf.nist.gov/19.33>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fvolume-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/volume-calculator/)
