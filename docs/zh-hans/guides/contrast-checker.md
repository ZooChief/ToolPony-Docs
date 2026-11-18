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







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/contrast-checker/>)







## 计算方法



对比度为（较亮颜色相对亮度 + 0.05）除以（较暗颜色相对亮度 + 0.05）。达标判断使用未舍入数值。普通文本 AA 为 4.5:1，AAA 为 7:1，大号文本分别为 3:1 和 4.5:1。

[文档站](https://docs.toolpony.com/zh-hans/guides/contrast-checker/)
