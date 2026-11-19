# 房貸計算器



比較固定利率房貸，計入首付、持有費用、提前還款和雙週還款。





## 示例



### 輸入



```
房價 400,000，首付 20%，期限 30 年，年利率 6%
```



### 預期結果



```
本息月供約 1,918.56
```







## 試一試

[打開完整工具 · 房貸計算器](<https://toolpony.com/zh-hant/tools/mortgage-calculator/>)





## 計算方法



每月利息爲剩餘本金乘以年利率再除以 12。費用按你填寫的年度金額和增長率估算。可按剩餘本金降至原房價 80% 停止計算按揭保險。雙週方案每兩週還半份月供，按年利率除以 26 計息。



$$
I_k=r B_{k-1},\qquad B_k=B_{k-1}-(M_k-I_k)
$$





[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fmortgage-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/mortgage-calculator/)
