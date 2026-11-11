# 圖片取色器



點擊示例或選擇圖片。點擊任意位置，或輸入像素座標讀取 HEX 與 RGBA。可以複製顏色，也可導出帶座標的 CSV 色板。





## 開始使用



1. 使用內置示例或選擇圖片。
2. 點擊位置，或輸入 X 與 Y 後採樣原圖的對應像素。
3. 複製 HEX 或導出最多十六條帶座標與 RGBA 的 CSV。







## 示例



### 輸入



```
內置示例，X = 32，Y = 32
```



### 預期結果



```
#285eaa · RGBA 40, 94, 170, 255
```







## 試一試



[打開完整工具](<https://toolpony.com/zh-hant/tools/image-color-picker/>)







## 使用提示



預覽可能縮小，但採樣仍讀取對應原始像素。瀏覽器可能在解碼時轉換色彩配置。







## 適用範圍



支持 JPG、PNG、WebP、AVIF 或 GIF，上限 20 MB 與 2400 萬像素。讀取瀏覽器解碼後的像素。左上角座標爲 (0, 0)，最多記錄 16 個採樣點。

[文檔站](https://docs.toolpony.com/zh-hant/guides/image-color-picker/)
