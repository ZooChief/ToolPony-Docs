# Calculateur de toiture



Estimez la surface du toit, les squares, les paquets de bardeaux, les rouleaux de feutre et le coût.





## Prise en main



1. Choisissez l’emprise et la pente ou l’angle. Pour une emprise rectangulaire, entrez les dimensions mesurées.
2. Pour une toiture complexe, additionnez les pans mesurés et saisissez le total comme surface de toit connue.







## Exemple



### Entrée



```
Emprise de 2 000 ft², pente de 6/12, débord de 1 ft.
```



### Résultat attendu



```
Environ 2 461 ft², 28 squares avec une marge de 10 %.
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/roofing-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Avec la seule emprise A, le débord horizontal e est estimé par A + 4,4e(√A + e). Pour un rectangle mesuré, utilisez (l + 2e)(w + 2e), puis appliquez le facteur de pente. Un square de toiture vaut 100 ft². Vérifiez les couvertures indiquées par le fabricant.



$$
A_{\rm proj}\approx A+4.4e(\sqrt A+e),\qquad A_{\rm rect}=(l+2e)(w+2e)
$$



$$
A_{\rm roof}=A_{\rm proj}\sqrt{1+(p/12)^2}=\frac{A_{\rm proj}}{\cos\theta},\quad N_{\rm squares}=\left\lceil\frac{A_{\rm roof,ft^2}(1+a/100)}{100}\right\rceil
$$







## Mode de calcul



**Emprise et pente**

- Emprise au sol
- Unité de surface · cm² / m² / in² / ft² / yd² / acre / h
- Élévation pour 12 à l’horizontale
- Débord horizontal
- Unité du débord · mm / cm / m / en / ft / yd
- Prix unitaire
- Unité de prix · cm² / m² / in² / ft² / yd² / acre / h
- Marge de pertes · %





**Emprise et angle**

- Emprise au sol
- Unité de surface · cm² / m² / in² / ft² / yd² / acre / h
- Angle du toit · °
- Débord horizontal
- Unité du débord · mm / cm / m / en / ft / yd
- Prix unitaire
- Unité de prix · cm² / m² / in² / ft² / yd² / acre / h
- Marge de pertes · %





**Surface de toit connue**

- Surface de toit
- Unité de surface · cm² / m² / in² / ft² / yd² / acre / h
- Prix unitaire
- Unité de prix · cm² / m² / in² / ft² / yd² / acre / h
- Marge de pertes · %





**Longueur et largeur mesurées**

- Longueur
- Unité de longueur · mm / cm / m / en / ft / yd
- Largeur
- Unité de largeur · mm / cm / m / en / ft / yd
- Élévation pour 12 à l’horizontale
- Débord horizontal
- Unité du débord · mm / cm / m / en / ft / yd
- Prix unitaire
- Unité de prix · cm² / m² / in² / ft² / yd² / acre / h
- Marge de pertes · %

[Documentation](https://docs.toolpony.com/fr/guides/roofing-calculator/)
