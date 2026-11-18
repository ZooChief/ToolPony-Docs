# Vérificateur de contraste



Comparez deux couleurs opaques aux seuils de contraste WCAG 2.2.





## Exemple



### Entrée



```
#000000 sur #FFFFFF
```



### Résultat attendu



```
21:1
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/contrast-checker/>)







## Méthode de calcul



Le contraste est (luminance claire + 0,05) divisé par (luminance sombre + 0,05). Le contrôle utilise le rapport non arrondi. Le texte normal exige 4,5:1 pour AA et 7:1 pour AAA. Le grand texte exige 3:1 pour AA et 4,5:1 pour AAA.

[Documentation](https://docs.toolpony.com/fr/guides/contrast-checker/)
