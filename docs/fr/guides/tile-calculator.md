# Calculatrice de quantité de carreaux



Estimer les tuiles, les boîtes et le coût à partir des dimensions des tuiles, de l'espacement des joints et de la zone à couvrir.





## Prise en main



1. Entrez la longueur, la largeur et l'espacement des tuiles. Un écart négatif signifie que les tuiles se chevauchent.
2. Entrez soit une zone connue, soit deux dimensions de pièce. Entrez les carreaux par boîte pour calculer les boîtes entières.
3. Pour couper et casser, entrez une allocation sous Plus d'options. L'outil estime la couverture par zone.







## Exemple



### Entrée



```
180 ft², carreaux de 12 in × 12 in, joint de ¼ in, 12 par boîte
```



### Résultat attendu



```
173 tuiles, 15 boîtes
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/tile-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Divisez la zone par (longueur de la tige + écart) × (largeur de la tige + écart), puis arrondissez-la. Les modèles de écart négatif se chevauchent. Ajoutez une allocation sélectionnée par l'utilisateur avant de convertir en boîtes entières.



$$
N=\left\lceil\frac{A}{(l+g)(w+g)}\right\rceil,\quad N_{\rm order}=\left\lceil N(1+a/100)\right\rceil
$$



À 180 pi2 avec 12 tuiles carrées et 1⁄4 d'écart, l'estimation est de 173 tuiles. Avec une allocation de 10% et 12 tuiles par boîte, commandez 191 tuiles, arrondies jusqu'à 16 boîtes.



Le modèle de couverture utilise une longueur et une largeur efficaces pour chaque tuile. L'allocation couvre la coupe, les motifs et la rupture.







## Mode de calcul



**Zone connue**

- Longueur du carrelage
- Unité de longueur du carrelage
- Largeur du carrelage
- Unité de largeur des carreaux
- Lacune ou chevauchement
- Unité d'écart ou de chevauchement
- Superficie totale
- Unité de surface
- Carreaux par boîte
- Prix unitaire
- Prix par
- Décharge pour déchets · %





**Salle rectangulaire**

- Longueur du carrelage
- Unité de longueur du carrelage
- Largeur du carrelage
- Unité de largeur des carreaux
- Lacune ou chevauchement
- Unité d'écart ou de chevauchement
- Longueur de la salle
- Unité de longueur de la chambre
- Largeur de la chambre
- Unité de largeur de la chambre
- Carreaux par boîte
- Prix unitaire
- Prix par
- Décharge pour déchets · %

[Documentation](https://docs.toolpony.com/fr/guides/tile-calculator/)
