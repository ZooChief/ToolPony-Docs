# 舍入计算器



按小数位或二进制分数步长精确舍入，支持九种规则。





## 示例



### 输入



```
−2.5，个位，半数取偶
```



### 预期结果



```
−2
```







## 试一试

[打开完整工具 · 舍入计算器](<https://toolpony.com/zh-hans/tools/rounding-calculator/>)





## 计算方法



将精确余数与半个步长比较，恰好一半时按方向或奇偶规则处理。最接近模式在平局时远离零。



$$
x=qs+r,\qquad 0\le r<s,\qquad r=\tfrac{s}{2}\text{ at a tie}
$$



位数 2 表示保留到百分位，0 表示个位，−2 表示百位。分数步长可舍入到 1/4 或 1/16 等倍数。



半数取偶只在正好一半时选择偶数倍。例如 −2.5 得 −2，−3.5 得 −4。向上取整始终朝正无穷方向。





[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Frounding-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/rounding-calculator/)
