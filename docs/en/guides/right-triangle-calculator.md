# Right triangle calculator



Find the legs, hypotenuse and angles from two known measurements, including altitude, area or perimeter.





## Get started



1. Enter two measurements, including at least one length, area or perimeter.
2. The two solutions swap the labels of the legs and acute angles.







## Example



### Input



```
c = 5, h = 2.4
```



### Expected result



```
Legs 3 and 4, area 6, perimeter 12. Either leg can be a.
```







## Try it

[Open full tool · Right triangle calculator](<https://toolpony.com/en/tools/right-triangle-calculator/>)





## Calculation method



c is the hypotenuse. h is its perpendicular altitude. Use consistent length units and the corresponding square unit for area.



$$
c^2=a^2+b^2,\quad h=ab/c,\quad S=ab/2,\quad P=a+b+c
$$



$$
a,b=\frac{\sqrt{c^2+2ch}\;\pm\;\sqrt{c^2-2ch}}{2}
$$





[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fright-triangle-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/right-triangle-calculator/)
