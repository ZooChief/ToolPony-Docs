# Guía de uso · Calculadora de área superficial



Calcula la superficie de un sólido. En depósitos, tubos y otros sólidos con bases planas, elige qué caras cubrir y compara sus áreas.





## Ejemplo



### Entrada



```
Esfera con radio 2 m
```



### Resultado esperado



```
≈50.2655 m²
```





<a id="case-study"></a>



## Revestir un depósito abierto



1. Introduce las medidas interiores de 120 cm por 0,8 m y una profundidad de 450 mm. Elige la superficie lateral y una base para cubrir las cuatro paredes y el fondo.
2. Las paredes suman 1,80 m² y el fondo 0,96 m², para un total de 2,76 m² sin juntas ni desperdicio. Todas las caras incluyen la tapa y suman 3,72 m².



[Ejecutar ejemplo](<https://toolpony.com/es/tools/surface-area-calculator/#example-open-tank>)





## Pruébalo

[Abrir herramienta completa · Calculadora de área superficial](<https://toolpony.com/es/tools/surface-area-calculator/>)





## Método de cálculo



Una superficie cerrada incluye todas sus bases. El área de cada base se calcula a partir de sus dimensiones. La superficie del elipsoide se evalúa con una integral elíptica simétrica.



$$
A_{\mathrm{cylinder}}=2\pi r^2+2\pi rh,\qquad A_{\mathrm{sphere}}=4\pi r^2
$$







## Modo de cálculo





### Esfera



- Radio
- Unidad radiactiva
- Unidad de área







### Cono



- Radio
- Unidad radiactiva
- Altura perpendicular
- Unidad de altura perpendicular
- Caras que se cubren · Todas las caras / Solo superficie lateral
- Unidad de área







### Cubo



- Longitud del borde
- Unidad de longitud de borde
- Caras que se cubren · Todas las caras / Solo superficie lateral / Lateral y una base
- Unidad de área







### Cilindro



- Radio
- Unidad radiactiva
- Altura perpendicular
- Unidad de altura perpendicular
- Caras que se cubren · Todas las caras / Solo superficie lateral / Lateral y una base
- Unidad de área







### Tanque rectangular



- Longitud
- Unidad de longitud
- Ancho
- Unidad de ancho
- Altura perpendicular
- Unidad de altura perpendicular
- Caras que se cubren · Todas las caras / Solo superficie lateral / Lateral y una base
- Unidad de área







### Cápsula



- Radio
- Unidad radiactiva
- Longitud del cilindro recto
- Unidad de longitud del cilindro
- Unidad de área







### Capa esférica



- Radio de la esfera
- Unidad del radio de la esfera
- Radio de la base
- Unidad de radio de base
- Altura de la tapa
- Unidad de altura de capa
- Cap con ambos radios conocidos · Capa más pequeña / Gorro más grande
- Caras que se cubren · Todas las caras / Solo superficie lateral
- Unidad de área







### frusto cónico



- Radio de primer extremo
- Unidad de radio de primer extremo
- Segundo radio de final
- Segunda unidad de radio de extremo
- Altura perpendicular
- Unidad de altura perpendicular
- Caras que se cubren · Todas las caras / Solo superficie lateral / Lateral y primera base / Lateral y segunda base
- Unidad de área







### Elipsoide



- Primer semi-eje
- Primera unidad semi-eje
- Segundo semi-eje
- Segunda unidad semi-eje
- Tercer semi-eje
- Tercera unidad semi-eje
- Unidad de área







### pirámide cuadrada



- Longitud del borde
- Unidad de longitud de borde
- Altura perpendicular
- Unidad de altura perpendicular
- Caras que se cubren · Todas las caras / Solo superficie lateral
- Unidad de área







### Tubo hueco



- Diámetro exterior
- Unidad de diámetro exterior
- Diámetro interior
- Unidad de diámetro interior
- Longitud
- Unidad de longitud
- Caras que se cubren · Todas las caras / Solo superficie lateral / Lateral y una base
- Unidad de área







### Hemisferio



- Radio
- Unidad radiactiva
- Caras que se cubren · Todas las caras / Solo superficie lateral
- Unidad de área







### Toro anular



- Radius de Centerline
- Unidad de radio central
- Radio del tubo
- Unidad del radio del tubo
- Unidad de área







**Fuentes del método** [BIPM · SI](<https://www.bipm.org/en/publications/si-brochure>) · [NIST DLMF · Triaxial ellipsoids](<https://dlmf.nist.gov/19.33>)



[ZooChief](<https://docs.toolpony.com/es/about/>) · [Informar de un problema con el resultado](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fes%2Fguides%2Fsurface-area-calculator%2F>)

[Documentación](https://docs.toolpony.com/es/guides/surface-area-calculator/)
