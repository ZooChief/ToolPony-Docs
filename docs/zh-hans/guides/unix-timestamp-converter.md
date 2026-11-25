# Unix 时间戳转换使用指南



在 Unix 秒、毫秒、微秒、纳秒与 UTC 日期之间双向转换，保留每一位数字。





## 示例



### 输入



```
0 秒
```



### 预期结果



```
1970-01-01T00:00:00.000Z
```





<a id="case-study"></a>



## 纪元前一纳秒



1. 选择 ns 并输入 -1，UTC 时间是 1969-12-31T23:59:59.999999999Z。切换转换方向可取回原整数。
2. 核对不同时区的日志时，1970-01-01T05:44:59.999999999+05:45 也表示这一刻。可以单独复制某个单位，或把四种单位导出到同一行 CSV。



[运行示例](<https://toolpony.com/zh-hans/tools/unix-timestamp-converter/#example-before-epoch>)





## 试一试

[打开完整工具 · Unix 时间戳转换](<https://toolpony.com/zh-hans/tools/unix-timestamp-converter/>)





## 计算方法



Unix 时间从 1970-01-01T00:00:00Z 开始计数，忽略闰秒。支持 UTC 1900 至 9999 年，日期须带时区标记，小数秒最多 9 位。







## 计算模式





### 时间戳转日期



- Unix 时间戳
- 单位 · 秒 / 毫秒 / 微秒 / 纳秒







### 日期转时间戳



- 带时区偏移的 ISO 8601
- 单位 · 秒 / 毫秒 / 微秒 / 纳秒







**方法来源** [GNU · Seconds since the Epoch](<https://www.gnu.org/software/coreutils/manual/html_node/Seconds-since-the-Epoch.html>) · [IETF · RFC 3339](<https://www.rfc-editor.org/rfc/rfc3339>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Funix-timestamp-converter%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/unix-timestamp-converter/)
