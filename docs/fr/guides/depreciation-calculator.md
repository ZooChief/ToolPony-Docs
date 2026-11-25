# Guide pratique · Calculatrice d’amortissement comptable



Construisez un calendrier annuel de chiffres linéaires, de solde décroissant ou de somme d'années.





## Exemple



### Entrée



```
17 500 $ coût, 2 500 $ récupération, 6 ans, ligne droite
```



### Résultat attendu



```
2 500 par an
```







## Essayer

[Ouvrir l’outil complet · Calculatrice d’amortissement comptable](<https://toolpony.com/fr/tools/depreciation-calculator/>)





## Méthode de calcul



Le solde en baisse applique les facteurs/vie à l'ouverture de la valeur comptable et s'arrête à la récupération. Les chiffres de la somme des années sont attribués par les autres années. Les montants sont arrondis par année.



$$
D_{\mathrm{SL}}=\frac{C-S}{n},\quad D_{k,\mathrm{SYD}}=(C-S)\frac{n-k+1}{n(n+1)/2}
$$







## Mode de calcul





### Ligne droite



- Coût de l ' actif
- Valeur de récupération
- Vie utile
- Arrondi · Deux décimales / Montant entier







### Baisse de l'équilibre



- Coût de l ' actif
- Valeur de récupération
- Vie utile
- Facteur d'amortissement
- Arrondi · Deux décimales / Montant entier







### Chiffres de la somme des années



- Coût de l ' actif
- Valeur de récupération
- Vie utile
- Arrondi · Deux décimales / Montant entier







[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fdepreciation-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/depreciation-calculator/)
