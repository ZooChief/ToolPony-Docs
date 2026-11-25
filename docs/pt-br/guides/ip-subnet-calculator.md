# Guia de uso · Calculadora de sub-redes IP



Inspecione redes IPv4 e IPv6, máscaras, intervalos e contagens de endereços, ou teste se um IP pertence a um bloco CIDR.





## Exemplo



### Entrada



```
192.0.2.129 /27
```



### Resultado esperado



```
Rede 192.0.2.128/27, 30 hosts utilizáveis
```





<a id="case-study"></a>



## Verificar um limite de sub-rede



1. 192.0.2.128/27 inclui .159, seu endereço de broadcast IPv4. .160 fica fora e IPv6 pertence a outra família.



[Executar exemplo](<https://toolpony.com/pt-br/tools/ip-subnet-calculator/#example-subnet-boundary>)





## Dois terminais IPv6



2001:db8::8/127 contém ::8 e ::9, nas posições 1 e 2. IPv6 não usa endereço de broadcast.



[Executar exemplo](<https://toolpony.com/pt-br/tools/ip-subnet-calculator/#example-ipv6-endpoints>)







## Experimente

[Abrir ferramenta completa · Calculadora de sub-redes IP](<https://toolpony.com/pt-br/tools/ip-subnet-calculator/>)





## Método de cálculo



E o endereço com uma máscara de prefixo para encontrar o primeiro endereço. A parte da máquina tem 2^(bits de endereço - prefixo) possibilidades. IPv4 / 31 usa a máquina legada contando por padrão, com uma opção RFC 3021 ponto- a- ponto. Um prefixo CIDR em linha tem precedência.



$$
\text{Addresses}=2^{w-p},\qquad w\in\{32,128\}
$$



O IPv4 aceita um comprimento de prefixo ou uma máscara pontilhada contígua. Por exemplo, 192.0.2.129 com 255.255.255.224 dá a mesma rede que 192.0.2.129/27.



A categoria de tamanho de prefixo segue a convenção A/B/C da ferramenta de comparação. A classe de endereço histórico aparece separadamente. Use o intervalo de endereços para a associação ao CIDR. A opção de configuração ponto- a- ponto muda apenas a contagem de máquinas /31.







## Modo de cálculo





### IPv4



- Endereço IPv4 ou CIDR
- Máscara de pré-fixação ou sub-rede
- Usar ambos os endereços em ligações /31 ponto- a- ponto







### IPv6



- Endereço IPv6 ou CIDR
- Prefixo







### Verificar a associação do endereço



- Rede CIDR
- Endereço a verificar







**Referências do método** [IETF · RFC 4632 (CIDR)](<https://www.rfc-editor.org/rfc/rfc4632>) · [IETF · RFC 3021 (/31 links)](<https://www.rfc-editor.org/rfc/rfc3021>) · [IETF · RFC 5952 (IPv6 text)](<https://www.rfc-editor.org/rfc/rfc5952>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fip-subnet-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/ip-subnet-calculator/)
