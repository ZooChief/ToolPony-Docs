# Calculatrice matricielle



Ajoutez, multipliez, transposez, inversez, résolvez ou trouvez le rang et le déterminant. Copiez le résultat en TSV ou téléchargez CSV.





## Prise en main



1. Utilisez l’exemple ou saisissez vos propres valeurs.
2. Calculez, puis copiez le résultat ou téléchargez les détails.







## Exemple



### Entrée



```
A = [2, 4; 1, 3], B = [1, −2; 4, 5]
```



### Résultat attendu



```
A + B = [3, 2; 5, 8]
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/matrix-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Séparer chaque rangée par une nouvelle ligne ou un point-virgule. Les valeurs peuvent être séparées par des espaces ou des virgules. Un tableau JSON imbriqué est accepté.



$$
(AB)_{ij}=\sum_{k=1}^{n}A_{ik}B_{kj},\qquad A^{-1}A=I
$$



$$
[A\mid B]\longrightarrow[I\mid X]\quad\Rightarrow\quad AX=B
$$







## Mode de calcul



**Ajouter A + B**

- Matrice A
- Matrice B





**Soustraction A − B**

- Matrice A
- Matrice B





**Multiplier A × B**

- Matrice A
- Matrice B





**Résolvez A × X = B**

- Matrice A
- Matrice B





**Déterminant**

- Matrice A





**Inverse**

- Matrice A





**Transposer**

- Matrice A





**Puissance entière**

- Matrice A
- Exposant





**Multiplication scalaire**

- Matrice A
- Scalaire





**Tableau de classement et de rang réduit**

- Matrice A

[Documentation](https://docs.toolpony.com/fr/guides/matrix-calculator/)
