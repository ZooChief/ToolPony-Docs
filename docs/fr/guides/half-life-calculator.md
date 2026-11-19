# Calculatrice de demi-vie



Résoudre la désintégration exponentielle de trois mesures, ou convertir entre la demi-vie, la durée de vie moyenne et la constante de désintégration.





## Exemple



### Entrée



```
100 à 10 en 50 unités de temps
```



### Résultat attendu



```
Demi-vie 15.0515
```







## Essayer

[Ouvrir l’outil complet · Calculatrice de demi-vie](<https://toolpony.com/fr/tools/half-life-calculator/>)





## Méthode de calcul



La désintégration exponentielle est N(t) = N0 · 2^(−t/T). T est la demi-vie, la durée de vie moyenne est T/ln(2), et la constante de désintégration est ln(2)/T. La conversion utilise ln(2) arrondi à dix décimales. Utilisez la même unité de temps pour tous les champs.



$$
N(t)=N_0\,2^{-t/T},\qquad \lambda=\frac{\ln 2}{T},\qquad \tau=\frac1\lambda
$$



Choisissez d'abord l'inconnu. Utilisez des unités de temps cohérentes dans les trois autres champs. Pour une quantité initiale de 100 et une demi-vie de 10, la quantité restante après 20 unités de temps est de 25.







## Mode de calcul



**Trouver la demi-vie**

- Quantité restante
- Quantité initiale
- Temps écoulé





**Trouver la quantité restante**

- Quantité initiale
- Temps écoulé
- Demi-vie





**Trouver la quantité initiale**

- Quantité restante
- Temps écoulé
- Demi-vie





**Trouver le temps écoulé**

- Quantité restante
- Quantité initiale
- Demi-vie





**Convertir les mesures de désintégration**

- Mesure connue · Demi-vie / Durée de vie moyenne / Décaissement constant
- Valeur







[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fhalf-life-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/half-life-calculator/)
