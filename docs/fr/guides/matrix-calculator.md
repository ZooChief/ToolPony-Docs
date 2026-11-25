# Guide pratique · Calculatrice matricielle



Résolvez des systèmes linéaires et calculez déterminants, inverses, rangs et produits avec des fractions et des décimaux exacts. Collez des cellules de tableur et exportez le résultat.





## Exemple



### Entrée



```
A = [2, 4; 1, 3], B = [1, −2; 4, 5]
```



### Résultat attendu



```
A + B = [3, 2; 5, 8]
```





<a id="case-study"></a>



## Compter deux types de lots



1. Un petit lot contient 2 pinces noires et 1 blanche, un grand lot 3 noires et 2 blanches. On compte 17 noires et 10 blanches. Les colonnes de A décrivent les lots, B contient les totaux. On trouve 4 petits lots et 3 grands. Multipliez A par X pour vérifier les deux totaux.



[Essayer l’exemple](<https://toolpony.com/fr/tools/matrix-calculator/#example-packing-matrix>)





## Un déterminant égal à un



Le produit sur la diagonale est le carré d’un milliard. L’autre produit vaut (un milliard − 1) × (un milliard + 1). La différence vaut exactement 1. Les deux lignes sont indépendantes.



[Essayer l’exemple](<https://toolpony.com/fr/tools/matrix-calculator/#example-determinant-one>)







## Deux variables libres



La deuxième équation est le double de la première. Dans x + y + z = 4, on choisit y et z, puis x = 4 − y − z. À partir de (4, 0, 0), deux vecteurs du noyau donnent les variations possibles. Remplacez le second total 8 par 9 pour faire apparaître la contradiction.



[Essayer l’exemple](<https://toolpony.com/fr/tools/matrix-calculator/#example-free-variables>)







## Essayer

[Ouvrir l’outil complet · Calculatrice matricielle](<https://toolpony.com/fr/tools/matrix-calculator/>)





## Méthode de calcul



La réduction par lignes utilise des rationnels exacts. Le nombre de colonnes pivot donne le rang. Dans A × X = B, une ligne de zéros à gauche avec un second membre non nul indique une incompatibilité. Les colonnes libres déterminent les directions à ajouter à une solution particulière.



$$
(AB)_{ij}=\sum_{k=1}^{n}A_{ik}B_{kj},\qquad A^{-1}A=I
$$



$$
[A\mid B]\longrightarrow[I\mid X]\quad\Rightarrow\quad AX=B
$$







## Mode de calcul





### Ajouter A + B



- Matrice A
- Matrice B







### Soustraction A − B



- Matrice A
- Matrice B







### Multiplier A × B



- Matrice A
- Matrice B







### Résolvez A × X = B



- Matrice A
- Matrice B







### Déterminant



- Matrice A







### Inverse



- Matrice A







### Transposer



- Matrice A







### Puissance entière



- Matrice A
- Exposant







### Multiplication scalaire



- Matrice A
- Scalaire







### Tableau de classement et de rang réduit



- Matrice A







**Références de la méthode** [MIT OpenCourseWare · Solving Ax = b](<https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/resources/solving-ax-b-row-reduced-form-r/>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fmatrix-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/matrix-calculator/)
