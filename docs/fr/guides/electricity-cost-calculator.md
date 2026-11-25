# Guide pratique · Calculateur du coût de l’électricité



Calculez le coût de l’énergie à partir des watts électriques, de la puissance frigorifique et du rendement, ou de deux relevés. Vérifiez les kWh par jour et par période.





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





<a id="case-study"></a>



## Lire les watts d’un climatiseur de fenêtre



1. La fiche du LG LW6014ER indique 6 000 BTU/h de puissance frigorifique et 530 W électriques. À pleine charge, 8 heures par jour pendant 30 jours donnent 0,53 × 8 × 30 = 127,2 kWh. À 0,20 par kWh, le coût de l’énergie est de 25,44.



[Essayer l’exemple](<https://toolpony.com/fr/tools/electricity-cost-calculator/#example-window-power>)





## Vérifier une facture avec deux relevés



En 30 jours, le compteur passe de 612345,125 à 612492,365 kWh. L’écart est de 147,24 kWh, soit 4,908 kWh par jour. À 0,15 par kWh, l’énergie coûte 22,086 avant abonnement et taxes.



[Essayer l’exemple](<https://toolpony.com/fr/tools/electricity-cost-calculator/#example-meter-readings>)







## Estimer la puissance électrique avec l’EER



Avec 6 000 BTU/h et un EER nominal de 12 BTU/Wh, la puissance électrique vaut 6 000 ÷ 12 = 500 W. À pleine charge, 8 heures par jour pendant 30 jours donnent 120 kWh. Utilisez l’EER correspondant aux conditions indiquées.



[Essayer l’exemple](<https://toolpony.com/fr/tools/electricity-cost-calculator/#example-cooling-eer>)







## Essayer

[Ouvrir l’outil complet · Calculateur du coût de l’électricité](<https://toolpony.com/fr/tools/electricity-cost-calculator/>)





## Méthode de calcul



Coût de l’énergie = kWh × tarif unitaire. La consommation mesurée est l’index final moins l’index initial. Les BTU/h divisés par l’EER, ou les watts frigorifiques divisés par le COP, donnent des watts électriques. Les estimations utilisent 30,44 jours par mois et 365,25 par an.



$$
E_{\rm kWh}=M_1-M_0,\qquad P_{\rm W}=\frac{Q_{\rm Btu/h}}{\mathrm{EER}}=\frac{Q_{\rm W}}{\mathrm{COP}}
$$



$$
E_{\rm kWh}=P_{\rm kW}\,t_{\rm h}\,f\,n,\qquad C=E_{\rm kWh}\,r
$$







## Mode de calcul





### Nombre de jours fixe



- Base du calcul · Puissance électrique / Puissance frigorifique / Relevés du compteur
- Puissance électrique
- Unité de puissance · W / kW / BTU/h / PS / TR
- Puissance frigorifique
- Unité de puissance frigorifique · BTU/h / kW / TR
- Type de rendement · EER (BTU/Wh) / COP (W/W)
- Rendement nominal
- Index initial · kWh
- Index final · kWh
- Charge moyenne · %
- Appareils
- Heures par jour · h
- Jours
- Prix par kWh







### Du jour à l’année



- Préréglage d’appareil
- Base du calcul · Puissance électrique / Puissance frigorifique
- Puissance électrique
- Unité de puissance · W / kW / BTU/h / PS / TR
- Puissance frigorifique
- Unité de puissance frigorifique · BTU/h / kW / TR
- Type de rendement · EER (BTU/Wh) / COP (W/W)
- Rendement nominal
- Charge moyenne · %
- Appareils
- Utilisation
- Unité d’utilisation · Minutes par jour / Heures par jour / Heures par semaine / Heures par mois / Jours par semaine / Jours par mois / Jours par an / Mois par an
- Prix par kWh







**Références de la méthode** [LG · LW6014ER electrical specification](<https://images.thdstatic.com/catalog/pdfImages/e3/e3b8396a-44d1-4372-b120-7532036b2488.pdf>) · [Ohio Consumers’ Counsel · Read an electric meter](<https://www.occ.ohio.gov/sites/default/files/2021-07/OCC-How-to-Read-an-Electric-Meter.pdf>) · [U.S. Department of Energy · Room air conditioner ratings](<https://www.energy.gov/sites/prod/files/2015/06/f22/room_ac_rfi.pdf>) · [NIST · International Table Btu](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-footnotes>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Felectricity-cost-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/electricity-cost-calculator/)
