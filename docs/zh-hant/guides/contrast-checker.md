# 顏色對比度檢查使用指南



檢查文字和界面組件在實色或半透明圖層上的對比度，並試用達到 WCAG 閾值的文字色。





## 示例



### 輸入



```
#000000 放在 #FFFFFF 上
```



### 預期結果



```
21:1
```





<a id="case-study"></a>



## 白底正文選哪種灰色能達到 AA



1. 試算白底上的 \#777777，對比度約爲 4.48:1。即使保留一位小數看起來是 4.5，按未經舍入的比值判斷，普通大小的正文仍未達到 WCAG AA。
2. 保持白色背景，改試 \#767676，對比度約爲 4.54:1，普通正文達到 AA。兩組顏色都達到大號文字的 3:1 閾值。
3. 覈對設計稿中實際渲染的文字色和背景色。如果文字疊在圖片或半透明層上，請取背景中對比最弱處的最終顏色進行檢查。工具給出的是這一組實色的結果。
4. 試用白底上的 \#00000080，合成後文字色是 \#7F7F7F，對比度約爲 4.00∶1。應用建議的 \#767676，普通文字對比度升至 4.54∶1。



[運行示例](<https://toolpony.com/zh-hant/tools/contrast-checker/#example-translucent-text>)





## 試一試

[打開完整工具 · 顏色對比度檢查](<https://toolpony.com/zh-hant/tools/contrast-checker/>)





## 計算方法



對比度爲（較亮顏色相對亮度 + 0.05）除以（較暗顏色相對亮度 + 0.05）。達標判斷使用未舍入數值。普通文本 AA 爲 4.5:1，AAA 爲 7:1，大號文本分別爲 3:1 和 4.5:1。





**方法來源** [W3C · WCAG 2.2 (1.4.3, AA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html>) · [W3C · WCAG 2.2 (1.4.6, AAA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-enhanced.html>) · [W3C · Non-text contrast](<https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html>) · [W3C · Source-over compositing](<https://www.w3.org/TR/compositing-1/#simplealphacompositing>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fcontrast-checker%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/contrast-checker/)
