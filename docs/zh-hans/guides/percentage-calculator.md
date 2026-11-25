# 百分比计算器使用指南



计算百分比和百分点变化，按两次折扣求成交价或反推原价。





## 开始使用



1. 要算 240 的 15%，选择「求百分比对应的数值」。已知部分为 36 且知道总量或比例时，选择相应反推模式。
2. 有先后顺序和原值时，选「百分比变化」。两个正数没有基准先后时，选「百分比差异」。
3. 15% 输入 15。可用下面的例子核对计算结果。







## 示例



### 输入



```
240 的 15%
```



### 预期结果



```
36
```





<a id="case-study"></a>



## 同一件商品连续打折



1. 原价 250，先减 20% 得 200，再按 200 减 10%，成交价为 180。两次合计降价 28%。点击反推验证可以还原原价。



[运行示例](<https://toolpony.com/zh-hans/tools/percentage-calculator/#example-two-discounts>)





## 从 4% 提高到 5%



注册率从 4% 提高到 5%，相差 1 个百分点。以原来的 4% 为基准，相对增幅为 1 ÷ 4 = 25%。



[运行示例](<https://toolpony.com/zh-hans/tools/percentage-calculator/#example-percentage-points>)







## 试一试

[打开完整工具 · 百分比计算器](<https://toolpony.com/zh-hans/tools/percentage-calculator/>)





## 计算方法



相对变化率以原值的绝对值为分母。两个百分率相减得到百分点变化。连续增减的系数相乘。对称差异率以两数绝对值的均值为分母。



$$
x=yp/100,\quad p=100x/y,\quad y=100x/p
$$



$$
\Delta\%=100\frac{x_1-x_0}{|x_0|},\quad D\%=200\frac{|x_1-x_0|}{|x_1|+|x_0|}
$$



80 增至 100 的变化率为 25%，因为原值是 80。同样两个数的百分比差异约为 22.22%，因为分母是均值 90。



涨 20% 后为 120，用「反推原值」可得 100。变化率 −100% 无法反推。原值为 0 时无法计算百分比变化率。



实测为 90、参考为 96 时，绝对百分误差为 6.25%。相对于这个正参考值的有符号结果为 −6.25%。







## 计算模式





### 求百分比对应的数值



- 百分比 · %
- 数值







### 求所占百分比



- 部分
- 总量







### 求总量



- 部分
- 百分比 · %







### 百分比变化



- 数值含义 · 一般数值 / 百分率 (%)
- 原值
- 新值







### 百分比差异



- 数值一
- 数值二







### 带符号数值的差异率



- 数值一
- 数值二







### 按比例增减



- 原值
- 变化率（带正负） · %
- 第二次增减 · %







### 反推原值



- 新值
- 变化率（带正负） · %
- 第二次增减 · %







### 百分误差



- 实测值
- 参考值
- 误差口径 · 绝对值 / 相对于参考值的有符号误差







**方法来源** [Eurostat · Percentage point](<https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Glossary:Percentage_point>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fpercentage-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/percentage-calculator/)
