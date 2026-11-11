# JSON 格式化



粘贴 JSON，选择缩进后格式化或压缩。可复制结果或下载 JSON 文件，也可以按 Cmd/Ctrl + Enter 执行。





## 开始使用



1. 粘贴 JSON 文档。
2. 选择两个或四个空格后格式化；需要紧凑结果时选择压缩。
3. 复制结果或下载 JSON 文件。







## 示例



### 输入



```
{"name":"ToolPony","ready":true}
```



### 预期结果



```
{
  "name": "ToolPony",
  "ready": true
}
```







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/json-formatter/>)







## 使用提示



键名和字符串需要双引号。JSON 不允许注释和尾随逗号；工具会拒绝超出安全精度的数字，避免静默改写数值。







## 适用范围



最大 1 MB。拒绝无效 JSON 和超出安全精度的数字；不执行应用级 schema 校验。

[文档站](https://docs.toolpony.com/zh-hans/guides/json-formatter/)
