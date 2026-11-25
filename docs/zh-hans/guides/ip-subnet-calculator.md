# IP 子网计算器使用指南



查看 IPv4 与 IPv6 的网络地址、掩码、范围和地址数量，或判断 IP 是否属于一个 CIDR 网段。





## 示例



### 输入



```
192.0.2.129 /27
```



### 预期结果



```
网络 192.0.2.128/27，可用主机 30 个
```





<a id="case-study"></a>



## 核对网段边界



1. 192.0.2.128/27 含首末地址，末地址 .159 是 IPv4 广播地址。下一个地址 .160 已在网段之外。输入 IPv6 地址会标明版本不同。



[运行示例](<https://toolpony.com/zh-hans/tools/ip-subnet-calculator/#example-subnet-boundary>)





## 两个 IPv6 端点



2001:db8::8/127 包含 ::8 和 ::9，分别为第 1 和第 2 个地址。IPv6 没有广播地址。



[运行示例](<https://toolpony.com/zh-hans/tools/ip-subnet-calculator/#example-ipv6-endpoints>)







## 试一试

[打开完整工具 · IP 子网计算器](<https://toolpony.com/zh-hans/tools/ip-subnet-calculator/>)





## 计算方法



地址与前缀掩码按位与得到首地址。主机位的可能组合数为 2 的（地址位数减去前缀长度）次方。IPv4 /31 默认采用传统主机计数，可切换 RFC 3021 点对点规则。地址自带 CIDR 前缀时优先采用。



$$
\text{Addresses}=2^{w-p},\qquad w\in\{32,128\}
$$



IPv4 可输入前缀长度或连续位的点分掩码。192.0.2.129 与 255.255.255.224 的结果等同于 192.0.2.129/27。



前缀类别沿用对照工具的 A/B/C 口径，按首地址位划分的历史类别另行显示。用地址区间判断 CIDR 归属，点对点选项只改变 /31 的主机计数。







## 计算模式





### IPv4



- IPv4 地址或 CIDR
- 前缀或子网掩码
- /31 点对点链路使用两个地址







### IPv6



- IPv6 地址或 CIDR
- 前缀







### 检查地址归属



- CIDR 网段
- 待检查地址







**方法来源** [IETF · RFC 4632 (CIDR)](<https://www.rfc-editor.org/rfc/rfc4632>) · [IETF · RFC 3021 (/31 links)](<https://www.rfc-editor.org/rfc/rfc3021>) · [IETF · RFC 5952 (IPv6 text)](<https://www.rfc-editor.org/rfc/rfc5952>)



[ZooChief](<https://docs.toolpony.com/zh-hans/about/>) · [反馈结果问题](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fzh-hans%2Fguides%2Fip-subnet-calculator%2F>)

[文档站](https://docs.toolpony.com/zh-hans/guides/ip-subnet-calculator/)
