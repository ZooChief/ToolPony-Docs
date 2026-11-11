# Calculateur de remboursement anticipé



Comparez les versements restants, les suppléments, un remboursement intégral et deux modèles pour des versements toutes les deux semaines.





## Prise en main



1. Après des suppléments antérieurs, utilisez le solde et la mensualité de capital et intérêts du relevé. Sinon, déduisez le solde du prêt initial et de la durée restante.
2. Choisissez un plan puis saisissez les suppléments mensuels, annuels ou ponctuels. Par défaut ils commencent aux mois 1, 12 et 1. Les options avancées permettent de changer ces débuts.
3. Comparez le plan choisi au plan régulier, puis téléchargez l’échéancier restant ou le comparatif CSV.
4. Le modèle couvre le capital et les intérêts fixes. Le montant réel peut inclure des intérêts quotidiens, frais et pénalités. Vérifiez auprès du prêteur.







## Exemple



### Entrée



```
400 000 sur 30 ans à 6 %. Il reste 25 ans, avec 500 en plus par mois.
```



### Résultat attendu



```
207 mois restants, 122 306,21 d’intérêts économisés
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/mortgage-payoff-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Le mode du prêt initial suppose que les versements précédents ont suivi l’échéancier prévu. Les intérêts mensuels sont le solde multiplié par le taux annuel divisé par douze. Le modèle regroupé ajoute une demi-mensualité tous les six mois. Le modèle à 26 versements utilise une demi-mensualité et le taux annuel divisé par 26.



$$
B=M\frac{1-(1+r)^{-n}}r\quad(r>0),\qquad B=Mn\quad(r=0)
$$



$$
I_k=rB_{k-1},\qquad B_k=\max(0,B_{k-1}-M+I_k-E_k)
$$



$$
E_{6j}=M/2\quad\text{(grouped)},\qquad M_{26}=M/2,\quad r_{26}=r_{\rm annual}/26
$$







## Mode de calcul



**Prêt initial et durée restante**

- Montant initial
- Années du prêt initial
- Mois supplémentaires initiaux
- Taux annuel · %
- Années restantes
- Mois restants supplémentaires
- Mode de remboursement · Versements supplémentaires / Versements réguliers / Toutes les deux semaines, regroupé au mois / Toutes les deux semaines, 26 versements par an / Rembourser le capital maintenant
- Supplément mensuel
- Supplément annuel
- Versement supplémentaire unique
- Premier mois des suppléments mensuels
- Premier mois des suppléments annuels
- Mois du versement unique





**Solde actuel et mensualité**

- Capital restant dû
- Versement mensuel
- Taux annuel · %
- Mode de remboursement · Versements supplémentaires / Versements réguliers / Toutes les deux semaines, regroupé au mois / Toutes les deux semaines, 26 versements par an / Rembourser le capital maintenant
- Supplément mensuel
- Supplément annuel
- Versement supplémentaire unique
- Premier mois des suppléments mensuels
- Premier mois des suppléments annuels
- Mois du versement unique

[Documentation](https://docs.toolpony.com/fr/guides/mortgage-payoff-calculator/)
