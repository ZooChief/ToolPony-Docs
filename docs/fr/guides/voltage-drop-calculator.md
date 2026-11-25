# Guide pratique · Calculateur de chute de tension



Estimez la chute de tension en CC, monophasé ou triphasé équilibré à partir du calibre ou de la résistance.





## Prise en main



1. Choisissez un modèle. En triphasé, saisissez la tension entre phases et le courant de ligne. Indiquez la distance aller.
2. La distance limite dépend du pourcentage choisi. Vérifiez séparément le courant admissible, la température et les exigences d’installation.







## Exemple



### Entrée



```
120 V, monophasé, 500 ft, 1 A et 1,2 Ω/km
```



### Résultat attendu



```
Chute de 0,37 V, soit 0,30 %
```





<a id="case-study"></a>



## Utiliser une table de câbles



1. À 1 mV/(A·m), 50 m aller et 100 A donnent 5 V sur ce câble. L’exemple Schneider ajoute 10 V en amont, soit 15 V sur tout le trajet.



[Essayer l’exemple](<https://toolpony.com/fr/tools/voltage-drop-calculator/#example-cable-table>)





## Circuit triphasé parallèle



Deux conducteurs par phase se partagent 20 A. À 400 V sur 100 m, avec R = 1 Ω/km, X = 0,5 Ω/km et un facteur inductif de 0,8, la chute atteint 1,91 V et la charge reçoit 398,09 V.



[Essayer l’exemple](<https://toolpony.com/fr/tools/voltage-drop-calculator/#example-parallel-cable>)







## Chute supérieure à la source



Sous 24 V continu, 10 A et 1 km aller à 5 Ω/km impliquent une chute de 100 V. Le modèle ne donne pas de tension de charge à ce courant.



[Essayer l’exemple](<https://toolpony.com/fr/tools/voltage-drop-calculator/#example-cable-limit>)







## Essayer

[Ouvrir l’outil complet · Calculateur de chute de tension](<https://toolpony.com/fr/tools/voltage-drop-calculator/>)





## Méthode de calcul



Utilisez la longueur aller et des conducteurs parallèles identiques. Multipliez I·L·R par 2 en CC ou monophasé et par √3 en triphasé équilibré. Pour une charge inductive, combinez R et X selon le facteur de puissance. Les calibres utilisent des valeurs nominales vers 20 °C. Utilisez les données du fabricant pour le câble réel.



$$
\Delta V=\frac{k I L R_{\rm eff}}{n},\quad k=2\ \text{(DC, 1)}\phi,\quad k=\sqrt{3}\ \text{(3)}\phi
$$



$$
R_{\rm eff}=R\cos\theta+X\sin\theta,\quad \%\Delta V=100\frac{\Delta V}{V_s}
$$







## Mode de calcul





### Résistance ou impédance connue



- Valeur de la fiche · Impédance du conducteur / Coefficient de chute du circuit
- Résistance ou impédance par longueur
- Unité par longueur · Ω/km / Ω/m / mΩ/m / 1 000 ft / Ω/ft / mΩ/ft
- Coefficient du circuit dans la table · mV/(A·m)
- Tension · V
- Circuit · DC / CA monophasé / CA triphasé
- Conducteurs en parallèle par phase
- Distance aller
- Unité de longueur · ft / m / mi / km
- Courant · A
- Limite de chute pour estimer la distance · %







### Estimer selon le calibre



- Matériau · Cuivre / Aluminium / Argent / Or
- Calibre du fil
- Tension · V
- Circuit · DC / CA monophasé / CA triphasé
- Conducteurs en parallèle par phase
- Distance aller
- Unité de longueur · ft / m / mi / km
- Courant · A
- Limite de chute pour estimer la distance · %







### Estimer selon la section



- Matériau · Cuivre / Aluminium / Argent / Or
- Section transversale · mm²
- Tension · V
- Circuit · DC / CA monophasé / CA triphasé
- Conducteurs en parallèle par phase
- Distance aller
- Unité de longueur · ft / m / mi / km
- Courant · A
- Limite de chute pour estimer la distance · %







### Résistance et réactance



- Résistance
- Réactance par longueur
- Unité par longueur · Ω/km / Ω/m / mΩ/m / 1 000 ft / Ω/ft / mΩ/ft
- Facteur de puissance inductif
- Tension · V
- Circuit · DC / CA monophasé / CA triphasé
- Conducteurs en parallèle par phase
- Distance aller
- Unité de longueur · ft / m / mi / km
- Courant · A
- Limite de chute pour estimer la distance · %







**Références de la méthode** [Schneider Electric · Voltage drop in steady load conditions](<https://www.electrical-installation.org/enwiki/Calculation_of_voltage_drop_in_steady_load_conditions>)



[ZooChief](<https://docs.toolpony.com/fr/about/>) · [Signaler un problème de résultat](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Ffr%2Fguides%2Fvoltage-drop-calculator%2F>)

[Documentation](https://docs.toolpony.com/fr/guides/voltage-drop-calculator/)
