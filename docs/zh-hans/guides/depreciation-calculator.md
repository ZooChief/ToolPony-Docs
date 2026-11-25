# 折旧计算器使用指南



生成直线法、余额递减法或年数总和法的年度折旧表。





## 示例



### 输入



```
原值 17,500，残值 2,500，6 年，直线法
```



### 预期结果



```
每年折旧 2,500
```







## 试一试

[打开完整工具 · 折旧计算器](<https://toolpony.com/zh-hans/tools/depreciation-calculator/>)





## 计算方法



直线法将可折旧金额按使用年限均分。余额递减法按系数除以年限乘以期初账面价值，达到残值即停止。年数总和法按剩余年限权重分配，每年进行金额舍入。



$$
D_{\mathrm{SL}}=\frac{C-S}{n},\quad D_{k,\mathrm{SYD}}=(C-S)\frac{n-k+1}{n(n+1)/2}
$$







## 计算模式





### 直线法



- 资产原值
- 残值
- 使用年限
- 舍入精度 · 两位小数 / 取整数







### 余额递减法



- 资产原值
- 残值
- 使用年限
- 折旧系数
- 舍入精度 · 两位小数 / 取整数







### 年数总和法



- 资产原值
- 残值
- 使用年限
- 舍入精度 · 两位小数 / 取整数







[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fdepreciation-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/depreciation-calculator/)
