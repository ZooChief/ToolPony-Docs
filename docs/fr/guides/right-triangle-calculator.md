# Calculateur de triangle rectangle



Calculez les côtés, l’hypoténuse et les angles à partir de deux mesures, y compris la hauteur, l’aire ou le périmètre.





## Prise en main



1. Saisissez deux mesures, dont une longueur, une aire ou le périmètre.
2. Les deux solutions permutent les étiquettes des côtés de l’angle droit et des angles aigus.







## Exemple



### Entrée



```
c = 5, h = 2,4
```



### Résultat attendu



```
Côtés 3 et 4, aire 6, périmètre 12. Le côté a peut être l’un ou l’autre.
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/right-triangle-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



c est l’hypoténuse et h sa hauteur perpendiculaire. Utilisez la même unité de longueur et son carré pour l’aire.



$$
c^2=a^2+b^2,\quad h=ab/c,\quad S=ab/2,\quad P=a+b+c
$$



$$
a,b=\frac{\sqrt{c^2+2ch}\;\pm\;\sqrt{c^2-2ch}}{2}
$$

[Documentation](https://docs.toolpony.com/fr/guides/right-triangle-calculator/)
