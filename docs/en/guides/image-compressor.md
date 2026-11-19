# Image compressor



Choose up to 12 images and set JPEG or WebP, quality or target size per file, and an optional maximum side. Compare each result and download separately or as a ZIP.





## Get started



1. Choose up to 12 images and select JPEG or WebP.
2. Set quality or a file-size limit per image. The optional maximum side scales down large images proportionally. In Target size mode, allow resizing for additional reduction.
3. Compare each result. Download an individual file or put the successful images in a ZIP.







## Example



### Input



```
Two photos, WebP, 100 KB per image, maximum side 1200 px, resizing allowed
```



### Expected result



```
A ZIP of the WebP images that reach the target, each up to 100,000 bytes.
```







## Try it

[Open full tool · Image compressor](<https://toolpony.com/en/tools/image-compressor/>)





## Good to know



KB means 1,000 bytes here. Target size is an upper bound, not an exact byte count. JPEG/WebP are lossy. For a transparent PNG, choose WebP to retain transparency. A small original can become larger; the result reports that honestly.







## Limits



20 MB and 24 megapixels per image. Up to 64 MiB input and output per batch. The maximum side only shrinks larger images. JPEG and WebP use lossy encoding. Animations become still images and original metadata is removed.





**Method references** [WHATWG · HTML Canvas](<https://html.spec.whatwg.org/multipage/canvas.html#dom-canvas-toblob-dev>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fimage-compressor%2F>)

[Documentation](https://docs.toolpony.com/en/guides/image-compressor/)
