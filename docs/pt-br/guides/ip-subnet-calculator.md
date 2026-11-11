# Calculadora de sub-redes IP



Inspecione redes IPv4 e IPv6, máscaras, intervalos e contagens de endereços, ou teste se um IP pertence a um bloco CIDR.





## Primeiros passos



1. Use o exemplo ou insira seus próprios valores.
2. Calcule, copie o resultado ou baixe os detalhes disponíveis.







## Exemplo



### Entrada



```
192.0.2.129 /27
```



### Resultado esperado



```
Rede 192.0.2.128/27, 30 hosts utilizáveis
```







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/ip-subnet-calculator/>)







## Notas de uso



O cálculo é feito no seu navegador. Use unidades consistentes.







## Método de cálculo



E o endereço com uma máscara de prefixo para encontrar o primeiro endereço. A parte da máquina tem 2^(bits de endereço - prefixo) possibilidades. IPv4 / 31 usa a máquina legada contando por padrão, com uma opção RFC 3021 ponto- a- ponto. Um prefixo CIDR em linha tem precedência.



$$
\text{Addresses}=2^{w-p},\qquad w\in\{32,128\}
$$



O IPv4 aceita um comprimento de prefixo ou uma máscara pontilhada contígua. Por exemplo, 192.0.2.129 com 255.255.255.224 dá a mesma rede que 192.0.2.129/27.



A categoria de tamanho de prefixo segue a convenção A/B/C da ferramenta de comparação. A classe de endereço histórico aparece separadamente. Use o intervalo de endereços para a associação ao CIDR. A opção de configuração ponto- a- ponto muda apenas a contagem de máquinas /31.







## Modo de cálculo



**IPv4**

- Endereço IPv4 ou CIDR
- Máscara de pré-fixação ou sub-rede
- Usar ambos os endereços em ligações /31 ponto- a- ponto





**IPv6**

- Endereço IPv6 ou CIDR
- Prefixo





**Verificar a associação do endereço**

- Rede CIDR
- Endereço a verificar

[Documentação](https://docs.toolpony.com/pt-br/guides/ip-subnet-calculator/)
