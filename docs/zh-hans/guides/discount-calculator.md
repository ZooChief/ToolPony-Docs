# 折扣计算器



叠加多个折扣、减去固定优惠券，并对折后价格计税。





## 示例



### 输入



```
原价 100，先减 20% 再减 10%
```



### 预期结果



```
折后 72，相当于减 28%
```







## 试一试

[打开完整工具 · 折扣计算器](<https://toolpony.com/zh-hans/tools/discount-calculator/>)





## 计算方法



依次应用百分比折扣，再减固定优惠，最后计税。最多 10 个 0% 至 100% 的折扣率。



连续打八折和九折，剩下原价的 0.8 × 0.9。按顺序填写折扣率，再按需添加优惠券或税。



已知折后价或节省金额时可用反推模式。反推采用单个税前折扣。







## 计算模式



**应用折扣**

- 原价
- 减免百分比列表
- 固定优惠金额
- 税率 · %





**反推原价**

- 折后价
- 折扣类型 · 百分比 / 固定金额
- 折扣





**求折扣率与节省金额**

- 原价
- 已知金额 · 折后价 / 节省金额
- 金额





**由节省金额求价格**

- 节省金额
- 折扣率 · %







[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fdiscount-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/discount-calculator/)
