# 大数计算器



使用精确大整数和十进制系数计算，支持为除法与平方根设置舍入位数。





## 示例



### 输入



```
9,007,199,254,740,993 + 7
```



### 预期结果



```
9007199254741000
```







## 试一试

[打开完整工具 · 大数计算器](<https://toolpony.com/zh-hans/tools/big-number-calculator/>)





## 计算方法



加减乘、整数幂和整数运算使用 BigInt 系数。除法舍入到所选小数位数。平方根可截断或就近舍入。结果范围内支持正负整数指数。



$$
x=m\cdot 10^e,\quad x_1x_2=(m_1m_2)\cdot 10^{e_1+e_2}
$$





[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fbig-number-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/big-number-calculator/)
