# Calculadora de distâncias



Encontrar a distância entre dois pontos 2D ou 3D, ou estimar a distância de superfície entre as coordenadas geográficas.





## Primeiros passos



1. Use o exemplo ou insira seus próprios valores.
2. Calcule, copie o resultado ou baixe os detalhes disponíveis.







## Exemplo



### Entrada



```
2D: (0, 0) a (3, 4)
```



### Resultado esperado



```
Distância 5
```







## Experimente



[Abrir ferramenta completa](<https://toolpony.com/pt-br/tools/distance-calculator/>)







## Notas de uso



O cálculo é feito no seu navegador. Use unidades consistentes.







## Método de cálculo



A distância cartesiana utiliza a norma Euclidiana. Os modos geográficos utilizam a aproximação do elipsoide WGS 84 e Lambert. Os pontos quase antipodais utilizam uma aproximação esférica.



$$
d=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2+(z_2-z_1)^2}
$$



Use o modo 2D ou 3D para coordenadas que já compartilham uma escala linear. Converta ambos os pontos para a mesma unidade primeiro.



Para as coordenadas geográficas, o Norte e o Leste são positivos. Use o modo grau- minuto- segundo quando uma pesquisa indicar campos angulares separados. O resultado estima um caminho de superfície elipsoidal.







## Modo de cálculo



**2D**

- X1
- Y1
- X2
- Y2





**3D**

- X1
- Y1
- Z1
- X2
- Y2
- Z2





**Latitude e longitude**

- Primeira latitude · °
- Primeira longitude · °
- Segunda latitude · °
- Segunda longitude · °





**Graus, minutos e segundos**

- Primeiros graus de latitude
- Primeiros minutos de latitude
- Primeiros segundos de latitude
- Primeiro hemisfério de latitude · N / S
- Primeiros graus de longitude
- Primeiros minutos de longitude
- Primeiros segundos de longitude
- Primeiro hemisfério de longitude · E / W
- Segundos graus de latitude
- Segundos minutos de latitude
- Segundos de latitude
- Segundo hemisfério de latitude · N / S
- Segundo grau de longitude
- Segundos minutos de longitude
- Segundos de longitude
- Hemisfério de segunda longitude · E / W

[Documentação](https://docs.toolpony.com/pt-br/guides/distance-calculator/)
