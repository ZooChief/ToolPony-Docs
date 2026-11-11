# Calculateur de paillis



Estimez le volume, les sacs et le coût du paillis pour une ou plusieurs parcelles.





## Prise en main



1. Saisissez la surface totale ou un rectangle par ligne, par exemple 6, 2, m. Les unités peuvent varier selon les lignes.
2. Réglez l’épaisseur et choisissez un prix en vrac ou par sac. La contenance personnalisée se règle dans les options.







## Exemple



### Entrée



```
200 ft², épaisseur de 2 in, sacs de 2 ft³ à 5 l’unité.
```



### Résultat attendu



```
33,3 ft³, 17 sacs, coût total de 85.
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/mulch-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Additionnez les surfaces sans chevauchement, puis appliquez l’épaisseur et la marge. Divisez par la contenance du sac et arrondissez au supérieur. Le vrac est facturé au volume.



$$
A=\sum_i l_iw_i,\quad V=Ad(1+a/100),\quad N=\left\lceil\frac{V}{V_{\rm bag}}\right\rceil
$$







## Mode de calcul



**Surface connue**

- Surface
- Unité de surface · cm² / m² / in² / ft² / yd² / acre / h
- Épaisseur
- Unité d’épaisseur · mm / cm / m / en / ft / yd
- Prix unitaire
- Unité de prix
- Contenance d’un sac
- Unité par sac · ft³ / yd³ / m³ / L
- Marge de pertes · %





**Plusieurs rectangles**

- Longueur, largeur, unité par ligne
- Épaisseur
- Unité d’épaisseur · mm / cm / m / en / ft / yd
- Prix unitaire
- Unité de prix
- Contenance d’un sac
- Unité par sac · ft³ / yd³ / m³ / L
- Marge de pertes · %

[Documentation](https://docs.toolpony.com/fr/guides/mulch-calculator/)
