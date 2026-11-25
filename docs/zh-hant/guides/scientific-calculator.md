# 科學計算器使用指南



計算包含冪、階乘、三角函數、根式和對數的數學表達式。





## 示例



### 輸入



```
sqrt(81) + 2^3 × sin(30)，角度制
```



### 預期結果



```
13
```





<a id="case-study"></a>



## 測量對角線



1. 一塊麪板長 12 釐米、寬 5 釐米。粘貼 √(12² + 5²)，對角線是 13 釐米。也可以選中式子的一部分，點 x² 只對選中部分求平方。
2. 算完對角線，選 DEG，輸入 asin(5/Ans)，可得到 5 釐米邊的對角，約 22.62°。



[運行示例](<https://toolpony.com/zh-hant/tools/scientific-calculator/#example-panel-diagonal>)





## 試一試

[打開完整工具 · 科學計算器](<https://toolpony.com/zh-hant/tools/scientific-calculator/>)





## 計算方法



按括號、後綴、乘方、乘除、加減的優先級計算。乘方從右結合，百分號表示除以 100。結果採用浮點運算。





**方法來源** [Python · Power and unary operators](<https://docs.python.org/3/reference/expressions.html#the-power-operator>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fscientific-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/scientific-calculator/)
