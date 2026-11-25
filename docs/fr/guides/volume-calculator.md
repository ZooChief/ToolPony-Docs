# Guide pratique · Calculatrice de volume



Calculez une capacité ou un volume en litres ou en unités cubes. Les diamètres extérieur et intérieur et la longueur d’un tube donnent le volume de sa paroi.





## Exemple



### Entrée



```
Sphère avec rayon 2 m
```



### Résultat attendu



```
≈33.5103 m³
```





<a id="case-study"></a>



## Estimer le volume d’eau sous la marque de remplissage



1. Mesurez le diamètre intérieur et la profondeur jusqu’au repère. Lancez l’exemple pour un réservoir cylindrique de 1 m de diamètre et de 1,2 m de profondeur utile. Le rayon est réglé sur 0,5 m et la sortie en litres.
2. Le volume vaut π × 0,5² × 1,2 m³, soit environ 942,48 L. Saisir le diamètre dans le champ du rayon quadruple le résultat à cause du carré.
3. Abaissez le repère de 0,2 m et saisissez 1 m de profondeur. La capacité passe à environ 785,40 L. Les deux repères délimitent donc environ 157,08 L.



[Essayer l’exemple](<https://toolpony.com/fr/tools/volume-calculator/#example-tank-fill-line>)





## Paroi et capacité



Pour un mètre de tube de diamètres extérieur 60 mm et intérieur 48 mm, la paroi occupe environ 1,018 L et le tube peut contenir 1,810 L. Le CSV conserve les deux résultats et les deux diamètres.



[Essayer l’exemple](<https://toolpony.com/fr/tools/volume-calculator/#example-pipe-wall>)







## Essayer

[Ouvrir l’outil complet · Calculatrice de volume](<https://toolpony.com/fr/tools/volume-calculator/>)





## Méthode de calcul



Le volume d'un prisme est sa surface de base multipliée par la hauteur perpendiculaire. Un cône ou une pyramide divise ce produit par trois. Un tube creux soustrait le cylindre intérieur. Un capuchon sphérique accepte deux dimensions.



$$
V_{\mathrm{cone}}=\tfrac13\pi r^2h,\qquad V_{\mathrm{sphere}}=\tfrac43\pi r^3
$$







## Mode de calcul





### Sphère



- Rayon
- Unité de rayonnement
- Volume unité







### Cône



- Rayon
- Unité de rayonnement
- Hauteur du perpendiculaire
- Unité de hauteur perpendiculaire
- Volume unité







### Cube



- Longueur des bords
- Unité de longueur des bords
- Volume unité







### Cylindre



- Rayon
- Unité de rayonnement
- Hauteur du perpendiculaire
- Unité de hauteur perpendiculaire
- Volume unité







### Réservoir rectangulaire



- Longueur
- Unité de longueur
- Largeur
- Unité de largeur
- Hauteur du perpendiculaire
- Unité de hauteur perpendiculaire
- Volume unité







### Capsule



- Rayon
- Unité de rayonnement
- Longueur du cylindre droit
- Unité droite de longueur du cylindre
- Volume unité







### Couvercle sphérique



- Rayon de la sphère
- Unité du rayon de la sphère
- Rayon de la base
- Unité de rayon de base
- Hauteur du culot
- Unité de hauteur du culot
- Cap avec les deux rayons connus · Petite casquette / Couvercle plus grand
- Volume unité







### Frustum conique



- Rayon du premier bout
- Unité de rayon de première extrémité
- Rayon de deuxième extrémité
- Unité de rayon de deuxième extrémité
- Hauteur du perpendiculaire
- Unité de hauteur perpendiculaire
- Volume unité







### Ellipsoïde



- Première semi-axe
- Première unité semi-axe
- Deuxième semi-axe
- Deuxième unité semi-axe
- Troisième demi-axe
- Troisième unité semi-axe
- Volume unité







### Pyramide carrée



- Longueur des bords
- Unité de longueur des bords
- Hauteur du perpendiculaire
- Unité de hauteur perpendiculaire
- Volume unité







### Tube creux



- Diamètre extérieur
- Unité de diamètre extérieur
- Diamètre intérieur
- Unité de diamètre intérieur
- Longueur
- Unité de longueur
- Volume unité







### Hémisphère



- Rayon
- Unité de rayonnement
- Volume unité







### Tore annulaire



- Rayon de ligne centrale
- Unité de rayon de ligne centrale
- Rayon du tube
- Unité du rayon du tube
- Volume unité







**Références de la méthode** [BIPM · SI](<https://www.bipm.org/en/publications/si-brochure>) · [NIST DLMF · Triaxial ellipsoids](<https://dlmf.nist.gov/19.33>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fvolume-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/volume-calculator/)
