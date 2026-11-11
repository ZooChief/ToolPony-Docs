# Calculatrice de surface en pieds carrés



Estimation de la surface et du coût des matériaux pour neuf formes, avec des mesures mixtes et une déduction pour déchets.





## Prise en main



1. Choisissez la forme de la zone. Utilisez les dimensions extérieures pour la bordure ou l'anneau rectangle. Le secteur prend un rayon et un angle central.
2. Définissez l'unité à côté de chaque mesure. Entrez le nombre de zones identiques et éventuellement le prix par unité de zone sélectionnée.
3. Lire la surface nette en pieds carrés et mètres. Ajouter une réserve de déchets sous Plus d'options pour estimer la quantité à commander.







## Exemple



### Entrée



```
13 pi × 9 pi, quantité 1
```



### Résultat attendu



```
117 ft² (10,86965568 m²)
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/square-footage-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Convertir les dimensions en une unité commune, trouver la surface d'une forme, et de multiplier par la quantité. Coût utilise la surface avec n'importe quelle allocation sélectionnée, converti en unité de prix. Les dimensions frontalières sont mesurées à l'extérieur.



$$
A_{\rm border}=lw-(l-2b)(w-2b),\qquad A_{\rm ring}=\pi b(d-b)
$$



$$
A_{\rm sector}=r^2\theta/2,\qquad A_{\rm order}=q A(1+w/100)
$$



La largeur de la bordure b est mesurée à l'intérieur de chaque bord. Pour un anneau, d est le diamètre extérieur. Un rectangle extérieur de 13 pi × 9 pi avec une bordure de 2 pi a 72 pi2 de bordure par pièce.



Pour un secteur, r est le rayon et φ est l'angle en radians après toute conversion. Dans la formule de l'ordre, q est la quantité et w est l'écart en pourcentage.







## Mode de calcul



**Rectangle**

- Longueur
- Unité de longueur
- Largeur
- Unité de largeur
- Quantité
- Prix unitaire
- Prix par surface
- Décharge pour déchets · %





**Bordure rectangle**

- Longueur
- Unité de longueur
- Largeur
- Unité de largeur
- Largeur des frontières
- Unité de largeur des frontières
- Quantité
- Prix unitaire
- Prix par surface
- Décharge pour déchets · %





**Cercle**

- Diamètre
- Unité de diamètre
- Quantité
- Prix unitaire
- Prix par surface
- Décharge pour déchets · %





**Anneau**

- Diamètre extérieur
- Unité de diamètre extérieur
- Largeur des frontières
- Unité de largeur des frontières
- Quantité
- Prix unitaire
- Prix par surface
- Décharge pour déchets · %





**Triangle · trois côtés**

- Premier côté
- Première unité latérale
- Deuxième côté
- Deuxième unité latérale
- Troisième côté
- Troisième unité latérale
- Quantité
- Prix unitaire
- Prix par surface
- Décharge pour déchets · %





**Triangle · base et hauteur**

- Base
- Unité de base
- Hauteur du perpendiculaire
- Unité de hauteur perpendiculaire
- Quantité
- Prix unitaire
- Prix par surface
- Décharge pour déchets · %





**Trapèze**

- Premier côté parallèle
- Première unité parallèle latérale
- Deuxième côté parallèle
- Deuxième unité parallèle latérale
- Hauteur du perpendiculaire
- Unité de hauteur perpendiculaire
- Quantité
- Prix unitaire
- Prix par surface
- Décharge pour déchets · %





**Secteur circulaire**

- Rayon
- Unité de rayonnement
- Angle central
- Unité d'angle · Diplômes / Radians
- Quantité
- Prix unitaire
- Prix par surface
- Décharge pour déchets · %





**Parallélogramme**

- Base
- Unité de base
- Hauteur du perpendiculaire
- Unité de hauteur perpendiculaire
- Quantité
- Prix unitaire
- Prix par surface
- Décharge pour déchets · %

[Documentation](https://docs.toolpony.com/fr/guides/square-footage-calculator/)
