# UUID 生成器使用指南



使用浏览器的安全随机源生成第 4 版 UUID。





## 示例



### 输入



```
生成 1 个标识符
```



### 预期结果



```
格式示例：550e8400-e29b-41d4-a716-446655440000
```





<a id="case-study"></a>



## 为导入文件准备 27 个 ID



1. 生成 27 个大写 UUID。每个标识符的第三段以 4 开头，第四段以 8、9、A 或 B 开头。
2. 最后一页是第 25 至 27 行。可以复制第 27 行核对单条记录，也可以下载文本文件，一次导入原顺序的全部 27 行。



[运行示例](<https://toolpony.com/zh-hans/tools/uuid-generator/#example-import-ids>)





## 试一试

[打开完整工具 · UUID 生成器](<https://toolpony.com/zh-hans/tools/uuid-generator/>)





## 计算方法



第 4 版 UUID 使用 122 个随机位，另有 6 位用于版本和变体。每批最多 500 个。





**方法来源** [IETF · RFC 9562 (UUID)](<https://www.rfc-editor.org/rfc/rfc9562>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fuuid-generator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/uuid-generator/)
