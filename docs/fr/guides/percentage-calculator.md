# Guide pratique · Calculatrice de pourcentage



Calculez un pourcentage, comparez des taux en points ou appliquez et inversez deux remises.





## Prise en main



1. Pour une partie comme 15% de 240, choisissez Pourcentage d'une valeur. Si la partie est 36 et que vous connaissez le total ou le taux, choisissez le mode inverse correspondant.
2. Choisissez Pourcentage de changement pour une vieille et nouvelle valeur ordonnée. Utilisez Pourcentage de différence pour deux valeurs positives sans référence.
3. Inscrivez 15 pour 15%. Comparez le résultat par rapport aux exemples travaillés ci-dessous.







## Exemple



### Entrée



```
15% sur 240
```



### Résultat attendu



```
36
```





<a id="case-study"></a>



## Deux remises successives



1. À partir de 250, une remise de 20 % donne 200. La seconde remise de 10 % porte sur 200 et donne 180. La baisse totale est de 28 %. Inversez le calcul pour retrouver le prix initial.



[Essayer l’exemple](<https://toolpony.com/fr/tools/percentage-calculator/#example-two-discounts>)





## Passer de 4 % à 5 %



Le taux d’inscription passe de 4 % à 5 %, soit un point de pourcentage de plus. Rapportée aux 4 % initiaux, la hausse est de 1 ÷ 4 = 25 %.



[Essayer l’exemple](<https://toolpony.com/fr/tools/percentage-calculator/#example-percentage-points>)







## Essayer

[Ouvrir l’outil complet · Calculatrice de pourcentage](<https://toolpony.com/fr/tools/percentage-calculator/>)





## Méthode de calcul



La variation relative utilise la valeur absolue de la base. Soustraire deux taux donne des points de pourcentage. Les facteurs successifs se multiplient. L’écart symétrique utilise la moyenne des valeurs absolues.



$$
x=yp/100,\quad p=100x/y,\quad y=100x/p
$$



$$
\Delta\%=100\frac{x_1-x_0}{|x_0|},\quad D\%=200\frac{|x_1-x_0|}{|x_1|+|x_0|}
$$



80 → 100 est un changement de 25% parce que 80 est la valeur de départ. La différence de pourcentage entre les mêmes nombres est d'environ 22.22% parce que le dénominateur est leur moyenne, 90.



Après une augmentation de 20% à 120, Inverser un changement donne 100. Un changement de -100% ne peut pas être inversé.



Pour une valeur mesurée de 90 et une référence de 96, l'erreur absolue en pourcentage est de 6,25 %. Le résultat signé avec cette référence positive est de − 6,25 %.







## Mode de calcul





### Pourcentage d'une valeur



- Pourcentage · %
- Valeur







### Trouver le pourcentage



- Partie
- Entière







### Trouvez l'ensemble



- Partie
- Pourcentage · %







### Variation en pourcentage



- Type des valeurs · Montants / Taux (%)
- Valeur initiale
- Nouvelle valeur







### Différence en pourcentage



- Première valeur
- Deuxième valeur







### Différence avec les valeurs signées



- Première valeur
- Deuxième valeur







### Appliquer une modification



- Valeur initiale
- Changement signé · %
- Deuxième variation · %







### Inverser un changement



- Nouvelle valeur
- Changement signé · %
- Deuxième variation · %







### Erreur en pourcentage



- Valeur mesurée
- Valeur de référence
- Convention sur l'erreur · Absolu / Signé par rapport à la référence







**Références de la méthode** [Eurostat · Percentage point](<https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Glossary:Percentage_point>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fpercentage-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/percentage-calculator/)
