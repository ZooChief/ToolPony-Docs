# 颜色对比度检查



比较两个不透明颜色，并检查是否达到 WCAG 2.2 对比度阈值。





## 示例



### 输入



```
#000000 放在 #FFFFFF 上
```



### 预期结果



```
21:1
```





<a id="case-study"></a>



## 白底正文选哪种灰色能达到 AA



1. 试算白底上的 \#777777，对比度约为 4.48:1。即使保留一位小数看起来是 4.5，按未经舍入的比值判断，普通大小的正文仍未达到 WCAG AA。
2. 保持白色背景，改试 \#767676，对比度约为 4.54:1，普通正文达到 AA。两组颜色都达到大号文字的 3:1 阈值。
3. 核对设计稿中实际渲染的文字色和背景色。如果文字叠在图片或半透明层上，请取背景中对比最弱处的最终颜色进行检查。工具给出的是这一组实色的结果。





## 试一试

[打开完整工具 · 颜色对比度检查](<https://toolpony.com/zh-hans/tools/contrast-checker/>)





## 计算方法



对比度为（较亮颜色相对亮度 + 0.05）除以（较暗颜色相对亮度 + 0.05）。达标判断使用未舍入数值。普通文本 AA 为 4.5:1，AAA 为 7:1，大号文本分别为 3:1 和 4.5:1。





**方法来源** [W3C · WCAG 2.2 (1.4.3, AA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html>) · [W3C · WCAG 2.2 (1.4.6, AAA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-enhanced.html>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fcontrast-checker%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/contrast-checker/)
