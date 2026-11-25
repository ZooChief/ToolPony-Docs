# 概率计算器使用指南



输入事件概率或观测次数，比较两个条件概率，反求独立事件概率，或计算重复试验与正态区间。





## 示例



### 输入



```
独立事件 A = 0.31，B = 0.56
```



### 预期结果



```
至少一个发生：0.6964
```





<a id="case-study"></a>



## 两场工作坊的出席情况



1. 50 人中，18 人两场都到，12 人仅参加上午场（AM），6 人仅参加下午场（PM），14 人两场都没到。下午场 24 人里有 18 人也参加了上午场，占 75%。上午场 30 人里有 18 人下午又来了，占 60%。



[运行示例](<https://toolpony.com/zh-hans/tools/probability-calculator/#example-workshop-attendance>)





## 试一试

[打开完整工具 · 概率计算器](<https://toolpony.com/zh-hans/tools/probability-calculator/>)





## 计算方法



并集概率是两个边际概率之和减去交集概率。在 B 发生的条件下，A 的概率为 P(A ∩ B) / P(B)。独立事件的交集概率等于两个边际概率的乘积。



$$
P(A\cup B)=P(A)+P(B)-P(A\cap B)
$$



$$
P(A\cap B)=P(A)P(B)\quad\text{(independent)}
$$







## 计算模式





### 两个独立事件



- A 的概率
- B 的概率







### 已知交集



- 输入方式 · 概率 / 观测次数
- A 的概率
- B 的概率
- 两个事件均发生
- 事件 A 名称
- 事件 B 名称
- A ∩ B
- A ∩ ¬B
- ¬A ∩ B
- ¬A ∩ ¬B







### 反求独立事件



- 第一已知量 · A 的概率 / B 的概率 / A 不发生 / B 不发生 / 两个事件均发生 / 至少一个事件发生 / 恰好一个事件发生 / 两个事件均不发生
- 第一概率
- 第二已知量 · A 的概率 / B 的概率 / A 不发生 / B 不发生 / 两个事件均发生 / 至少一个事件发生 / 恰好一个事件发生 / 两个事件均不发生
- 第二概率







### 重复独立试验



- A 的概率
- A 的试验次数
- B 的概率
- B 的试验次数







### 正态分布区间



- 均值
- 标准差
- 下界
- 上界







**方法来源** [OpenStax · Contingency Tables](<https://openstax.org/books/introductory-statistics-2e/pages/3-4-contingency-tables>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fprobability-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/probability-calculator/)
