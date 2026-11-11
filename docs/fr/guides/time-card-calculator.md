# Calculateur de feuille d’heures



Saisissez une semaine de services et de pauses avec arrondi, règles de paie et CSV.





## Prise en main



1. Saisissez les heures comme 08:30, 8.30 ou 8:30 AM. Indiquez les pauses en heures et minutes, par exemple 00:30.
2. Choisissez l’arrondi et les règles de paie si nécessaire. Téléchargez le CSV ou imprimez. L’enregistrement local du brouillon est facultatif.







## Exemple



### Entrée



```
08:30–17:00 avec 00:30 de pause
```



### Résultat attendu



```
08:00:00
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/time-card-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Déduisez la pause puis arrondissez le temps net. Une fin plus tôt est le lendemain. Les seuils journaliers ou hebdomadaires et les taux sont saisis par l’utilisateur.



$$
t_i=(e_i-s_i)\bmod 1440-b_i,\qquad t'_i=q\,\operatorname{round}(t_i/q)\quad(q>0)
$$



$$
P=(t_{\rm base}+m\,t_{\rm overtime})r/60
$$

[Documentation](https://docs.toolpony.com/fr/guides/time-card-calculator/)
