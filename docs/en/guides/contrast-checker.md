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





<a id="case-study"></a>



## Choose a gray that passes for normal text on white



1. Try the \#777777 example on a white background. The ratio is about 4.48:1. Normal text falls short of WCAG AA even though the displayed number rounds to 4.5 to one decimal place.
2. Try \#767676 on the same background. The ratio rises to about 4.54:1 and normal text passes AA. Both examples meet the 3:1 threshold for large text.
3. Check the actual foreground and background of the text in your design. For text over an image or a translucent layer, sample the final colors at the least contrasting part of the background. A check of two solid colors covers that pair.





## Try it

[Open full tool · Contrast checker](<https://toolpony.com/en/tools/contrast-checker/>)





## Calculation method



Contrast is (lighter luminance + 0.05) divided by (darker luminance + 0.05). Use the unrounded ratio for pass/fail. Normal text needs 4.5:1 for AA or 7:1 for AAA. Large text needs 3:1 for AA or 4.5:1 for AAA.





**Method references** [W3C · WCAG 2.2 (1.4.3, AA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html>) · [W3C · WCAG 2.2 (1.4.6, AAA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-enhanced.html>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fcontrast-checker%2F>)

[Documentation](https://docs.toolpony.com/en/guides/contrast-checker/)
