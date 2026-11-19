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





<a id="case-study"></a>



## Choisir un gris conforme au niveau AA pour un texte courant sur fond blanc



1. Essayez \#777777 sur blanc. Le rapport vaut environ 4,48:1. Même s’il s’arrondit à 4,5 à une décimale, le texte courant reste sous le seuil WCAG AA sur la valeur exacte.
2. Essayez \#767676 sur le même fond. Le rapport passe à environ 4,54:1 et le texte courant atteint AA. Les deux exemples atteignent 3:1 pour les grands caractères.
3. Vérifiez les couleurs réellement affichées. Pour du texte sur une image ou un calque translucide, prélevez les couleurs finales à l’endroit le moins contrasté. Le résultat porte sur cette paire de couleurs unies.





## Essayer

[Ouvrir l’outil complet · Vérificateur de contraste](<https://toolpony.com/fr/tools/contrast-checker/>)





## Méthode de calcul



Le contraste est (luminance claire + 0,05) divisé par (luminance sombre + 0,05). Le contrôle utilise le rapport non arrondi. Le texte normal exige 4,5:1 pour AA et 7:1 pour AAA. Le grand texte exige 3:1 pour AA et 4,5:1 pour AAA.





**Références de la méthode** [W3C · WCAG 2.2 (1.4.3, AA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html>) · [W3C · WCAG 2.2 (1.4.6, AAA)](<https://www.w3.org/WAI/WCAG22/Understanding/contrast-enhanced.html>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fcontrast-checker%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/contrast-checker/)
