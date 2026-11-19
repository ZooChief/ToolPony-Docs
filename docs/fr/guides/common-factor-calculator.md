# Calculatrice de diviseurs communs



Énumérez tous les facteurs communs positifs et calculez le plus grand facteur commun de plusieurs entiers.





## Exemple



### Entrée



```
12, 18, 30
```



### Résultat attendu



```
1, 2, 3, 6
```







## Essayer

[Ouvrir l’outil complet · Calculatrice de diviseurs communs](<https://toolpony.com/fr/tools/common-factor-calculator/>)





## Méthode de calcul



Les facteurs communs d'une liste sont exactement les diviseurs de son plus grand diviseur commun. L'algorithme euclidien trouve que diviseur sans énumérer tous les facteurs d'entrée.



$$
d\mid a_1,\ldots,a_n\iff d\mid\gcd(a_1,\ldots,a_n)
$$





[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fcommon-factor-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/common-factor-calculator/)
