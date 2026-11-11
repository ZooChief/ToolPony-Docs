# YAML 转 JSON



粘贴 YAML 文档，一键转换为排版整齐的 JSON。映射使用字符串键，结果可复制或下载。





## 开始使用



1. 粘贴一份 YAML 文档，映射键应为字符串。
2. 转换为 JSON。
3. 检查结果，然后复制或下载。







## 示例



### 输入



```
name: ToolPony
ready: true
```



### 预期结果



```
{
  "name": "ToolPony",
  "ready": true
}
```







## 试一试



[打开完整工具](<https://toolpony.com/zh-hans/tools/yaml-to-json/>)







## 使用提示



不支持多文档、自定义标签、循环别名，以及 JSON 无法表达的值。若某个值应当是字符串而非布尔值或数字，请使用引号。







## 适用范围



最大 1 MB。不支持自定义标签、多文档、非字符串键、过量别名、循环结构或无法被 JSON 保真的值。

[文档站](https://docs.toolpony.com/zh-hans/guides/yaml-to-json/)
