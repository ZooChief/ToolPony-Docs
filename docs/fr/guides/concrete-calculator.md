# Calculatrice de quantité de béton



Estimer le volume de béton, le poids et les sacs entiers pour les dalles, les semelles, les tubes, les bordures et les escaliers.





## Prise en main



1. Choisissez la forme correspondante et les unités de réglage pour chaque mesure. Un tube utilise des diamètres extérieurs et intérieurs.
2. Pour les escaliers, entrez le nombre de montées et la longueur de la plate-forme supérieure séparément. Utilisez le nombre de pièces identiques pour d'autres formes.
3. Remplacer la densité par défaut par la valeur indiquée sur l'étiquette du matériau si elle est connue. Utilisez la table de tout le sac pour les commandes.







## Exemple



### Entrée



```
7 ft × 3 ft × 5 en dalle, quantité 2
```



### Résultat attendu



```
17,5 ft³, soit 2 327,50 lb à 133 lb/ft³
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/concrete-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Le volume est égal à la surface transversale multipliée par la longueur. La valeur par défaut utilise 133 lb/ft3 pour les livres et 2 130 kg/m3 pour les kilogrammes. Une densité personnalisée convertit les deux résultats d'une seule valeur.



$$
V_{\rm slab}=lwhq,\quad V_{\rm tube}=\pi hq(d_o^2-d_i^2)/4
$$



$$
V_{\rm stairs}=brn\left[p+u(n-1)/2\right],\qquad m=V\rho
$$



Dans la formule de l'escalier, b est la largeur, r la montée, u la course horizontale, n le nombre de montées, et p la profondeur de la plate-forme supérieure. Le volume solide comprend des marches n−1 et la plate-forme supérieure.



Pour deux dalles de 7 pi × 3 pi × 5 pi, 133 lb/ft3 donne 2327,50 lb, ou 38,79 équivalents d'un sac de 60 lb. La table de commande arrondit à 39 sacs avant toute allocation.







## Mode de calcul



**Bases en lambeaux ou rectangulaires**

- Longueur
- Unité de longueur
- Largeur
- Unité de largeur
- Épaisseur ou hauteur
- Épaisseur ou unité de hauteur
- Quantité
- Densité de béton sur mesure · lb/ft³
- Décharge pour déchets · %





**Colonne ou base ronde**

- Diamètre
- Unité de diamètre
- Profondeur ou hauteur
- Unité de profondeur ou de hauteur
- Quantité
- Densité de béton sur mesure · lb/ft³
- Décharge pour déchets · %





**Dalle ou tube circulaire**

- Diamètre extérieur
- Unité de diamètre extérieur
- Diamètre intérieur
- Unité de diamètre intérieur
- Profondeur ou hauteur
- Unité de profondeur ou de hauteur
- Quantité
- Densité de béton sur mesure · lb/ft³
- Décharge pour déchets · %





**Bordure et caniveau**

- Profondeur de courbure
- Unité de profondeur de courbure
- Largeur du gouttière
- Unité de largeur de gouttière
- Hauteur de la courbe au-dessus de la gouttière
- Hauteur de la courbe au-dessus de l'unité de gouttière
- Épaisseur du drapeau
- Unité d'épaisseur du drapeau
- Longueur
- Unité de longueur
- Quantité
- Densité de béton sur mesure · lb/ft³
- Décharge pour déchets · %





**Escaliers solides et quai**

- Exécuter par étape
- Exécution par unité d'étape
- Augmentation par étape
- Augmentation par unité d'étape
- Largeur de l'escalier
- Unité de largeur d'escalier
- Profondeur de la plate-forme supérieure
- Unité de profondeur de la plateforme supérieure
- Nombre d ' étapes
- Densité de béton sur mesure · lb/ft³
- Décharge pour déchets · %

[Documentation](https://docs.toolpony.com/fr/guides/concrete-calculator/)
