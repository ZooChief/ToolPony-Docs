# Calculatrice statistique



Résumer un ensemble de données avec la moyenne, la médiane, les modes, les quartiles et la dispersion de la population et de l'échantillon.





## Prise en main



1. Utilisez l’exemple ou saisissez vos propres valeurs.
2. Calculez, puis copiez le résultat ou téléchargez les détails.







## Exemple



### Entrée



```
2, 4, 4, 6, 9
```



### Résultat attendu



```
Moyenne 5, médiane 4
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/statistics-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Les quartiles utilisent l'interpolation linéaire à (n−1)p. La variance de la population se divise par n et la variance de l'échantillon par n−1. Entrez jusqu'à 1 000 valeurs séparées par des virgules ou un espace blanc.



$$
\bar x=\frac{1}{n}\sum_{i=1}^{n} x_i,\qquad s=\sqrt{\frac{\sum_i(x_i-\bar x)^2}{n-1}}
$$



$$
\operatorname{SE}(\bar x)=\frac{s}{\sqrt n},\qquad \bar x\pm z\operatorname{SE}(\bar x)
$$



Utiliser l'écart-type d'échantillon pour un sous-ensemble de population et l'écart-type de population pour un ensemble complet. Le tableau de confiance montre l'approximation normale de la moyenne à plusieurs niveaux de confiance.







## Mode de calcul



**Résumé des données**

- Valeurs





**Écart type de l'échantillon**

- Valeurs





**Écart-type de population**

- Valeurs

[Documentation](https://docs.toolpony.com/fr/guides/statistics-calculator/)
