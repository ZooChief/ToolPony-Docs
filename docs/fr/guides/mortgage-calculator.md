# Calculatrice de prêt immobilier



Comparez une hypothèque à taux fixe avec l'acompte, les coûts récurrents, les paiements supplémentaires et les paiements bihebdomadaires.





## Prise en main



1. Utilisez l’exemple ou saisissez vos propres valeurs.
2. Calculez, puis copiez le résultat ou téléchargez les détails.







## Exemple



### Entrée



```
Logement 400 000; en baisse de 20 %; 30 ans; 6%
```



### Résultat attendu



```
1 918,56 principal mensuel et intérêts
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/mortgage-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



L’intérêt mensuel est le capital restant dû multiplié par le taux annuel et divisé par 12. Les frais suivent les montants annuels et taux de croissance saisis. Dans ce modèle, le PMI peut s’arrêter à 80 % de la valeur initiale du logement. Le scénario toutes les deux semaines utilise la moitié de la mensualité et le taux annuel divisé par 26.



$$
I_k=r B_{k-1},\qquad B_k=B_{k-1}-(M_k-I_k)
$$

[Documentation](https://docs.toolpony.com/fr/guides/mortgage-calculator/)
