# Guide pratique · Calculateur de toiture



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





<a id="case-study"></a>



## Commander les bardeaux



1. Un toit plat de 25 × 40 ft couvre 1 000 ft². Avec 10 % de marge et 3 paquets par 100 ft², achetez 33 paquets. À 75 chacun, le total est de 2 475.



[Essayer l’exemple](<https://toolpony.com/fr/tools/roofing-calculator/#example-roof-order>)





## Lire la couverture du paquet



Pour 1 100 ft² à couvrir, 33 paquets de 33,3 ft² couvrent 1 098,9 ft². Il en faut 34, soit 1 132,2 ft².



[Essayer l’exemple](<https://toolpony.com/fr/tools/roofing-calculator/#example-package-label>)







## Deux débords différents



Pour 8 × 5 m, avec 25 cm en égout et 40 cm en pignon, la projection mesure 8,8 × 5,5 m. Avec une pente de 5/12, 10 % de marge et 3 m² par paquet, commandez 20 paquets.



[Essayer l’exemple](<https://toolpony.com/fr/tools/roofing-calculator/#example-roof-overhang>)







## Essayer

[Ouvrir l’outil complet · Calculateur de toiture](<https://toolpony.com/fr/tools/roofing-calculator/>)





## Méthode de calcul



Avec la seule emprise A, le débord horizontal e est estimé par A + 4,4e(√A + e). Pour un rectangle mesuré, utilisez (l + 2e)(w + 2e), puis appliquez le facteur de pente. Un square de toiture vaut 100 ft². Vérifiez les couvertures indiquées par le fabricant.



$$
A_{\rm proj}\approx A+4.4e(\sqrt A+e),\qquad A_{\rm rect}=(l+2e)(w+2e)
$$



$$
A_{\rm roof}=A_{\rm proj}\sqrt{1+(p/12)^2}=\frac{A_{\rm proj}}{\cos\theta},\quad N_{\rm squares}=\left\lceil\frac{A_{\rm roof,ft^2}(1+a/100)}{100}\right\rceil
$$







## Mode de calcul





### Emprise et pente



- Emprise au sol
- Unité de surface · cm² / m² / in² / ft² / yd² / acre / h
- Élévation pour 12 à l’horizontale
- Débord horizontal
- Unité du débord · mm / cm / m / en / ft / yd
- Prix unitaire
- Unité de prix · cm² / m² / in² / ft² / yd² / acre / h
- Marge de pertes · %
- Couverture par paquet · Paquets par carré de toiture / Surface par paquet
- Paquets pour 100 ft²
- Surface utile d’un paquet
- Prix par paquet (facultatif)







### Emprise et angle



- Emprise au sol
- Unité de surface · cm² / m² / in² / ft² / yd² / acre / h
- Angle du toit · °
- Débord horizontal
- Unité du débord · mm / cm / m / en / ft / yd
- Prix unitaire
- Unité de prix · cm² / m² / in² / ft² / yd² / acre / h
- Marge de pertes · %
- Couverture par paquet · Paquets par carré de toiture / Surface par paquet
- Paquets pour 100 ft²
- Surface utile d’un paquet
- Prix par paquet (facultatif)







### Surface de toit connue



- Surface de toit
- Unité de surface · cm² / m² / in² / ft² / yd² / acre / h
- Prix unitaire
- Unité de prix · cm² / m² / in² / ft² / yd² / acre / h
- Marge de pertes · %
- Couverture par paquet · Paquets par carré de toiture / Surface par paquet
- Paquets pour 100 ft²
- Surface utile d’un paquet
- Prix par paquet (facultatif)







### Longueur et largeur mesurées



- Longueur
- Unité de longueur · mm / cm / m / en / ft / yd
- Largeur
- Unité de largeur · mm / cm / m / en / ft / yd
- Élévation pour 12 à l’horizontale
- Débord horizontal
- Unité du débord · mm / cm / m / en / ft / yd
- Débord en pignon si différent
- Prix unitaire
- Unité de prix · cm² / m² / in² / ft² / yd² / acre / h
- Marge de pertes · %
- Couverture par paquet · Paquets par carré de toiture / Surface par paquet
- Paquets pour 100 ft²
- Surface utile d’un paquet
- Unité de surface · cm² / m² / in² / ft² / yd² / acre / h
- Prix par paquet (facultatif)







**Références de la méthode** [GAF · Bundle coverage per roofing square](<https://www.gaf.com/en-us/blog/your-home/how-many-bundles-of-shingles-are-in-a-square---63a47862-f7e1-4e73-abcf-8d09917a8b8d>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Froofing-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/roofing-calculator/)
