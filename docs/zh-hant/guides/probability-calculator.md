# 概率計算器使用指南



輸入事件概率或觀測次數，比較兩個條件概率，反求獨立事件概率，或計算重複試驗與正態區間。





## 示例



### 輸入



```
獨立事件 A = 0.31，B = 0.56
```



### 預期結果



```
至少一個發生：0.6964
```





<a id="case-study"></a>



## 兩場工作坊的出席情況



1. 50 人中，18 人兩場都到，12 人僅參加上午場（AM），6 人僅參加下午場（PM），14 人兩場都沒到。下午場 24 人裏有 18 人也參加了上午場，佔 75%。上午場 30 人裏有 18 人下午又來了，佔 60%。



[運行示例](<https://toolpony.com/zh-hant/tools/probability-calculator/#example-workshop-attendance>)





## 試一試

[打開完整工具 · 概率計算器](<https://toolpony.com/zh-hant/tools/probability-calculator/>)





## 計算方法



並集概率是兩個邊際概率之和減去交集概率。在 B 發生的條件下，A 的概率爲 P(A ∩ B) / P(B)。獨立事件的交集概率等於兩個邊際概率的乘積。



$$
P(A\cup B)=P(A)+P(B)-P(A\cap B)
$$



$$
P(A\cap B)=P(A)P(B)\quad\text{(independent)}
$$







## 計算模式





### 兩個獨立事件



- A 的概率
- B 的概率







### 已知交集



- 輸入方式 · 概率 / 觀測次數
- A 的概率
- B 的概率
- 兩個事件均發生
- 事件 A 名稱
- 事件 B 名稱
- A ∩ B
- A ∩ ¬B
- ¬A ∩ B
- ¬A ∩ ¬B







### 反求獨立事件



- 第一已知量 · A 的概率 / B 的概率 / A 不發生 / B 不發生 / 兩個事件均發生 / 至少一個事件發生 / 恰好一個事件發生 / 兩個事件均不發生
- 第一概率
- 第二已知量 · A 的概率 / B 的概率 / A 不發生 / B 不發生 / 兩個事件均發生 / 至少一個事件發生 / 恰好一個事件發生 / 兩個事件均不發生
- 第二概率







### 重複獨立試驗



- A 的概率
- A 的試驗次數
- B 的概率
- B 的試驗次數







### 正態分佈區間



- 均值
- 標準差
- 下界
- 上界







**方法來源** [OpenStax · Contingency Tables](<https://openstax.org/books/introductory-statistics-2e/pages/3-4-contingency-tables>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fprobability-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/probability-calculator/)
