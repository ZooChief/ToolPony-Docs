# 图片格式转换



一次添加不同格式的图片，自动识别输入类型。每张图可分别设置输出格式、质量和背景，结果可逐张下载或打包成 ZIP。





## 开始使用



1. 添加最多 12 张图片，工具会按内容识别每张图的输入格式。
2. 可统一设置输出格式，也可分别调整每张图的格式、质量和背景。
3. 转换后可对比预览，逐张下载或打包成 ZIP。







## 示例



### 输入



```
PNG · 64 × 32 px (四角透明) → JPEG · 白色背景
```

[示例 · PNG](<https://toolpony.com/samples/toolpony-64x32.png>)

### 预期结果



```
JPEG · 64 × 32 px (四角为白色)
```





<a id="case-study"></a>



## 把透明 PNG 发成 JPEG 前，怎样核对底色



1. 在空的图片转换器中点「试用样例文件」。会出现两张 64 × 32 像素的图片，一张是透明 PNG，预设输出 JPEG。另一张是白底 JPEG，预设输出 PNG。
2. 转换后点缩略图切换到输出。第一张的四角变白了。第二张转成 PNG 后四角也仍然不透明，近白色的像素已经写在源文件中。想保留原有透明区域，把第一张改为 PNG 输出，背景选「保留透明」。
3. 转换长条图片时看文件行里的输出尺寸。10,000 × 100 像素的横幅会等比缩为 8,192 × 82 像素。调整画质只会改变编码质量。
4. 还可以把样例 JPEG 放进图片颜色取样器，查看左上角 (0, 0)。在 Chromium 实测，解码后是 RGBA (255, 255, 243, 255)，呈近白色。由这张 JPEG 转出的 PNG 保留这组值，最后的 255 表示完全不透明。



[图片取色器](<https://toolpony.com/zh-hans/tools/image-color-picker/>)





## 试一试

[打开完整工具 · 图片格式转换](<https://toolpony.com/zh-hans/tools/image-converter/>)





## 使用提示



PNG 保留透明度，JPEG 适合不含透明区域的照片，WebP 支持透明度与质量调节。原图由浏览器解码；动图会变成单帧。







## 适用范围



每批最多 12 张、64 MiB，单张最多 20 MiB、2400 万像素。可用编解码格式由浏览器决定。动图输出单帧，不保留原始元数据。



需要保留透明区域时选 PNG，照片和通用兼容性优先时选 JPEG。JPEG 会用选定的背景色填充透明区域。WebP 支持透明度和质量调整。浏览器支持 AVIF 编码时会显示该输出选项。



例如，带透明区域的 WebP 标志可以转成透明 PNG。只接受 JPEG 的表单可以使用白底输出。JPEG 转成 PNG 后保留原图可见的细节。





**方法来源** [W3C · PNG](<https://www.w3.org/TR/png-3/>) · [WHATWG · HTML Canvas](<https://html.spec.whatwg.org/multipage/canvas.html#dom-canvas-toblob-dev>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fimage-converter%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/image-converter/)
