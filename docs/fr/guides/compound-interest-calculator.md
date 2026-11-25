# Guide pratique · Calculatrice d’intérêts composés



Projetez un solde avec des contributions récurrentes et de l'inflation, ou convertissez-vous entre les fréquences composées.





## Exemple



### Entrée



```
10 000 à 5 % par an pendant 10 ans
```



### Résultat attendu



```
16,288.95
```





<a id="case-study"></a>



## Comparer des versements sur 30 mois



1. Avec 10 000 au départ puis 100 par mois pendant 2 ans et 6 mois, un taux nominal de 6 % capitalisé chaque mois donne 14 842,00 avec des versements en fin de mois, dont 13 000 versés. En début de mois, le solde atteint 14 858,14. À 3 % d’inflation annuelle, le premier solde équivaut à 13 784,77 aujourd’hui.





## Essayer

[Ouvrir l’outil complet · Calculatrice d’intérêts composés](<https://toolpony.com/fr/tools/compound-interest-calculator/#example-30-months>)





## Méthode de calcul



La croissance annuelle effective est de 1+r/m^m−1, ou exp(r)−1 avec addition continue. Les contributions génèrent des intérêts du début ou de la fin de chaque période.



$$
A=P(1+r/m)^{mt},\qquad \mathrm{APY}=(1+r/m)^m-1
$$







## Mode de calcul





### Solde futur



- Capital emprunté
- Taux annuel · %
- Années
- Mois
- Capitalisation
- Contribution périodique
- Fréquence des contributions · Annuelle / Semestrielle / Trimestrielle / Mensuelle / Deux fois par mois / Toutes les deux semaines / Hebdomadaire / Quotidienne
- Contribuer au début de la période
- Taux d'inflation annuel · %







### Taux d'intérêt équivalent



- Taux annuel · %
- Composition originale
- Compilation des cibles







**Références de la méthode** [Investor.gov · Compound Interest](<https://www.investor.gov/financial-tools-calculators/calculators/compound-interest-calculator>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fcompound-interest-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/compound-interest-calculator/)
