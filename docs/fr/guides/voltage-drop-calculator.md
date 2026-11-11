# Calculateur de chute de tension



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







## Essayer



[Ouvrir l’outil complet](<https://toolpony.com/fr/tools/voltage-drop-calculator/>)







## Notes



Le traitement se fait dans le navigateur. Utilisez des unités cohérentes.







## Méthode de calcul



Utilisez la longueur aller et des conducteurs parallèles identiques. Multipliez I·L·R par 2 en CC ou monophasé et par √3 en triphasé équilibré. Pour une charge inductive, combinez R et X selon le facteur de puissance. Les calibres utilisent des valeurs nominales vers 20 °C. Utilisez les données du fabricant pour le câble réel.



$$
\Delta V=\frac{k I L R_{\rm eff}}{n},\quad k=2\ \text{(DC, 1)}\phi,\quad k=\sqrt{3}\ \text{(3)}\phi
$$



$$
R_{\rm eff}=R\cos\theta+X\sin\theta,\quad \%\Delta V=100\frac{\Delta V}{V_s}
$$







## Mode de calcul



**Résistance ou impédance connue**

- Résistance ou impédance par longueur
- Unité par longueur · Ω/km / Ω/m / mΩ/m / 1 000 ft / Ω/ft / mΩ/ft
- Tension · V
- Circuit · DC / CA monophasé / CA triphasé
- Conducteurs en parallèle par phase
- Distance aller
- Unité de longueur · ft / m / - Oui. / km
- Courant · A
- Limite de chute pour estimer la distance · %





**Estimer selon le calibre**

- Matériau · Cuivre / Aluminium / Argent / Or
- Calibre du fil
- Tension · V
- Circuit · DC / CA monophasé / CA triphasé
- Conducteurs en parallèle par phase
- Distance aller
- Unité de longueur · ft / m / - Oui. / km
- Courant · A
- Limite de chute pour estimer la distance · %





**Estimer selon la section**

- Matériau · Cuivre / Aluminium / Argent / Or
- Section transversale · mm²
- Tension · V
- Circuit · DC / CA monophasé / CA triphasé
- Conducteurs en parallèle par phase
- Distance aller
- Unité de longueur · ft / m / - Oui. / km
- Courant · A
- Limite de chute pour estimer la distance · %





**Résistance et réactance**

- Résistance
- Réactance par longueur
- Unité par longueur · Ω/km / Ω/m / mΩ/m / 1 000 ft / Ω/ft / mΩ/ft
- Facteur de puissance inductif
- Tension · V
- Circuit · DC / CA monophasé / CA triphasé
- Conducteurs en parallèle par phase
- Distance aller
- Unité de longueur · ft / m / - Oui. / km
- Courant · A
- Limite de chute pour estimer la distance · %

[Documentation](https://docs.toolpony.com/fr/guides/voltage-drop-calculator/)
