# Comparateur CSV



Collez ou importez les deux tableaux. Gardez l’en-tête puis sélectionnez séparateur et colonnes clés. Comparez et filtrez les changements. Le CSV convient aux tableurs. Le JSON conserve le texte original et le rapport complet.





## Prise en main



1. Collez ou importez les deux tableaux. Gardez l’en-tête puis sélectionnez séparateur et colonnes clés.
2. Comparez et filtrez les changements. Le CSV convient aux tableurs. Le JSON conserve le texte original et le rapport complet.







## Exemple



### Entrée



```
ID,Name,Qty
001,Oak,2
002,Pine,1
004,Ash,3

Qty,ID,Name
4,001,Oak
1,003,Fir
3,004,Ash
```



### Résultat attendu



```
Ajoutés 1 · Supprimés 1 · Modifiés 1
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/csv-compare/>)







## Limites



Jusqu’à 1 Mio UTF-8, 5 000 lignes et 80 colonnes par tableau. La comparaison conserve les zéros initiaux. Les clés vides et en double sont signalées à part. Les numéros comptent les enregistrements à partir de l’en-tête.

[Documentation](https://docs.toolpony.com/fr/guides/csv-compare/)
