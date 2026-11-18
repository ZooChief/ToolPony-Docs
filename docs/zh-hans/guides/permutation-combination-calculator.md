# 排列组合计算器



精确计算有序与无序选择，支持可重复和不重复两种方式。





## 示例



### 输入



```
n=10，r=3，不重复
```



### 预期结果



```
排列 720，组合 120
```







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/permutation-combination-calculator/>)







## 计算方法



不重复时 nPr = n!/(n−r)!，nCr = nPr/r!。可重复时有序方案为 nʳ，无序方案为 C(n+r−1,r)。

[文档站](https://docs.toolpony.com/zh-hans/guides/permutation-combination-calculator/)
