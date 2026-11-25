# 颜色转换器使用指南



将 CSS 颜色转换为 HEX、RGB、HSL 和 OKLCH，保留透明度并预览广色域颜色的 sRGB 替代色。





## 示例



### 输入



```
rgb(102, 51, 153)
```



### 预期结果



```
#663399，hsl(270 50% 40%)
```





<a id="case-study"></a>



## 为 sRGB 素材准备广色域替代色



1. 粘贴 color(display-p3 0 1 0 / 70%)。这个绿色超出 sRGB，两个色样分别展示输入和映射后的替代色。按此映射生成的 HEX 为 \#00FB29B3。
2. 复制 RGB 一行可保留精确的 0.7 不透明度。八位 HEX 把不透明度存成一个字节 B3，即 179/255。



[运行示例](<https://toolpony.com/zh-hans/tools/color-converter/#example-wide-gamut>)





## 试一试

[打开完整工具 · 颜色转换器](<https://toolpony.com/zh-hans/tools/color-converter/>)





## 计算方法



HEX 将 sRGB 通道舍入到字节。超出 sRGB 色域时，沿 OKLCH 色度映射后导出。输入预览保留原色彩空间。





**方法来源** [W3C · CSS Color 4](<https://www.w3.org/TR/css-color-4/>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fcolor-converter%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/color-converter/)
