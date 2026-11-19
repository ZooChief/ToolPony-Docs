# 圖片格式轉換



一次添加不同格式的圖片，自動識別輸入類型。每張圖可分別設置輸出格式、質量和背景，結果可逐張下載或打包成 ZIP。





## 開始使用



1. 添加最多 12 張圖片，工具會按內容識別每張圖的輸入格式。
2. 可統一設置輸出格式，也可分別調整每張圖的格式、質量和背景。
3. 轉換後可對比預覽，逐張下載或打包成 ZIP。







## 示例



### 輸入



```
PNG · 64 × 32 px (四角透明) → JPEG · 白色背景
```

[示例 · PNG](<https://toolpony.com/samples/toolpony-64x32.png>)

### 預期結果



```
JPEG · 64 × 32 px (四角爲白色)
```





<a id="case-study"></a>



## 把透明 PNG 發成 JPEG 前，怎樣覈對底色



1. 在空的圖片轉換器中點「試用樣例文件」。會出現兩張 64 × 32 像素的圖片，一張是透明 PNG，預設輸出 JPEG。另一張是白底 JPEG，預設輸出 PNG。
2. 轉換後點縮略圖切換到輸出。第一張的四角變白了。第二張轉成 PNG 後四角也仍然不透明，近白色的像素已經寫在源文件中。想保留原有透明區域，把第一張改爲 PNG 輸出，背景選「保留透明」。
3. 轉換長條圖片時看文件行裏的輸出尺寸。10,000 × 100 像素的橫幅會等比縮爲 8,192 × 82 像素。調整畫質只會改變編碼質量。
4. 還可以把樣例 JPEG 放進圖片顏色取樣器，查看左上角 (0, 0)。在 Chromium 實測，解碼後是 RGBA (255, 255, 243, 255)，呈近白色。由這張 JPEG 轉出的 PNG 保留這組值，最後的 255 表示完全不透明。



[圖片取色器](<https://toolpony.com/zh-hant/tools/image-color-picker/>)





## 試一試

[打開完整工具 · 圖片格式轉換](<https://toolpony.com/zh-hant/tools/image-converter/>)





## 使用提示



PNG 保留透明度，JPEG 適合不含透明區域的照片，WebP 支持透明度與質量調節。原圖由瀏覽器解碼；動圖會變成單幀。







## 適用範圍



每批最多 12 張、64 MiB，單張最多 20 MiB、2400 萬像素。可用編解碼格式由瀏覽器決定。動圖輸出單幀，不保留原始元數據。



需要保留透明區域時選 PNG，照片和通用兼容性優先時選 JPEG。JPEG 會用選定的背景色填充透明區域。WebP 支持透明度和質量調整。瀏覽器支持 AVIF 編碼時會顯示該輸出選項。



例如，帶透明區域的 WebP 標誌可以轉成透明 PNG。只接受 JPEG 的表單可以使用白底輸出。JPEG 轉成 PNG 後保留原圖可見的細節。





**方法來源** [W3C · PNG](<https://www.w3.org/TR/png-3/>) · [WHATWG · HTML Canvas](<https://html.spec.whatwg.org/multipage/canvas.html#dom-canvas-toblob-dev>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fimage-converter%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/image-converter/)
