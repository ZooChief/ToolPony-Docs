# 长除法计算器



支持整数与小数除法，查看商、余数、小数结果以及长除法步骤。





## 示例



### 输入



```
12,345 ÷ 67
```



### 预期结果



```
商 184，余数 17
```







## 试一试

[打开完整工具 · 长除法计算器](<https://toolpony.com/zh-hans/tools/long-division-calculator/>)





## 计算方法



被除数和除数按同一 10 的幂放大。整数商向零取整，带符号余数满足被除数 = 商 × 除数 + 余数。步骤表使用绝对值。



$$
a=bq+r,\quad q=\operatorname{trunc}(a/b),\quad |r|<|b|
$$

[文档站](https://docs.toolpony.com/zh-hans/guides/long-division-calculator/)
