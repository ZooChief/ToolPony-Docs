# Calculateur du coût de l’électricité



Estimez consommation et coût par appareil, charge et tarif sur une durée fixe ou du jour à l’année.





## Prise en main



1. Indiquez la puissance absorbée, l’usage et le tarif. Les préréglages proposent des valeurs modifiables.







## Exemple



### Entrée



```
1 000 W, 2 h/jour, 30 jours, 0,2 par kWh
```



### Résultat attendu



```
60 kWh, coût de 12
```







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/electricity-cost-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



L’énergie est le produit de la puissance en kW, des heures, de la charge moyenne et du nombre d’appareils. Le tarif est fixe. Le modèle utilise 30,44 jours par mois et 365,25 par an. Pour la climatisation, utilisez la puissance électrique absorbée.



$$
E_{\rm kWh}=P_{\rm kW}\,t_{\rm h}\,f\,n,\qquad C=E_{\rm kWh}\,r
$$







## Mode de calcul



**Nombre de jours fixe**

- Puissance
- Unité de puissance · W / kW / BTU/h / PS / TR
- Charge moyenne · %
- Appareils
- Heures par jour · h
- Jours
- Prix par kWh





**Du jour à l’année**

- Préréglage d’appareil
- Puissance
- Unité de puissance · W / kW / BTU/h / PS / TR
- Charge moyenne · %
- Appareils
- Utilisation
- Unité d’utilisation · Minutes par jour / Heures par jour / Heures par semaine / Heures par mois / Jours par semaine / Jours par mois / Jours par an / Mois par an
- Prix par kWh

[Documentation](https://docs.toolpony.com/fr/guides/electricity-cost-calculator/)
