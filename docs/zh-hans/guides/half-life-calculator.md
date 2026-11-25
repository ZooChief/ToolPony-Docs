# 半衰期计算器使用指南



已知任意三个衰变量求第四个，或换算半衰期、平均寿命和衰变常数。





## 示例



### 输入



```
50 个时间单位内从 100 衰减到 10
```



### 预期结果



```
半衰期约 15.0515
```







## 试一试

[打开完整工具 · 半衰期计算器](<https://toolpony.com/zh-hans/tools/half-life-calculator/>)





## 计算方法



指数衰变满足 N(t) = N₀ · 2^(−t/T)。T 为半衰期，平均寿命为 T/ln(2)，衰变常数为 ln(2)/T。换算时 ln(2) 取十位小数，各字段使用同一种时间单位。



$$
N(t)=N_0\,2^{-t/T},\qquad \lambda=\frac{\ln 2}{T},\qquad \tau=\frac1\lambda
$$



先选要求解的量。其余三个字段使用一致时间单位。初始量 100、半衰期 10 时，20 个时间单位后的剩余量为 25。







## 计算模式





### 求半衰期



- 剩余量
- 初始量
- 经过时间







### 求剩余量



- 初始量
- 经过时间
- 半衰期







### 求初始量



- 剩余量
- 经过时间
- 半衰期







### 求经过时间



- 剩余量
- 初始量
- 半衰期







### 换算衰变量



- 已知量 · 半衰期 / 平均寿命 / 衰变常数
- 数值







[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fhalf-life-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/half-life-calculator/)
