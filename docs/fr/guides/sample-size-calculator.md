# Calculatrice de taille d’échantillon



Trouver un échantillon d'enquête minimum ou estimer la marge d'erreur avec correction de population finie.





## Exemple



### Entrée



```
confiance à 95 %, marge de 4 %, proportion de 35 %, N = 1 000
```



### Résultat attendu



```
354 échantillons
```







## Essayer

[Ouvrir l’outil complet · Calculatrice de taille d’échantillon](<https://toolpony.com/fr/tools/sample-size-calculator/>)





## Méthode de calcul



La taille initiale est z2p(1-p)/e2. Pour une population finie, diviser cette taille par 1 + (taille initiale–1)/N et arrondir. Le calcul d'erreur utilise la même proportion et le même modèle de population finie.



$$
n_0=\frac{z^2p(1-p)}{e^2},\qquad n=\left\lceil\frac{n_0}{1+(n_0-1)/N}\right\rceil
$$







## Mode de calcul



**Trouver la taille de l'échantillon**

- Niveau de confiance · %
- Marge d’erreur · %
- Proportion de la population · %
- Taille de la population (0 pour une durée illimitée)





**Trouver la marge d'erreur**

- Niveau de confiance · %
- Taille de l'échantillon
- Proportion de la population · %
- Taille de la population (0 pour une durée illimitée)







[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fsample-size-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/sample-size-calculator/)
