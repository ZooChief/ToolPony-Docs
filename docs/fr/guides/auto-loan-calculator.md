# Calculateur de prêt auto



Calculez la mensualité ou le prix maximal du véhicule avec reprise, solde dû, remise et taxes.





## Prise en main



1. Saisissez le prix ou une mensualité cible. Indiquez l’apport, la reprise, le solde dû et les remises.
2. Indiquez le taux et les frais. Choisissez les déductions et le financement, puis exportez l’échéancier.







## Exemple



### Entrée



```
Prix 30 000, apport 5 000, 5 % sur 60 mois
```



### Résultat attendu



```
471,78 par mois hors taxes et frais
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/auto-loan-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Saisissez le taux et choisissez les déductions de l’assiette. Les taxes et frais financés s’ajoutent au capital. La valeur nette de reprise est le prix de reprise moins le solde dû. Le taux mensuel est fixe.



$$
P=V-D-(T-O)-R+F,\quad M=\frac{Pr}{1-(1+r)^{-n}},\quad M=\frac Pn\; (r=0)
$$



V est le prix, D l’apport, T la valeur de reprise, O le solde dû, R la remise et F les taxes et frais financés. P est le capital, M le versement mensuel, r le taux mensuel et n le nombre de mois.







## Mode de calcul



**Calculer la mensualité**

- Prix du véhicule
- Mois
- Taux annuel · %
- Apport
- Valeur de reprise
- Solde dû sur la reprise
- Remise en espèces
- Taxe de vente · %
- Immatriculation et autres frais
- Déduire la reprise de l’assiette
- Déduire la remise de l’assiette
- Financer les taxes et frais
- Devise





**Trouver le prix du véhicule**

- Versement mensuel
- Mois
- Taux annuel · %
- Apport
- Valeur de reprise
- Solde dû sur la reprise
- Remise en espèces
- Taxe de vente · %
- Immatriculation et autres frais
- Déduire la reprise de l’assiette
- Déduire la remise de l’assiette
- Financer les taxes et frais
- Devise

[Documentation](https://docs.toolpony.com/fr/guides/auto-loan-calculator/)
