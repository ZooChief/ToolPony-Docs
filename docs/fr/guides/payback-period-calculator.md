# Calculatrice de délai de récupération



Trouver une récupération régulière et actualisée des flux de trésorerie annuels croissants ou irréguliers.





## Prise en main



1. Utilisez l’exemple ou saisissez vos propres valeurs.
2. Calculez, puis copiez le résultat ou téléchargez les détails.







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



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/payback-period-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Au premier passage de zéro, interpolez la fraction de cette année. Les flux de trésorerie actualisés divisent l'année k par (1+r)^k. Un flux constant utilise la formule de rente inverse pour le remboursement actualisé.



$$
C_k=\sum_{i=0}^{k}F_i,\qquad F_i^{\mathrm{PV}}=\frac{F_i}{(1+r)^i}
$$







## Mode de calcul



**Flux de trésorerie réguliers ou croissants**

- Investissement initial
- Flux de trésorerie de la première année
- Croissance ou déclin annuel · %
- Années
- Taux d'actualisation annuel · %





**Flux de trésorerie annuels irréguliers**

- Investissement initial
- Flux de trésorerie annuels ultérieurs
- Taux d'actualisation annuel · %

[Documentation](https://docs.toolpony.com/fr/guides/payback-period-calculator/)
