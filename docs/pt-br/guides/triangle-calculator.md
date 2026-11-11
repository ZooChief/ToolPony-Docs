# Calculadora de triângulos



Calcule ângulos, alturas, medianas e centros a partir de três medidas.





## Primeiros passos



1. Insira três medidas, sendo ao menos uma de um lado.
2. Selecione radianos para π/2. Em LLA, tanto um ângulo agudo quanto seu suplementar podem ser válidos.
3. Na tabela, A está na origem e B no semieixo x positivo. Exporte a tabela selecionada em CSV.







## Exemplo



### Entrada



```
a = 7, b = 10, A = 30°
```



### Resultado esperado



```
Duas soluções, com c ≈ 13,55923 e 3,76127.
```







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/triangle-calculator/>)







## Notas de uso



O cálculo é feito no seu navegador. Use unidades consistentes.







## Método de cálculo



Use uma única unidade de comprimento. O lado a fica oposto ao ângulo A, e o mesmo vale para b/B e c/C. Só os ângulos não definem o tamanho.



$$
\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C},\qquad a^2=b^2+c^2-2bc\cos A
$$



$$
\Delta=\sqrt{s(s-a)(s-b)(s-c)},\quad s=\tfrac{a+b+c}{2},\quad h_a=2\Delta/a
$$



$$
m_a=\tfrac12\sqrt{2b^2+2c^2-a^2},\qquad r=\Delta/s,\qquad R=abc/(4\Delta)
$$







## Modo de cálculo



**Medidas conhecidas**

- Lado a
- Lado b
- Lado c
- Ângulo A
- Ângulo B
- Ângulo C
- Unidade angular · Graus / Radianos





**Três lados (LLL)**

- Lado a
- Lado b
- Lado c





**Dois lados e ângulo entre eles (LAL)**

- Lado b
- Lado c
- Ângulo A · °





**Dois ângulos e um lado**

- Ângulo A · °
- Ângulo B · °
- Lado conhecido · a / b / c
- Lado





**Dois lados e um ângulo oposto (LLA)**

- Lado a
- Lado b
- Ângulo A · °





**Catetos do triângulo retângulo**

- Lado a
- Lado b

[Documentação](https://docs.toolpony.com/pt-br/guides/triangle-calculator/)
