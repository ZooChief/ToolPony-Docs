# Contrast checker



Compare two opaque colors against WCAG 2.2 contrast thresholds.





## Example



### Input



```
#000000 on #FFFFFF
```



### Expected result



```
21:1
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/contrast-checker/>)







## Calculation method



Contrast is (lighter luminance + 0.05) divided by (darker luminance + 0.05). Use the unrounded ratio for pass/fail. Normal text needs 4.5:1 for AA or 7:1 for AAA. Large text needs 3:1 for AA or 4.5:1 for AAA.

[Documentation](https://docs.toolpony.com/en/guides/contrast-checker/)
