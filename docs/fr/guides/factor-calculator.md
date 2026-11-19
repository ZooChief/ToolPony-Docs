# Calculatrice de diviseurs



Énumérez chaque diviseur positif, toutes les paires de facteurs et la factorisation principale.





## Exemple



### Entrée



```
120
```



### Résultat attendu



```
16 diviseurs positifs, dont 1 et 120
```







## Essayer

[Ouvrir l’outil complet · Calculatrice de diviseurs](<https://toolpony.com/fr/tools/factor-calculator/>)





## Méthode de calcul



Un diviseur divise l'entrée avec zéro reste. Chaque petit diviseur d paires avec n/d, donc recherche jusqu'à √n trouve chaque paire.



$$
d\mid n\iff n\bmod d=0,\qquad n=d\cdot(n/d)
$$

[Documentation](https://docs.toolpony.com/fr/guides/factor-calculator/)
