# URL 编码与解码使用指南



编码或解码 URL、组件和表单值，也可按顺序编辑查询参数，保留同名参数与空值。





## 示例



### 输入



```
编码组件：a+b & c
```



### 预期结果



```
a%2Bb%20%26%20c
```





<a id="case-study"></a>



## 保留搜索词里的加号



1. 用表单值模式编码 C++ &amp; tea，结果是 C%2B%2B+%26+tea。原有加号写成 %2B，空格写成 +，&amp; 写成 %26。反向转换可还原原文；切换到 URI 组件模式，空格会写成 %20。
2. 在“查询参数”中打开含两个 tag 的案例，把第二个值改为 UI &amp; UX。首个 tag、空值与 \#filters 都会保留，改过的值会写成 UI+%26+UX。



[运行示例](<https://toolpony.com/zh-hans/tools/url-encoder-decoder/#example-query-plus>)





## 试一试

[打开完整工具 · URL 编码与解码](<https://toolpony.com/zh-hans/tools/url-encoder-decoder/>)





## 计算方法



组件会转义保留分隔符，完整 URL 保留分隔符，表单值以 + 表示空格。编辑查询参数时，参数名和值分别按表单规则编码，路径和片段保留。





**方法来源** [IETF · RFC 3986](<https://www.rfc-editor.org/rfc/rfc3986>) · [WHATWG · Form encoding](<https://url.spec.whatwg.org/#application/x-www-form-urlencoded>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Furl-encoder-decoder%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/url-encoder-decoder/)
