# Color converter guide



Convert CSS colors to HEX, RGB, HSL and OKLCH, with opacity and an sRGB fallback for wide-gamut colors.





## Example



### Input



```
rgb(102, 51, 153)
```



### Expected result



```
#663399, hsl(270 50% 40%)
```





<a id="case-study"></a>



## Prepare a wide-gamut color for an sRGB asset



1. Paste color(display-p3 0 1 0 / 70%). The green is outside sRGB. The two swatches show the source and its mapped fallback. With this mapping the HEX value is \#00FB29B3.
2. Copy the RGB row to keep opacity at exactly 0.7. The eight-digit HEX represents opacity in one byte, B3 (179/255).



[Run example](<https://toolpony.com/en/tools/color-converter/#example-wide-gamut>)





## Try it

[Open full tool · Color converter](<https://toolpony.com/en/tools/color-converter/>)





## Calculation method



HEX rounds sRGB channels to bytes. Colors outside sRGB are mapped along OKLCH chroma before export. The source preview retains the supplied color space.





**Method references** [W3C · CSS Color 4](<https://www.w3.org/TR/css-color-4/>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fcolor-converter%2F>)

[Documentation](https://docs.toolpony.com/en/guides/color-converter/)
