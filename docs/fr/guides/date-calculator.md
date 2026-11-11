# Calculateur de dates



Comptez les jours calendaires et ouvrés, ou décalez une date.





## Prise en main



1. Saisissez deux dates et choisissez si la plus récente est incluse. Les jours fériés se règlent dans les options.
2. Saisissez une valeur négative pour reculer. Le mode jours ouvrés ignore les samedis, dimanches et jours fériés saisis.







## Exemple



### Entrée



```
Du 2020-01-01 au 2020-02-01
```



### Résultat attendu



```
31 jours calendaires, 23 jours ouvrés
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/date-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Les jours ouvrés vont du lundi au vendredi, hors jours fériés saisis. AAAA-MM-JJ est unique, MM-JJ est annuel. Un décalage inclut la date la plus ancienne et exclut la plus récente. Le résultat peut tomber un jour non ouvré. Les mois courts s’arrêtent à leur dernier jour.







## Mode de calcul



**Entre deux dates**

- Date de début
- Date de fin
- Inclure la date de fin
- Jours fériés (AAAA-MM-JJ ou MM-JJ)





**Ajouter ou soustraire à une date**

- Date de début
- Années
- Mois
- Semaines
- Jours





**Décaler en jours ouvrés**

- Date de début
- Jours ouvrés
- Jours fériés (AAAA-MM-JJ ou MM-JJ)

[Documentation](https://docs.toolpony.com/fr/guides/date-calculator/)
