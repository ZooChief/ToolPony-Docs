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





<a id="case-study"></a>



## Rapprocher deux stocks après un changement d’ordre des colonnes



1. Chargez l’exemple de stock et choisissez ID comme clé. L’ancien fichier commence par ID, Name, Qty, tandis que le nouveau place Qty en tête. Comparez les deux exports.
2. La quantité de l’article 001 (Oak) passe de 2 à 4. Le 002 disparaît, le 003 apparaît et le 004 reste identique. Le résultat compte une modification, une suppression et un ajout malgré le déplacement des colonnes.
3. Remplacez seulement 001 par 1 dans le nouvel export. Vous obtenez deux ajouts, deux suppressions et aucune modification. Conservez les zéros initiaux à l’export pour rapprocher les mêmes articles.





## Essayer

[Ouvrir l’outil complet · Comparateur CSV](<https://toolpony.com/fr/tools/csv-compare/>)





## Limites



Jusqu’à 1 Mio UTF-8, 5 000 lignes et 80 colonnes par tableau. La comparaison conserve les zéros initiaux. Les clés vides et en double sont signalées à part. Les numéros comptent les enregistrements à partir de l’en-tête.



Pour un inventaire, utilisez une référence stable comme clé. Si 0012 devient 12 dans le nouvel export, la comparaison signale une suppression et un ajout. Gardez les zéros initiaux dans les deux fichiers pour comparer les quantités du même article.





**Références de la méthode** [IETF · RFC 4180 (CSV)](<https://www.rfc-editor.org/rfc/rfc4180>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fcsv-compare%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/csv-compare/)
