# 比例計算器使用指南



求比例中的未知項，按精確分數縮放，或保持寬高比將圖片放入畫布並計算留白與裁切。





## 示例



### 輸入



```
3:4 = x:20
```



### 預期結果



```
x=15
```





<a id="case-study"></a>



## 把橫圖完整放入海報



1. 將 1920 × 1080 的橫圖放入 1200 × 900 的畫布。寬度決定縮放倍數爲 5/8，成圖爲 1200 × 675。垂直方向還剩 225 像素，居中時上下各留 112.5 像素。



[運行示例](<https://toolpony.com/zh-hant/tools/ratio-calculator/#example-fit-poster>)





## 鋪滿同一塊畫布



鋪滿這張海報時以高度爲準，縮放 5/6 後得到 1600 × 900。居中放置時，左右各裁去 200 像素。



[運行示例](<https://toolpony.com/zh-hant/tools/ratio-calculator/#example-fill-poster>)







## 試一試

[打開完整工具 · 比例計算器](<https://toolpony.com/zh-hant/tools/ratio-calculator/>)





## 計算方法



在分母非零時，A:B = C:D 等價於 A × D = B × C。完整放入取寬、高兩個縮放倍數中較小的一個，鋪滿取較大的一個。留白與裁切分別給出每個方向的總量。







## 計算模式





### 求未知項



- A
- B
- C
- D







### 化簡或縮放



- 第一項
- 第二項
- 縮放倍數







### 按倍數放大或縮小



- 第一項
- 第二項
- 縮放方式 · 倍數 / 完整放入 / 鋪滿裁切
- 方向 · 縮小 / 放大
- 倍數
- 畫布寬度
- 畫布高度







**方法來源** [W3C · Object fitting](<https://www.w3.org/TR/css-images-3/#the-object-fit>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fratio-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/ratio-calculator/)
