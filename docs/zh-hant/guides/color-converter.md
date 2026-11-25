# 顏色轉換器使用指南



將 CSS 顏色轉換爲 HEX、RGB、HSL 和 OKLCH，保留透明度並預覽廣色域顏色的 sRGB 替代色。





## 示例



### 輸入



```
rgb(102, 51, 153)
```



### 預期結果



```
#663399，hsl(270 50% 40%)
```





<a id="case-study"></a>



## 爲 sRGB 素材準備廣色域替代色



1. 粘貼 color(display-p3 0 1 0 / 70%)。這個綠色超出 sRGB，兩個色樣分別展示輸入和映射後的替代色。按此映射生成的 HEX 爲 \#00FB29B3。
2. 複製 RGB 一行可保留精確的 0.7 不透明度。八位 HEX 把不透明度存成一個字節 B3，即 179/255。



[運行示例](<https://toolpony.com/zh-hant/tools/color-converter/#example-wide-gamut>)





## 試一試

[打開完整工具 · 顏色轉換器](<https://toolpony.com/zh-hant/tools/color-converter/>)





## 計算方法



HEX 將 sRGB 通道舍入到字節。超出 sRGB 色域時，沿 OKLCH 色度映射後導出。輸入預覽保留原色彩空間。





**方法來源** [W3C · CSS Color 4](<https://www.w3.org/TR/css-color-4/>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fcolor-converter%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/color-converter/)
