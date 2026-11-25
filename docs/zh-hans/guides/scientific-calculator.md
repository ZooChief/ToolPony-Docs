# 科学计算器使用指南



计算包含幂、阶乘、三角函数、根式和对数的数学表达式。





## 示例



### 输入



```
sqrt(81) + 2^3 × sin(30)，角度制
```



### 预期结果



```
13
```





<a id="case-study"></a>



## 测量对角线



1. 一块面板长 12 厘米、宽 5 厘米。粘贴 √(12² + 5²)，对角线是 13 厘米。也可以选中式子的一部分，点 x² 只对选中部分求平方。
2. 算完对角线，选 DEG，输入 asin(5/Ans)，可得到 5 厘米边的对角，约 22.62°。



[运行示例](<https://toolpony.com/zh-hans/tools/scientific-calculator/#example-panel-diagonal>)





## 试一试

[打开完整工具 · 科学计算器](<https://toolpony.com/zh-hans/tools/scientific-calculator/>)





## 计算方法



按括号、后缀、乘方、乘除、加减的优先级计算。乘方从右结合，百分号表示除以 100。结果采用浮点运算。





**方法来源** [Python · Power and unary operators](<https://docs.python.org/3/reference/expressions.html#the-power-operator>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fscientific-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/scientific-calculator/)
