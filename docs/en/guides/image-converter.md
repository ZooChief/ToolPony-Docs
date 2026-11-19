# Image converter



Add mixed image formats in one batch. ToolPony detects each input and lets you choose the output format, quality and background per image. Download individual files or a ZIP.





## Get started



1. Add up to 12 images. ToolPony detects each input format from its contents.
2. Set the output format for the batch, or choose each image’s format, quality and background.
3. Convert, compare the previews, and download individual results or a ZIP.







## Example



### Input



```
PNG · 64 × 32 px (transparent corners) → JPEG · white background
```

[Example · PNG](<https://toolpony.com/samples/toolpony-64x32.png>)

### Expected result



```
JPEG · 64 × 32 px (white corners)
```





<a id="case-study"></a>



## Check a transparent PNG before sending a JPEG



1. Choose “Try sample files” in the empty converter. It loads a transparent PNG and an opaque JPEG, both 64 × 32 px. The PNG is set to export as JPEG and the JPEG as PNG.
2. Convert and toggle each thumbnail to inspect the output. The JPEG has white corners. The PNG made from the JPEG also has opaque corners because that source already contained near-white pixels. To keep the original transparency, export the first file as PNG with a transparent background.
3. For a long banner, check the output dimensions shown in the row. A 10,000 × 100 px image exports at 8,192 × 82 px after proportional scaling. Changing the quality only affects encoding.
4. For a pixel check, open the sample JPEG in the color picker at (0, 0). Chromium decoded that corner as RGBA (255, 255, 243, 255). The PNG exported from the same JPEG kept those values, including the opaque alpha of 255.



[Image color picker](<https://toolpony.com/en/tools/image-color-picker/>)





## Try it

[Open full tool · Image converter](<https://toolpony.com/en/tools/image-converter/>)





## Good to know



PNG preserves transparency. JPEG is suited to opaque photographs. WebP supports transparency and adjustable quality. Your browser decodes the original; animation is reduced to one frame.







## Limits



Up to 12 images and 64 MiB per batch, with 20 MiB and 24 megapixels per input. PNG, JPEG and WebP output depends on browser encoders. Animated images become a single frame and original metadata is removed.



Choose PNG to keep transparency or JPEG for photos and compatibility. JPEG fills transparent areas with the selected background. WebP supports transparency and adjustable quality. AVIF appears as an output option when the browser can encode it.



For example, a transparent WebP logo can become a transparent PNG. A PNG that needs to work in a JPEG-only form can use a white background. A JPEG converted to PNG keeps its visible detail.





**Method references** [W3C · PNG](<https://www.w3.org/TR/png-3/>) · [WHATWG · HTML Canvas](<https://html.spec.whatwg.org/multipage/canvas.html#dom-canvas-toblob-dev>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fimage-converter%2F>)

[Documentation](https://docs.toolpony.com/en/guides/image-converter/)
