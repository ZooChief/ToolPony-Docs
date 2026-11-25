# IP subnet calculator guide



Inspect IPv4 and IPv6 networks, masks, ranges and address counts, or test whether an IP belongs to a CIDR block.





## Example



### Input



```
192.0.2.129 /27
```



### Expected result



```
Network 192.0.2.128/27, 30 usable hosts
```





<a id="case-study"></a>



## Check a subnet boundary



1. The /27 from 192.0.2.128 ends at .159 inclusive. The last address is the IPv4 broadcast, .160 is outside, and an IPv6 address has a different family.



[Run example](<https://toolpony.com/en/tools/ip-subnet-calculator/#example-subnet-boundary>)





## Two IPv6 endpoints



2001:db8::8/127 includes ::8 and ::9. Their positions are 1 and 2. IPv6 has no broadcast address.



[Run example](<https://toolpony.com/en/tools/ip-subnet-calculator/#example-ipv6-endpoints>)







## Try it

[Open full tool · IP subnet calculator](<https://toolpony.com/en/tools/ip-subnet-calculator/>)





## Calculation method



AND the address with a prefix mask to find the first address. The host part has 2^(address bits − prefix) possibilities. IPv4 /31 uses legacy host counting by default, with an RFC 3021 point-to-point option. An inline CIDR prefix takes precedence.



$$
\text{Addresses}=2^{w-p},\qquad w\in\{32,128\}
$$



IPv4 accepts a prefix length or a contiguous dotted mask. For example, 192.0.2.129 with 255.255.255.224 gives the same network as 192.0.2.129/27.



The prefix-size category follows the comparison tool’s A/B/C convention. The historical address class appears separately. Use the address range for CIDR membership. The optional point-to-point setting changes /31 host counting only.







## Calculation mode





### IPv4



- IPv4 address or CIDR
- Prefix or subnet mask
- Use both addresses on /31 point-to-point links







### IPv6



- IPv6 address or CIDR
- Prefix







### Check address membership



- CIDR network
- Address to check







**Method references** [IETF · RFC 4632 (CIDR)](<https://www.rfc-editor.org/rfc/rfc4632>) · [IETF · RFC 3021 (/31 links)](<https://www.rfc-editor.org/rfc/rfc3021>) · [IETF · RFC 5952 (IPv6 text)](<https://www.rfc-editor.org/rfc/rfc5952>)



[ZooChief](<https://docs.toolpony.com/en/about/>) · [Report a problem with this result](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fen%2Fguides%2Fip-subnet-calculator%2F>)

[Documentation](https://docs.toolpony.com/en/guides/ip-subnet-calculator/)
