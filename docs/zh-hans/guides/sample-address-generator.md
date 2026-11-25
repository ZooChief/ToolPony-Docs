# 虚拟地址生成器使用指南



生成 18 个国家和地区的地址测试数据，支持行政区选择、本地地址格式及批量导出。





## 开始使用



1. 选择国家或地区和行政区，设置条数及联系信息。
2. 使用相同的随机种子和设置即可复现同一批。可复制单个字段或导出 TXT、CSV、JSON。
3. 选择「保存到本机」后，地址样例保存在当前浏览器，可在工具内移除。







## 示例



### 输入



```
德国 · 柏林 · 随机种子 pony-demo
```



### 预期结果



```
Testperson 001
Beispielstraße 4957
10115 Berlin
Deutschland
```





<a id="case-study"></a>



## 核对加拿大带单元号的地址



1. 选择加拿大安大略省，种子填 label-review，生成两条带单元号的测试地址，关闭联系信息。相同设置会得到同一组样例。
2. 在下载的文本里，单元号位于门牌号前，中间是连字符。城市行的 ON 与邮编之间有两个空格。JSON 还会把各个地址部分分别保存在独立字段中。



[运行示例](<https://toolpony.com/zh-hans/tools/sample-address-generator/#example-canadian-label>)





## 试一试

[打开完整工具 · 虚拟地址生成器](<https://toolpony.com/zh-hans/tools/sample-address-generator/>)





## 计算方法



每批最多 100 条。城市与邮编用于展示格式，街道与收件人由工具合成。电话使用保留示例号或占位符。适用于表单及软件测试。





**方法来源** [USPS · Publication 28, §213](<https://pe.usps.com/text/pub28/28c2_003.htm>) · [Canada Post · Civic address](<https://www.canadapost-postescanada.ca/cpc/en/support/articles/addressing-guidelines/civic-address.page>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fsample-address-generator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/sample-address-generator/)
