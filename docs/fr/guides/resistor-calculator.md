# Calculateur de résistances et de codes couleur



Décodez 3 à 6 anneaux et calculez la résistance en série, en parallèle ou d’un fil rond.





## Prise en main



1. Choisissez le nombre d’anneaux ou le montage. L’anneau de tolérance est souvent espacé des autres.
2. Saisissez le diamètre et la longueur du fil rond. Le préréglage renseigne une conductivité modifiable.







## Exemple



### Entrée



```
4 anneaux : vert, rouge, rouge, or
```



### Résultat attendu



```
5,200 Ω ±5%
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/resistor-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Lisez les chiffres, le multiplicateur, la tolérance et le coefficient de température éventuel. Trois anneaux indiquent une tolérance de 20 %. Pour un fil rond uniforme, R = L/(σA). Vérifiez les marquages spéciaux sur la fiche du composant.



$$
R_{\rm series}=\sum_i R_i,\quad R_{\rm parallel}=\left(\sum_i 1/R_i\right)^{-1},\quad R_{\rm wire}=\frac{L}{\sigma\pi(d/2)^2}
$$



$$
R_{\rm band}=D\,10^m,\qquad R_{\min,\max}=R_{\rm band}(1\mp t/100)
$$







## Mode de calcul



**4 anneaux**

- Premier chiffre
- Deuxième chiffre
- Multiplicateur
- Tolérance





**3 anneaux**

- Premier chiffre
- Deuxième chiffre
- Multiplicateur





**5 anneaux**

- Premier chiffre
- Deuxième chiffre
- Troisième chiffre
- Multiplicateur
- Tolérance





**6 anneaux**

- Premier chiffre
- Deuxième chiffre
- Troisième chiffre
- Multiplicateur
- Tolérance
- Coefficient de température





**Parallèle**

- Résistances en Ω





**Série**

- Résistances en Ω





**Conducteur rond**

- Longueur
- Unité de longueur · mm / cm / m / km / en / ft / yd / - Oui.
- Diamètre
- Unité de diamètre · mm / cm / m / km / en / ft / yd / - Oui.
- Préréglage du matériau · Personnalisé / Cuivre / Cuivre recuit / Aluminium / Argent / Or
- Conductivité · S/m

[Documentation](https://docs.toolpony.com/fr/guides/resistor-calculator/)
