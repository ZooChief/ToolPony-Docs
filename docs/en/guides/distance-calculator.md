# Distance calculator



Find the distance between two 2D or 3D points, or estimate the surface distance between geographic coordinates.





## Get started



1. Use the example values or enter your own measurements.
2. Calculate, then copy the result or download the available details.







## Example



### Input



```
2D: (0, 0) to (3, 4)
```



### Expected result



```
Distance 5
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/distance-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



Cartesian distance uses the Euclidean norm. Geographic modes use the WGS 84 ellipsoid and Lambert’s approximation. Nearly antipodal points use a spherical approximation. This is a surface estimate.



$$
d=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2+(z_2-z_1)^2}
$$



Use the 2D or 3D mode for coordinates that already share a linear scale. Convert both points to the same unit first.



For geographic coordinates, north and east are positive. Use the degree-minute-second mode when a survey gives separate angular fields. The result estimates an ellipsoidal surface path.







## Calculation mode



**2D**

- X1
- Y1
- X2
- Y2





**3D**

- X1
- Y1
- Z1
- X2
- Y2
- Z2





**Latitude and longitude**

- First latitude · °
- First longitude · °
- Second latitude · °
- Second longitude · °





**Degrees, minutes and seconds**

- First latitude degrees
- First latitude minutes
- First latitude seconds
- First latitude hemisphere · N / S
- First longitude degrees
- First longitude minutes
- First longitude seconds
- First longitude hemisphere · E / W
- Second latitude degrees
- Second latitude minutes
- Second latitude seconds
- Second latitude hemisphere · N / S
- Second longitude degrees
- Second longitude minutes
- Second longitude seconds
- Second longitude hemisphere · E / W

[Documentation](https://docs.toolpony.com/en/guides/distance-calculator/)
