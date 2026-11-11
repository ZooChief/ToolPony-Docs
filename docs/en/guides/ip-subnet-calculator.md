# IP subnet calculator



Inspect IPv4 and IPv6 networks, masks, ranges and address counts, or test whether an IP belongs to a CIDR block.





## Get started



1. Use the example values or enter your own measurements.
2. Calculate, then copy the result or download the available details.







## Example



### Input



```
192.0.2.129 /27
```



### Expected result



```
Network 192.0.2.128/27, 30 usable hosts
```







## Try it



[Open full tool](<https://toolpony.com/en/tools/ip-subnet-calculator/>)







## Good to know



The calculation runs in your browser. Use consistent units in fields with no explicit unit.







## Calculation method



AND the address with a prefix mask to find the first address. The host part has 2^(address bits − prefix) possibilities. IPv4 /31 uses legacy host counting by default, with an RFC 3021 point-to-point option. An inline CIDR prefix takes precedence.



$$
\text{Addresses}=2^{w-p},\qquad w\in\{32,128\}
$$



IPv4 accepts a prefix length or a contiguous dotted mask. For example, 192.0.2.129 with 255.255.255.224 gives the same network as 192.0.2.129/27.



The prefix-size category follows the comparison tool’s A/B/C convention. The historical address class appears separately. Use the address range for CIDR membership. The optional point-to-point setting changes /31 host counting only.







## Calculation mode



**IPv4**

- IPv4 address or CIDR
- Prefix or subnet mask
- Use both addresses on /31 point-to-point links





**IPv6**

- IPv6 address or CIDR
- Prefix





**Check address membership**

- CIDR network
- Address to check

[Documentation](https://docs.toolpony.com/en/guides/ip-subnet-calculator/)
