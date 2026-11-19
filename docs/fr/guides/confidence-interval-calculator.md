# Calculatrice d’intervalle de confiance



Estimer un intervalle moyen normal ou un intervalle Wilson pour une proportion.





## Exemple



### Entrée



```
n = 36, moyenne 56, écart type 8, 99%
```



### Résultat attendu



```
56 ± 3.434
```







## Essayer

[Ouvrir l’outil complet · Calculatrice d’intervalle de confiance](<https://toolpony.com/fr/tools/confidence-interval-calculator/>)





## Méthode de calcul



La marge normale est de z fois l'erreur standard s/ √n. Les intervalles de score de Wilson ajustent le centre et la largeur pour les proportions et restent à l'intérieur \[0,1\].



$$
\bar{x}\pm z_{1-\alpha/2}\frac{s}{\sqrt n}
$$



$$
\frac{\widehat{p}+z^2/(2n)\pm z\sqrt{\widehat{p}(1-\widehat{p})/n+z^2/(4n^2)}}{1+z^2/n}
$$







## Mode de calcul



**Intervalle moyen normal**

- Taille de l'échantillon
- Moyenne
- Écart-type
- Niveau de confiance · %





**Intervalle de proportion de Wilson**

- Taille de l'échantillon
- Succès
- Niveau de confiance · %

[Documentation](https://docs.toolpony.com/fr/guides/confidence-interval-calculator/)
