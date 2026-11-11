# 直角三角形计算器



根据两个已知量求直角边、斜边和角度，支持从高、面积或周长反推。





## 开始使用



1. 请输入两个已知量，其中至少一项是边长、高、面积或周长。
2. 两个解互换两条直角边及两个锐角的标号。







## 示例



### 输入



```
c = 5，h = 2.4
```



### 预期结果



```
两条直角边为 3 和 4，面积为 6，周长为 12。任一边均可记为 a。
```







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/right-triangle-calculator/>)







## 使用提示



计算在浏览器内完成。无单位标记的字段请使用一致单位。







## 计算方法



c 是斜边，h 是斜边上的垂直高。长度统一单位，面积使用对应的平方单位。



$$
c^2=a^2+b^2,\quad h=ab/c,\quad S=ab/2,\quad P=a+b+c
$$



$$
a,b=\frac{\sqrt{c^2+2ch}\;\pm\;\sqrt{c^2-2ch}}{2}
$$

[文档站](https://docs.toolpony.com/zh-hans/guides/right-triangle-calculator/)
