# Ratio calculator guide



Solve a ratio, scale exact fractions, or fit and crop an image to a frame with its aspect ratio preserved.





## Example



### Input



```
3:4 = x:20
```



### Expected result



```
x=15
```





<a id="case-study"></a>



## Fit a landscape image inside a poster



1. Place a 1920 × 1080 image inside a 1200 × 900 frame. Width limits the scale to 5/8. The image becomes 1200 × 675 and leaves 225 pixels of vertical space, or 112.5 on each side when centered.



[Run example](<https://toolpony.com/en/tools/ratio-calculator/#example-fit-poster>)





## Fill the same frame edge to edge



To fill that poster, use the height as the limiting dimension. A 5/6 scale gives 1600 × 900. Centering the image crops 200 pixels from the left and 200 from the right.



[Run example](<https://toolpony.com/en/tools/ratio-calculator/#example-fill-poster>)







## Try it

[Open full tool · Ratio calculator](<https://toolpony.com/en/tools/ratio-calculator/>)





## Calculation method



A × D = B × C for A:B = C:D with nonzero denominators. Fit uses the smaller of frame width/source width and frame height/source height. Fill uses the larger. The unused or cropped amount is the total along each axis.







## Calculation mode





### Solve a proportion



- A
- B
- C
- D







### Simplify or scale



- First term
- Second term
- Scale factor







### Enlarge or reduce a ratio



- First term
- Second term
- Resize by · Factor / Fit inside / Fill and crop
- Direction · Reduce / Enlarge
- Factor
- Frame width
- Frame height







**Method references** [W3C · Object fitting](<https://www.w3.org/TR/css-images-3/#the-object-fit>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fratio-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/ratio-calculator/)
