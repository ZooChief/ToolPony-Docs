# Guide pratique · Calculatrice de délai de récupération



Trouver une récupération régulière et actualisée des flux de trésorerie annuels croissants ou irréguliers.





## Exemple



### Entrée



```
17 500 initiale, première entrée 4 700, croissance 8%, réduction 6%
```



### Résultat attendu



```
Remboursement de 3,379 ans, actualisé 3,841 ans
```







## Essayer

[Ouvrir l’outil complet · Calculatrice de délai de récupération](<https://toolpony.com/fr/tools/payback-period-calculator/>)





## Méthode de calcul



Au premier passage de zéro, interpolez la fraction de cette année. Les flux de trésorerie actualisés divisent l'année k par (1+r)^k. Un flux constant utilise la formule de rente inverse pour le remboursement actualisé.



$$
C_k=\sum_{i=0}^{k}F_i,\qquad F_i^{\mathrm{PV}}=\frac{F_i}{(1+r)^i}
$$







## Mode de calcul





### Flux de trésorerie réguliers ou croissants



- Investissement initial
- Flux de trésorerie de la première année
- Croissance ou déclin annuel · %
- Années
- Taux d'actualisation annuel · %







### Flux de trésorerie annuels irréguliers



- Investissement initial
- Flux de trésorerie annuels ultérieurs
- Taux d'actualisation annuel · %







[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fpayback-period-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/payback-period-calculator/)
