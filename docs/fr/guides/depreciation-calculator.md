# Calculatrice d’amortissement comptable



Construisez un calendrier annuel de chiffres linéaires, de solde décroissant ou de somme d'années.





## Prise en main



1. Utilisez l’exemple ou saisissez vos propres valeurs.
2. Calculez, puis copiez le résultat ou téléchargez les détails.







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



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/depreciation-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Le solde en baisse applique les facteurs/vie à l'ouverture de la valeur comptable et s'arrête à la récupération. Les chiffres de la somme des années sont attribués par les autres années. Les montants sont arrondis par année.



$$
D_{\mathrm{SL}}=\frac{C-S}{n},\quad D_{k,\mathrm{SYD}}=(C-S)\frac{n-k+1}{n(n+1)/2}
$$







## Mode de calcul



**Ligne droite**

- Coût de l ' actif
- Valeur de récupération
- Vie utile
- Arrondi · Deux décimales / Montant entier





**Baisse de l'équilibre**

- Coût de l ' actif
- Valeur de récupération
- Vie utile
- Facteur d'amortissement
- Arrondi · Deux décimales / Montant entier





**Chiffres de la somme des années**

- Coût de l ' actif
- Valeur de récupération
- Vie utile
- Arrondi · Deux décimales / Montant entier

[Documentation](https://docs.toolpony.com/fr/guides/depreciation-calculator/)
