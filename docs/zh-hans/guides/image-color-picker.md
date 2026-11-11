# 图片取色器



点击示例或选择图片。点击任意位置，或输入像素坐标读取 HEX 与 RGBA。可以复制颜色，也可导出带坐标的 CSV 色板。





## 开始使用



1. 使用内置示例或选择图片。
2. 点击位置，或输入 X 与 Y 后采样原图的对应像素。
3. 复制 HEX 或导出最多十六条带坐标与 RGBA 的 CSV。







## 示例



### 输入



```
内置示例，X = 32，Y = 32
```



### 预期结果



```
#285eaa · RGBA 40, 94, 170, 255
```







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/image-color-picker/>)







## 使用提示



预览可能缩小，但采样仍读取对应原始像素。浏览器可能在解码时转换色彩配置。







## 适用范围



支持 JPG、PNG、WebP、AVIF 或 GIF，上限 20 MB 与 2400 万像素。读取浏览器解码后的像素。左上角坐标为 (0, 0)，最多记录 16 个采样点。

[文档站](https://docs.toolpony.com/zh-hans/guides/image-color-picker/)
