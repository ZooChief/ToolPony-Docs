# Tile calculator



Estimate tiles, boxes and cost from tile dimensions, grout spacing, and the area to cover.





## Get started



1. Enter the tile length, width, and spacing. A negative gap means the tiles overlap.
2. Enter either a known area or two room dimensions. Enter tiles per box to compute whole boxes.
3. For cutting and breakage, enter an allowance under More options. The tool estimates coverage by area.







## Example



### Input



```
180 ft², 12 in × 12 in tiles, ¼ in gap, 12 per box
```



### Expected result



```
173 tiles, 15 boxes
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/tile-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



Divide the area by (tile length + gap) × (tile width + gap), then round up. Negative gap models overlap. Add a user-selected allowance before converting to whole boxes.



$$
N=\left\lceil\frac{A}{(l+g)(w+g)}\right\rceil,\quad N_{\rm order}=\left\lceil N(1+a/100)\right\rceil
$$



At 180 ft² with 12 in square tiles and a ¼ in gap, the estimate is 173 tiles. With a 10% allowance and 12 tiles per box, order 191 tiles, rounded up to 16 boxes.



The coverage model uses an effective length and width for each tile. Allowance covers cutting, patterns and breakage. Confirm the final layout with your actual room and tile dimensions.







## Calculation mode



**Known area**

- Tile length
- Tile length unit
- Tile width
- Tile width unit
- Gap or overlap
- Gap or overlap unit
- Total area
- Area unit
- Tiles per box
- Unit price
- Price per
- Waste allowance · %





**Rectangular room**

- Tile length
- Tile length unit
- Tile width
- Tile width unit
- Gap or overlap
- Gap or overlap unit
- Room length
- Room length unit
- Room width
- Room width unit
- Tiles per box
- Unit price
- Price per
- Waste allowance · %

[Documentation](https://docs.toolpony.com/en/guides/tile-calculator/)
