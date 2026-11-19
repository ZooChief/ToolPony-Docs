# 房贷计算器



比较固定利率房贷，计入首付、持有费用、提前还款和双周还款。





## 示例



### 输入



```
房价 400,000，首付 20%，期限 30 年，年利率 6%
```



### 预期结果



```
本息月供约 1,918.56
```







## 试一试

[打开完整工具 · 房贷计算器](<https://toolpony.com/zh-hans/tools/mortgage-calculator/>)





## 计算方法



每月利息为剩余本金乘以年利率再除以 12。费用按你填写的年度金额和增长率估算。可按剩余本金降至原房价 80% 停止计算按揭保险。双周方案每两周还半份月供，按年利率除以 26 计息。



$$
I_k=r B_{k-1},\qquad B_k=B_{k-1}-(M_k-I_k)
$$





[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fmortgage-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/mortgage-calculator/)
