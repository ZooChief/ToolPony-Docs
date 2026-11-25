# 比例计算器使用指南



求比例中的未知项，按精确分数缩放，或保持宽高比将图片放入画布并计算留白与裁切。





## 示例



### 输入



```
3:4 = x:20
```



### 预期结果



```
x=15
```





<a id="case-study"></a>



## 把横图完整放入海报



1. 将 1920 × 1080 的横图放入 1200 × 900 的画布。宽度决定缩放倍数为 5/8，成图为 1200 × 675。垂直方向还剩 225 像素，居中时上下各留 112.5 像素。



[运行示例](<https://toolpony.com/zh-hans/tools/ratio-calculator/#example-fit-poster>)





## 铺满同一块画布



铺满这张海报时以高度为准，缩放 5/6 后得到 1600 × 900。居中放置时，左右各裁去 200 像素。



[运行示例](<https://toolpony.com/zh-hans/tools/ratio-calculator/#example-fill-poster>)







## 试一试

[打开完整工具 · 比例计算器](<https://toolpony.com/zh-hans/tools/ratio-calculator/>)





## 计算方法



在分母非零时，A:B = C:D 等价于 A × D = B × C。完整放入取宽、高两个缩放倍数中较小的一个，铺满取较大的一个。留白与裁切分别给出每个方向的总量。







## 计算模式





### 求未知项



- A
- B
- C
- D







### 化简或缩放



- 第一项
- 第二项
- 缩放倍数







### 按倍数放大或缩小



- 第一项
- 第二项
- 缩放方式 · 倍数 / 完整放入 / 铺满裁切
- 方向 · 缩小 / 放大
- 倍数
- 画布宽度
- 画布高度







**方法来源** [W3C · Object fitting](<https://www.w3.org/TR/css-images-3/#the-object-fit>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fratio-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/ratio-calculator/)
