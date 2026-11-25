# Guia de uso · Calculadora de área superficial



Calcule a área superficial de um sólido. Para tanques, tubos e outros sólidos com bases planas, escolha as faces a cobrir e compare as áreas.





## Exemplo



### Entrada



```
Esfera com raio de 2 m
```



### Resultado esperado



```
≈50.2655 m²
```





<a id="case-study"></a>



## Revestir um tanque aberto



1. Informe as medidas internas de 120 cm por 0,8 m e profundidade de 450 mm. Escolha a lateral e uma base para cobrir as quatro paredes e o fundo.
2. As paredes somam 1,80 m² e o fundo 0,96 m². São 2,76 m² antes de emendas e perdas. Todas as faces incluem a tampa e somam 3,72 m².



[Executar exemplo](<https://toolpony.com/pt-br/tools/surface-area-calculator/#example-open-tank>)





## Experimente

[Abrir ferramenta completa · Calculadora de área superficial](<https://toolpony.com/pt-br/tools/surface-area-calculator/>)





## Método de cálculo



Uma superfície fechada inclui todas as bases. A área de cada base é calculada pelas suas dimensões. A superfície do elipsoide é avaliada numericamente com uma integral elíptica simétrica.



$$
A_{\mathrm{cylinder}}=2\pi r^2+2\pi rh,\qquad A_{\mathrm{sphere}}=4\pi r^2
$$







## Modo de cálculo





### Esfera



- Raio
- Unidade de raios
- Unidade de área







### Cone



- Raio
- Unidade de raios
- Altura perpendicular
- Unidade de altura perpendicular
- Faces a cobrir · Todas as faces / Só a superfície lateral
- Unidade de área







### Cubo



- Comprimento da borda
- Unidade de comprimento da borda
- Faces a cobrir · Todas as faces / Só a superfície lateral / Lateral e uma base
- Unidade de área







### Cilindro



- Raio
- Unidade de raios
- Altura perpendicular
- Unidade de altura perpendicular
- Faces a cobrir · Todas as faces / Só a superfície lateral / Lateral e uma base
- Unidade de área







### Tanque retangular



- Comprimento
- Unidade de comprimento
- Largura
- Unidade da largura
- Altura perpendicular
- Unidade de altura perpendicular
- Faces a cobrir · Todas as faces / Só a superfície lateral / Lateral e uma base
- Unidade de área







### Cápsula



- Raio
- Unidade de raios
- Comprimento do cilindro reto
- Unidade de comprimento do cilindro reto
- Unidade de área







### Tampa esférica



- Raio da esfera
- Unidade do raio da esfera
- Raio da base
- Unidade de raio de base
- Altura da tampa
- Unidade de altura da tampa
- Tampa com ambos os raios conhecidos · Tampa mais pequena / Tampa maior
- Faces a cobrir · Todas as faces / Só a superfície lateral
- Unidade de área







### Frusto cónico



- Raio da primeira extremidade
- Unidade de raio de primeira extremidade
- Raio da segunda extremidade
- Unidade de raio de segunda extremidade
- Altura perpendicular
- Unidade de altura perpendicular
- Faces a cobrir · Todas as faces / Só a superfície lateral / Lateral e primeira base / Lateral e segunda base
- Unidade de área







### Elipsoide



- Primeiro semieixo
- Primeira unidade de semieixo
- Segundo semieixo
- Segunda unidade de semieixo
- Terceiro semieixo
- Terceira unidade de semieixo
- Unidade de área







### Pirâmide quadrada



- Comprimento da borda
- Unidade de comprimento da borda
- Altura perpendicular
- Unidade de altura perpendicular
- Faces a cobrir · Todas as faces / Só a superfície lateral
- Unidade de área







### Tubo oco



- Diâmetro exterior
- Unidade de diâmetro exterior
- Diâmetro interno
- Unidade de diâmetro interior
- Comprimento
- Unidade de comprimento
- Faces a cobrir · Todas as faces / Só a superfície lateral / Lateral e uma base
- Unidade de área







### Hemisfério



- Raio
- Unidade de raios
- Faces a cobrir · Todas as faces / Só a superfície lateral
- Unidade de área







### Toro anular



- Raio da linha central
- Unidade de raio central
- Raio do tubo
- Unidade do raio do tubo
- Unidade de área







**Referências do método** [BIPM · SI](<https://www.bipm.org/en/publications/si-brochure>) · [NIST DLMF · Triaxial ellipsoids](<https://dlmf.nist.gov/19.33>)



[ZooChief](<https://docs.toolpony.com/pt-br/about/>) · [Relatar um problema no resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fpt-br%2Fguides%2Fsurface-area-calculator%2F>)

[Documentação](https://docs.toolpony.com/pt-br/guides/surface-area-calculator/)
