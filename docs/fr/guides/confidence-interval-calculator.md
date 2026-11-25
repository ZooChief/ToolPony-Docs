# Guide pratique · Calculatrice d’intervalle de confiance



Estimez une moyenne à partir de données ou de statistiques résumées avec z ou Student, et une proportion avec Wilson.





## Exemple



### Entrée



```
n = 36, moyenne 56, écart type 8, 99%
```



### Résultat attendu



```
56 ± 3.434
```





<a id="case-study"></a>



## Un intervalle avec cinq mesures



1. Les mesures 48, 49, 50, 51 et 52 ont une moyenne de 50. Avec l’écart-type de l’échantillon et quatre degrés de liberté, l’intervalle de Student à 95 % va de 48,04 à 51,96 environ. Le calcul suppose des observations indépendantes et une population approximativement normale.



[Essayer l’exemple](<https://toolpony.com/fr/tools/confidence-interval-calculator/#example-five-measurements>)





## Aucun défaut sur 30 contrôles



Trente contrôles indépendants donnent zéro défaut. L’intervalle de Wilson à 95 % pour la proportion de défauts s’étend de 0 % à environ 11,35 %. Davantage de contrôles sans défaut le resserrent.



[Essayer l’exemple](<https://toolpony.com/fr/tools/confidence-interval-calculator/#example-no-failures>)







## Essayer

[Ouvrir l’outil complet · Calculatrice d’intervalle de confiance](<https://toolpony.com/fr/tools/confidence-interval-calculator/>)





## Méthode de calcul



La marge vaut valeur critique × écart-type / √n. Utilisez z si σ est connu et Student à n − 1 degrés de liberté avec un écart-type d’échantillon. Wilson estime une proportion binomiale à partir des succès et essais.



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## Mode de calcul





### Intervalle de la moyenne



- Source des données · σ connu / s observé / Observations
- Taille de l'échantillon
- Moyenne
- Écart-type
- Valeurs observées
- Niveau de confiance · %







### Intervalle de proportion de Wilson



- Taille de l'échantillon
- Succès
- Niveau de confiance · %







**Références de la méthode** [NIST · Confidence limits for the mean](<https://www.itl.nist.gov/div898/handbook/eda/section3/eda352.htm>) · [NIST · Confidence limits for a proportion](<https://www.itl.nist.gov/div898/handbook/prc/section2/prc241.htm>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fconfidence-interval-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/confidence-interval-calculator/)
