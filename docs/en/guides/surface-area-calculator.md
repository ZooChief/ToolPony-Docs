# Surface area calculator guide



Calculate a solid’s surface area. For tanks, pipes and other solids with flat ends, choose the faces to cover and compare their areas.





## Example



### Input



```
Sphere with radius 2 m
```



### Expected result



```
≈50.2655 m²
```





<a id="case-study"></a>



## Line an open rectangular tank



1. Use inside dimensions of 120 cm by 0.8 m and a depth of 450 mm. Cover the four walls and one end, the floor of the tank.
2. The walls use 1.80 m² and the floor 0.96 m², for a total of 2.76 m² before seams or waste. Selecting all faces adds a lid and brings the total to 3.72 m².



[Run example](<https://toolpony.com/en/tools/surface-area-calculator/#example-open-tank>)





## Try it

[Open full tool · Surface area calculator](<https://toolpony.com/en/tools/surface-area-calculator/>)





## Calculation method



A closed surface includes all its ends. End areas are calculated from their dimensions. Ellipsoid area is evaluated numerically with a symmetric elliptic integral.



$$
A_{\mathrm{cylinder}}=2\pi r^2+2\pi rh,\qquad A_{\mathrm{sphere}}=4\pi r^2
$$







## Calculation mode





### Sphere



- Radius
- Radius unit
- Area unit







### Cone



- Radius
- Radius unit
- Perpendicular height
- Perpendicular height unit
- Surfaces to cover · All faces / Sides only
- Area unit







### Cube



- Edge length
- Edge length unit
- Surfaces to cover · All faces / Sides only / Sides and one end
- Area unit







### Cylinder



- Radius
- Radius unit
- Perpendicular height
- Perpendicular height unit
- Surfaces to cover · All faces / Sides only / Sides and one end
- Area unit







### Rectangular tank



- Length
- Length unit
- Width
- Width unit
- Perpendicular height
- Perpendicular height unit
- Surfaces to cover · All faces / Sides only / Sides and one end
- Area unit







### Capsule



- Radius
- Radius unit
- Straight cylinder length
- Straight cylinder length unit
- Area unit







### Spherical cap



- Sphere radius
- Sphere radius unit
- Base radius
- Base radius unit
- Cap height
- Cap height unit
- Cap with both radii known · Smaller cap / Larger cap
- Surfaces to cover · All faces / Sides only
- Area unit







### Conical frustum



- First end radius
- First end radius unit
- Second end radius
- Second end radius unit
- Perpendicular height
- Perpendicular height unit
- Surfaces to cover · All faces / Sides only / Sides and first end / Sides and second end
- Area unit







### Ellipsoid



- First semi-axis
- First semi-axis unit
- Second semi-axis
- Second semi-axis unit
- Third semi-axis
- Third semi-axis unit
- Area unit







### Square pyramid



- Edge length
- Edge length unit
- Perpendicular height
- Perpendicular height unit
- Surfaces to cover · All faces / Sides only
- Area unit







### Hollow tube



- Outer diameter
- Outer diameter unit
- Inner diameter
- Inner diameter unit
- Length
- Length unit
- Surfaces to cover · All faces / Sides only / Sides and one end
- Area unit







### Hemisphere



- Radius
- Radius unit
- Surfaces to cover · All faces / Sides only
- Area unit







### Ring torus



- Centerline radius
- Centerline radius unit
- Tube radius
- Tube radius unit
- Area unit







**Method references** [BIPM · SI](<https://www.bipm.org/en/publications/si-brochure>) · [NIST DLMF · Triaxial ellipsoids](<https://dlmf.nist.gov/19.33>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fsurface-area-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/surface-area-calculator/)
