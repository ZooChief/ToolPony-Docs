# Guide pratique · Calculatrice du taux de rendement interne



Trouver le taux effectif annuel à partir des flux annuels irréguliers ou d'une valeur finale et des dépôts ou retraits réguliers.





## Exemple



### Entrée



```
55 000 dépenses avec 14 000, 18 000, 22 000, 26 000 entrées
```



### Résultat attendu



```
IRR 15,093%
```







## Essayer

[Ouvrir l’outil complet · Calculatrice du taux de rendement interne](<https://toolpony.com/fr/tools/irr-calculator/>)





## Méthode de calcul



Les flux de trésorerie à mode fixe utilisent la fréquence de paiement sélectionnée et le moment de début ou de fin de paiement. Choisissez si un paiement de début de période est également compté à la limite du terminal. La recherche de taux couvre −99.9999% à 10 000%.



$$
0=\sum_{i=0}^n\frac{F_i}{(1+r)^{t_i}}
$$







## Mode de calcul





### Flux annuels irréguliers



- Investissement initial
- Flux de trésorerie annuels ultérieurs







### Flux fixes et solde de clôture



- Investissement initial
- Années complètes
- Mois supplémentaires
- Solde de clôture
- Montant du paiement
- Type de paiement · Retrait / Dépôt
- Paiements par an · 1 / 2 / 4 / 12 / 24 / 26 / 52
- Calendrier des paiements · Fin de période / Début de la période
- Inclure le paiement terminal en mode de début







[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Firr-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/irr-calculator/)
