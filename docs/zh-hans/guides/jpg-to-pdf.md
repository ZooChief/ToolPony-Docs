# 图片转 PDF使用指南



添加最多 20 张图片，调整顺序、纸张、方向和边距。每张图片生成一页，再下载合成的 PDF。





## 开始使用



1. 从设备添加图片。
2. 用箭头调整页面顺序，选择 A4、US Letter 或图片尺寸。
3. 生成并下载 PDF。







## 示例



### 输入



```
一张横向 JPG，再添加一张纵向 PNG → A4，自动方向
```



### 预期结果



```
按顺序生成两页 PDF，第一页横向，第二页纵向。
```







## 试一试

[打开完整工具 · 图片转 PDF](<https://toolpony.com/zh-hans/tools/jpg-to-pdf/>)





## 使用提示



每张图片居中占一页，保持比例，不拉伸；透明区域为白色。浏览器解码时处理图片方向，JPEG 会重新编码。图片尺寸模式按每个像素对应一个 PDF 点生成页面，忽略方向和边距。文件不上传。







## 适用范围



输入总计 30 MB，每张最大 20 MB、2400 万像素，总像素最多 6000 万；编码后的图片总计最多 64 MB。支持浏览器可解码的 JPG、PNG、WebP、AVIF 和 GIF，动图只保留单帧。透明区域变为白色，JPEG 会重新编码，不保留元数据。





**方法来源** [PDF Association · ISO 32000-2](<https://pdfa.org/resource/iso-32000-2/>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fjpg-to-pdf%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/jpg-to-pdf/)
