# IP 子網計算器使用指南



查看 IPv4 與 IPv6 的網絡地址、掩碼、範圍和地址數量，或判斷 IP 是否屬於一個 CIDR 網段。





## 示例



### 輸入



```
192.0.2.129 /27
```



### 預期結果



```
網絡 192.0.2.128/27，可用主機 30 個
```





<a id="case-study"></a>



## 覈對網段邊界



1. 192.0.2.128/27 含首末地址，末地址 .159 是 IPv4 廣播地址。下一個地址 .160 已在網段之外。輸入 IPv6 地址會標明版本不同。



[運行示例](<https://toolpony.com/zh-hant/tools/ip-subnet-calculator/#example-subnet-boundary>)





## 兩個 IPv6 端點



2001:db8::8/127 包含 ::8 和 ::9，分別爲第 1 和第 2 個地址。IPv6 沒有廣播地址。



[運行示例](<https://toolpony.com/zh-hant/tools/ip-subnet-calculator/#example-ipv6-endpoints>)







## 試一試

[打開完整工具 · IP 子網計算器](<https://toolpony.com/zh-hant/tools/ip-subnet-calculator/>)





## 計算方法



地址與前綴掩碼按位與得到首地址。主機位的可能組合數爲 2 的（地址位數減去前綴長度）次方。IPv4 /31 默認採用傳統主機計數，可切換 RFC 3021 點對點規則。地址自帶 CIDR 前綴時優先採用。



$$
\text{Addresses}=2^{w-p},\qquad w\in\{32,128\}
$$



IPv4 可輸入前綴長度或連續位的點分掩碼。192.0.2.129 與 255.255.255.224 的結果等同於 192.0.2.129/27。



前綴類別沿用對照工具的 A/B/C 口徑，按首地址位劃分的歷史類別另行顯示。用地址區間判斷 CIDR 歸屬，點對點選項只改變 /31 的主機計數。







## 計算模式





### IPv4



- IPv4 地址或 CIDR
- 前綴或子網掩碼
- /31 點對點鏈路使用兩個地址







### IPv6



- IPv6 地址或 CIDR
- 前綴







### 檢查地址歸屬



- CIDR 網段
- 待檢查地址







**方法來源** [IETF · RFC 4632 (CIDR)](<https://www.rfc-editor.org/rfc/rfc4632>) · [IETF · RFC 3021 (/31 links)](<https://www.rfc-editor.org/rfc/rfc3021>) · [IETF · RFC 5952 (IPv6 text)](<https://www.rfc-editor.org/rfc/rfc5952>)



[ZooChief](<https://docs.toolpony.com/zh-hant/about/>) · [反饋結果問題](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hant%2Fguides%2Fip-subnet-calculator%2F>)

[文檔站](https://docs.toolpony.com/zh-hant/guides/ip-subnet-calculator/)
