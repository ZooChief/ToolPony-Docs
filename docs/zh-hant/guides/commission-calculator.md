# 佣金計算器使用指南



求銷售額、佣金率或佣金，也可計算底傭疊加階梯佣金。





## 示例



### 輸入



```
銷售額 16,500，佣金率 8.25%
```



### 預期結果



```
佣金 1,361.25
```







## 試一試

[打開完整工具 · 佣金計算器](<https://toolpony.com/zh-hant/tools/commission-calculator/>)





## 計算方法



單一費率乘以銷售額。階梯表每行的閾值是該檔上限，百分比僅作用於該檔收入，固定佣金在進入該檔時支付一次。



$$
C=C_0+\sum_i s_i r_i\quad\text{(percentage tiers)}
$$







## 計算模式





### 求佣金



- 銷售額
- 佣金率 · %







### 求費率



- 銷售額
- 佣金金額







### 求銷售額



- 佣金率 · %
- 佣金金額







### 底傭與階梯



- 銷售額
- 底傭
- 底傭類型 · 固定金額 / 銷售額百分比
- 每行填寫檔位上限和費率（% 或固定金額）。用 \* 表示不限。







[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fcommission-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/commission-calculator/)
