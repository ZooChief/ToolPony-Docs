# Guide pratique · Calculatrice d’aire



Trouvez la zone des formes planes en onze modes avec des unités d'entrée mixtes et une unité de sortie sélectionnable.





## Exemple



### Entrée



```
Un rectangle de 4 m sur 3 m
```



### Résultat attendu



```
12 m²
```





<a id="case-study"></a>



## Découper un anneau



1. Pour un joint plat de diamètre extérieur 60 mm avec un trou de 40 mm, saisissez des rayons de 30 et 20 mm. Choisissez mm² pour l’aire.
2. L’aire vaut 500π mm², soit environ 1 570,80 mm². Les deux découpes totalisent 100π mm, soit environ 314,16 mm. Le fichier contient chaque circonférence et les mesures saisies.



[Essayer l’exemple](<https://toolpony.com/fr/tools/area-calculator/#example-gasket>)





## Essayer

[Ouvrir l’outil complet · Calculatrice d’aire](<https://toolpony.com/fr/tools/area-calculator/>)





## Méthode de calcul



Les dimensions se convertissent en mètres avant le calcul. Le triangle à trois côtés utilise la formule Heron. Un secteur utilise la moitié du rayon carré fois son angle en radians.



$$
A_{\mathrm{rectangle}}=lw,\qquad A_{\mathrm{sector}}=\tfrac12 r^2\theta
$$



$$
A_{\mathrm{triangle}}=\sqrt{s(s-a)(s-b)(s-c)},\quad s=\tfrac12(a+b+c)
$$







## Mode de calcul





### Rectangle



- Longueur
- Unité de longueur
- Largeur
- Unité de largeur
- Unité de surface







### Carré



- Longueur du côté
- Unité du côté
- Unité de surface







### Triangle · trois côtés



- Premier côté
- Première unité latérale
- Deuxième côté
- Deuxième unité latérale
- Troisième côté
- Troisième unité latérale
- Unité de surface







### Triangle · base et hauteur



- Longueur de la base
- Unité de la base
- Hauteur du perpendiculaire
- Unité de hauteur perpendiculaire
- Unité de surface







### Trapèze



- Premier côté parallèle
- Première unité parallèle latérale
- Deuxième côté parallèle
- Deuxième unité parallèle latérale
- Hauteur du perpendiculaire
- Unité de hauteur perpendiculaire
- Unité de surface







### Cercle



- Rayon
- Unité de rayonnement
- Unité de surface







### Secteur circulaire



- Rayon
- Unité de rayonnement
- Angle central
- Unité d’angle · Degrés / Radians
- Unité de surface







### Ellipse



- Première semi-axe
- Première unité semi-axe
- Deuxième semi-axe
- Deuxième unité semi-axe
- Unité de surface







### Parallélogramme



- Longueur de la base
- Unité de la base
- Hauteur du perpendiculaire
- Unité de hauteur perpendiculaire
- Unité de surface







### Couronne circulaire



- Rayon extérieur
- Unité de rayon extérieur
- Rayon intérieur
- Unité de rayon intérieur
- Unité de surface







### Polygone régulier



- Longueur du côté
- Unité du côté
- Nombre de côtés
- Unité de surface







**Références de la méthode** [BIPM · SI](<https://www.bipm.org/en/publications/si-brochure>) · [NIST DLMF · Lengths of plane curves](<https://dlmf.nist.gov/19.30>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Farea-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/area-calculator/)
